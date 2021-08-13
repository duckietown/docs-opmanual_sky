# Part 4: Camera, Propellers, and Mounting Part 2 Instructions {#build-part4-instructions status=ready}


### Plug in the micro USB to USB cable

If it is not plugged in already, plug the 6" micro USB to USB cable into the micro USB port of the flight controller.


## Attach the Pi Camera to the drone frame

### Detach the Pi Hat

Gently lift near the pin header to detach the Pi hat

### Screw the Pi Camera unto the bottom platform

1. Using 4 M2 6mm screws and 4 M2 6mm nuts, attach the camera to the bottom plaform. Attach so the camera faces downward and the FFC goes towards the drone. Ensure that the attachment is not skewed.
2. If not already done, attach the FFC to the Pi Cam. The blue side should face upwards.

INSERT: Photo of how to attach camera to frame

<!--
<figure>
   <figcaption>Pi Cam mounted</figcaption>
   <img style='width:300px' src=""/>
</figure>
-->
INSERT: Photo of how to attach camera cable to camera

<!--
 <figure>
     <figcaption> FFC Attachment to Pi Cam (shorter side in camera port)</figcaption>
     <img style='width:200px' src=""/>
 </figure>
-->
### Connect FFC to the Pi

You'll need to slightly twist the FFC so that the blue side faces the Raspberry pi's ports.

Feed the flexible flat cable (FFC) from the Pi Cam through the slot in Pi Hat, then connect it to the Pi's camera port, i.e. the black port close to the HDMI port.

Note: Do not just push the FFC into the slot. [Watch this video](https://www.youtube.com/watch?v=VzYGDq0D1mw) on how to insert the camera properly.

Note: Due to some misdimensions, you'll need to slightly twist the FFC before passing it throught the slot in the Pi hat so that the blue side faces the Raspberry pi's ports.

<!--
<figure class="flow-subfigures">  
    <figcaption>Connecting Pi Cam</figcaption>
    <figure>
        <figcaption>FFC cable through Pi Hat</figcaption>
        <img style='width:230px' src=""/>
    </figure>
    <figure>  
        <figcaption>FFC cable in Pi camera port</figcaption>
        <img style='width:230px' src=""/>
    </figure>
</figure>  
-->
### Re-attach Pi Hat

Put the Pi Hat back onto the Pi. Refer to [part 1](#build-part1-attach-pihat) for detailed instructions to attach the Pi hat.


### Plug in the Flight Controller USB

Plug in the Flight Controller USB to any of the USB ports on the Raspberry Pi. The USB sends the autonomous flight commands from the Pi to the FC.

Note: For the sake of wire management, it's advisable to loop the USB-TTL wires and USB wires around the cutout in the top platform. See image below.


<figure>
    <figcaption>USB Cable Plugged into Pi</figcaption>
    <img style='width:200px' src="usb-cable-attached.png"/>
</figure>


## Landing Gear

Place the slimmer side of each arm into the opening on the landing gear. Then gently slide the landing gear upwards until it can not be pushed further. 

<figure>
   <figcaption>Landing gear attached</figcaption>
   <img style='width:300px' src="photos/Landing-gear-attached.png"/>
</figure>


## Ziptie ESCs and PWM Connectors to Frame Arms

Use the small zipties to secure the ESCs and motor wires to the bottom of each frame arm. To do this, gently fold the Esc and motor wires into a neat stack under each arm, then thread the zip ties through the holes in each frame arm.  Ziptie the ESC to either the sides or bottom of the arms. Lastly, use zip ties to secure the PWM connectors to the sides of each frame arm.

Note: We do not want any wiring flaying up as the propellers spin.

<!--
<figure class="flow-subfigures-3">  
    <figcaption>Use Zip-ties to Secure Everything</figcaption>
    <figure>
        <figcaption>ESC and Motor Wires with Zipties</figcaption>
        <img style='width:230px' src=""/>
    </figure>
    <figure>  
        <figcaption>PWM Connector with Zipties</figcaption>
        <img style='width:230px' src=""/>
    </figure>
</figure>  
-->
## Propellers

Attach the propellers to the drone so that it may fly; attach CW propellers to the CW motors, and CCW propellers to the CCW motors. The motors have small arrows on them in the center to indicate which type they are.

Note: The bolts on the motors that spin CCW tighten when turned CW, and the bolts on the motors that spin CW tighten when turned CCW.

Use the 8 mm wrench to tighten the bolts down so that the bottom of the propeller is flat on the top of the motor. Screw bolts down tightly, but not so tight that you could not remove the propellers if you had to.

<!--
<figure class="flow-subfigures-4">  
    <figcaption>Put on Propellers</figcaption>
    <figure>
        <figcaption>Notice Arrows Indicating the Type of Propeller</figcaption>
        <img style='width:230px' src=""/>
    </figure>
    <figure>  
        <figcaption>Attaching Propellers</figcaption>
        <img style='width:230px' src=""/>
    </figure>
    <figure>  
        <figcaption>Propeller Flat on Motor</figcaption>
        <img style='width:250px' src=""/>
    </figure>
</figure>  
-->

<div class='check' markdown="1">

*Propeller Direction:*

1. The arrows on the propellers should be on visible from the top of the drone

2. The arrows should be going in the same direction as the arrows on the motors.

*Propeller Attachment:*

1. The propellers **must** be flat on the base of the motor

2. Make sure there is no gap between the propeller, the motor, and the motor nut.

3. Holding the motor still, try to spin the prop and make sure the props **cannot** spin around the motor shaft; the motors and the props should spin together.







1. Make sure ESC-motor wires are ziptied down properly. If not, you risk having a short.

2. Spin the propellers manually with your finger. Ensure no wires are hit by the propellers.

3. Make sure no wires or parts are dangling from the drone frame.

</div>
