# 🦯 Sense-Stride

**Sense-Stride** is a smart assistive walking cane designed to improve mobility and safety for visually impaired individuals. It combines time-of-flight sensors, a motion detector, and haptic feedback to detect and alert the user of nearby obstacles in all directions. Built using an STM32H563ZI microcontroller, it offers enhanced spatial awareness while remaining lightweight and user-friendly.

---

## 🚀 Features

- Obstacle detection using **VL53L0X ToF sensors** (Front, Left, Right)
- **Rear motion detection** using a PIR sensor
- **Directional haptic feedback** for real-time alerts
- Roller-integrated bottom for smooth motion
- Robust and ergonomic mechanical design
- Operates independently without external connectivity

---

## 🛠️ Technologies Used

- **Microcontroller**: STM32H563ZI (ARM Cortex-M33)
- **Sensors**: 3x VL53L0X ToF sensors, 1x PIR sensor
- **Feedback**: 4x haptic vibration motors
- **Communication**: I2C bus for sensor integration
- **Software**: Arduino IDE-based implementation, real-time plotting via Serial Plotter

---

## 🔧 System Architecture

The system consists of:
- VL53L0X sensors for distance measurement in 3 directions
- PIR sensor mounted near the shoulder for rear motion detection
- STM32H563ZI MCU for processing and control
- Haptic motors corresponding to each sensor
- A structured software algorithm for real-time monitoring and feedback

---

## 📊 Results Summary

- Obstacle detection accuracy: **95%**
- Rear detection accuracy: **94%**
- Average response latency: **~50 ms**
- Real-time visualization using Arduino Serial Plotter

---

## 👨‍💻 Contributors

- **Megharsh L** – Firmware Development, Sensor Integration  
- **Phalguna KR** – Hardware Design, Testing  
- **E Uday** – System Design, VLSI Architecture  
- **Rudragowda K S** – PIR Integration, Testing  
- **Dr. Madhusudhana K** – Project Mentor and HOD, SDMIT

---

## 📄 License

Specify license here (e.g., MIT, Apache 2.0)

---

## 📚 Acknowledgements

- Department of Electronics and Communication, SDM Institute of Technology, Ujire  
- All users who participated in testing and feedback  
- Arduino and STM32 communities for tools and documentation

---

## 🔗 References

Please refer to the full [project documentation](https://github.com/Megharsh05/Sense-Tride) for detailed technical details and literature references.

