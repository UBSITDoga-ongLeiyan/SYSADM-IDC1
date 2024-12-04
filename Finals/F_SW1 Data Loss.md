+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 282fc004a82447809c3a4e4dfce22e99 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Leiyan M. Doga-ong         | DATE PERFORMED:        | /40      |
|                                  | 11/19/24               |          |
+----------------------------------+------------------------+----------+
| Section: IDC1                    | DATE SUBMITTED:        |          |
|                                  | 11/19/24               |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Data Loss

Instruction/s:

Read and analyze the data loss scenarios provided. Create a data
recovery plan by providing impact assessment, recovery plan and
preventive measures for each scenario. Lastly, answer the reflection
question.

**Evaluation Criteria Guide:**

1.  Impact Assessment:

-   Accurately identifies the potential consequences of the data loss.

-   Quantifies the potential financial, operational, and reputational
    impact.

    1.  Recovery Plan:

```{=html}
<!-- -->
```
-   Proposes a detailed, feasible, and timely recovery plan.

-   Includes steps for data restoration, system recovery, and business
    continuity.

-   Identifies the necessary resources and personnel.

    1.  Preventive Measures:

```{=html}
<!-- -->
```
-   Recommends specific measures to prevent similar incidents in the
    future.

-   Addresses potential vulnerabilities in security, hardware, and
    software.

-   Proposes regular backups, security audits, and employee training.

-   Recommends appropriate RAID levels for data redundancy and
    performance.

