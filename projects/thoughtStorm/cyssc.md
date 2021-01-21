CYSSC Platform Modernization      
====================================

### What scientific or technological uncertainties did you attempt to overcome? (Maximum 350 words)      



.. The approach to this SRED application is *process as patent*.
The client was tasked with auditing and documenting three systems that sat upon an IBM AIX UNIX infrastructure with Power 7 and 8 processors.
Once the audit of the three systems was completed,
their business,
presentation,
and data layers understood,
a port to Red Hat Linux and then to the cloud.

.. The theory of the SRED application is that the process of migrating old,
complex legacy systems on UNIX variants,
but especially IBM,
which has a huge footprint in the banking and government sectors of the computing world,
is in itself a process patented by experience which provides a road map for similar projects that can be marketed directly to the legacy IBM market looking to go to cloud,
which,
is trends persist,
will be nearly one hundred percent of these systems.            

The Ministry of Children,
Community and Social Services (Ministry) mandate includes responsibilities for Social Assistance,
Child Welfare,
and Spousal and Child Support.
These three programs are foundational to the Ministry’s vision of helping children,
youth and adults access services,
supports and opportunities in their communities.


The Ministry relies on a variety of applications to support its mandate.
Of these applications,
the three largest are the Social Assistance Management System (SAMS) to deliver Social Assistance services,
the Child Protection Information Network (CPIN) as the consolidated case management system for Children’s Aid Societies that maintains critical information about every child in need of protection,
and the Family Case Management System (FCMS) to manage and process payments for spousal and child support.


The Common Cluster Platform (CCP) hardware used to house these applications is IBM Power 7/8 infrastructure on which the underpinning technology stack run.


Implementing a digital platform includes migrating to LINUX operating system,
new ITS GoCloud infrastructure,
decommissioning existing Common Cluster Platform (CCP),
adopting Cloud technology,
performance tuning,
and setting up a Disaster Recovery infrastructure.
It will also include the migration (“lift and shift”) of hosted applications such as SAMS,
CPIN,
FCMS,
mFTIS,
as well as operational tools and software such as OEM,
Nagios,
RTC,
Cognos,
Control-M,
Informatica,
etc.
to the new platform.
Application re-architecture is not in scope,
that is only changes required to make applications run in the ITS GoCloud platform will be accommodated.






***4.
Was the overall approach undertaken for the purpose of achieving a scientific or a technological advancement? Explain.
***                       

-   ***Advancements can occur in knowledge of new techniques,
but also in our understanding how best to use them and which solutions,
techniques,
are appropriate for which purposes.
***                 

Team followed TSI’s internal process to plan a successful implementation:


The goal was to understand Ministry requirements and current state of technology.
Team needed to ensure this documentation was accurate and complete.
This was followed up by building an alignment on the *target state* infrastructure including documenting the assumptions and technical constraints.
The infrastructure was quite old compared to today’s standards.
The state of technology at the beginning of the project had several shortcomings and/or limitations,
as well as technological problems and unknown elements.


**Application Migration **        

Key challenges in moving application from one environment to another environment are the compatibility with the new infrastructure and integration with other systems.
Not all the technical parameters and integration points were known.


**Data Migration **               

The most difficult challenge is moving one data structure to another,
called Data Transmit,
where in the legacy system all of the data is in one bulk layer,
whereas in the new architecture,
it is divided into three components,
links,
text,
and images.
We were uncertain of the development approach which would allow data connection and data transport between two CMS system versions,
where the data content would be displayed from both sides from the different versions.


**Activities**   ***2.
Did the effort involve formulating hypotheses (*approaches,
* specifically aimed at reducing or eliminating that uncertainty? *Iterations,
*                      Explain.
***                       

*outcome,
success,
failures)*      TSI technical team came up with different scenario and based on early assessment,
applications and data migration was divided into logical buckets – this was based on applications and database by lines of business,
technical complexities & similarities.


A.
Cloud Migration Assessment and Planning                          

-   Discover and evaluate applications                  

-   Engage Stakeholders           

-   Catalog on-prem resources and software                      

-   Categorize Application needs and workload e.
g.
Platform,
Data,
Connectivity,
Security & Compliance,
Network,
High Availability and Maintenance  

