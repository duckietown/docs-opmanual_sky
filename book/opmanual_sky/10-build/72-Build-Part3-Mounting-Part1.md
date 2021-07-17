# Part 3: Mounting Part 1  Overview {#build-part3-Mounting-Part1-overview status=ready}


## Preface
In this phase of the build, you'll be constructing the frame and attaching essential components to it-- the motors, ESCs, and the flight controller.

### Drone Orientation

**INSERT FINAL PICTURE WITH MOTOR AND ESC ATTACHED WITH LABELS FOR FRONT, BACK, LEFT, RIGHT

For reference, here are the motor directions with respect to the frame:

<figure>
    <figcaption>Motor Directions on Drone</figcaption>
    <img style='width:400px' src="photos/motor_directions.png"/>
</figure>

<figure>
    <figcaption>Labeled drone</figcaption>
    <img style='width:200px' src=""/>
</figure>

## Required Materials

**Part : Quantity**
 
- Counter-clockwise Motors (soldered with bullet plugs): 2
- Clockwise Motors (soldered with bullet plugs): 2
- Long M3 Bolts (included w/ motor): 16
- Short M3 Bolts (included w/ motor)): 4
- Electronic Speed Controllers (ESCs) (soldered to bullet sockets) : 4
- Flight Controller: 1
- Raspberry Pi 3b+ and Pi hat
- Bottom Platform: 1
- Top platform: 1
- Arms: 4
- Sandwich Platform: 2
- Propeller Guards: 4
- M3 Screws:  
    6mm: 9  
    10mm:  
    12mm: 16  
    16mm: 4
- M3 Nuts: 21
- Soldering Tools
- Standoffs: 4
- Screwdriver: 1
- Hex Key: 1



## Attaching Motors and ESC 

### Constructing Frame
We're going to begin by attaching the arms to the bottom platform. The bottom platform should have the PDB already attached to it. 


Layer the arm with the Bottomr and Sandwich Platforms as shown below. 

**INSERT PICTURE OF LAYERED ARMS AND SANDWICH PLATFORM

<!--
<figure>
    <figcaption>Layering arms and sandwich platform</figcaption>
    <img style='width:200px' src=""/>
</figure>
-->
Using 16 12mm screws and 16 M3 nuts, secure the layered arms and sandwich platform. See picture below.

**INSERT PICTURE OF SCREWS GOING THROGUH PLATFORM AND ARMS
<!--
<figure>
    <figcaption>Layering arms and sandwich platform</figcaption>
    <img style='width:200px' src=""/>
</figure>
-->
Now, we can attach the motors to the arms. We'll need to layer the arms with the propeller guards as well. 

Layer the arms and the propeller guards as shown below.

**INSERT PICTURE OF LAYERED ARMS AND PROPELLER GUARDS
<!--

<figure>
    <figcaption>Layering arms and propeller guards</figcaption>
    <img style='width:200px' src=""/>
</figure>
-->
### Attach clockwise (CW) motors

Attach CW motors to the bottom-right and top-left of the drone frame, using 4 black long bolts (included with the motors) for each attachment to the layered arms and propeller guards. Tighten with Hex key.

Note: Align the motors so the wires point towards the frame.

**Insert Picture of screwed on CW layered motors with layered arms and propeller.
<!--
<figure>
    <figcaption>Top view of Motor attachment</figcaption>
    <img style='width:200px' src=""/>
</figure>
-->
### Attach Counter-Clockwise (CCW) Motors

Attach CCW motors to the bottom-left and top-right of the drone frame, using 4 black long bolts (included with the motors) for each attachment to the layered arms and propeller guards. Tighten with Hex key.

Note: Align the motors so the wires point towards the frame.

**Insert Picture of screwed on CW layered motors with layered arms and propeller.
<!--
<figure>
    <figcaption>Top view of Motor attachment</figcaption>
    <img style='width:350px' src=""/>
</figure>
-->
### Solder ESCs to the PDB

An ESC (i.e. Electronic Speed Control) is a component which requires power. It takes this power and provides a variable amount of it to a motor; since a motor's RPM depends on how much power it gets, an ESC can control how fast a motor spins by controlling how much power it supplies the motor.
<!--
<figure>
    <figcaption>ESCs Soldered to PDB</figcaption>
    <img style='width:400px' src=""/>
