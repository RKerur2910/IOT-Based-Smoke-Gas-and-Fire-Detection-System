# IOT-Based-Smoke-Gas-and-Fire-Detection-System

🔥 Fire and Smoke Detection System Using Arduino
This project demonstrates the development of a Fire and Smoke Detection System using the Arduino platform. The system monitors environmental conditions using sensors to detect fire and smoke, and alerts users using a buzzer and LED when hazards are detected.

This solution is suitable for home security, industrial safety, or any environment requiring reliable fire monitoring.

🚀 Features
🔥 Fire Detection – Uses a flame sensor to detect nearby fire.

💨 Smoke Detection – Uses an MQ-2 gas sensor to identify smoke and harmful gases.

🚨 Alert System – Activates a buzzer and LED when hazards are detected.

🤖 Arduino-Based – Easy to build and program.

💰 Cost-Effective – Built with affordable components.

🧰 Components Required
Arduino Uno (or compatible board)

Flame Sensor

MQ-2 Gas Sensor (Smoke/Gas)

Buzzer

LED (e.g., Red for alert)

Resistors (e.g., 220Ω for LED, as needed for circuit)

Breadboard & Jumper Wires

USB Cable / Power Supply

🔌 Circuit Diagram & Wiring
🔥 Flame Sensor
Pin	Arduino
VCC	5V
GND	GND
A0	A0

💨 MQ-2 Gas Sensor
Pin	Arduino
VCC	5V
GND	GND
A0	A1

🔔 Buzzer & LED
Component	Arduino Pin
Buzzer	D2
LED	D3

Note: Connect the negative terminals to GND through appropriate resistors.

⚙️ How It Works
Flame Detection: The flame sensor continuously checks for infrared light from fire. If a flame is detected, it sends a signal to the Arduino.

Smoke Detection: The MQ-2 sensor monitors air quality. If smoke or harmful gases exceed a set threshold, it sends a high signal.

Alert: If either the flame or smoke sensor triggers an alert, the system activates a buzzer and LED to notify users of potential danger.

🎯 Calibration
MQ-2 Sensor: Needs environmental calibration. Adjust the smokeThreshold in the code (default: 300) based on sensor readings.

Flame Sensor: May also need to be tested and adjusted for sensitivity.

🔧 Installation & Testing
Build the Circuit: Wire all components according to the diagram.

Upload the Code: Open Arduino IDE, paste the sketch, and upload it to your board.

Monitor the System: Power the Arduino. The system begins detecting fire and smoke.

Test Triggers: Use a lighter or incense stick to simulate smoke or flame detection.

🛠️ Troubleshooting
Issue	Solution
Sensor not detecting	Check connections, power, and analog input pins
False alarms	Calibrate sensors; check for environmental factors (humidity, gases)
No alert on detection	Ensure buzzer and LED are wired correctly and receiving signals from the Arduino

🤝 Contributing
Feel free to fork this repo, report issues, or submit pull requests with improvements!

