---
layout: page
permalink: /thesis-abstract/
title: "Getting Out of Flatland: Interaction and Introspection with Tangible Augmented Objects"
modified: 2015-06-08 09:28
tags: []
image:
  feature: CCoO_header.jpg
  credit: 
  creditlink: 
share: 
vvvv: false
---

<!-- ### Motivation: Why do we care about the problem and the results? -->
Most of our waking hours are now spent staring at a screen. While the advances in touch screens have enabled a more expressive interaction space with our devices, by using our fingers to interact with digital content, what we see and manipulate on screen is still being kept away from us, locked behind a glassy surface. The range of capabilities of the human senses is much richer than what screens can currently offer. In order to be sustainable in the future, interaction with the digital world should leverage these human capabilities instead of letting them atrophy. One way to provide richer interaction and visualization modalities is to rely on the physical world itself as a host for digital content. Spatial Augmented Reality provides a technical mean towards this idea, by using projectors to shed digitally controlled light onto real-world objects to augment them and their environment with features and content. This paves the way to a future where everyday objects will be embedded with rich and expressive capabilities, while still being anchored in the real world.

<!-- ### Problem statement: What problem are your trying to solve? -->
In this thesis, we are interested in two main aspects related to these tangible augmented objects. In a first time, we are raising the question on *how to interact* with digital content when it is hosted on physical objects. As a basis for our investigation, we studied interaction modalities that leverage traditional input and output devices found in a typical desktop environment. Our rationale for this approach is to leverage the experience of users with traditional digital tools while at the same time steering towards a physically enriched interaction space. In a second time, we investigate how these augmented artifacts, combined with physiological computing, can be used to raise our awareness of the processes of our own bodies and minds and, eventually, foster *introspection* activities. This took the form of two different projects where we used tangible avatars to let users explore and customize real-time physiological feedback of their own inner states.


## Interaction with Spatial Augmented Reality
The first part of the thesis is focusing on the interaction with physical objects, augmented using SAR. The work includes an evaluation of a pointing technique (CurSAR) and an interaction metaphor for bridging interaction on traditional computer screens and physical augmented objects.

### CurSAR
[![](/images/cursar-header.jpg)](/images/abstract-cursar.jpg)

[**CurSAR**]({{ site.url }}/cursar-pointing-in-spatial-augmented-reality-from-2d-pointing-devices/) is a project investigating the use of 2D input devices to point at augmented physical objects. The main goal of the study was to compare the performance of a pointing task in a SAR and SCREEN condition. We created an experimental setup that allowed to have the same view of augmented objects either physical (SAR) or virtual (SCREEN).  Participants were 11% slower in the SAR condition. However, the transfer function of the mouse to the cursor, even without the physical presence of a screen as a reference system for the cursor, continued to the be effective.


### Tangible Viewports: Bridging Desktop Computers and Physical Augmented Objects
<iframe width="560" height="315" src="https://www.youtube.com/embed/q1lcti0P8Rk" frameborder="0" allowfullscreen></iframe>

Tangible Viewports is an interaction metaphor developed to integrate physical objects into a desktop computer environment. It consists of an on-screen window that is aware of physical objects placed in front of it. When the screen cursor is about to be occluded by the object from the point of view of the user, the cursor appears on the surface of the physical object. Most activities involving digital creation are still conveyed on desktop or laptop computers (e.g. design, graphics, programming, etc). Enabling seamless interaction between native computer applications such as Photoshop and programming environments and physical objects makes it possible to envision a way to let users and developers create, tweak and interact with augmented objects with traditional tools.

The proposed system also supports different input modalities depending of the object's spatial relationship with the screen. When located in front of the screen, it is possible to use any computer input device (i.e. mouse, graphics tablet) to create graphics, animations and interactive elements on the surface of the object directly. When the object is picked up, it is for example possible to interact with the different elements with direct touch. Considered in a creative workflow, this quick back and forth between the development environment (screen-centric) and the direct manipulation (handheld) could reduce the feedback loop when iterating over an idea or design.



## Physiological Introspection with Tangible Augmented Objects
The body is the most intimate thing we have. Even though we live with it everyday of our life, many of the internal intricacies of our inner states are not explicitly made available to us. In this chapter, we are interested in the use of tangible augmented objects as a way to expose and explore our inner states in a playful way.

### Teegi: Tangible EEG Interface
<iframe src="//player.vimeo.com/video/104486980" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

[**Teegi**]({{ site.url }}/teegi-tangible-eeg-interface/) is a Tangible EEG (ElectroEncephaloGraphy) Interface. It uses a physical puppet on which your brain activity is displayed in real-time using SAR. EEG technologies are still very complex and the knowledge required to have access to EEG readings and processing can be a deterrent for novice users that are interested in the brain. By creating a fully tangible installation, users can explore their own brain activity by manipulating dedicated mini-puppets that each corresponds to a high level brain activity (closing eyes, motor movement, relaxation/meditation). Users are free to explore what happens in their EEG readings by moving their limbs or try to changer their inner state and locate the brain regions that are specific to these activities.


### TOBE: Tangible Out of Body Experience
<iframe width="560" height="315" src="https://www.youtube.com/embed/yX0rMKO1aVA" frameborder="0" allowfullscreen></iframe>

TOBE stands for Tangible Out of Body Experience. It is a direct follow-up of the Teegi project that is interested in increasing the freedom of the users regarding two factors: the physiological readings and the visual representations of said readings. The main idea of this platform is to allow users to build a tangible augmented avatar that will react to their own body's internal state. Compared to Teegi, users have access to a greater range of physiological sensors such as ECG, breathing, GSR and some interpreted EEG signals. Moreover, they are creating the visual mapping themselves by selecting a visual representation, creating an animation using a simplified touch interface and linking it to one of their real-time physiological readings.

By letting users create their own representations of their real-time inner state through a tangible avatar, we are interested to see if users are more involved with their own physiology. Additionally, it can serve as a mediation facilitator, letting novice users explore what can be measured on the body, the way it is measured and how they relate to these measurements.

## Publications

{% bibliography %}