</figure>
-->

Note: Do **not** solder the wires flat against the PDB - solder them at ~20&deg; angle. If you solder them flat, then you will not be able to fit the PDB into the drone frame.   

### Connect the motors to the ESCs

For each motor, connect its plug bullet connectors to the socket bullet connectors of the ESC in the motor’s corner (e.g. top-left motor connects to top-left ESC). Any connection order will suffice for now, as you will be able to change them in a latter phase.


### Attaching the Flight Controller
Gather  
- 4 M3 16mm screws and 4 nuts  
- Flight Controller  
- Soldering Tools  

### Attaching Flight Controller

The flight controller will be installed upside down unto the bottom platform. It's important that the flight controller is mounted straight and with as little skew as possible. See Pictures below.

<!--
<figure>
    <figcaption>Flight controller mounted</figcaption>
    <img style='width:300px' src=""/>
</figure>
-->
### Solder leads to PDB

Solder the other end of the 1.5 inch red and black wires to the PDB. Due to limited PDB pads, you will need to solder onto another pair of wires. The red wire should connect to a positive (+) pad and the black wire should connect to a negative (-) pad.
<!--
<figure>
    <figcaption>Battery Monitor Lead Soldered to PDB</figcaption>
    <img style='width:300px' src=""/>
</figure>
-->
Note: While trying to solder on these wires, you may accidentally unsolder the existing wires from the PDB. We recommend temporarily holding down the existing wires with long-nose pliers, tape, or helping hands. 



## Assembling the Frame

At this point, You should have the following set up

**INSERT: Image of Frame after following instructions above

<!--
<figure>
    <figcaption>Checkpoint</figcaption>
    <img style='width:300px' src=""/>
</figure>
-->
Now, we'll assemble the rest of the frame. Then mount the Raspberry pi and TOF sensor

Gather:  
Standoffs: 4
Top Platform: 1
M3 6mm Screws: 9
M3 nuts: 1
Raspberry pi
Pi hat
Screwdriver

Flip the Bottom platform/ Arm assembly over to the top side ( Pressnuts facing up). 
Screw in the standoffs to the 4 empty pressnuts.

INSERT: image of standoffs screwed in
<!--
<figure>
    <figcaption>Drone frame with standoffs</figcaption>
    <img style='width:300px' src=""/>
</figure>
-->
Line up the holes on top platform with the holes at the top of the standoffs. Use 4 6mm M3 screws to attach the top platform to the standoffs

INSERT: image of top platform screwed in
<!--
<figure>
    <figcaption>Drone frame with top platform attached</figcaption>
    <img style='width:300px' src=""/>
</figure>
-->
If not already detached, detach the Pi hat from the raspberry pi and set aside. Take care that the wires reaching from the pi hat to the PDB are not tangled or caught between any platforms.

Using 4 6mm M3 Screws, attach the Raspberry pi to the top platform. It should be screwed into pressnuts embedded in the top platform. 

Note: Orient the Raspberry pi so the USB ports are facing the side of the frame the flight controller is mounted on.

INSERT: image of raspberry pi screwed into top platform 
<!--
<figure>
    <figcaption>Drone frame with Raspberry Pi attached</figcaption>
    <img style='width:300px' src=""/>
</figure>
-->
Now, reattach the Pi hat to the mounted pi. Lastly, we'll mount the TOF sensor to the frame. 
The TOF sensor will be positioned at the back of the drone using a 6mm M3 and a M3 nut, extend the TOF sensor wire from the pi hat through the opening in the top platform down to the bottom platform.
Ensure the sensor is not skewed. See figure below.

INSERT: image of TOF screwed into top platform 
<!--
<figure>
    <figcaption>Mounted TOF sensor</figcaption>
    <img style='width:300px' src=""/>
</figure>
-->
## Checkpoint of drone assembly

At this point, your drone should look like the images below


INSERT: 2 image views (side , angled) of drone

<!--
<figure class="flow-subfigures">  
    <figcaption>Pi Hat</figcaption>
    <figure>
       <figcaption>View 1</figcaption>
       <img style='width:220px' src=""/>
    </figure>
    <figure>  
       <figcaption>View 2</figcaption>
       <img style='width:220px' src=""/>
    </figure>
</figure>
 -->
