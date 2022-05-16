<b>ABSTRACT</b> :

Wiper is an essential component that used to wipe raindrops or any water from the vehicle’s windscreen.
The previous system used to activate the wiper manually and the process of pulling up the wiper is difficult to be handled. 
Thus, this system is proposed to solve these problems. The objectives of this project are to upgrade the older cars system by providing automatic wiping system, to improve the system by using sensor with actuator and to design a basic program that will fully operate with the system. 
The concept of this proposed wiper system is similar with other existing conventional wiper. 
It contros the movement of wiper using a single switch designed for all of its functions as switch off, switch on , start the wiper represented by LEDs and change the speed.

<b><h1>Wiper Control System</h1></b> 
<h2>Introduction:</h2>
Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed and made to clear the water from a windscreen. Most of cars have two wipers on the windscreen, one on the rear window and the other on each headlight.
The wiper parts visible from outside the car are the rubber blade, the wiper arm holding the blade, a spring linkage, and parts of the wiper pivots.
The wiper itself has about six parts called pressure points or claws that are small arms under the wiper
Existing system manually used control stalk to activate wiper and the process of pulling up wiper is difficult to be handled.
The driver needs to switch on and off the control stalk and it will reduce the driver’s concentration during the driving.
Thus, this system is proposed to solve all these problems. The concept of this wiper system is similar with other conventional wiper, yet this system will be upgraded to an automatic control system by using a controller.
Whenever the water hit a dedicated sensor that located on windscreen, it will send a signal to move on the wiper motor.
Once water is not detected by sensor, the wiper will automatically stop. This will help the driver to give more concentration and reduce the car accident probability.
The system  activates the wipers to be operated in full automatic mode.
It has a response time at 0.1 seconds. It allowed for a quick reaction when it is a sudden splashes of water that will make the driver totally ‘blinds’ when the situation happened.
With the automatic wiper, the driver can avert from the risk of an accident. The automatic wiper is important during the heavy traffic e.g. in town, city, school zone and other public place. 
A driver may be subjected to many distractions with bad weather, dangerous road conditions and fatigue.

<h2>Objective:</h2>
To switch off & on and change the speed of wiper(represented through LEDs - blue red , orange) using stm32 by using a single switch button in the arm emulator.

<h2>Components:</h2>
.STM Cube IDE<br>
.Qemu<br>
.Arm controller<br>
.Push Button<br>
.LED +3<br>
.5V Power Supply<br>
.Switch<br>

<h2>HIGH LEVEL REQUIREMENTS:</h2>
SNO	DESCRIPTION	STATUS<br>
HLR1	Qemu Programmming for Arm controller<br>
HLR2	PUSH BUTTON INTERFACING WITH STM32S407Vg	IMPLEMENTED<br>
<h2>LOW LEVEL REQUIREMENTS:</h2>
SNO	DESCRIPTION	STATUS<br>
HLR1-LLR1	To control switch off & on using single button long press<br>
HLR1-LLR2	To change the speed by a click<br>
HLR2-LLR1	To blink the LEDs used as wipers<br>
HLR2-LLR2 To properly control & manage the system

<h2>Block Diagram</h2>

![image](https://user-images.githubusercontent.com/72467936/168502767-94be7c43-4e69-4143-8313-5a4aa89e81ec.png)

<h2>Flowchart</h2>

![image](https://user-images.githubusercontent.com/72467936/168503351-6c69d3b7-6e55-470c-a5e6-d1937bad87af.png)

<h2>Circuit Diagram</h2>

![image](https://user-images.githubusercontent.com/72467936/168502790-7c81dd77-6728-495a-9321-9e1a365e5896.png)