+----------------+----------------+----------------+-----------------+
| **Scenario**   | **Impact       | **Recovery     | **Preventive    |
|                | Assessment**   | Plan**         | Measures**      |
+================+================+================+=================+
| A system       | Critical       | To lessen the  | Several         |
| administrator  | corporate      | effect of a    | preventive      |
| accidentally   | activities     | database       | measures can be |
| deletes a      | that rely on   | failure, take  | done to avoid   |
| critical       | the database   | immediate      | future database |
| database       | may be         | action to      | failures and    |
| containing     | disrupted,     | isolate the    | data loss.      |
| customer       | resulting in   | affected       | Regular         |
| information    | reduced        | system and     | thorough and    |
| while          | productivity   | prevent        | incremental     |
| performing     | and            | additional     | backups are     |
| routine        | efficiency.    | data loss. If  | required to     |
| maintenance.   | Revenue loss   | you need help, | ensure data     |
|                | could be       | contact the    | recoverability. |
|                | caused by      | database       | Access to       |
|                | system         | administrator  | crucial systems |
|                | failures and   | or the IT      | and data should |
|                | dissatisfied   | support team.  | be restricted   |
|                | customers.     | Lost data can  | to authorized   |
|                | Service        | be recovered   | persons using   |
|                | interruptions  | by using       | strong access   |
|                | and data       | database       | restrictions.   |
|                | privacy        | backup and     | System          |
|                | violations     | recovery       | administrators  |
|                | could harm the | solutions. If  | should be       |
|                | company\'s     | backups are    | trained on the  |
|                | reputation,    | not            | best practices  |
|                | possibly       | accessible,    | for data        |
|                | resulting in a | data recovery  | handling and    |
|                | loss in        | software may   | deletion.       |
|                | customer trust | be used as an  | Additionally,   |
|                | and negative   | alternative.   | version control |
|                | publicity.     | The database   | systems can be  |
|                |                | can be         | used to track   |
|                |                | returned to    | changes to      |
|                |                | its original   | important data, |
|                |                | state after    | enabling easy   |
|                |                | the data has   | rollback if     |
|                |                | been           | necessary.      |
|                |                | recovered.     |                 |
|                |                | Thorough       |                 |
|                |                | testing of the |                 |
|                |                | restored       |                 |
|                |                | system is      |                 |
|                |                | required to    |                 |
|                |                | assure its     |                 |
|                |                | proper         |                 |
|                |                | operation.     |                 |
+----------------+----------------+----------------+-----------------+
| A major hard   | A hard drive   | To reduce the  | Several         |
| drive failure  | failure can    | impact of a    | preventive      |
| occurs on a    | have a         | hard disk      | measures can be |
| server hosting | substantial    | failure,       | put in place to |
| essential      | impact on      | immediately    | prevent data    |
| business       | business       | isolate the    | loss and hard   |
| applications,  | operations by  | affected       | disk failures   |
| resulting in   | disrupting     | server to      | in the future.  |
| data loss.     | services and   | avoid further  | Redundancy and  |
|                | applications   | data loss.     | fault tolerance |
|                | hosted on the  | Start the      | can be achieved |
|                | failed drive,  | recovery       | by implementing |
|                | resulting in   | procedure by   | RAID            |
|                | lower          | getting in     | configurations, |
|                | productivity   | touch with the | such as RAID-1, |
|                | and            | IT support     | RAID-5, or      |
|                | efficiency.    | staff. If RAID | RAID-6. It is   |
|                | Lost revenue   | is configured, | important to    |
|                | can be caused  | try data       | regularly       |
|                | by system      | recovery from  | backup          |
|                | outages and    | the redundant  | important data  |
|                | possible data  | devices.       | and keep it     |
|                | recovery       | Otherwise, you | offsite.        |
|                | expenses. The  | should look    | Furthermore,    |
|                | o              | into data      | hardware        |
|                | rganization\'s | recovery       | components can  |
|                | reputation can | services. Once | have their      |
|                | be harmed by   | the data has   | lifespan        |
|                | service        | been           | extended and    |
|                | interruptions  | retrieved,     | problems        |
|                | and possible   | replace the    | avoided with    |
|                | data breaches, | failed drive   | regular         |
|                | which can      | and restore    | inspection and  |
|                | result in a    | the system and | maintenance.    |
|                | decline in     | data from      |                 |
|                | consumer trust | backup.        |                 |
|                | and poor       |                |                 |
|                | publicity.     |                |                 |
+----------------+----------------+----------------+-----------------+
| A powerful     | Significant    | Recovering     | A thorough      |
| earthquake     | disruptions    | from a data    | disaster        |
| strikes a data | could occur    | center failure | recovery plan   |
| center,        | for all data   | requires quick | must to be      |
| causing        | center-hosted  | action.        | created and     |
| significant    | services and   | Prioritize     | evaluated on a  |
| damage to      | apps. Business | data recovery  | regular basis.  |
| hardware and   | disruption,    | utilizing      | Important       |
| power          | data recovery, | offsite        | information     |
| i              | and hardware   | backups, cloud | needs to be     |
| nfrastructure. | replacement    | storage, or    | backed up and   |
|                | could cost the | data recovery  | kept offsite in |
|                | company a lot  | services after | a secure        |
|                | of money.      | evaluating the | location.       |
|                | Extended       | damage and     | Single points   |
|                | service        | engaging on    | of failure can  |
|                | outages and    | the disaster   | be lessened     |
|                | possible data  | recovery plan. | using           |
|                | loss can also  | Use a disaster | redundancy in   |
|                | seriously harm | recovery site  | network         |
|                | the company\'s | or temporary   | connections,    |
|                | brand          | infrastructure | cooling         |
|                | reputation,    | to restore     | systems, and    |
|                | which can      | services.      | power sources.  |
|                | result in a    | Lastly,        | Getting the     |
|                | decline in     | rebuild the    | right insurance |
|                | client loyalty | data center    | coverage can    |
|                | and bad        | and repair any | also lessen the |
|                | publicity.     | damaged        | financial       |
|                |                | equipment.     | damages brought |
|                |                |                | on by a data    |
|                |                |                | center failure. |
+----------------+----------------+----------------+-----------------+
| A ransomware   | There might be | In order to    | Strong security |
| attack         | a disruption   | lessen the     | procedures are  |
| encrypts       | to vital       | effects of a   | necessary to    |
| critical data, | corporate      | ransomware     | stop ransomware |
| rendering it   | systems and    | attack,        | attacks. Put    |
| inaccessible.  | procedures,    | immediate      | strong security |
|                | which would    | action is      | measures in     |
|                | reduce         | essential. To  | place, such as  |
|                | efficiency and | stop the virus | intrusion       |
|                | productivity.  | from spreading | detection       |
|                | Expenses for   | further,       | systems and     |
|                | ransom         | isolate the    | firewalls, and  |
|                | payments, data | affected       | conduct         |
|                | recovery, and  | devices and    | frequent        |
|                | system         | seek help from | security        |
|                | restoration    | cybersecurity  | assessments.    |
|                | could be very  | professionals. | Employees       |
|                | high for the   | Try to         | should receive  |
|                | company.       | retrieve data  | training on     |
|                | Furthermore,   | from backups   | cybersecurity   |
|                | service        | or unaffected  | best practices. |
|                | interruptions  | systems. If    | Update software |
|                | and data       | decryption     | and systems     |
|                | breaches can   | doesn\'t work, | with the most   |
|                | harm an        | think about    | recent security |
|                | o              | data recovery  | patches.        |
|                | rganization\'s | services.      | Lastly, have a  |
|                | reputation by  | Lastly,        | thorough        |
|                | reducing       | restore clean  | recovery        |
|                | customer       | system images  | strategy in     |
|                | loyalty and    | and recovered  | place and keep  |
|                | causing poor   | data by wiping | regular         |
|                | reviews.       | and            | backups.        |
|                |                | reformatting   |                 |
|                |                | compromised    |                 |
|                |                | systems.       |                 |
+----------------+----------------+----------------+-----------------+
| A system       | Business       | In order to    | Make sure       |
| administrator  | operations can | lessen the     | backups are     |
| misconfigures  | be seriously   | effects of a   | functioning     |
| a backup       | disrupted by   | backup         | properly by     |
| system,        | system         | failure,       | testing them    |
| leading to     | outages,       | immediate      | regularly to    |
| data           | particularly   | action is      | avoid future    |
| corruption and | if they affect | essential.     | failures. Keep  |
| loss.          | important      | Contact the IT | an eye out for  |
|                | information.   | support staff, | mistakes and    |
|                | Delays in data | isolate the    | irregularities  |
|                | recovery could | affected       | in backup       |
|                | hinder crucial | system, and    | systems.        |
|                | procedures and | look into the  | Finally, put    |
|                | result in lost | problem. Try   | strong security |
|                | revenue. Fines | to retrieve    | measures in     |
|                | and legal      | data from      | place to guard  |
|                | repercussions  | earlier system | against         |
|                | may follow     | snapshots or   | corruption and  |
|                | noncompliance  | backups. Use   | unwanted access |
|                | with data      | data recovery  | to backups.     |
|                | privacy laws.  | software if    |                 |
|                | Backups that   | backups are    |                 |
|                | are improperly | corrupted. To  |                 |
|                | designed or    | avoid more     |                 |
|                | unprotected    | failures,      |                 |
|                | might make     | restore the    |                 |
|                | recovery even  | system from a  |                 |
|                | more difficult | known reliable |                 |
|                | and pose more  | backup and     |                 |
|                | security       | adjust the     |                 |
|                | threats.       | backup system. |                 |
+----------------+----------------+----------------+-----------------+
| **Reflection   |                |                |                 |
| Question**     |                |                |                 |
|                |                |                |                 |
| *How would you |                |                |                 |
| explain to     |                |                |                 |
| your           |                |                |                 |
| company\'s     |                |                |                 |
| stakeholders   |                |                |                 |
| if, despite    |                |                |                 |
| your best      |                |                |                 |
| efforts, some  |                |                |                 |
| data was still |                |                |                 |
| unrecoverable  |                |                |                 |
| after          |                |                |                 |
| implementing   |                |                |                 |
| data recovery  |                |                |                 |
| measures? What |                |                |                 |
| steps would    |                |                |                 |
| you take to    |                |                |                 |
| mitigate the   |                |                |                 |
| impact of this |                |                |                 |
| data loss and  |                |                |                 |
| prevent future |                |                |                 |
| occurrences?*  |                |                |                 |
|                |                |                |                 |
| When dealing   |                |                |                 |
| with           |                |                |                 |
| unrecoverable  |                |                |                 |
| data, open and |                |                |                 |
| understanding  |                |                |                 |
| communication  |                |                |                 |
| is essential.  |                |                |                 |
| Acknowledge    |                |                |                 |
| the problem    |                |                |                 |
| clearly and    |                |                |                 |
| offer your     |                |                |                 |
| heartfelt      |                |                |                 |
| apologies for  |                |                |                 |
| any            |                |                |                 |
| inconvenience. |                |                |                 |
| Describe the   |                |                |                 |
| steps taken to |                |                |                 |
| recover the    |                |                |                 |
| data,          |                |                |                 |
| including the  |                |                |                 |
| difficulties   |                |                |                 |
| that were      |                |                |                 |
| faced.         |                |                |                 |
| Evaluate the   |                |                |                 |
| consequences   |                |                |                 |
| of the data    |                |                |                 |
| loss by        |                |                |                 |
| determining    |                |                |                 |
| the specific   |                |                |                 |
| data lost and  |                |                |                 |
| its            |                |                |                 |
| significance.  |                |                |                 |
| Provide        |                |                |                 |
| mitigating     |                |                |                 |
| measures such  |                |                |                 |
| data           |                |                |                 |
| restoration,   |                |                |                 |
| workarounds,   |                |                |                 |
| or acquiring   |                |                |                 |
| further        |                |                |                 |
| information.\  |                |                |                 |
| \              |                |                |                 |
| Put in place   |                |                |                 |
| more rigorous  |                |                |                 |
| data           |                |                |                 |
| protection     |                |                |                 |
| measures, such |                |                |                 |
| as frequent    |                |                |                 |
| backups,       |                |                |                 |
| strong         |                |                |                 |
| security       |                |                |                 |
| procedures,    |                |                |                 |
| and frequent   |                |                |                 |
| system audits, |                |                |                 |
| to stop        |                |                |                 |
| similar        |                |                |                 |
| incidents in   |                |                |                 |
| the future.    |                |                |                 |
| Employees      |                |                |                 |
| should receive |                |                |                 |
| backup and     |                |                |                 |
| data security  |                |                |                 |
| training.      |                |                |                 |
| Consider       |                |                |                 |
| performing a   |                |                |                 |
| thorough       |                |                |                 |
| investigation  |                |                |                 |
| to identify    |                |                |                 |
| the root cause |                |                |                 |
| of the data    |                |                |                 |
| loss and       |                |                |                 |
| updating the   |                |                |                 |
| disaster       |                |                |                 |
| recovery plan  |                |                |                 |
| accordingly.   |                |                |                 |
|                |                |                |                 |
| To reduce the  |                |                |                 |
| effect of data |                |                |                 |
| loss, use best |                |                |                 |
| practices like |                |                |                 |
| regular backup |                |                |                 |
| testing,       |                |                |                 |
| robust backup  |                |                |                 |
| strategies,    |                |                |                 |
| secure offsite |                |                |                 |
| storage,       |                |                |                 |
| strong         |                |                |                 |
| encryption,    |                |                |                 |
| and regular    |                |                |                 |
| system         |                |                |                 |
| updates.       |                |                |                 |
| Provide an     |                |                |                 |
| accurate       |                |                |                 |
| incident       |                |                |                 |
| response       |                |                |                 |
| strategy,      |                |                |                 |
| frequently     |                |                |                 |
| educate staff  |                |                |                 |
| members about  |                |                |                 |
| data security, |                |                |                 |
| and            |                |                |                 |
| monitor and    |                |                |                 |
| enhance        |                |                |                 |
| security       |                |                |                 |
| protocols.     |                |                |                 |
+----------------+----------------+----------------+-----------------+

