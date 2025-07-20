Name:SANDEEP S
Company:CODETECH IT SOLUTIONS
ID:CT06DG25
Domain:EMBEDDED SYSTEM
Duration:June 10th to July 25th

Project Title:
Temperature Monitoring System using Arduino
 Objective:
To build a simple, cost-effective system that:

Continuously monitors the ambient temperature using a sensor.

Displays the temperature on an LCD screen or Serial Monitor.

Can be adapted for real-time temperature logging, threshold alerts, or environmental automation.

 Project Concept:
The system uses a temperature sensor (LM35 or DHT11) to measure the ambient temperature.

An Arduino board reads the sensor data and converts it to Celsius.

The temperature is displayed either:

On a 16x2 LCD display, or

Via the Serial Monitor on a connected computer.

 Hardware Components:
Component	Description
Arduino UNO/Nano	Microcontroller for processing
LM35 or DHT11	Temperature sensor
16x2 LCD (optional)	To display the temperature visually
Potentiometer	For LCD contrast control (if used)
Breadboard & wires	For circuit prototyping
Power Source	USB cable or 9V battery

 Circuit Overview:
➤ Using LM35 + Serial Monitor
LM35 OUT → Arduino A0

LM35 VCC → Arduino 5V

LM35 GND → Arduino GND

➤ Optional LCD Display:
LCD connected to Arduino pins (RS, EN, D4–D7).

Potentiometer used to adjust contrast.

 Software / Code Features:
Reads analog voltage from LM35.

Converts voltage to temperature in Celsius.

Displays temperature:

On Serial Monitor every second

Or on 16x2 LCD screen (if connected)

 Expected Output:
 If using Serial Monitor:
makefile
Copy
Edit
Temperature: 25.78 °C
Temperature: 26.01 °C
Temperature: 26.14 °C
 If using 16x2 LCD:
makefile
Copy
Edit
Temp: 25.78 C

 Working Principle:
Step	Description
1. Sensor senses ambient temperature.	
2. Sensor outputs voltage proportional to the temperature.	
3. Arduino reads this voltage via analog pin.	
4. Arduino converts it to temperature (in °C).	
5. The result is displayed via Serial Monitor or LCD.	

 Applications:
Weather stations

Smart thermostats

Industrial temperature monitoring

Server room/environment control

Educational projects

