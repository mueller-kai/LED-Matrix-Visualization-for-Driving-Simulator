This code visualizes arrows on a LED Matrix that is installed in the driving simulator of the Reutlingen University of applied Science. Navigation messages are read from the CAN-Bus and the corresponding arrow visualization is shown. 
The mindset of the project is to imagine future developments in the automotive industry.

in other words: 
Navigation message: Turn right
Visualization: Animate arrows right

Animation can be adjusted based on how far the turn is away form the current position of the car.

https://user-images.githubusercontent.com/72653744/123142842-2c481a00-d45a-11eb-918d-467cd26b0e3d.mp4

The Code runs on a Arduino 4.0 Teensy. It coordinates 1536 LEDs.
The IDE provided by Arduino is recommended for use. It can be downloaded from the Arduino website (https://www.arduino.cc/en/software). The required library for reading the CAN messages is is part of the repo (seeed_arduino_can_lib_for_driving_sim.zip) and must be integrated in the following way. In the IDE under Sketch > Include library > Add .ZIP library. To install a modified Sketch on the Arduino, the computer must be connected to the Arduino via a USB cable.
