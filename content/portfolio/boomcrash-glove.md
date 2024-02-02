+++
date = "2019-12-10T19:41:01+05:30"
title = "Wearable Music Interface - BOOMCRASH Glove"
draft = false
image = "img/portfolio/BOOMCRASH/POE.png"
showonlyimage = false
weight = 1
# tags = ['please', 'hi']
+++

A pair of gloves powered by Arduino and Max/MSP that create real-time, reactive sound based off the wearer’s gestures and movements.

*Keywords: Product design, Interactive electronics, Programming, Audiovisual programming*
<!--more-->

**The Goal:** Design and fabricate a project that incorporates hardware - mechanical and electrical - and software components.

**The Outcome:** A pair of wearable music interfaces featuring several sensors that send data to a host of software instruments to produce real-time sound.

**My Role:** I collaborated with the team to develop the initial product and scope it appropriately based on our time and budgetary constraints. After the initial ideation process, I focused predominately on the programming and software, integrating Arduino with the audiovisual-focused programming language Max/MSP.

**The Process:** Our process is documented extensively on our (website)[http://pie.olin.edu/2019/boomcrash/]. 

Our initial ideation process involved determining what we might make that would satisfy the assignment’s integrated software and hardware goals. Once we agreed that we wanted “gloves that would make sound”, it became a matter of determining what kinds of sounds we would make.

I explored several means of generating sound in response to sensor input, including Arduino native sound generation and MIDI control. 

As part of the goal was to create pleasing sounds, we pivoted to the more robust Max, which I had some passing experience with. Many of my initial programming challenges were in simply achieving steady communication between our Arduino and the computer—Troubleshooting Bluetooth issues and serial monitoring. Once this was achieved, I spent some time considering which sounds might correspond to which gestures, attempting to figure out intuitive responses that would delight the user. From there, it was a matter of building simple synthesizer modules and converting the raw sensor data to something that scaled with Max’s inbuilt synths.

**Highlighted Methods, Frameworks, and Skills:**
- [Max/MSP](https://cycling74.com/)
- Arduino
- Bluetooth serial connection
- Iterative design
- Design sprinting

*Team of 5 - Reid Bowen, Katie Foster, Shirin Kuppusamy, and Becca Suchower; 2019*