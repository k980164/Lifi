# Lifi
An explorative study on testing the feasibility of transmitting data through light.

#INTRODUCTION.
With Wi-Fi being the  modern and most common medium of transmission of data, it is also to be noted that it consists of  certain drawbacks such as  range of efficient data transfer, uniformity of signal strength etc., So this technology can be replaced by future proof technology namely Li-Fi (Light Fidelity) which tends to use light.

#COMPONENTS:
ARDUINO UNO, BLUE LEDs, JUMPERS AND RESISTORS

#APPROACH:
In our model we intend transmit data using light. The initial steps include transmitting alphabets and can be then extended to words followed by images and videos. At this junction we have transmitted alphabets.
We made use of an Arduino microcontroller in order to code for the transmitter and receiver section.  LEDs were used for the transmission of data, information was fed to the LED using Arduino.
With light as a medium, we could transmit the data to the receiver which consists of an LDR. After the LDR detects the data, it sends the data received in the form of binary 1’s and 0’s. 
The program that we have developed coverts the alphabets into their corresponding binary value, this binary value is then transmitted serially via the LED. The LED glows when the binary value is ‘1’ and  the LED turns off when binary value is ‘0’. This turn off and turn on is done in rate of milliseconds or even lesser therefore the flickering of light is not detected by the naked eye.
When we interrupt the light, this leads to the stopping of the data flow. Hence, we get a default message. The alphabets and words are represented in the ASCII format here.




