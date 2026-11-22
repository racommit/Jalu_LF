# Jalu_LF 🏎️🚗

**Jalu_LF** is an Arduino-based Line Follower Robot project developed as part of a Microcontroller course. The robot is affectionately named **Jalu**, representing the robot built and programmed by our team.

The project focuses on implementing microcontroller concepts, infrared sensor integration, motor control, and basic autonomous navigation.

## 🔗 Technologies & Components

The robot is built using the following hardware components:

- **Arduino Uno** (DIP or SMD)
- **L298N Motor Driver**
- **5-Channel Infrared Sensor Module**
  - Far Left (L2)
  - Left (L1)
  - Center
  - Right (R1)
  - Far Right (R2)
- **DC Motors**
- Battery as the power supply

## 📸 Project Gallery

![Brandon VIEW](https://github.com/racommit/Brandon_LF/blob/main/foto%201.jpg)

## ⚙️ Project Description

Throughout the development and testing process, we identified several factors that significantly affect the performance and stability of Jalu as a line follower robot.

For fellow developers who want to build or modify a similar robot, here are some important considerations based on our experimental results:

### 1. Sensor-to-Surface Distance

The distance between the infrared sensors and the track surface affects sensor readings. We recommend positioning the sensors as close to the ground as possible to achieve more consistent detection.

### 2. DC Motor Speed

Motor speed should be adjusted according to the sensor reading frequency. Excessive motor speed may cause the robot to lose track of the line, especially when navigating curves.

### 3. Battery Capacity

Battery capacity and voltage stability directly influence motor performance and the overall reliability of the robot.

### 4. Control Logic

The logic implemented in the program plays an important role in determining how the robot responds to sensor inputs. Proper conditional statements and motor control algorithms are essential for accurate line tracking.

**Note:** These considerations are based on our team's experimental observations. Actual performance may vary depending on hardware configurations, component specifications, track conditions, and environmental factors. Developers are encouraged to experiment and adjust their implementations accordingly.

## 📝 Development Notes

The latest program updates and additional functions are maintained in the following branch:

- [penambahan-fungsi](https://github.com/racommit/Jalu_LF/tree/penambahan-fungsi)

The `main` branch is intended to be updated every two weeks to keep the primary version synchronized with the project's development progress.

## 👥 Credits & Contributors

**Developed by the 4th Group Team**

| Contributor | Role |
|---|---|
| Ahmad Aldisar Syarifuddin | Technician Support |
| Patansyah | Technician Support |
| Reno Isnan Suwarno | Technician Support, Project Idea |
| Rizky Agusti | Technician Support, Programmer, Project Idea |

## 👨‍💻 Project Owner

![Owner](https://github.com/racommit/Jalu_LF/blob/main/owner.jpg)

---

*Built with curiosity, teamwork, and a passion for robotics.* 🏎️
