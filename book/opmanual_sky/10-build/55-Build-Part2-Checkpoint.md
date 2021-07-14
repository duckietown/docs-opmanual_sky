# Part 2: TOF Sensor Checkpoint {#build-part2-checkpoint status=ready}

**Expected Time**: 20 minutes

## Overview

You will now checks to see if the IR sensor on your drone is working properly. You will using the drone software and the web interface to see drone's height estimate.


## Reading the IR sensor on the web interface

### Connect to the drone

1. Plug the battery into your drone build and connect to the drone's wifi network. By default, the network is named, *defaultdrone*, and the password is *bigbubba*.

1. Browse to the drone's code editor: [http://192.168.42.1:8081](http://192.168.42.1:8081)

1. In a new tab, browse to the web interface: [http://192.168.42.1](http://192.168.42.1). The web interface is what you will use to fly the drone. It also contains graphs that show data from the sensors.


### Start up the code

1. In the code editor, click the menu bar in the top left corner, then click Terminal > New Terminal

1. Type `./start` and press enter

1. Go back to the web interface tab, wait about 5 seconds, and refresh the page. Make sure that you see "Connected" at the top of the page. If you do not see this, wait a few more seconds and try refreshing again.

### Test

1. locate the *Height Readings* chart on the web interface

1. Use your hand to move the IR sensor closer and further to an object and check that the Height Readings chart is changing



Congrats on finishing Build Part 2!
