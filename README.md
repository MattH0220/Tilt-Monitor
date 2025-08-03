# Tilt-Monitor

## Overview
Drill Guide Pro is a precision drilling assistance tool designed to improve accuracy and efficiency for professional and DIY drilling tasks. This personal project integrates advanced sensors and microcontrollers to deliver real-time feedback, ensuring precise drill alignment and depth control. The system combines custom hardware and embedded software in a compact, user-friendly package compatible with standard drilling equipment.

## Objective
The goal of Drill Guide Pro was to develop a portable, reliable device that enhances drilling accuracy through sensor-based feedback and automated control. The project focused on integrating multiple sensors and a microcontroller into a cohesive system, prioritizing ease of use, precision, and durability. Key objectives included achieving accurate angle and depth measurements and providing real-time user feedback.

### Skills Gained
- Embedded systems programming for sensor integration and real-time control.
- Sensor calibration and data processing for precise measurements.
- PCB design and circuit prototyping for compact hardware.
- Mechanical design for ergonomic and durable device housing.
- Firmware development using C/C++ for microcontrollers.
- Iterative testing and problem-solving to optimize performance.
- Project planning and technical documentation.

### Tools and Technologies
- **Sensors**: MPU-6050 (accelerometer/gyroscope), VL53L0X (ToF distance sensor), Hall-effect sensor.
- **Microcontroller**: STM32F103 for sensor data processing and feedback control.
- **Software**: STM32CubeIDE (firmware), KiCAD (PCB design), FreeCAD (mechanical design).
- **Hardware**: Multimeter, oscilloscope, soldering station for prototyping.
- **Other**: 3D printer for custom enclosures and mounting components.

## Development Steps
1. **Sensor Selection and Integration**  
   Chose MPU-6050 for tilt/orientation, VL53L0X for depth measurement, and a Hall-effect sensor for drill bit position detection. Interfaced with the STM32F103 using I2C and GPIO for accurate data collection.

2. **Firmware Development**  
   Wrote firmware to process sensor data in real-time, calculate drill angles, and monitor depth. Implemented a feedback system with LEDs and a vibration motor for user alerts.

3. **Hardware Design**  
   Designed a compact PCB to house the STM32F103, sensors, and feedback components, optimized for signal integrity and low power consumption with a rechargeable battery.

4. **Mechanical Design**  
   Developed a 3D-printed enclosure for electronics protection and drill mounting, ensuring ergonomic design and operational durability.

5. **Testing and Calibration**  
   Calibrated sensors and validated system accuracy through real-world drilling tests, achieving ±1° tilt accuracy and ±0.5 mm depth accuracy.

6. **System Integration and Validation**  
   Integrated all subsystems into a single prototype, testing performance in simulated and actual drilling scenarios to ensure low-latency feedback and reliability.
