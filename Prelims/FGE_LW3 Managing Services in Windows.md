+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 712ad9bd2a804447896c5c63e4392118 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Doga-ong, Leiyan M.        | DATE PERFORMED:        |          |
|                                  | 08-28-24               |          |
+----------------------------------+------------------------+----------+
| Section: IDC1                    | DATE SUBMITTED:        |          |
|                                  | 08-28-24               |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Managing Services in Windows

# Requirement: 

-   A virtual machine running Linux and Windows OS

    **Services** are background processes that run independently of user
    interactions in Windows. They provide essential system functions,
    such as network connectivity, printing, and time synchronization.
    This lab will guide you through the process of managing services
    using the Services app.

# Instructions:  {#instructions .list-paragraph}

1.  Open the Start menu and search for \"Services\"

2.  Familiarize yourself with the columns, including Service Name,
    Display Name, Status, and Startup type.

3.  Right-click on a service and select \"Start\", \"Stop\", or
    \"Restart\". Fill out the table below

  -----------------------------------------------------------------------------------------------------------------------
  **Status**   **Name of   **Screenshot**
               Service**   
  ------------ ----------- ----------------------------------------------------------------------------------------------
  Start        Adobe       ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image2.png){width="5.015748031496063in"
               Version Cue height="3.1377952755905514in"}
               CS4         

                           

  Stop         Adobe       ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image3.png){width="5.001402012248469in"
               Version Cue height="2.23676290463692in"}
               CS4         

  Restart      Adobe       ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image4.png){width="4.9468547681539805in"
               Version Cue height="1.877785433070866in"}
               CS4         

  Pause                    
  -----------------------------------------------------------------------------------------------------------------------

4.  Select five network services, right-click to view its properties.
    Modify the startup setting to Manual.

> **SS**:
>
> **Adobe Version Cue CS4**
>
> ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image5.png){width="3.263157261592301in"
> height="3.7852613735783027in"}
>
> **App Readiness**
>
> ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image6.png){width="3.2718974190726158in"
> height="3.776517935258093in"}
>
> **Application Identity Properties**
>
> ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image7.png){width="3.5970723972003498in"
> height="4.253606736657917in"}
>
> **Bluetooth Audio Gateway Service Properties**
>
> ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image8.png){width="3.552315179352581in"
> height="4.151826334208224in"}
>
> **Cellular Time Properties**
>
> ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image9.png){width="3.6362128171478565in"
> height="4.21946741032371in"}
>
> **Bluetooth Audio Gateway Service Properties**
>
> ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image8.png){width="3.63913823272091in"
> height="4.253299431321085in"}

5.  Explore the \"General\", \"Recovery\", and \"Log On\" tabs to
    understand additional service settings.

6.  Create a batch file that will be added as a new service later on.
    Refer to the batch file code below.

> ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image10.png){width="4.808325678040245in"
> height="2.0055664916885387in"}

7.  Save the batch file in Z:\\lastname_timer.bat

![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image11.png){width="4.413371609798775in"
height="3.039873140857393in"}

8.  Use the sc command to add timer.bat service in the command line
    interface.

> *sc create BatchTimerService binPath= \"path_to_your_batch_file.bat\"
> start= auto*
>
> *net start BatchTimerService*
>
> **Replace path_to_your_batch_file.bat with the actual path to your
> batch file.**

9.  Verify that BatchTimerService has been added to the services.

> **SS:**
>
> ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image12.png){width="3.5077832458442693in"
> height="4.124730971128609in"}

10. **Testing the Service:** Now, if you open a new command prompt, you
    should see the timer countdown without requiring your interaction.
    Once the timer finishes, you\'ll see the \"Timer finished!\"
    message.

> **SS:**
>
> ![](vertopal_712ad9bd2a804447896c5c63e4392118/media/image13.png){width="4.3964468503937in"
> height="2.1461329833770777in"}

**Rubric**

  ---------------------------------------------------------------------------------------
  **Criteria**      **Excellent       **Good (7)**    **Needs          **Unsatisfactory
                    (10)**                            Improvement      (1)**
                                                      (3)**            
  ----------------- ----------------- --------------- ---------------- ------------------
  Understanding of  Demonstrates a    Shows a solid   Has a basic      Shows little or no
  Services          deep              understanding   understanding of understanding of
                    understanding of  of services,    services, but    services.
                    the concept of    but may lack    may struggle     
                    services, their   some depth in   with specific    
                    roles, and their  specific areas. concepts.        
                    importance in                                      
                    Windows.                                           

  Service           Successfully      Demonstrates    Can perform      Struggles to
  Management Skills starts, stops,    proficiency in  basic service    perform even basic
                    restarts, and     managing        management       service management
                    configures        services, but   tasks, but may   tasks.
                    services using    may encounter   need assistance  
                    the Services app. minor           or guidance.     
                                      difficulties.                    

  Custom Service    Successfully      Can create a    Has limited      Cannot create a
  Creation          creates and       custom service, experience with  custom service.
                    manages a custom  but may         creating custom  
                    service using the encounter minor services.        
                    appropriate tools difficulties or                  
                    and techniques.   require                          
                                      assistance.                      

  Problem-Solving   Demonstrates      Can effectively May require      Struggles to
                    strong            troubleshoot    assistance to    troubleshoot and
                    problem-solving   and resolve     troubleshoot     resolve issues.
                    skills when       most issues     some issues.     
                    encountering      related to                       
                    challenges or     service                          
                    errors.           management.                      

  Documentation and Provides clear    Documents the   Provides basic   Does not provide
  Reporting         and concise       lab activities  documentation,   any documentation
                    documentation of  adequately, but but may be       or reporting.
                    the lab           may lack some   disorganized or  
                    activities,       detail or       incomplete.      
                    including         clarity.                         
                    relevant                                           
                    screenshots and                                    
                    observations.                                      

  **Score:**        **50 /50**                                         
  ---------------------------------------------------------------------------------------
