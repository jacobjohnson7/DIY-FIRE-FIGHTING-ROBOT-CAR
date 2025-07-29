# DIY-FIRE-FIGHTING-ROBOT-CAR
An autonomous Arduino-based fire-fighting robot that detects fire using IR flame sensors and extinguishes it with a water pump. It navigates toward flames, reducing human risk in hazardous areas. Features motorized movement, sensor integration, and automated extinguishing. Code is in C/C++ for real-time control.

# DIY Fire Fighting Robot | Auto Fire Chaser & Extinguisher

## Project Overview
This project presents an autonomous fire-fighting robot built using an Arduino microcontroller. The robot detects fire through infrared (IR) flame sensors, navigates towards the fire source, and activates a water pump to extinguish the flames. This system reduces human risk in dangerous fire-prone areas and can be applied in environments such as chemical labs, factories, server rooms, and remote locations.

## Features
- **Autonomous fire detection:** Uses 3 IR flame sensors to detect the presence and direction of fire.
- **Motorized mobility:** Four DC gear motors controlled by an L298 motor driver enable smooth navigation.
- **Fire extinguishing:** A water pump controlled via a TIP-122 transistor sprays water to put out the fire.
- **Servo motor control:** Mini servo helps aim the water spray accurately.
- **Powered by rechargeable 18650 batteries** for portability and extended use.
- **Low-cost and efficient** using basic electronic components and Arduino programming.

## Components Used
| Component                  | Quantity | Purpose                                |
|----------------------------|----------|---------------------------------------|
| Arduino UNO                | 1        | Microcontroller                        |
| IR 4-Pin Flame Sensors     | 3        | Fire detection                        |
| BO DC Gear Motors          | 4        | Movement                             |
| L298 Motor Driver          | 1        | Motor control                        |
| Mini Servo                 | 1        | Water spray aiming                   |
| Water Pump (5-9V)          | 1        | Fire extinguishing                   |
| Water Tank / Bottle        | 1        | Water storage                       |
| 3.7V 18650 Batteries       | 2        | Power supply                       |
| TIP-122 Transistor + Capacitor + Resistor | 1 set  | Control high current devices       |
| Solder-less Breadboard     | 1        | Circuit prototyping                  |
| Jumper Wires               | -        | Electrical connections               |
| Chassis                   | 1        | Robot structure                     |

## Programming Languages
- **C / C++** for Arduino microcontroller programming enabling real-time sensor reading, motor control, and actuator management.

## How It Works
1. IR flame sensors detect the heat and infrared light emitted by fire.
2. Sensor data is sent to the Arduino for processing.
3. The robot moves toward the fire using DC motors controlled via the L298 motor driver.
4. Upon reaching the fire source, the Arduino activates the water pump through a TIP-122 transistor.
5. The mini servo aims the water spray for efficient extinguishing.

## Installation & Usage
1. Assemble the hardware components as per the wiring diagram.
2. Upload the Arduino code (`fire_fighting_robot.ino`) to the Arduino UNO.
3. Power on the robot using the rechargeable batteries.
4. Place the robot in an environment with a fire source for autonomous operation.

## Safety Precautions
- Use small, controlled flames during testing.
- Ensure water and electrical components are properly insulated.
- Keep away from hazardous chemicals during operation.

## Future Improvements
- Integrate wireless control or monitoring via IoT.
- Add smoke sensors for early fire detection.
- Enhance navigation using ultrasonic sensors or camera modules.

---

**Feel free to contribute, report issues, or suggest improvements!**

---

### License
This project is open-source under the MIT License.

---

### Contact
For questions or support, please open an issue or contact [firerobot@gmail
.com].
