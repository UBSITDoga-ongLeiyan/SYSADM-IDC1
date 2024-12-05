+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| da3278fd163e43229e6dc25fb0cae713 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Leiyan M. Doga-ong         | DATE PERFORMED:        |          |
|                                  | 02/12/2024             |          |
+----------------------------------+------------------------+----------+
| Section: IDC1                    | DATE SUBMITTED:        |          |
|                                  | 06/12/2024             |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Final Requirement

**Final Project: Comprehensive System Administration & Policy
Integration**

**Objective:** Students will apply their knowledge of system
administration by designing and implementing a comprehensive system
environment while integrating the revised policies from their draft
assignments. This project will demonstrate their understanding of system
management, security protocols, and policy enforcement.

**Project Overview:** Students will create a detailed proposal and
implementation plan for a fictional organization. This plan should
encompass the following elements:

1.  **System Architecture Design**

    -   Create a network diagram illustrating the layout of the
        organization\'s IT infrastructure.

    -   Identify and describe key components such as servers,
        workstations, firewalls, and switches.

-   The system architecture is designed to give the company a safe,
    well-structured, and effective IT infrastructure. A router sends
    data to internal components, and a firewall protects the network\'s
    perimeter by filtering traffic between the Internet and internal
    systems. Employees and external users can access services like
    organizational resources and employee self-service tools through the
    Web Server, which is connected by Switch 1 and hosts the company\'s
    website and internal portals. Internally, Switch2 is connected to a
    File Server and an Application Server that manage
    department-specific applications for Finance and HR as well as
    shared files and structured databases.

-   Finance staff access similar resources through their PCs, including
    finance-specific databases and shared files. This structure ensures
    security by segmenting networks while centralizing data and
    applications, making the system scalable, manageable, and secure for
    both departments. Similar resources, such as databases and shared
    files tailored to the finance industry, are accessible to finance
    staff via their PCs. By centralizing data and apps and dividing
    networks, this structure makes the system secure, scalable, and
    manageable for both departments.

![](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image2.png){width="7.027083333333334in"
height="8.228472222222223in"}

2.  **Operating System Deployment**

    -   Choose at least two operating systems (e.g., Linux and Windows)
        and explain the rationale for each choice.

-   Windows Server 2012 and Windows 11 are the operating systems I used
    since they offer a solid foundation for the company\'s IT
    infrastructure by utilizing robust server capabilities and advanced
    user interfaces. Effective administration, strong security, and
    compatibility with the apps needed for a productive workplace are
    all guaranteed by this combination.

![](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image3.png){width="6.107136920384952in"
height="3.3821905074365706in"}

![](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image4.png){width="6.162551399825022in"
height="1.7953554243219598in"}

-   Detail the installation process, configuration settings, and any
    automation tools used (e.g., Ansible, Puppet).

```{=html}
<!-- -->
```
-   Setting up the virtual machine (VM) to boot from the installation
    media, like the mounted ISO file, is the first step in the
    installation process for Windows Server 2012. Users are given the
    option to choose their preferred keyboard, language, and time when
    the virtual machine boots up. By utilizing the advantages of
    virtualization, the flexibility supports in customizing the server
    environment to meet certain organizational requirements.

-   The boot process for Windows 11 on a virtual machine also begins
    with a mounted ISO file. To configure the keyboard layout, language,
    and region, users need to stick to a set of instructions. They can
    choose privacy settings and connect to a virtual network with the
    help of the setup process.

![A screenshot of a computer Description automatically
generated](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image5.png){width="3.2608716097987753in"
height="2.8858191163604547in"}

![A screenshot of a computer Description automatically
generated](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image6.png){width="5.313241469816273in"
height="1.3439370078740158in"}

![](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image7.png){width="4.11515748031496in"
height="1.510627734033246in"}

![A screenshot of a computer Description automatically
generated](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image8.png){width="3.17752624671916in"
height="1.6773173665791776in"}

3.  **User and Access Management**

    -   Outline user roles and access levels, utilizing a least
        privilege approach.

-   Comprehensive user roles are established in the user and access
    management framework to provide efficient security and operation
    inside the company. The main roles are [Administrator]{.underline},
    who has complete control over system configurations and settings;
    [Standard User]{.underline}, who can access files and apps that are
    essential to their work; and [Guest]{.underline}, who has restricted
    access for external or temporary users. The least privilege concept,
    which lowers the possibility of accidentally changes or illegal
    access by limiting user permissions to the minimal level necessary
    for their jobs.

