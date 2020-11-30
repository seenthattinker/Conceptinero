

Challenges -
Ability to control experience with gaze, or later iterations, using hand motions, and hand motion detection, to control most aspects of experience.
prototypes built.

Development of Interactive Hardware Systems for Manipulation of 3D graphics
-As game engines were not natively built to function with touch screen, we experience system failure when integrating the two natively. It was uncertain how best to architect a multi-touch intelligence layer and capacitive membrane display that could generate the graphics near the glass and precisely resolve X/Y coordinates on screen and communicate with UDK.



AR/VR bad at?

Legible text. Due to refresh rates and lensing effects, the eye finds it hard to comfortably move along lines of text. Publishing on concave surfaces, bumping up anti-aliasing, and increasing contrast are all techniques that you can use. This is getting better with the next generation of headsets.
Tactile feedback. Fortunately, sound effects and visual animations can help to replace the feeling of touch.
The real world. Moving around in a real-world space can be dangerous with no real-world positional cues, so it’s essential for developers to think about building experiences that limit real-world locomotion. Again, this is being advanced with the next generation of devices.

Don’t make me sick! Latency, taking camera control from the user, moving horizon lines – these are all things that can cause sim sickness.

Use sound. Since VR designers don’t have control of the camera, we need to help guide users towards UI elements. Sound in VR is also great way to reinforce the sense of space and the experienced responsiveness of buttons and other widgets.


Occulus and Leap Motion -

Leap Motion VR Support Now Directly Integrated in Unreal Engine
Bringing hands into virtual reality just got a major upgrade. Now officially integrated in Unreal Engine 4.11, getnamo’s independent plugin for Leap Motion makes it faster and easier than ever to integrate Leap Motion Orion into your VR projects!

unreal_gif1 This popular community plugin is now the official plugin and brings new features like rigged character hands, Image Hands, passthrough, and built-in support for the Oculus Rift. Visit developer.leapmotion.com/unreal to get started.

The new plugin is also fully compatible with the radically new tracking capabilities of our Orion software. “It’s amazing to see the Leap Motion Controller improve over time in an engine where you have full control,” says getnamo, aka Jan Kaniewski.

“You could see hints of what it could be early on, but it was at times frustrating. Now with Orion that frustration is gone and you can just reach out and touch things. You know they’re not there, but in your mind and in your hands, phantom sensations give you momentary feelings of their solid realness.”

We believe that technology has the power to augment human capabilities. In many ways it has, but in many ways we’re still separated from the vast worlds of data trapped behind glass screens. The rise of VR means that the old dreams of interacting with digital content on a physical level are coming to life. But to make that happen, you need a more natural interface. You need the power and complexity of the human hand.

This is why we built Orion, which is fundamentally different than anything we’ve released before. It’s part hardware, part software, built from the ground up to tackle the unique challenges of hand tracking for VR. It comes with a huge increase in the general capabilities of our tracking technology and a profound shift in the reliability guarantees of markerless motion tracking systems.

Orion software represents a radical shift in how we do hand tracking. We’ve unlocked lower latency. Longer range. Better and faster hand recognition. Vastly improved robustness to cluttered backgrounds and ambient light. Even applications will be faster thanks to a new API that can be used initially in Unity. And we’re only getting started.

Because the shift is so stark, we’re making the software available today for Windows on the Leap Motion Controller. The beta preview comes with new demos like Blocks. Built on our upcoming interaction engine, Blocks shows how we can recreate nuanced physical interactions with digital objects in a way never before possible.

The Orion beta is just a first taste of what we have on the horizon, as we’re working directly with OEMs to embed Orion hardware into VR headsets.


Work Done

Gaze - VR experience. number of options related to control. hands and gaze were the most usable.
develop a system that allows UI UX challenge. Occulus interface provides Unity API to provide gaze control.
For hand motion - Leap Motion was used. shrunk down verion of Kinect - kinect deals with large broad body motions. Leap deals wiht hands. We glued leap motion to front of Occulus to recognize hands. We experinced leap motion is not prcise controller, as how well it can pick up hand shapes and gestures which impact realism and location accuracy.
There was a firmware update which helped this to improve the experience, but only after our development.

