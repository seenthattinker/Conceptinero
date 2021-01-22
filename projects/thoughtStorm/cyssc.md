CYSSC Platform Modernization      
====================================

### What scientific or technological uncertainties did you attempt to overcome? (Maximum 350 words)      

￼
<!---
The approach to this SRED application is *process as patent*. The client was tasked with auditing and documenting three systems that sat upon an IBM AIX UNIX infrastructure with Power 7 and 8 processors. Once the audit of the three systems was completed, their business, presentation, and data layers understood, a port to Red Hat Linux and then to the cloud.

The theory of the SRED application is that the process of migrating old, complex legacy systems on UNIX variants, but especially IBM, which has a huge footprint in the banking and government sectors of the computing world, is in itself a process patented by experience which provides a road map for similar projects that can be marketed directly to the legacy IBM market looking to go to cloud, which, is trends persist, will be nearly one hundred percent of these systems.    
-->

We needed a process to move three layer systems
&mdash;
data,
business,
presentation
&mdash;
from a legacy infrastructure to the cloud.




The Ministry of Children,
Community and Social Services (Ministry) mandate includes responsibilities for social assistance,
child welfare,
and spousal and child support.
The Ministry relies on a variety of applications to support its mandate.
Of these applications,
the three largest are the Social Assistance Management System (SAMS) to deliver social assistance services,
the Child Protection Information Network (CPIN) as the consolidated case management system for Children’s Aid Societies that maintains critical information about every child in need of protection,
and the Family Case Management System (FCMS) to manage and process payments for spousal and child support.
The Common Cluster Platform (CCP) hardware used to house these applications is IBM Power 7/8 infrastructure on which the underpinning technology stack run.
The legacy Operating System (OS) is IBM's AIX UNIX variant.


AIX cannot go directly to the cloud.
The three applications had to first be ported to Linux,
along with the CCP.
This is a non-commercial use so we had flexibility with the Linux base.
After research and investigation,
we selected Red Hat Enterprise Linux (RHEL).
We had to design the process in conformity to,
*GO-ITS 25.21 Cloud First Principles and Security Requirements*,
The Ontario Public Service (OPS) security and compliance standard.

<!--
Process is the SRED
-->

The plan had to include,
new ITS GoCloud infrastructure,
decommissioning existing Common Cluster Platform (CCP),
adopting Cloud technology,
performance tuning,
and setting up a Disaster Recovery Plan (DRP) inclusive of infrastructure.



The migration
&mdash;
lift and shift
&mdash;
of the AIX hosted applications:
SAMS,
CPIN,
FCMS,
mFTIS,
as well as operational tools and software such as OEM,
Nagios,
RTC,
Cognos,
Control-M,
Informatica,
and others to the new platform.

Application re-architecture was not in scope.
Only changes required to make applications run in the ITS GoCloud platform were part of the process.
The first stage we developed was accurate inventory of Ministry requirements and current state of technology.
This involved ensuring documentation was accurate and complete.
Then we built an alignment on the *target state* infrastructure,
including documenting the assumptions and technical constraints.
The infrastructure was quite old compared to today’s standards.
The state of technology at the beginning of the project had several shortcomings and/or limitations,
as well as technological problems and unknown elements.


### What work did you perform in the tax year to overcome the scientific or technological uncertainties described in line 242?

APPLICATION MIGRATION   

We created a compatibility map with the new infrastructure to integrate the systems.
This involved a forensic audit of all the working parts.
For each of these component parts we had to map to a duplicate service on GoCloud.
Not all the technical parameters and integration points were known.


DATA MIGRATION      

We had to move one data structure to another.
The legacy system had all of the data in one bulk layer.
The new architecture has a data layer divided into three components:
links,
text,
and images.
We were uncertain of the development approach.
We needed a data connection and data transport between two Content Management System (CMS) versions,
one in which the data content could be displayed from both sides from the different versions.
We had to map applications and data migration into logical buckets
&mdash;
applications and database by lines of business,
technical complexity,
and similarity.


CLOUD MIGRATION ASSESSMENT AND PLANNING    

We had to port each application across two fields of operation,
the first being RHEL and the other being GoCloud.                       
We had to engage stakeholders,
catalog resources and software on premises,
examine Service Level Agreements (SLA),
ensure continuous operation as we ported to the cloud.               

We categorized Application needs and workload e.
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






Red Hat is a non-commercial platform.
GNU License.
The SRED is the process.
