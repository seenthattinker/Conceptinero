

### What technological obstacles did you have to overcome? 350 words max – 50 lines of 78 characters



Impetus provides virtual collaboration contexts,
tools,
and management.
The tool set is Drupal&trade; 7 with custom modules.
We built an asynchronous automatic portal generator upon the Drupal Content Management System (CMS),
and this forms a foundation for our collaboration context
&mdash;
Impetus InSite Platform&trade;.
The InSite Event Platform&trade;,
our major development work for 2020,
presented the uncertainties which necessitated research and experimental development to move our business model into synchronous services,
true virtual collaboration defined by client need,
flexible and autonomous enough to allow clients to select the services they want for the collaboration.

The InSite Event Platform required that we move from an asynchronous to a synchronous model.
This makes us a live event system.
Our goal was to replicate everything possible in a live event where people are physically present.

Because of our foundation with Drupal,
everything we added to the asynchronous system to make it synchronous had to be done with a Drupal module.
This involved research and experimentation to assess whether any of the existing modules could serve our purposes.
In all instances they could not,
requiring that we develop the modules ourselves.

To facilitate a virtual event we needed live video,
which we facilitated by writing a Drupal module for Zoom.
We improved our workflow and data store for clients.

Finally,
we added to our automatic portal builder with asynchronous task tracking for percentage completed.
All of these tasks required experimental development to accomplish the goal.







### What work did you perform in the tax year to overcome those technological obstacles?   700 words max - 100 lines of 78 characters


ASYNCHRONOUS TO SYNCHRONOUS

InSite Event Platform borrowed from our asynchronous portal and incorporated it into its synchronous functioning,
like internal product launches,
internal company wide meetings with different departments and closed sessions within the overall virtual meeting context provided by InSite.

ZOOM INTEGRATION


This required Zoom&trade; integration.
There were no Drupal modules to bring API capability for Zoom.
The idea was definitely in the community.
There were open source projects in development,
but nothing even beta,
only alpha,
and therefore unsuitable for production use.
We had to develop our own.
This necessitated a robust registration process with tiered access,
delimiting between temporary users,
users,
managers,
administrators,
and advisers,
so that these and other roles could be properly assigned to a Zoom meeting.
We coded an obfuscation of the identity so that it could participate in Zoom but not register a user or password with Zoom.
This means we fully ported Zoom to our virtual context.
Their technology fully integrated into our InSite virtual collaboration context.

.. Was this API assessed? https://www.drupal.org/project/zoomapi Does the Impetus created API distribute collateral aggregated by Zoom? Chat notes? Recordings? Webhooks?

.. Is the Zoom API developed in-house being retained for competitive advantage or will it be offered to Drupal as a contribution to that open source project?

.. Has Trevor documented the leveraged libraries?


WORKFLOW AND DATA STORE

We implemented comprehensive workflow and essential data store for all our sales and client data,
We integrated with our Google Workspace&trade;,
and essentially created an ERP (Enterprise Resource Planning) system customized to what we do
&mdash;
virtual collaboration.
Our sales and client teams can access the data from the right side panel.
We created our workflow with AppSheet&trade;.

The impetus for this experimentation was the cost prohibitive options for cloud based ERPs on the market.
SalesForce&trade; or NetSuite&trade; are not feasible.

We knew that we would have to do scripting to glue the system together.
We had to do extensive work on the data modeling,
storing different types of data,
then setting up access points in the system to that data for different stakeholders.



PRIOR AND POST SESSION EVENT ACTIVITIES


We programmed events prior to,
in session,
and post session,
to provide a schedule to a virtual gathering.


PORTAL BUILDER AUTOMATION

Two major features were added this year.
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


SAILS AND ANCHOR TOOL

This is a gamified canvas that allows users to drag and drop icons to populate scenarios.
We extended our custom Drupal module to allow for the upload of custom icons and graphics.


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
