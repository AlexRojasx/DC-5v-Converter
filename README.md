<h1>DC/DC-5v-Converter</h1>

<h2>Project Description:</h2>

The DC/DC 5v converter project is aimed to create a simple and easy way to power a usb device. The primary focus was for this device to be able to power an Orange Pi off of a Rev Robotics PDH (Power Distribution Hub) for simple integration in a FRC Robot. This simple PCB board design was used to deepen understanding of circit design, PCB layout, and PCB manufacturing.

<h2>Skills Learned:</h2>

-PCB Design and Layout  
-How to Utilize Bypass Capacitors  
-Understanding of component selection  
-PCB Manufacturing

<h2>Tools Used:</h2>

-Kicad for PCB Layout and Design  
-Oscilloscope for analyzing noise and PCB trobleshooting  

<h2>Screenshots:</h2>

<b>Schematic:</b>
![image](https://github.com/AlexRojasx/DC-5v-Converter/assets/116775585/43da6133-3bca-4cef-b5c7-7b38efd9ebae)

The circit utilized a LM340s-5.0 fixed power regulator, which required a custom symbol and footprint to be made. The LM340 requires a 0.22uF bypass capacitor to filter any noise that could be caused from external influences, as well as a Schottky diode for reverse polarity protection.

<b>PCB Layout:</b>
![image](https://github.com/AlexRojasx/DC-5v-Converter/assets/116775585/a4e3fc0f-a301-4d48-956e-8f59b2c27949)

*description of pcb Layout

<h2>Datasheets:</h2>

Ti LM340s-5v Voltage regulator: https://www.ti.com/lit/ds/symlink/lm340.pdf 