![A screenshot of a computer Description automatically
generated](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image9.png){width="3.3650524934383204in"
height="2.8441469816272966in"}

![A screenshot of a computer Description automatically
generated](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image10.png){width="4.521464348206474in"
height="3.125436351706037in"}

![A screenshot of a computer Description automatically
generated](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image11.png){width="5.460965660542432in"
height="2.71671697287839in"}

![](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image12.png){width="6.324562554680665in"
height="1.5519192913385826in"}

![A screenshot of a computer Description automatically
generated](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image13.png){width="4.823698600174978in"
height="1.917617016622922in"}

![A screenshot of a computer Description automatically
generated](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image14.png){width="6.466578083989502in"
height="2.6054188538932634in"}

-   Describe how to implement user accounts, groups, and permissions.

```{=html}
<!-- -->
```
-   Active Directory will be used to create user accounts and groups in
    order to properly implement these functions. This makes it possible
    to handle user identities and access rights securely. To guarantee
    that users have access to only the resources necessary to carry out
    their tasks, permissions will be granted according to certain job
    responsibilities.

4.  **Security Measures**

    -   Integrate security protocols, such as firewalls, antivirus, and
        intrusion detection systems.

-   Implement firewalls to monitor and regulate incoming and outgoing
    network traffic, limiting unwanted access.

![](vertopal_da3278fd163e43229e6dc25fb0cae713/media/image15.png){width="2.9274923447069114in"
height="0.4792333770778653in"}

-   Draft a basic incident response plan for potential security
    breaches.

```{=html}
<!-- -->
```
-   The plan lays out an organized procedure that includes four
    important steps: identification, where threats are identified and
    evaluated; containment, where affected systems are isolated to stop
    additional harm; eradication, where the breach\'s underlying cause
    is dealt with; and recovery, where systems are returned to normal
    operations and vulnerabilities are patched.

5.  **Backup and Recovery Plan**

    -   Develop a strategy for data backup, including frequency and
        types of backups (full, incremental).

    -   Outline the recovery process in case of data loss.

-   Regular backups are scheduled as part of the backup strategy to
    protect important data. Weekly full backups will be made to record
    all system states, and daily incremental backups will only record
    changes since the last backup. Combining these two factors reduces
    downtime during data recovery and maximizes storage efficiency.

-   To properly restore data in the case of loss, a well-defined
    recovery procedure is necessary in addition to the backup plan.
    Prior to attempting any restoration, this procedure will include
    certain steps for confirming the backups\' integrity to make sure
    the data is reliable and uncorrupted. After verification, the
    recovery procedure will explain how to quickly resume regular
    operations by restoring data from both complete and incremental
    backups.

6.  **Policy Integration**

    -   Incorporate changes made to the policy drafts during the course.

    -   Discuss how these policies will be enforced, monitored, and
        updated as needed.

-   Policy drafts must be carefully updated to reflect the latest
    regulations and business best practices. We\'ll actively take into
    account the input from earlier evaluations to enable ongoing
    development and flexibility in response to changing circumstances.

-   Clear methods for enforcement will be created to support these
    revised policies. This involves putting in place monitoring systems
    that keep track on compliance to set procedures and identify any
    irregularities. To evaluate the policies\' efficacy and make the
    required modifications in light of changing operating circumstances
    and new threats, regular assessments will be planned. The company
    can encourage a culture of security and accountability by putting in
    place a strong framework for policy integration. This will guarantee
    that all staff members are aware of their responsibilities for
    upholding compliance and protecting the company\'s resources.

7.  **Documentation**

    -   Provide comprehensive documentation for all systems,
        configurations, and policies.

    -   Include a user manual for end-users and system administrators.

-   The efficient administration of IT systems and regulations depends
    on thorough and understandable documentation. To make the
    environment easy for administrators and users to understand and
    navigate, this involves maintaining thorough records of all systems,
    configurations, and operating procedures. System specifications,
    configuration settings, and policy guidelines will all be presented
    in each document in an organized manner to increase clarity and
    decrease confusion. Through the provision of easily accessible
    documentation, the organization guarantees that users can promptly
    locate the information required to carry out their activities
    efficiently, and administrators can consult these resources for
    compliance and troubleshooting purposes.

-   A user manual designed to end users and system administrators will
    also be created. This handbook will provide you detailed
    instructions on how to use the apps and systems, solve frequent
    problems, and comprehend security procedures. It will go over the
    fundamental features, login processes, and useful tool usage advice
    for end users. The handbook will cover advanced setups, maintenance
    duties, and user account and permission management for system
    administrators. The company supports training and onboarding
    procedures, increases operational efficiency, and promotes a culture
    of knowledge sharing and continual improvement by offering easily
    available documentation and an extensive user manual.

