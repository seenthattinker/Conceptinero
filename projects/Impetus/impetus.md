Impetus T661
=================

### What technological obstacles did you have to overcome? 350 words max – 50 lines of 78 characters

Impetus provides virtual collaboration contexts,
as well as tools and management for said contexts.
The tool set is Drupal&trade; 7 with custom modules.
The following technological obstacles were encountered.

INSITE EVENT PLATFORM&trade;

We had an asynchronous automatic portal generator built upon the Drupal Content Management System (CMS).
This formed the foundation for our collaboration context,
the InSite Platform&trade;.
For competitive advantage,
we realized the need for a synchronous platform,
or elements thereof,
and this became the business plan for the InSite Event&trade; Platform.

Because of the Drupal foundation,
everything we needed to add to make it synchronous had to work with Drupal.
This involved research and experimentation to assess whether any of the existing modules could serve our purposes.
In all instances they could not,
requiring that we develop the modules ourselves.

To improve security,
and for seamless integration of web meetings into client workflows,
we realized the need for an integrated web meeting solution.
It had to work with our private,
fully-managed portal platform for advisory boards,
workshops,
and virtual congresses.
We selected Zoom &copy;.
No suitable Drupal module existed.
we had to develop our own Zoom integration.

DATA COLLECTION AND WORKFLOW

We needed to retool our workflow to come up with something equivalent to an ERP (Enterprise Resource Planning).
We wanted to incorporate a lot of throughput and collaboration with office tools,
document production and distribution,
and data retention.
There was nothing readily available in the Drupal module library.


PORTAL BUILDER AUTOMATION

we wanted asynchronous task tracking by percentage completed for our automatic portal builder.
There was no out-of-the-box add-on available.
we needed an integrated data collection and workflow solution to collect structured data from the initial sales process through to the delivery and closure of client projects.


INSITE MAPPING&trade; GAMIFICATION TOOL

We needed to abstract our backdrop canvas,
treasure map,
and plotting tools,
sails and anchors,
for any type of plotting/mapping activity.
We needed to extend our drag and drop functionality.
There wasn't anything that could be integrated with Drupal and the Impetus set of custom tools.


### What work did you perform in the tax year to overcome those technological obstacles?   700 words max - 100 lines of 78 characters

THE INSITE EVENT PLATFORM

In order to improve the security and seamless integration of web meetings into client workflows,
Impetus took to developing an integrated web meeting solution within their private and fully-managed portal platform for advisory boards,
workshops,
and virtual congresses.
Given its widespread use and superior performance,
the Zoom API was chosen as the web meeting integration service.
However,
much custom development was required to integrate the meeting registration,
meeting session/stage,
and reporting capabilities into Impetus' Drupal-based platform.
No other Drupal modules or open source libraries join together comprehensive meeting booking,
registration,
broadcast embedding,
and reporting capabilities.
For this project,
a custom registration flow,
integration with Impetus' user engagement tracking tool,
a secure joining process (using personal data obfuscation when sending to remote servers),
and comprehensive in-session real-time activities were developed.
No other platform we could find has integrated and abstracted these elements into a secure,
single-tenant platform.
Obstacles we had to overcome included mapping of portal users to meeting registrants on the Zoom side;
instant user attendance tracking since the data can't be queried on the Zoom side;
custom styling of the embedded broadcast since Zoom only provides a very basic web client;
and real-time discussion forums using a node.js server that maintains all of Impetus' unique comment functionality.

There were no Drupal modules to bring API capability for Zoom.
The idea was definitely in the community.
There were open source projects in development,
but nothing even beta,
only alpha,
and therefore unsuitable for production use.
They had to develop our own.

This necessitated a robust registration process with tiered access,
delimiting between temporary users,
users,
managers,
administrators,
and advisers,
so that these and other roles could be properly assigned to a Zoom meeting.
They coded an obfuscation of the identity so that it could participate in Zoom but not register a user or password with Zoom.
This means we fully ported Zoom to our virtual context.
Their technology fully integrated into our InSite virtual collaboration context,
but a lot of tinkering was required.



DATA COLLECTION AND WORKFLOW


Impetus implemented comprehensive workflow and essential data store for all our sales and client data,
Impetus integrated with our Google Workspace&trade;,
and essentially created an ERP system customized to what we do
&mdash;
virtual collaboration.
Our sales and client teams can access the data from the right side panel.
We created our workflow with AppSheet&trade;.
The requirement for this experimentation was the cost prohibitive options for cloud based ERPs on the market.
SalesForce&trade; or NetSuite&trade; are not feasible.

Two major features were added.
Automatic progress tracking for all types of asynchronous activities within the portal,
and the corollary UX front end design so advisers know where they are within a checkpoint.
This can be auto-deployed with the portal builder automation.
Previously,
we only had progress tracking on the client reporting side,
but not for the end user themselves.
There were no existing options in the Drupal open source community that met all of our needs.
We had to build our own around touchpoints.
We built the automation of form creation at the administrator level
&mdash;
the InSite Surveyor
&mdash;
so the virtual collaboration can take registered input.
We built upon the Drupal form module,
but the auto-creation was built interdependently atop that.




### What scientific or technological advancements did you achieve or attempt to achieve as a result of the work described in line 244? (Maximum 350 words)

We pushed the capabilities of Drupal as a CMS to become the foundation of a synchronous event management platform.
We accomplished this by substantially adding to the Drupal modules library.
We advanced automated portal creation to further customize the online collaboration platform we have created,
maintain,
and expand.
We extended Drupal significantly by allowing it to operate with Zoom through a bridged API that permits the site authentication and role allotment
&mdash;
manager,
organizer,
administrator,
and participant,
among others
&mdash;
by our system as opposed to the login system associated with Zoom.
In many ways,
we fabricated an ERP atop the Drupal CMS,
incorporating Google Workspace.

THE INSITE EVENT PLATFORM

On a technological level,
they integrated the Ajax Comments with Node.js libraries.
They found and corrected several bugs in the Ajax Comments module,
and they expanded it's functionality to handle the custom comment-related features that we added to our platform.
We created a Drupal compatible Zoom module which integrated with our existing authentication and role and privilege configuration.
This places us in best-of-class in the online collaboration market.


INSITE MAPPING GAMIFICATION TOOL

They developed their our own custom library/module,
using the JavaScript libraries jQuery draggable and jQuery droppable,
and the qTip2 library.


We extended our collaboration platform to incorporate synchronous functionality in meetings,
document production,
video,
audio,
conferencing,
and the ability to stratify these synchronous capabilities across various roles and privileges.
This places us in a more competitive position in the online collaboration market.
