---
id: 3D-User-Interfaces
title: 3D User Interfaces
desc: ''
updated: 1644290133579
created: 1643729067561
---

This [book](https://www.eecs.ucf.edu/~jjl/) was recommended to me by Blair MacIntyre. 

These notes are from the 2nd edition, published in 2017.

Chapter 1.1
> "A VR application may allow a user to place an object anywhere in 3D space, with any orientation-a task for which a 2D mouse is inadequate."

Right away this reminds me of the [Brave NUI World](https://www.amazon.com/Brave-NUI-World-Designing-Interfaces/dp/0123822319) book. 

Chapter 1.2
> "...development of 3D UIs is one of the most exciting areas of research in human-computer interaction (HCI) today.

...when is "today" in this book? 2017? 
My today is Feb 1, 2022 at 10:31:43 AM

Chapter 1.3: Terminology
> Degrees of freedom: The number of independent dimensions of the motion of a body. 

At the end of this chapter the authors arrive at this definition:
>3D interaction: ...if a user tours a model of a building on her desktop computer by choosing viewpoints from a traditional menu, no 3D interaction has taken place. On the other hand, 3D interaction does not necessarily mean that 3D input devices are used...

Good distinction between the input device and the type of interaction. I could use a 3D-capable input device to interact with a 2D environment, or a 2D input device to interact with a 3D environment.

Chapter 2.1: History of 3D UIs
> ...unforseen usability issues

Todo: read Sutherland(1968)

One of the first popular magazine covers about Virtual Reality wasn't about a VR headset, but instead showed the "DataGlove" which was a hand worn glove meant to manipulate a virtual environment.

Many difficult details to work out in these devices:
- how to know when a user is pointing to something in a VR environment?
- how to handle the user putting a device down to use another input device?
...side note: my Oculus Quest handles both of those quite well

>designers of 3D UIs...still are faced with technological limitations, such as input latency, limited 3D workspace, tracing dropouts and cumbersome devices that must be worn, held, or attached.

> Thus, the new subarea of HCI is termed 3D interaction, 3D user interface design, or 3D HCI

- IEEE Symposium on 3D User Interfaces
- ACM Symposium on Spatial User Interaction

Chapter 2.2: Roadmap to 3D UIs
> The defining feature of 3D UIs is that users are viewing and acting in a real and/or virtual 3D space.

Interaction Techniques for Composite and Application-Specific Tasks
> ...complex tasks in 3D UI are often **composed** of the universal tasks...
(emphasis mine)

> ...the task of cloning objects in space could ne see as a **composite** task involving selection, system control, and manipulation, but there are benefits to considering this task independently an designing specific interaction techniques for it(Chen and Bowman 2009).
(emphasis mine)

> ...it is not trivial to put these elements together in a usable and understandable way



**Three Important Terms**
- presence
> the feeling of "being there" tha you get when imersed in a virtual 3D world (Slater et al. 1994)
- cybersickness 
> feelings of physical discomfort brought on by the use of immersive systems (Kennedy et al. 2000)
- interaction fidelity
> the level of realism in the UI (McMahan et al. 2012)


2.2.3: Areas Impacted by 3D UIs
Medicine and Psychiatry
> For example, someone with a fear of snakes might be able to pick up and handle a virtual snake with a combination of 3D input devices and a realistic toy snake

... this reminds me of Dzongsar Khentsye Rinpoche's story of the snake, and how a Buddhist teacher might try to work with a student with such a fear. 
todo: insert that clip here

On HCI
I'm going to quote this short paragraph in full:
> The study of HCI has revealed many areas not addressed by traditional HCI. For example, what metrics should be used to study the user experience of a system? In typical UIs, metrics such as speed, accuracy, satisfaction, and perceived ease of use may be sufficient; in 3D UIs, we also need to asses things like physical comfort and presence. The development of heuristics or guidelines for good UI design is another area that has been studied thoroughly in traditional HCI but that requires further thought and expansion for 3D UIs. 

Chapter 3
> "human factors" refers to the capabilities, characteristics, and limitations the human user...

>...we focus on three interconnected human factors categories perceptual, cognitive, and physical ergonomics issues 

>While attention is still not fully understood, evidence indicates it has three components: orienting to sensory events, detecting signals doe focused processing, maintaining a vigilant or alert state.

>For example, consider a busy train station - a friend may be waving and, once you focus you attention on her, you may notice she is also calling your name. 

>...decision-making processes are in the center of information processing and depend on capturing, organizing, and combining information from various sources

>Skills can be a major focus of a 3DUI...skill transfer is an important factor in many VR training applications, with the expectation that skills learned in a VE can also be applied in the real world

*index of performance*
- IP = (ID / MT)
- - _index of difficulty_ / _movement time_

> *index of performance*is expressed in bits per second and has been used to define the performance of many input devices. 
- - the hand itself = 10.6 bits/s
- - a mouse = 10.4 bits/s
- - a joystick = 5.0 bits/s
- - a touchpad = 1.6  bits/s
- - - well...I am much faster with this mac's trackpad than any mouse 


_steering law_
...predictive model that describes the time to steer through a tunnel

[ ]install latex and put in the formula


**occlusion**
> also called contour interruption or interposition
the phenomenon in which an object closer to the user partially obstructs the view of an object farther away

**linear perspective**
> the phenomenon what makes parallel lines appear to converge as they move away from the viewer

...incidentally, this kind of phenomenon is what flat earthers use to 'prove' that the earth is flat. They say this is why you can't see objects which are actually beyond the horizon. They say no, they are just too far away to see, but that if you had a powerful enough telescope and nothing was in the way, you could Africa from NYC. See Eddie Bravo ranting on Rogan's show. Sigh. 🙄


**aerial perspective**
> also called atmospheric attenuation
is a cue that gauges relative distance by measuring the scattering and absorption of light through the atmosphere. For example, a nearer object will have more color saturation and brightness, while a more distant object will be duller and dimmer. 


**motion parallax**
>depth information is conveyed when objects are _moving_ relative to the viewer


audio - binaural cues
>The fundamental problem with binaural cues id that there are locations relative to the listener's head where ambiguous situations occur...one of the ways...can deal with ambiguous binaural cues is with dynamic movement of the...head or the sound source itself.

Reverberation, of course, is a useful way to locate a sound source.

**vestibular**
>The vestibular system is closely tied to the ear and auditory nerves...the vestibular sense can be best understood as the human balance system. 

>...the vestibular system affects the control of the eyes, neck, and trunk/limbs

>It is believed _cybersickness_ is caused by a mismatch between visual and vestibular cues.

## somatosensory
3.3.3

This is also called the haptic system.
>The somatosensory, or haptic, system is an important perceptual system dealing with what we feel when touching or grasping objects and how we perceive the location and movement of the parts of our bodies. 

[ ]pickup here