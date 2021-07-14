# Part 2: TOF Sensor Overview {#build-part2-overview status=ready}

## Preface

At a high level, a **sensor** is a device that _observes_ something about the world and reports its observations on an electrical wire. For example, a camera can be a sensor.

In contrast, an **actuator** is a device that _does_ something when provided power via an electrical wire. For example, a motor can be an actuator.

The simplest possible robot is one that has only actuators. However, a robot with any amount of autonomy would also require sensors. This is because such a robot would need observations about its world in order to decide what to do with its actuators.

In this part of the build, you will be adding your first sensor to the drone -- the Time of Flight (TOF) sensor. The TOF sensor is used to measure distance. We'll provide more details about the hardware used in this portion of the build, explain the circuit you'll be creating, and then get into the instructions.

## Required Materials
You will need [Build Part 1](#build-part1-overview) completed before you can begin this build part.

- **Part : Quantity**
- [TOF Sensor and Wire](#materials-ir) : 1
- [Analog to Digital Converter and included pins](#materials-adc) : 1
- [ADC wires](#materials-wires-adc) : 1
- [Soldering Tools](#materials-soldering-tools)

## Detailed Hardware Descriptions

### Time of Flight (TOF) Sensor
The IR sensor is used to measure distance. On the drone, we use this sensor to measure the height of the drone above the ground. The sensor works by emitting infrared light from one side, and measuring the time it takes for the light to be reflected back to the sensor. Based on this value and the known speed of light, the distance traveled can be calculated. Therefore, the sensor on the drone is able to determine the instantaneous height of the drone during flight.

<figure>
    <figcaption>Time of Flight Sensor and Wire</figcaption>
    <img style='width:200px' src=""/>
</figure>

### Analog to Digital Converter (ADC)
The Raspberry Pi GPIO pins can only read digital signals (1's and 0's). However, the IR sensor outputs an analog signal (a voltage value). In order for the Pi to read the output of the IR sensor, the analog output must be converted to digital first. This is the purpose of the Analog to Digital Converter, or ADC for short.

<figure>
    <figcaption>Analog to Digital Converter</figcaption>
    <img style='width:200px' src="photos/new-adc.png"/>
</figure>

### ADC wires

<figure>
    <figcaption>ADC Wires</figcaption>
    <img style='width:200px' src=""/>
</figure>

## Build Progress

After completing this section, your build will match the diagram below. Compare this diagram to the [completed drone diagram](#diagram-complete) and to the [Part 1 diagram](#build-part1-diagram) to see how what you're building up to the final result.

<figure>  
  <figcaption> Diagram for Build Part 2 </figcaption>
  <img style='width:400px' src=""/>
</figure>

The TOF sensor receives power from the Pi Hat, and the sensor output signal is
received by the ADC. The ADC converts the analog signal into a digital signal, and passes this to the Pi using the SCL and SDA inputs, (which is called I2C protocol).
