# FuzzBuddy

The overall goal of this project: 

To recreate the famous "Fuzz Face" guitar pedal from 1966 in our own way.

By Connor Donaldson and Tim Gould 


![fuzz-face-pedal](https://github.com/user-attachments/assets/38dbec36-bd87-42f1-8264-8cb17a61fd52)

This is the Fuzz Face guitar pedal that has been used by many popular artists such as Jimi Hendrix. 

![fuzz-face-bias](https://github.com/user-attachments/assets/eabae81a-ebe0-4e31-b517-412f1e557a19)

This was the main schematic that was used to create the "FuzzBudy" circuit. The main differences between the two are mainly the values used as resistors and potentiometers. 


![download](https://github.com/user-attachments/assets/54833f10-8ecd-42ba-a6e5-774d6ad25d60)


This is the FuzzBuddy circuit that we have created. Of course, it is naturally very similar to the original, however there are a few differences that make the FuzzBuddy stand out. One such difference is the filter at the end of the circuit, with the capacitor being in parallel with the resistor that goes to ground. A few more key differences are the values on all of the resistor and potentiometer values that can allow for a different sound. 

![LTSpiceSimulationResults](https://github.com/user-attachments/assets/20fd7386-8d93-428e-82a9-f91c065e1bec)

These are the simulation results of the circuit we created. The green wave is the input voltage from the guitar, and the blue wave is the output voltage from the circuit. 
The transistors within the circuit allow the combination of AC current and DC current. When the two currents meet, the AC current gets amplified through the transistors. However, the transistors also cause the signal to 'cut', creating the square wave from a sin wave. 

Parts List:

15k Resistor

2k Resistor

2 4k Resistors

2 AC128 Germanium Transistors

10.0uF Capacitor

2.0uF Capacitor

0.1uF Capacitor

50k Potentiometer

500k potentiometer

2 1/4 inch input audio jacks

9 Volt source

And an Electric Guitar

[IMG_7881.pdf](https://github.com/user-attachments/files/18033664/IMG_7881.pdf)

Here is an enviromental test of the circuit using a waveform generator and observing the output of the FuzzBuddy on the oscilloscope. We got our expected results from the circuit and the tests were successful. 
