# DIY-Low-Cost-Ventilator

* This project documents the process of converting a low-cost CPAP (Continuous Positive Airway Pressure) blower into a rudimentary non-invasive pressure support ventilator that could help with breathing during respiratory distress.  It's an evolving project, but in it's current form, it most aligned with the definition of a non-invasive pressure support BiPAP ventilator.

# Materials
1. [Continuous Positive Airway Pressure (CPAP)]

2.  [Arduino Nano]to control the motor speed, breathing cycles, and handle user input.   

3. Brushless DC Motor [Electronic Speed Controller] 

4. Button or switch for input control.  The code cycles through 5 levels of pressure. Double click to switch between CPAP and BiPAP/Fixed PEEP mode.

5. 12v DC power supply that can handle at least 5A.  The blower works pretty hard, and the breathing cycles can create voltage drops which will reset the Arduino if the supply is not strong enough.

6. Tubing and face mask.  

7. Optional [inline 12v battery backup]
