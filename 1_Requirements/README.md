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

<h2>HIGH LEVEL REQUIREMENTS:</h2>>
SNO	DESCRIPTION	STATUS<br>
HLR1	Qemu Programmming for Arm controller<br>
HLR2	PUSH BUTTON INTERFACING WITH STM32S407Vg	IMPLEMENTED<br>
<h2>LOW LEVEL REQUIREMENTS:</h2>
SNO	DESCRIPTION	STATUS<br>
HLR1-LLR1	To control switch off & on using single button long press<br>
HLR1-LLR2	To change the speed by a click<br>
HLR2-LLR1	To blink the LEDs used as wipers<br>
HLR2-LLR2 To properly control & manage the system
