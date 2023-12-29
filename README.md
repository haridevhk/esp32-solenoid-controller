# esp32-solenoid-controller
IOT controller or farm automation

Materials Needed:

Hardware:
ESP32 controller board

5V DC for ESP32 controller

12V DC solenoid valve

External 12V DC power supply

Breadboard

Jumper wires (male-to-male and male-to-female)


Software:

Arduino IDE (Integrated Development Environment)
Required libraries for ESP32 and Arduino IoT Cloud (to be installed in Arduino IDE)
Step-by-Step Guide:
1. Prepare Arduino IoT Cloud:
Sign in or create an account on the Arduino IoT Cloud platform.
Create a new 'Thing' and set up your ESP32 as a 'Device' within the Arduino IoT Cloud dashboard.
Note down the necessary credentials and information required to connect your ESP32 to the cloud.
2. Circuit Connection:
Place the ESP32 board on the breadboard.
Connect the 12V DC solenoid valve:
Connect the valve's VCC/+ terminal to the positive terminal of the 12V DC power supply.
Connect the valve's GND/- terminal to both the ESP32's GND pin and the negative terminal of the 12V power supply.
Connect the valve's signal wire (control wire) to a digital pin on the ESP32 (for example, Pin 12).
Make sure all connections are secure and no loose wires touch each other.
3. Arduino Sketch (Code):
Open the Arduino IDE on your computer.
Create a new sketch and include the necessary libraries for the ESP32 and Arduino IoT Cloud (if not already included).
Set up the IoT Cloud connection using the provided credentials and the 'thing' created earlier in the Arduino IoT Cloud dashboard.
Write the code to control the solenoid valve based on the cloud's state. Here's an example:
arduino
Copy code to arduino 
4. Upload Code to ESP32:
Connect the ESP32 to your computer via USB.
Choose the correct board and port in the Arduino IDE.
Upload the code to the ESP32.
5. Test the System:
Access the Arduino IoT Cloud dashboard using your web browser or the Arduino IoT Cloud app.
Locate and interact with your device.
Test the solenoid valve by toggling the corresponding switch or button in the dashboard.
6. Safety Considerations:
Ensure the correct polarity and voltage for all connections.
Use appropriate power supplies and handle electrical components carefully.
This detailed guide helps high school students connect a 12V DC solenoid valve to an ESP32 controller using Arduino IoT Cloud, facilitating remote control through an easy-to-use dashboard interface.
