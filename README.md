# Innoverse_Iriis

## Description: 
- Saviour is an emergency tool designed to provide critical support in challenging situations like being lost in a very remote place.
- It can transmit emergency signals like SOS using Morse Code via a radio transmitter and a flashing LED in areas without network coverage.
- The device incorporates GPS to provide precise location data, which can be transmitted to search and rescue teams, significantly improving the chances of locating lost individuals.
- The OLED display can display the Morse Code translated messages.
- Saviour is a valuable tool for travelers, hikers, and adventurers who may find themselves in remote areas without network coverage.
- It can also serve as an educational tool for those who wish to learn Morse Code.

## Design Prototype
- User selects the Mode between transmit a String or Location, by rotating a potentiometer.
- An OLED act as a screen for the user to display all the events.
- To send a String, User needs to scroll through the Alphabets and construct the string and then transmit.
- The Location is acquired by the GPS module
- The program inside the µC translates the String into Equivalent Morse Code and make it a digital ON and OFF signal sequence with varying pitch to denote the Dit and Dah
- The translated Digital Signal is then fed to the FM transmitter for transmission on Open Air at a frequency of 73.4MHz

**Figure 1: Block Diagram of Savior**

![image](https://user-images.githubusercontent.com/55133414/235340365-0b2e3507-5481-4c78-8ed0-5e43c68ce848.png)

## Radio Transmitter
- An LC tank circuit of resonant frequency 73.4 MHz

**Figure 2: Radio Transmitter**

![image](https://user-images.githubusercontent.com/55133414/235340710-b6dee785-2ab0-4d8a-85b3-09ad6ed42dbf.png)

## Tech Stack Used
- LC Oscillator
- PCB Design
- Dictionaries
- NMEA parsing
- PWM control
- RTOS

## Prototype

**Figure 3: Protype**
![image](https://user-images.githubusercontent.com/55133414/235340482-9f422210-1cf3-46b1-9195-1fd4bb7a3fed.png)




