# Smart-Car-Parking-system
This project demonstrates a Smart Car Parking System built using Arduino Nano R3. It automates the process of detecting a vehicle at the entrance and controlling a gate using a servo motor, while displaying real-time status on an LCD screen.
The system is designed as a low-cost and efficient prototype for basic parking automation.
🔧 Components Used
Arduino Nano R3
IR Obstacle Avoidance Sensor
16x2 LCD Display (I2C Module)
SG90 Servo Motor
Breadboard
Jumper Wires (Male & Female)
Laptop (Power Supply & Arduino IDE)
⚙️ Working Principle
The IR sensor detects the presence of a vehicle near the gate.
When a vehicle is detected:
The servo motor rotates to open the gate.
The LCD display shows “Car Detected” and “Gate Opening”.
After a short delay:
The gate closes automatically.
LCD updates the status accordingly.
💡 Features
🚘 Automatic vehicle detection
🔄 Servo-controlled gate system
📟 Real-time LCD status display
💰 Cost-effective implementation
⚡ Compact and efficient design
🛠️ Software Used
Arduino IDE
🚀 Applications
Parking systems in malls and offices
Residential parking automation
Entry/exit gate automation
🔮 Future Scope
Add multiple sensors for parking slot tracking
IoT integration for remote monitoring
Mobile app for real-time updates
RFID-based vehicle authentication
📂 How to Run
Connect all components as per the circuit design
Upload the Arduino code using Arduino IDE
Power the system via laptop or external supply
Place a vehicle near the sensor to test
