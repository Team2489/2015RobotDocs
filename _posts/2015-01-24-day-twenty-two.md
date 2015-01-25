---
layout: post
title:  "Day 22"
date:   2015-01-24 19:35:21
categories: jekyll update
excerpt: On the prototyping side, the elevator team attached the passive grabber to the elevator and made it stronger. They supported it from the bottom as well and supported the outer frame of the elevator so it doesnt flex as much. The actual design will be made of aluminum, and will thus be much more rigid.

---
## Day 22

### Elevator

On the prototyping side, the elevator team attached the passive grabber to the
elevator and made it stronger. They supported it from the bottom as well and
supported the outer frame of the elevator so it doesnt flex as much. The actual
design will be made of aluminum, and will thus be much more rigid.

The elevator subteam also continued work on the CAD of the elevator. After some
CADing, we realized that if we were to continue with our current design (with
two frames of 2" by 1" aluminum tubing), the flat cross beam (which provides
support and rigidity) would interfere with the side rollers for the carriage. We
decided instead to switch to U-tubing for the inside frame, which allows the
carriage to ride on the inside.

<img src={{ site.baseurl }}{{ post.url }}/images/view1.PNG width="400">
<img src={{ site.baseurl }}{{ post.url }}/images/view2.PNG width="400">

The carriage is currently a piece of aluminum with angle stock on both sides.
Each piece of angle stock supports two rollers, which ride on the inside of the
U-channel. We will probably 3D print the rollers at Mission, but given the
current timeframe, we need to order the 2" by 1" and the U-channel ASAP. We will
also need to make sheet metal for gussets and assemble the superstructure and
elevator soon.

<img src={{ site.baseurl }}{{ post.url }}/images/carriage.PNG width="400">
Below you can see the whole robot CAD with the elevator, as it currently stands.

<img src={{ site.baseurl }}{{ post.url }}/images/robot1.PNG width="400">

### Claw

The active claw was having trouble with stability, and the moving claw was
moving up and down. It wasn't able to hold a tote without flexing and having the
tote fall off, so they added a support block to keep it from flexing up and
down. They also added a tote hook to the back of it so it can grab totes from
the thinner side. The moving arm pushes the tote and guides it toward the claw
so it will always be aligned.


### Electronics / Programming

The programming and electronics team attempted to connect the Jetson to the
Internet, and succeeded several hours after the meeting ended. The team also
images the RoboRio on the plywood test board and configured the DLink to work
with it. The driver station can communicate with the board, but there is no code
in the roborio. Vignesh also confirmed -- the Jetson is DEFINITELY A RELAY. He
also asked me to add that he's been forgetting that at times, so if you see him,
please be sure to remind him that the Jetson IS A RELAY!**

### Field Design

We began assembling some basic field elements today -- specifically, the tote
loading chute. We cut 2x4's at an angle and will attach it (and hopefully
complete the chute) tomorrow.

Also, Dominic brought spinach and cheese packet-things during the meeting. For
this act of generosity, he received the below medal. Seriously though, they were
delicious. Thanks Dominic!

<img src={{ site.baseurl }}{{ post.url }}/images/dominic.JPG width="400">

** For the record, the last two sentences are a joke. You should still remind
Vignesh that the Jetson is a relay, even if you don't know what that means (I
definitely don't), but don't take it seriously.