**Grading Rubric**

  ----------------------------------------------------------------------------------
  **Criteria**   **Excellent (10       **Satisfactory (7  **Needs        **Score**
                 pts)**                pts)**             Improvement (4 
                                                          pts)**         
  -------------- --------------------- ------------------ -------------- -----------
  Impact         Accurately identifies Identifies some    Fails to       
  Assessment     all significant       key impacts but    identify       
                 impacts.              misses others.     significant    
                                                          impacts.       

  Recovery Plan  Proposes a            Proposes a basic   Fails to       
                 comprehensive,        plan but lacks     propose a      
                 detailed, and         detail or          viable plan.   
                 feasible plan.        feasibility.                      

  Preventive     Recommends strong,    Recommends some    Fails to       
  Measures       specific preventive   preventive         recommend any  
                 measures, including   measures but lacks preventive     
                 appropriate RAID      detail or          measures.      
                 levels.               specificity.                      

  Reflection     Clearly and concisely Provides a basic   Fails to       
  Question:      explains the          explanation but    provide a      
                 situation to          lacks clarity or   satisfactory   
                 stakeholders,         empathy.           explanation.   
                 acknowledging the                                       
                 limitations of data                                     
                 recovery.                                               

  **Total                                                                **/40**
  Score:**                                                               
  ----------------------------------------------------------------------------------
