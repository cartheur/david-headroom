# david-headroom
A new robotic head for an existing bipedal robot with an animated face

## The backstory

In 2015, a brilliant project called Poppy came onto the scene demonstrating the true power of 3D-printed designs for bipedal robots and that manufacturing of such robots could be done cheaply, effectively, and cost-efficiently to be able to reduce the cost-burden to the customer. This makes the idea of a bipedal robot with the behaviour of a child realistic to most buyers with a price-point somewhere in the 3-5k range. The presence, embedded as operational software, has specific and unique behaviour-based learning at runtime such that it can teach itself to walk and other gestures if demonstrated by its participant. This is novel and has not been attempted on a cost-efficient platform before.

## What is here

An attempt to adapt a new head to the robot that contains a plush face with animatronic eyes and mouth. I think that totallly digital robotic interfaces are not helpful at evolving the human-machine interface. They need to appear organic for humans to emotionally accept their presence and the level of intimacy they will ultimately provide. And people outside of that relationship should not be privy to any of it. Each of us needs to take our experience as it is and keep it memories stored on a robotic companion that is not shared with ANY external network. It is completely isolated from the Cloud and does not require external communications for its runtime.

This is the challenge set upon anyone who would like to participate with us on this project. This is not necessarily a test, rather, an introduction to curvature.

## Where are the instructions?

Please have a look at [this](/TaskReadMe.md) ReadMe.

## What does the face look like now?

Below is a figure of the face as it currently is oriented on a platform that has been previously developed.

![Animated face today](/face/animated-face.jpg "Necessary-face")

This schema follows our design priciples of the preference of "old-school" animatronics rather than digital displays. It is this level of branding that separates emotional toys from other kinds of social-consumer robot offerings. This strives for a mix of themes.

## The challenge

With this face, we need to crete a headcap that will mount at the neck with this joining part:

![AX-12A](/neck/AX-12A-SW-partial.jpg "Neck motor")

As an actual part, where you can find its CAD drawings [here](https://emanual.robotis.com/docs/en/dxl/ax/ax-18a/#reference).

![AX-12A](/neck/AX-12A-real.jpg "Neck motor")

That mounted onto the original headcap

![AX-12A](/head/old-head.png "Neck motor")

More focused, at this mount of the part

![AX-12A](/mount/original-neck-mount.png "Neck motor")

Where the STL file can be found [here](/neck/old-head-neck-mount.stl).

The idea is to build a new headcap that only has a tracing of the face joint as a flat surface:

![AX-12A](/face/faceplate-scan.jpg "Faceplate scan")

Where in the folder 'face" you can find photographs with a calibrated stick to show the dimensions. It will be a very challenging exercise to realize this cap with the new face and the addition of an internal computer. The face that needs to be supported, as a finished display:

![cartheur-presents](/face/face-mock.jpg "mock face")

Bear in-mind that the curved space above the forehead will most likely have a camera placement.
