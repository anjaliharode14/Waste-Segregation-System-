Project Description
The Waste Segregation System is an automated embedded system designed to classify solid waste into metallic, wet (organic), and dry categories. The system uses the Arduino Uno as the main controller along with multiple sensors and actuators to perform accurate and efficient waste segregation at the source level. This helps reduce manual effort and promotes eco-friendly waste management.

🎯 Objectives
Automate the waste segregation process
Reduce human effort and errors
Improve recycling efficiency
Promote sustainable waste management practices

🧰 Components Used
Arduino Uno
Inductive Proximity Sensor
Moisture / Rain Sensor
IR Obstacle Sensor
28BYJ-48 stepper motor
ULN2003 driver board
SG90 servo motor
Li-ion 18650 Batteries (3.7V × 2)
Jumper Wires
Buzzer (Optional)

⚙️ System Architecture
The system consists of three main parts:
Input Section – Sensors detect the type and presence of waste
Processing Unit – Arduino processes sensor data
Output Section – Motors perform bin rotation and lid control

🔄 Working Principle
The IR sensor detects the presence of waste.
The system activates and reads data from sensors.
Inductive sensor detects metallic waste.
Moisture sensor detects wet waste.
If neither condition is satisfied, waste is considered dry.
Arduino processes the data and sends signals to motors.
The stepper motor rotates the bin platform.
The servo motor opens the lid for disposal.

💻 Software Requirements
Arduino IDE
Embedded C Programming
Libraries Used:
CheapStepper
Servo

🔋 Power Supply
The system is powered using two 3.7V Li-ion 18650 batteries, providing portability and efficient energy usage.

📊 Results
Achieved nearly 100% accuracy in controlled testing
Fast response time with minimal delay
Smooth and reliable motor operation

📈 Applications
Household waste management
Smart cities
Public places (railways, malls, etc.)
Industrial waste segregation

🚀 Future Scope
Integration with IoT for real-time monitoring
Mobile app connectivity
AI/ML-based waste classification
Solar-powered system enhancement

⚠️ Limitations
Accuracy may reduce for mixed waste
Sensor dependency limits detection precision
Prototype suitable for small-scale use
