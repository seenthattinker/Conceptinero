xpertvr
==============


### What scientific or technological uncertainties did you attempt to overcome? (Maximum 350 words)


XpertVR &reg; exists in the virtual reality (VR) market space.
We produce simulations for training purposes and tools for market research.
We had the following technical uncertainties which required experimental development to overcome.

VR EMAIL DISTRIBUTION

We had to email reports to different types of people related to a VR experience.
The VR experience was networked.
The roles in the VR were participant and observer.
The participant had to make decisions.
The observer had to assess the decisions.
The participant and the observer received two different email reports from the same networked VR experience.
The participant was a student.
The observer was an instructor.

DATA COLLECTION IN VR

We had to develop data gathering methodologies and processes to access marketing data in created VRs.
There is no firm framework or industry standard for this work,
no working libraries or tool sets,
no data schema,
nothing.
As VR goes into the economy,
its role becomes more functional,
whereas,
most of the work in VR has been recreational
&mdash;
gaming as an example.
The market,
and its academic corollaries like business and marketing schools,
however,
are looking for productivity from VR.
Market surveys and consumer behavior studies are a natural match for VR.
The field is still undeveloped,
and,
as such,
much of the work is pioneering,
and,
therefore,
uses experimental development as its driving force.
We had to develop an eye-tracking tool for our VR scenarios to yield viable marketing data to our client.

SIMULATION PORTABILITY

There are two domains to VR:
simulation creation and simulation distribution.
Creation is the domain of VR scene/simulation creators,
software.
Distribution is the domain of hardware.
We employed a technique used in the gaming world
&mdash;
texture atlasing.
It required extensive experimental development to fit this gaming technique.
The results have been worthwhile,
though,
because we have created a portability to our scenarios by making them less memory intensive.
Many of the new VR headsets are separating themselves from the personal computer (PC) and cell phones
&mdash;
which have been inserted into non-PC connected headsets
&mdash;
and therefore require lighter,
or less memory and size intensive scenarios.
Texture atlasing has pushed our VR scenarios into the emerging independent headset market.



### What work did you perform in the tax year to overcome the scientific or technological uncertainties described in line 242?


NEW EMAIL GENERATION AND DISTRIBUTION FOR NETWORKED VR

XpertVR designed seven crime scenes to be experienced with VR.
They are accessed online with a headset at home.
When the participant steps into the crime scene they are given the details on how to navigate around,
interact with it,
and the basic case file as understood is imparted to the student.
This was designed for the Conestoga College Police Foundations diploma course.
They are then free to do their classwork in the 3D VR crime scene.
This is standard VR work,
but,
what makes this work stand out is the email distribution system brought to a networked VR experience.
The student is faced with decision-making siutations throughout the VR.
Those decisions are aggregated into a report for the student and a report for the professor.
Although this might sound straightforward,
in the VR world it is new territory.


The data collection was different for both parties.
Each of the seven crime scenes had multiple sub-scenarios for experience and random user experience
&mdash;
no repetition
&mdash;
so each student would have a different and random experience with the VR.
Each student has their VR experience assembled as a file which is sent to them,
as well as a separate file sent to the professor.
The file represents their decisions in the VR,
and from that the student writes the final report,
on which they are graded.

The unique aspect of this was the email component,
specifically the separate reports for the two grades of participants,
the student and the professor.
There were no existing libraries for this kind of development.
We diligently investigated and found nothing that suited our purpose.
We tried several third party solutions,
but they did not meet our needs.
We had to build this from scratch.
It represents a new email interface for networked VR applications.
It is absolutely reusable and it absolutely gives us a market advantage.

EYE-TRACKING TOOL

The business faculty at Brock University is using XpertVR templates to conduct market research studies.
One example is testing impulse buying.
Placing products at the front of the VR store which people might only buy upon seeing.
The research was designed to determine what forms buying patterns outside of what a user might need.
As this is being built out,
data collection tools are being created.
These data collection models will make us faster and better for other clients and are completely reusable.

We built an eye-tracking tool,
so as a VR user is going through a scenario a heat map is drawn when they stare at products.
This is not new to the VR creation space,
but ours works in tandem with a survey tool,
the other most important thing for the marketing sector.
The impetus behind productive VR is growing.
Marketers want to know not only how they can access data from clients,
but how they can do it without even asking questions,
hence the eye-tracking tool.
Only VR could deliver this,
a new level of honesty is marketing surveys because the VR scenario is not asking your opinion,
it's studying your attention through your eyes.

None of this work existed.
There were no libraries or APIs to gather data from the tracked eye behavior of a VR user.
We had to marry a data gathering based on eye-tracking,
data categorizing for storage schema,
and report preparation based on stored data.
This has significantly contributed to the practice of data gathering in VR,
and will certainly place XpertVR in a leading position in this market space.


ATLASING TEXTURES

We experimented with texture atlasing,
a common practice in the gaming world,
to reduce the size and resource consumption of our scenarios.
The repetition of small textures can be stored in a texture atlas.
The texture atlas is treated as a single unit by the graphics processor,
thus reducing resource utility.
The VR world has made little use of this gaming tool.
The APIs related to it are alien to the VR world.
We had to leverage from the GPU APIs to marry this technique to VR.
A PC VR headset is plugged into computer,
allowing for a high end,
resource intensive experience.
We leveraged from the gaming world to port our PC VR scenarios to standalone VR headsets.
This is becoming a lot more mainstream,
and will become a major developmental trend in VR to match the lower end standalone headsets.
We achieved this by atlasing our textures.
It has given us a methodology to single-source our scenarios.
We write the primary code once for the PC VR experience



### What scientific or technological advancements did you achieve or attempt to achieve as a result of the work described in line 244? (Maximum 350 words)


We advanced data gathering,
sorting,
and distribution,
and the utility of these things in multiple VR deployments,
as in the examples of policing and marketing.
We produced VR email distribution that emails reports to different types of people related to a networked VR experience.
This significantly advanced,
for us and for the industry,
the utility data gathering and distribution based on VR experiences.
We experimentally developed data gathering methodologies and processes to access and distribute marketing data in created VRs.
This has multiple uses in multiple industries.
It seriously advances our marketability,
reputation,
and gives us a competitive advantage in this market space.
We experimented outside of the VR development space,
importing techniques from the gaming world as associated with GPU APIs,
and experimenting with those techniques until they worked in the VR space.
This has allowed us to scale back the resource requirements for the emerging market of standalone headsets,
advancing the principle of single sourcing,
which is writing once and deploying to multiple platforms that have different resource economies.
This,
like the other experimental work described here,
has given us competitive advantage.