Although Occulus and Leap Motion were aware of each other, native interfaces existed, but did not provide types of gestures, acuracy. Leap motion and Unreal.
In order ot increase precision new modules, and libraries were developed as itdid not work properly out of hte bos. We needed to devise specific gestures or motions that users would be using, mapped out, tested, and ensure that precision and realism is achieved.

Firmware upgrade improves hardwares capability to recognize finer motion, which was missing in prevous broad sweeping gestures, push, pull, slive. load interfaec attached to the hand, load gestures related to specific motions. precision, and flexibility is alwatys in question with reslect ot the types of interactions you can have within the VR environments.



Development of Interactive Hardware Systems for Manipulation of 3D graphics
(September 2011 – November 2011) We began experimentation on manipulation of projections through glass, as implemented on a capacitive membrane that would enable touch controls. We first tried projection methods, but experienced throw distance issues at various angles. In addition, we discovered that the transparent capacitive membrane would also pick up the projected image, causing an unwanted 3D effect, which did not show on plain glass. We next hypothesized we should mount a 70-inch plasma to the glass, but immediately were faced with development of a non-standard industrial mounting system which would allow us to have a removable membrane connected at the appropriate distance in-front of the plasma screen, which would then be fastened at a close distance to the glass window. We built a miniature (42-inch) prototype version to test our hypotheses and integrated access to real-time content that was required through a combination of Wi-Fi network and locally sourced content. (November 2011 – December 2011) We explored the integration of the game engine to a touch screen, and created custom libraries which translate Windows touch inputs from C++ into C, and from C to the custom game languages. We sought a method to allow the game engine to receive touch input by development of a prototype using a native virtualized Flash Scale Form. Once we could resolve X/Y coordinates on screen and send to UDK, we experimented with having the input drive an object and respond. (January 2012 – July 2012) On the next iteration of a touch gesture translation engine, we discovered a challenge with UDK. It was technically difficult to adopt version control performance for our small infrastructure. UDK utilizes Input Package Management, but the packages were too dependent on a network build space, where material instancing could occur. We developed a customized module, a variant package management system, which allows isolation and update components of the geometry. We were successful assigning packages by modeller.

With regard to touch development, we explored the integration of game engines to a touch screen, and created a custom DLL which translates Windows touch inputs from C++ into C, and from C to the custom game languages. One obstacle was that the game engines were not built to function with a touch screen, and when we attempted to integrate the two, the system failed. Sought a method to allow the game engine to receive touch input. Built a prototype using a native virtualized Flash player called Scale Form. Found that Flash objects with 2D elements layered on top of the game engine responded well to touch input, and used this Flash object to drive the touch input. Once a clean touch input was present, it was fed to the game engine. Expanded on that using Windows gestures, and built our own DLL that utilized the Windows 7 gesture library, and translated it through the DLL to a language that was compatible with UDK, which was an improvement since we avoided using the virtualized Flash player.

While the visual aspect of VR is close to being solved, he stated that there are other areas of VR that need solutions, such as 3D audio, haptics, body tracking, and input.
computer latency might affect the simulation, providing a less-than-satisfactory end-user experience; the complicated nature of head-mounted displays and input systems such as specialized gloves and boots may require specialized training to operate,

The Oculus SDK is directly integrated with the popular game engines Unity 5, Unreal Engine 4,
The Leap Motion controller system consists of a hardware device and a software component which runs as a service or daemon on the host computer. The software component analyses images produced by the hardware and sends tracking information to applications. The Leap motion Unity plugin connects to this service to get data. Scripts included with the plugin translate Leap Motion coordinates to the Unity coordinate system. These scripts and additional graphic assets make it easy to add 3D, motion-controlled hands to a Unity scene.