8.  **Presentation**

    -   Prepare a presentation summarizing the project, highlighting key
        decisions and policies.

    -   Be prepared to answer questions regarding the implementation and
        policy integration.

**Grading Rubric**

  ---------------------------------------------------------------------------------------------------------
  **Criteria**   **Excellent   **Good      **Satisfactory   **Needs         **Unsatisfactory   **Points**
                 (90-100)**    (80-89)**   (70-79)**        Improvement     (0-59)**           
                                                            (60-69)**                          
  -------------- ------------- ----------- ---------------- --------------- ------------------ ------------

  ---------------------------------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------------
  **System       Clear,         Mostly     Basic        Lacks        No             /20
  Architecture   detailed, and  clear      layout;      clarity;     architecture   
  Design**       logical        layout;    several      many         provided.      
                 layout;        minor      components   components                  
                 includes all   details    missing.     missing.                    
                 required       missing.                                            
                 components.                                                        
  -------------- -------------- ---------- ------------ ------------ -------------- -----

  ---------------------------------------------------------------------------------------

  ------------------------------------------------------------------------------------------------
  **OS           Well-justified   Good choices with Basic      Poor             No           /20
  Deployment**   choices;         minor             choices;   justification;   deployment   
                 thorough         justifications;   some       lacks detail.    details      
                 installation and adequate details. details                     provided.    
                 configuration                      missing.                                 
                 details.                                                                    
  -------------- ---------------- ----------------- ---------- ---------------- ------------ -----

  ------------------------------------------------------------------------------------------------

  --------------------------------------------------------------------------------------
  **User and     Comprehensive    Good roles Basic      Vague roles;  No           /15
  Access         roles defined;   defined;   roles with significant   management   
  Management**   excellent        minor      limited    access        plan         
                 implementation   issues in  access     control       provided.    
                 of access        access     control.   issues.                    
                 controls.        control.                                         
  -------------- ---------------- ---------- ---------- ------------- ------------ -----

  --------------------------------------------------------------------------------------

  ----------------------------------------------------------------------------------------
  **Security   Strong integration Good         Basic         Poor        No security /15
  Measures**   of security        measures;    measures with measures;   measures    
               protocols;         minor gaps   significant   lacks       provided.   
               well-thought-out   in incident  gaps.         incident                
               incident response. response.                  response                
                                                             plan.                   
  ------------ ------------------ ------------ ------------- ----------- ----------- -----

  ----------------------------------------------------------------------------------------

  --------------------------------------------------------------------------------------------
  **Backup   Detailed and      Good         Basic         Vague        No                /10
  and        practical         strategies   strategies;   strategies   backup/recovery   
  Recovery   backup/recovery   with minor   lacks         with major   plan provided.    
  Plan**     strategies;       gaps in      clarity.      gaps.                          
             thorough          detail.                                                   
             explanation.                                                                
  ---------- ----------------- ------------ ------------- ------------ ----------------- -----

  --------------------------------------------------------------------------------------------

  -------------------------------------------------------------------------------------------------
  **Policy        Thorough        Good           Basic          Vague          No policy      /10
  Integration**   integration of  integration;   integration;   integration;   integration.   
                  policies; clear minor issues   lacks depth.   unclear                       
                  enforcement     in clarity.                   enforcement.                  
                  strategies.                                                                 
  --------------- --------------- -------------- -------------- -------------- -------------- -----

  -------------------------------------------------------------------------------------------------

  -------------------------------------------------------------------------------------------------------------
  **Documentation**   Comprehensive and Good             Basic            Poor             No              /5
                      clear             documentation;   documentation;   documentation;   documentation   
                      documentation;    minor            some clarity     lacks            provided.       
                      well-organized.   organizational   issues.          organization.                    
                                        issues.                                                            
  ------------------- ----------------- ---------------- ---------------- ---------------- --------------- ----

  -------------------------------------------------------------------------------------------------------------

  ------------------------------------------------------------------------------------------------------
  **Presentation**   Engaging,       Good            Basic           Poor            No             /5
                     clear, and      presentation;   presentation;   presentation;   presentation   
                     thorough        minor           struggles with  lacks clarity   given.         
                     presentation;   engagement      Q&A.            and engagement.                
                     excellent Q&A   issues.                                                        
                     handling.                                                                      
  ------------------ --------------- --------------- --------------- --------------- -------------- ----

  ------------------------------------------------------------------------------------------------------
