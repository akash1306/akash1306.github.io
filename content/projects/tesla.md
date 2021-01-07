+++
date = "2019-06-08"
title = "Tesla Coil Slayer Exciter"
description = "Project Kratos: A Mars Rover"
images = ["/images/kratos.jpeg"]
math = true
series = ["Projects", "Autonomous"]
+++
![Example image](/images/tesla.jpg)

The Tesla coil is an electrical resonant transformer circuit designed by inventor Nikola Tesla. It is used to produce high-voltage, low current, and high frequency alternating-current electricity. The primary and secondary circuits are tuned so they resonate at the same frequency; they have the same resonant frequency. This allows them to exchange energy, so the oscillating current alternates back and forth between the primary and secondary coils.

We aimed to build a solid-state tesla coil, which means that it creates oscillation by taking a DC input and output the sparks on the open end of the secondary coils. The sparks oscillate such that they produce the sound which we input through an audio jack, along with powering devices wirelessly. All of this happens while one end of the circuit is open!
The project started with a single coil circuit, which was then tuned to higher or lower frequency as needed. Then we moved towards a bigger coil to output more power and used two coils so that we could output the sound at two different frequencies at the same time.

The aim of our project is to examine the various utilities one can obtain using a slayer exciter tesla coil, a field relatively unexplored till date. A primary tesla coil made using Transistors serves the basic use of providing wireless power transfer, whereas, using a MOSFET and Gate Driver IC adds a dimension of new possibilities and wide-ranging applications in the field of wireless technology as well as levitation and artificial gravity.

**The basic working and how the circuit was used is explained below: **

![Tesla Circuit](/images/tesla2.JPG)

1. Turning the circuit on, R drives the base of the transistor Q
2. Q turns on and drives current into the primary of the transformer. The current is limited by the limited available base current.
3. The created magnetic field drives the secondary of the transformer.
4. The secondary voltage wants to grow large. But the tiny stray capacitance on the output resists the change, although very small, against the rise of the output end and so in return the voltage on the other end of the transformer goes down, pulling the base of the transistor low.
5. Diode D prevents the base voltage to fall more than 0.7V below ground, which in return pushes the output end of the secondary high.
6. The transistor turns off and so the magnetic field starts to reduce.
7. The base voltage rises again, Q turns on, and the cycle repeats.
8. The primary and secondary coil are loosely coupled. 

The circuit for the musical Tesla coil is much more complicated and use many different components, but deep within the circuit, the basic working is same as explained above. The only addition being, we input an audio signal, which is converted, to square wave, which modulates the output frequency, thus producing the musical sparks.
