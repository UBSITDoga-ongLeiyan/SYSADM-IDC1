+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 98e2aa5e54aa40459b660fac57048844 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Doniah Camille Dizon,      | DATE PERFORMED:        | /50      |
| Leiyan Doga-ong                  | 04/12/2024             |          |
+----------------------------------+------------------------+----------+
| Section: IDC1                    | DATE SUBMITTED:        |          |
|                                  | 04/12/2024             |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Capacity Management & Planning

# Part 2. Network Scalability Analysis

Recall the e-commerce website scenario we discussed earlier. Given the
expected surge in traffic, analyze the provided network topology
diagram. Identify potential bottlenecks and areas where scalability
might be a concern. Propose specific strategies to improve the
network\'s scalability and performance to ensure a seamless user
experience during the peak traffic period. Consider factors such as
increased user demand, new applications, and security threats.

The Edge Router connects the network to the Internet. Any issues with
bandwidth capacity or processing power at this layer could become a
bottleneck during high traffic demand. Each Layer 2 switch connects
multiple servers. If too many devices are connected, they can saturate
the switch ports. The lack of redundant paths could lead to downtime if
a component fails and if the servers are not load-balanced or equipped
to handle surges, performance degradation is likely.

To improve the network\'s scalability and performance, we added multiple
routers and switches to ensure failover capabilities. Then, implement
load balancers to distribute traffic efficiently across servers and
prevent any single server from becoming a bottleneck. Backup servers can
act as part of a load balancing setup where traffic and processing
requests are evenly distributed among multiple servers. This reduces the
load on individual servers, ensuring faster response times and higher
performance. During peak traffic periods, backup servers can handle the
surge, effectively scaling the network\'s capacity without requiring a
complete redesign. Also, if other servers fail, the back-up server
ensures the continuity of the services, protect data and minimizes
downtime. Add secondary uplinks between the Layer 2 switches and the
firewall to prevent single points of failure. Add more servers to each
VLAN and enable virtualization to scale resources dynamically. Also,
implement robust security protocols like firewall to mitigate threats,
especially during peak traffic periods when systems are more vulnerable.

![](vertopal_98e2aa5e54aa40459b660fac57048844/media/image2.webp){width="4.12122375328084in"
height="3.120138888888889in"}

![](vertopal_98e2aa5e54aa40459b660fac57048844/media/image3.png){width="7.027083333333334in"
height="4.279861111111111in"}

  ------------------------------------------------------------------------------
  Criteria          Excellent \| 10pts Good \| 7pts        Needs Improvement \|
                                                           4pts
  ----------------- ------------------ ------------------- ---------------------
  **Network         Accurately         Identifies key      Identifies some basic
  Analysis**        identifies         network components  network components
                    potential          and some potential  but lacks a
                    bottlenecks,       bottlenecks.        comprehensive
                    security risks,                        analysis.
                    and capacity                           
                    limitations.                           

  **Scalability     Proposes multiple  Proposes some       Proposes limited
  Planning**        relevant solutions relevant            scalability
                    and provides       scalability         strategies.
                    detailed           strategies but      
                    explanations,      lacks detail.       
                    including                              
                    potential                              
                    drawbacks and                          
                    benefits.                              

  **Evaluation of   Proposes           Provides a basic    Does not evaluate the
  Solutions**       comprehensive      evaluation of the   proposed solutions or
                    scalability        proposed solutions, provides a
                    strategies,        but lacks depth.    superficial
                    including specific                     evaluation.
                    recommendations                        
                    for hardware                           
                    upgrades, software                     
                    configurations,                        
                    and network                            
                    optimizations.                         

  **Proposed        Provides a         Provides a basic    Does not provide a
  Design**          detailed and       design but lacks    clear and detailed
                    well-justified     specific details    design.
                    design, including  and justifications. 
                    network diagrams,                      
                    configuration                          
                    details, and                           
                    implementation                         
                    plans.                                 

  **Evaluation and  Provides a         Provides a basic    Does not evaluate the
  Justification**   thorough           evaluation of the   proposed solutions or
                    evaluation of the  proposed solutions, provides a
                    proposed           but lacks depth.    superficial
                    solutions,                             evaluation
                    considering                            
                    factors like cost,                     
                    complexity, and                        
                    potential impact.                      

  Score:                                                   /50
  ------------------------------------------------------------------------------
