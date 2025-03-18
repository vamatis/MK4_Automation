# MK4_Automation
Code to run the injection cycle of the Buster Beagle 3D MK4 Injection Molding Machine

Watch the [video](https://youtu.be/S4sWyfVj5go) where I go over how the MK4 machine works. 
<img src="images/Main_copy.jpg">

## Buster Beagle 3D
Many of these videos give you a better understanding of the evolution of this machine and might clear any questions on how it works and how to build it. 
- [MK1 Injection Molding Machine](https://youtu.be/HoSVPHVESiE), The original and smaller hand crank desktop version.
- [MK2 Injection Molding Machine](https://youtu.be/JqHPNjSaw4w), The upgraded version of the MK1 with a larger 2 Cubic inch shot volume.
- [MK3 Injection Molding Machine](https://youtu.be/PvQU3Q8wwOU), The first vesion of the machine to introduce pneumatics, also increased volume to 3 Cubic Inches.
- [MK4 Chamber and Vise Upgrades](https://youtu.be/dzYe9b0Iuzc), Talks about the first upgrades that convert an MK3 to and MK4 machine. 

# Ardunio
You can find the arduino code for the project in the `/MK4_Automation` directory

## Libraries needed

All these libraries can be easily installed using the Arduino IDE library manager.
- `Encoder` by Paul Stoffregen.
- `Wire` by Arduino.
- `LiquidCrystal_I2C` by Frank de Brabander.
- `avr/wdt` by AVR Libc.
- `Servo` by Arduino.

# MK4 BOM
You can find the full BOM of the parts needed [HERE](https://docs.google.com/spreadsheets/d/1JVG8-Zt6J-UAuxbnEOaoJAQSUpH0-k1IP8Y7-RxV8Eo/edit?usp=drive_link)
- For the Buster Beagle 3D parts [CLICK HERE](https://www.busterbeagle3d.com/) 

# MK3/MK4 frame PDF file
[MK3/MK4 Frame Build](https://drive.google.com/file/d/1zg0rRujJQF1wtNAtguwyY8d_fwCQzAzu/view?usp=drive_link), Frame for the MK3 and MK4 builds are the same. The only difference would be the exclusion of the manual pneumatic button as well as longer upright aluminum extrusion, 10mm linear rods holding the triangle plate, and pnuematic cylinder if building the MK4 with the optional extension chamber. 

# MK4 Vise
- [MK4_Vise_Assembly PDF](https://drive.google.com/file/d/12hUAGlBEdqDP5q_SxHw-1Td8OqxFoPMN/view?usp=drive_link)
- [MK4 Vise Assembly Video](https://youtu.be/MoHPu2ggeWM)

# MK4 Wiring Diagram
<img src="images/MK4_WiringDiagram.jpg">

# MK4 Pneumatics Diagram
<img src="images/MK4_PneumaticDiagram.jpg">









