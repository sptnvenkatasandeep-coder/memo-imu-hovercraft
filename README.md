# memo-imu-hovercraft
Dual-mode hovercraft controlled via RF transmitter and IMU sensor for automatic stabilization
# MEMS IMU-Stabilized Arduino Hovercraft

A college engineering project featuring a hovercraft with propeller thrust propulsion, manual radio control via an RF transmitter, and automatic yaw/drift correction using an Arduino microcontroller and a MEMS IMU sensor.

---

## 🛠️ Components & Hardware
* **Microcontroller:** Arduino (Uno / Nano)
* **IMU Sensor:** MEMS IMU Sensor (e.g., MPU-6050)
* **Propulsion:** BLDC / DC Motors with Propellers & ESC
* **Radio Control:** RF Transmitter & Receiver
* **Chassis:** Foam board / Lightweight frame with air skirt
* **Power:** LiPo Battery Pack

---

## ⚙️ Working Mechanism
1. **Lift & Thrust:** Airflow provides the lift cushion, while the propeller generates directional thrust.
2. **Manual Control:** Transmitter commands control steering and throttle.
3. **IMU Feedback:** The MEMS IMU sensor monitors rotational changes and dynamically compensates to keep the craft steady.

---

## 🚀 How to Run
1. Open the `.ino` file in the Arduino IDE.
2. Connect your Arduino board via USB.
3. Select your board and port under **Tools**.
4. Click **Upload**.
5.
