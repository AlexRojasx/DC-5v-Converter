<h1>DC/DC-5v-Converter</h1>

<h2>Project Description:</h2>

The DC/DC 5v converter project is aimed to create a simple and easy way to power a usb device. The primary focus was for this device to be able to power an Orange Pi off of a Rev Robotics PDH (Power Distribution Hub) for simple integration in a FRC Robot. This simple PCB board design was used to deepen my understanding of circit design, PCB layout, and PCB manufacturing.

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

For the layout, I utilized copper pours connected to ground on both sides for an easy and accesible ground referance and to minimize any possible noise. The traces are also wide enough to handle the 0.5 amps of current at either 12v or 5v. The bypass capacitors are placed in close proximity to the IC to reduce as much noise as possible.

<b>PCB Assembly:</b>
![20240628_210202](https://github.com/AlexRojasx/DC-5v-Converter/assets/116775585/34638b3f-a545-43a0-bec8-a89dc57b157f)

<h2>What Could be Improved:</h2>

While the PCB is small, compact and is an overall improvement from the buck converters with its ease of use that the Frc team was using, there were a couple problems. One of the main problems was the heat dissipation of the PCB and the lack of heat sinks used causing the board to become very hot risking damage to some of the components if used for a sustained period of time. This problem is easily fixable with either the use of a proper heat sink or increasing the size of the board and ground pours for the PCB to act as a heat sink. Another problem was the lack of mounting holes, making it diffucult to build a secure case or mount the pcb securely to the robot. Mounting hole can be added to the pcb but it would most likely cause the board to be slightly bigger than it is now.

<h2>Datasheets:</h2>

Ti LM340s-5v Voltage regulator: https://www.ti.com/lit/ds/symlink/lm340.pdf 
