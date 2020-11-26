Robo Rep T661
=================


### What scientific or technological uncertainties did you attempt to overcome? (Maximum 350 words)

This technology evolved out of the work of a medical device representative who found himself wasting copious numbers of hours traveling to hospitals to be present at operations to instruct medical practitioners on medical
The medical device representative wanted to know if there was a way to do his job without being physically present.
He began to investigate the technology of telepresence,
but it was nowhere near where it needed to be to substitute for him in an operating room, there were no known or novel technological approaches to telepresence for surgery rooms. That began the experimental process to come up with a robotic representative that could stand in for a medical device representative in an operating theater, allowing the medical device representative to have eyes and the ears in the operating room,
and the ability to point,
instruct,
and communicate through the robotic device.

The technical uncertainty involved merging laser technology with recognition technology,
a term called *telepresence*,
and a control panel
&mdash;
currently operating on an iMac
&mdash;
through which a very complicated system of devices,
all mounted on a portable,
easily assembled and disassembled system,
can be operated remotely.
There were a number of moving parts that had to be negotiated over a network
&mdash;
cameras,  
lasers,
robotic motion,
computer code to govern action/reaction,
data layer based on visual recognition,
associated data layer with device instructions,
to name but a few
&mdash;
and these provided a number of test scenarios they we to run through,
documenting many failures to overcome the clear system uncertainty involved in the merger of the hardware and software.




The project represented an ergonomic challenge in the basic moving parts of the robotic medical device representative.
What was the best design for all of the functionality required by the medical device representative?
While robotics have insinuated themselves into many professional and manufacturing situations,
telepresence in an operating theater is completely new territory.
How could portability,
assembly,
and disassembly be packaged in with a functional robotic representative,
while not impacting the realtime nature and laser accuracy which was required to be replicated and reliable to 100%,
in each successive application in any new operating theater.

The next block of uncertainty was the complicated networking and cabling required to connect all of the various devices that would have to be in synchronization and governance to send and receive data and not confound the problem of movement for the robotic device.
The existing technology and knowledge base level at the onset of this project was limited to the functional objective usually only being accomplished using a plurality of different analog circuit boards,
cameras,
and servo controllers within many independent devices,
and not within one integrated,
and compact footprint and form factor.


### What work did you perform in the tax year to overcome the scientific or technological uncertainties described in line 242?

#### Electrical & Hardware

We needed to come up with an interface board that would have the different voltages available for the different peripherals.
The challenge was to be able to incorporate a single voltage supply,
and to then break down those voltages and ensure we provided enough current for each peripheral,
no underpowering and certainly no surges.

We created a new board to sustain a new power management layer responsible for orchestrating each device’s individual power needs,
as well as the different methods of integration (the limited serial, multi-drop-bus (MDB).
The protocols were determined by the embedded OS.

Mount location was achieved through experimental development,
discovering where the main power supply was going in,
and developing circuitry design that would work with the different voltages with a sufficient amount of current considering pre-existing component layout caused challenges.

The power supplies had to be highly efficient so overheating wouldn’t occur.
ESD testing was completed after adding a new component and proved satisfactory.
It was next necessary to convert the RS-232 to down to SPI,
so that the board would be able to communicate with all components.
Because MDB is a sort of serial,
but also all components are connected to the electrical circuit,
we encountered issues with different types of analog and digital peripherals in the connection.
A process of arbitration determines which device sends information at any point.
Work would continue next year.


#### Laser Pointer
The laser pointer presented unique telepresence challenges.
We had to articulate multiple trays and drawers of surgical components that may or may not get used.
Dozens of device options required articulation based on what's happening during the operation.
We had to be able to point at different parts,
describe them,
how to assemble and use them,
define conditions under which devices get used,
and which ones don't.

#### Cameras
The reason we have two cameras is so one can see where the laser points and ensure they're pointing at the correct thing,
and the second camera to look around the operating room and see what's going on,
who's talking and other important live data.

The top gimbal used two servo motors and two gear boxes in the final configuration where we can manipulate that laser pointer correctly.
All of this was done by experimental development,
systematically attempting a series of unusual servo alignment configurations,
experimenting with them,
determining how they failed the complex merger of all our needs,
then rebuilding with what we had learned.












### What scientific or technological advancements did you achieve or attempt to achieve as a result of the work described in line 244? (Maximum 350 words)

We built a system to operate at least six networked devices and some gear boxes.
The gear boxes are uniquely assembled into three different gimbals.
There are two high resolution digital cameras and a laser pointer.
We unified all of these system uncertainties into a working prototype.
We performed experimental development by systematically iterating through our design challenges to strip away configuration assumptions that did not pan out in prototyping.
We had knowledge
&mdash;
and the industry had knowledge
&mdash;
of how each of the component types worked individually,
but not together,
and there existed no tangential industry uses that bore sufficient similarity to a medical device representative telepresence.

We developed a telepresence apparatus which includes a first computer assembly configured to interface with a first memory assembly configured to tangibly store programmed coded instructions.
The programmed coded instructions are configured to urge the first computer assembly to compute whether to suspend transmission of an aspect of a telepresence data unit to the second computer assembly via the communication network,
depending on a match made between a user gesture signal and a predetermined user gesture.

There were many uncertainties in the engineering of the product.
We needed a number of brackets and number of moving parts that were quite complex that had never been put together before and we had to maintain the ideal of easy assembly,
easy disassembly,
and easy portability.

In this fiscal period we developed a two axis gimbals to integrate with the gear boxes to meet the ability to point a laser accurately as seen in realtime through a remote camera,
as part of our robotic and digital medical device representative.
We developed a novel and compact gear box form factor,
and in doing so set new patented standards for robotics in an operating theater.
The axes of both gear boxes intersected with one another.
This provided a new mobility for robotics specific to the operating theater.
Roborep is creating an affordable,
accessible,
telepresence system to provide on-demand,
real-time,
technical support during operating room procedures.  
It is a marriage of hardware and software.
The work has produced a patent:
U.S. patent application number 16/616327
&mdash;
Telepresence Management.
