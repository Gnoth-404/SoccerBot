# SoccerBot




## Features 🚀

- **Motorized Dribbler & Solenoid Kicker**: Precision ball control and kicking mechanism.  
- **3D-Printed Mecanum Wheels**: Full omnidirectional movement.  
- **Bluetooth Control**: Wirelessly controlled via a custom smartphone app.  
- **Servo Mechanism**: Adjustable servo for shooting angle.  
- **RGB Backlight**: Dynamic color-changing LED lighting for a cool visual effect.  

![Soccerbot](./fig/soccer_bot.jpg)

---

## 3D Design

![Design](./fig/design.png)


## Usage 📲

### 1. Upload Code (Arduino IDE)

1. **Clone the repo**:
   ```bash
   git clone https://github.com/your-username/robot-project.git
   ```
2. **Open in Arduino IDE**, install required libraries (`AFMotor`, `SoftwareSerial`).
3. **Connect Arduino**, select board & port.
4. **Upload** the sketch to the Arduino.

### 2. Control via Smartphone App

- **App built with MIT App Inventor**.
- Connect via Bluetooth and control:
  - **Movements**: 8 direction buttons.
  - **Drib**: Start, stop, speed dribbler.
  - **Fire**: Kick the ball.
  - **LED**: Turn on/off, color transitions.
  - **Servo**: Adjust angles using left and right button.

![App](./fig/android_bot.png)
---

## Circuit Diagram 🛠️
![Circuit Diagram](./fig/diagram.png)