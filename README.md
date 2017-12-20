NB: You might find useful the [sample proposal](https://github.com/zamfi/cca-programming-electronics-fall-2017/blob/master/hw/sample-proposal.md) useful in completing this assignment!

# IOT Ambient Weather Station

An IOT weather weather station that reacts to for basic weather events and prompts with a color.

## Summary

I built an internet connected weather station that reacts to San Francisco weather events published by Weather Underground via IFTTT. The station is currently set up to display 4 types of events that are important to me: Rain, Cloudy, Hot and Perfect. The purpose of the device is to decrease reliance on smart phones and utitlize passive indication of how the weahter is without stepping outside. Each event is mapped to a specific color, RAIN = CYAN, CLOUDY = INDIGO, HOT = REDORANGE, PERFECT = DEEPPINK. The colors prompt me to pick the approporiate clothing before leaving from my house in the East Bay. This simple tool will make it easier by makinging sure I leave dressed appropriately.

## Component Parts

On the hardware side my project consists of: 
- Particle Photon (Wifi Microcontroller) to transmit data from the cloud and communicate with LED's (INPUT / OUTPUT)
- 24 NeoPixel Ring displays the information that is dependant on the situation (OUTPUT)
- Standard buttons x 2 are my ability to test and control the LED states (INPUT)

On the software side of things I am using
- Particle.Build (web not IDE) interface which communicates with the Photon and receives information from IFTTT (INPUT / OUTPUT)
- IFTTT.com (If this then that) platform. This allows data to be sent in real time. This is an attractive solution for tracjing variable weather conditions without haveing to install multple libraries and sensors. (INPUT)

###Block Diagram

![Weather Station block diagram] (block_diagram/IMG_2592.JPG)

https://github.com/j-crespo/block_diagram/blob/master/IMG_2592.JPG

## Challenges

I had many. My main mistake was working with the IFTTT applets while at school. The network was not friendly since the level of security, and I lost a lot of hours becuase events would not publish.

I was working with bad of poorly calibrated weather sensors. I did not know how to trouble shoot and wasted a lot of time trying to get them to work.

## Timeline

What did you do in each of the past five weeks?

- Week 1: Write proposal
- Week 2: Ordered parts and started woking on IFTTT (did not go well)
- Week 3: Tinkered with IFTTT, did not go well.
- Week 4: Switch my plan to using live sensors. This was not working out and I started to freak out.
- Week 5: Present, this was pretty bad too. I wasn't abe to produce a working prototype.
- Week 6: Started to revive IFTTT using home network, it worked well!

## Completed Work

https://github.com/j-crespo/content/blob/master/IMG_2589-2.mov

https://github.com/j-crespo/content/blob/master/IMG_5520.JPG

https://github.com/j-crespo/content/blob/master/IFTTT_Applets.png

## References and links

http://www.instructables.com/id/Weather-Indicator-With-IoT-TfCD-Project/
