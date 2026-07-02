# 🔥 Fire-Robo
### Arduino-Based Autonomous Fire Fighting Robot

<p align="center">
  <img src="https://img.shields.io/badge/Arduino-Uno-blue?style=for-the-badge&logo=arduino">
  <img src="https://img.shields.io/badge/Language-C%2B%2B-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</p>

---

## 📖 Overview

**Fire-Robo** is an autonomous fire-fighting robot designed to detect flames, navigate toward the fire source, and extinguish it using a water spraying mechanism.

The project demonstrates the practical implementation of embedded systems, robotics, sensors, and automation using the Arduino platform. It is intended for educational purposes, robotics competitions, and real-world fire detection demonstrations.

---

## ✨ Features

- 🔥 Automatic flame detection
- 🚗 Autonomous navigation towards fire
- 💧 Water pump activation for extinguishing flames
- 🎯 Multi-directional flame sensing
- ⚡ Real-time response
- 🤖 Fully Arduino-based embedded system
- 🔋 Portable and battery-powered design

---

## 🛠 Hardware Components

| Component | Quantity |
|-----------|----------|
| Arduino Uno | 1 |
| Flame Sensor Module | 3 |
| L298N Motor Driver | 1 |
| DC Gear Motors | 2 |
| Servo Motor | 1 |
| Water Pump | 1 |
| Relay Module | 1 |
| Chassis | 1 |
| Wheels | 2 |
| Caster Wheel | 1 |
| Battery Pack | 1 |
| Jumper Wires | As Required |

---

## 💻 Software Used

- Arduino IDE
- Embedded C / Arduino C++
- Arduino Libraries

---

## ⚙ Working Principle

1. The flame sensors continuously monitor the surroundings.
2. Once a flame is detected, the Arduino identifies its direction.
3. The robot moves toward the detected flame.
4. When it reaches a predefined distance, the robot stops.
5. The servo motor aims the water nozzle.
6. The water pump is activated.
7. Water is sprayed until the flame is extinguished.
8. The robot resumes monitoring for additional fire sources.

---

## 📂 Project Structure

```
Fire-robo/
│
├── FireRobo.ino
├── README.md
├── circuit/
├── images/
└── documentation/
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/mohit2814v/Fire-robo.git
```

### Open the Project

1. Launch Arduino IDE.
2. Open the `.ino` file.
3. Select your Arduino board.
4. Select the correct COM Port.
5. Upload the code.

---

## 🔌 Circuit Connections

| Module | Arduino Pin |
|----------|-------------|
| Flame Sensor Left | Digital Pin |
| Flame Sensor Center | Digital Pin |
| Flame Sensor Right | Digital Pin |
| L298N IN1-IN4 | Digital Pins |
| Servo Motor | PWM Pin |
| Relay Module | Digital Pin |

> **Note:** Update the pin numbers according to your circuit connections.

---

## 📸 Project Images

Add your project images here.

```
images/
├── robot.jpg
├── circuit.png
├── working.jpg
```

Example:

```markdown
![Robot](images/robot.jpg)
```

---

## 🎥 Demonstration

Upload a demonstration video to YouTube and add it here.

```
https://youtu.be/your-video-link
```

---

## 📈 Applications

- Industrial fire monitoring
- Fire safety demonstrations
- Robotics competitions
- Educational institutions
- Embedded systems learning
- Smart automation projects

---

## 🔮 Future Improvements

- Wi-Fi control
- IoT monitoring
- Mobile App integration
- GSM emergency alerts
- Smoke sensor integration
- Camera-based fire detection
- AI-powered flame recognition
- Obstacle avoidance using Ultrasonic Sensor

---

## 🧠 Skills Demonstrated

- Arduino Programming
- Embedded Systems
- Robotics
- Sensor Interfacing
- Motor Control
- Servo Control
- Automation
- Circuit Design
- Problem Solving

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create your feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push the branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 👨‍💻 Author

**Mohit Gupta**

- GitHub: https://github.com/mohit2814v
- LinkedIn: *(Add your LinkedIn profile here)*

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates future development.

---

## 📄 License

This project is licensed under the MIT License.

---

<p align="center">
Made with ❤️ using Arduino and Robotics
</p>