Coordinate Systems
Unity3D uses a left-handed convention for its coordinate system, wheras the Leap Motion API uses a right-handed convention. (Essentially, the z-axis points in the opposite direction.) Unity also uses a default unit of meters, wheras the Leap Motion API uses millimeters. The plugin scripts internally transforms the tracking data to use the left-handed coordinate system and scales distance values to meters.

Unity coordinate system superimposed on the Leap Motion device in its HMD orientation.

Note: When working in Unity, always get Frame objects from the LeapServiceProvider. Otherwise, the data in the frame will still be in the native Leap coordinate system – not the Unity coordinate system. The LeapServiceProvider performs all the necessary scaling, rotation, and translation.

Hand Tracking
The Leap Motion controller uses optical sensors and infrared light. The sensors have a field of view of about 150 degrees. The effective range of the Leap Motion Controller extends from approximately .03 to .6 meters above the device (1 inch to 2 feet).
Detection and tracking work best when the controller has a clear, high-contrast view of an object’s silhouette. The Leap Motion software combines its sensor data with an internal model of the human hand to help cope with challenging tracking conditions.
In HMD mode, the tracking algorithms are optimized to recognize and track hands from a different point of view than in desktop mode.

Hand tracking and virtual reality are both emerging technologies, and combining the two into a fluid and seamless experience can be a real challenge.


Gesture-based interactions should be initiated with specific gestures that are rarely a part of casual movement. (For example, grabbing is a distinct action that can signal intent.)
 tracking potential hand poses, some will always track better than others. Whenever possible, encourage users to keep their fingers splayed and hands perpendicular to the field of view – like the Hovercast Menu system at the top of this post. This is by far the most reliable VR tracking pose. For similar reasons, be sure to avoid interactions that depend on the position of fingers when they are out of the device’s line of sight. Some other generally solid gestures and poses in VR include

index finger pointing (as long as it’s visible to the device)
grab gestures (with the palm facing away from the device)
the “Superman pose” (palms facing downwards, fingers outstretched)
Advancements:

The technological goal of this project is advancement of Development of Interactive Hardware Systems for Manipulation and control of 3D/VR environment.

The Development of Interactive Hardware Systems for Manipulation of 3D Graphics was an objective based on the need to develop methods to overcome touch and gesture manipulation barriers by developing our own multi-touch intelligence layer and capacitive membrane display systems. The current state of technology in game engines did not allow, and were not built to function with any touch screen, as when we attempted to integrate the two technologies the systems failed.

The work done resulted in the advancement our knowledge of information technology, and specifically in development of real-time 3D game engine technology, as applied to create the highest quality interactive 3D content for occulus based environments.

Key Learnings:
If I tell you to push or slice, people naturally gravitate ot limited spectrum of motion. this was a misconception, as different peokle have different ways to reacting teo motion instructions. We needed to test each of these edge cases, to allow the system to recognise the miton, and distill it down into what we are expecint hte spftwrae or control to do was paramount.
Contoller free interaction - hand controllers cannot be givein, as hte user cannot see the controller with eh occulus on their face.
Everyone knows how to use their hands, so being able to preemptively interret those hand motions, and how the software would interpret them would be paramount.

Arc Media - Holograms. Projecting image into tranparent screen. combined a kinect with a unity scene, when you walk infront of it, and will adjust the image with respect to where you are, based on hte kinect feedback. Off shoot of what wer were dong in VR.



Technological advancements for real-time content rendering that would allow users to both view and interact with virtual objects. Advanced techniques were sought in the following distinct areas:
-Third-party game engine integration, including methods to employ game engines
(such as Unity3D and Unreal Development Kit) outside standard gaming/simulation environments for realistic, dynamic object visualization.
-Touch development, including the ability to receive touch input as recognizable commands in game environments, development of an intuitive and responsive touch language, and connection of 3D cameras to navigate scenes in
a natural and intuitive manner.




occulus VR advancements.txt
Displaying occulus VR advancements.txt.