-   Plan migration – PaaS/SaaS; “Lift and Shift; Application Evaluation; Application re-architecting; Organization Readiness e.
g.
Resources,
Risk,
Dependencies etc.


-   Plan sprints to migrate       

B.
Cloud Build & Implementation Support                           

-   Prepare migration plan and    
 execute iterative sprints     

-   Select Applications and       
 strategy – Rehost,
Refactor,

 Re-architect,
Re-build        

-   Apply / implement the         
 migration strategy            

-   Start sprints to move from    
 on-prem to Azure using        
 Automation tools available    

-   Optimize sprints – improve    
 capabilities and analyze      
 cost,
risk etc.


-   Secure and manage migration   
 sprints – Security,
Data      
 protection,
Network Access    
 Control,
NSG Azure DDoS       
 protection                    

C.
Delivery Team Automation       
Coaching and Knowledge Transfer   

-   Engage Stakeholders and       
 Ministry team members         

-   Prepare and communicate       
 Assessment report and         
 Migration Plan                

-   Analyze and evaluate          
 dependencies                  

-   Start iterative migration     
 sprints                       

![](media/image2.
emf){width="5.
32
6388888888889in"                  
height="3.
6319444444444446in"}    

***3.
Was the overall approach    
adopted consistent with a         
systematic investigation or       
search,
including formulating and
testing the hypotheses by         
experiment or analysis?           
Explain.
***                       

TSI team used the above-mentioned
approach as a starting points and
as more data became available,

tweaks were made to further       
refine it.


***5.
Was a record of the         
hypotheses tested and the results
kept as the work progressed?      
Explain.
***                       

*When describing work,
focus on   
the following:*                   

-   *Chronological Milestones of the process (initial design,
different versions of prototype development,
alpha testing,
beta testing,
black-box testing etc.
) *     

-   *Barriers /challenges encountered and how they were solved (or not solved)*       

-   *What results were obtained? What conclusions were drawn? What happened next? *         

*Also identify/describe the work done by subcontractors (if applicable).
*                     

*Include all activities (for example,
initial designs,
experiments,
analysis,
data collection,
prototype design/testing/modification,
all testing,
small scale and large scale beta testing and their results,
re-work due to problems,
re-design,
etc.
)*                 

*Provide dates by month if possible (example: “the version was developed by June 2017")*     

Yes,
Mandy to provide details     

**Major Technological              ***1.
Was there a scientific or a
Obstacles,
**                       technological uncertainty?***     

**Issues**                         -   *Explain the Specific         
 constraints and technological challenges,
they are often due to the specific nature of the product,
which technologies are to be used,
and/or the setting in which the software is to be used.
*

-   *What were the technical issues / challenges / limitations /constraints in this setting? *               

*(Underline technology issues,
not product functions and features.
) *                      

-   ***Need to understand the specific constraints or technological barriers ***    

-   ***Use specific technical terminology*\ ***Examples of constraints:*  

 -   *Volume of data (Process more than 150 terabytes of data)*                 

 -   *Footprint (Consume less than 100k of memory)*     

 -   *Scalability (Gracefully adapt to increase/decrease of load)*                    

 -   *Response time (Requests performed within 100ms)*  

 -   *Concurrency (Handle 1,
000 users simultaneously)*          

 -   *Synchronization (Synchronize with a sessionless system)*      

 -   *Stability (Mean Time Between Failure &gt; 1 year)*                    

 -   *Legacy & Compatibility Issues (Work seamlessly with legacy data model)*  

 -   *Open Source Tools and Plug-ins did not work as intended (Needed to develop new uses/extend capabilities*             

<!-- -->                          

-   Reduced maintenance and support overhead – 300K lines of code removed               

-   Ease of access – one-click sign in (SSO) with Azure AD,
Public Secure and Google\* accounts                      

-   Increased scalability (i.
e.
Audit/Logging scales to 5M+ events per minute); access to 1.
2B events                   

-   Established capabilities for clients by perform trends analysis and alerting         

-   Improved cross-platform enablement and security (windows,
iPad,
mobile) without needing VPN or PKI complexities                  

-   Adopted progressive,
modern methodologies and technologies and increased confidence in cloud migration delivery                      

-   Observed a cultural and behavioral shift (i.
e.
continuous delivery) and demonstrated highly effective ‘balanced team’ with increased levels of collaboration and shared responsibility                
