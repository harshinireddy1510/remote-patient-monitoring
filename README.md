# remote-patient-monitoring
An ESP32-based Remote Patient Monitoring System developed during the Elevance Skills internship. This project includes six tasks covering FreeRTOS, IoT monitoring, role-based dashboards, offline data buffering, smart bed control, dosage monitoring, and system integration using Wokwi, MQTT, and web technologies.
# Remote Patient Monitoring System

## Project Overview

The **Remote Patient Monitoring System** is an IoT-based healthcare monitoring project developed as part of the Elevance Skills Internship. It uses an ESP32 microcontroller, sensors, MQTT communication, and web-based dashboards to demonstrate real-time patient monitoring, remote control, adaptive sampling, and fault-tolerant operation.

The project consists of six tasks that demonstrate different aspects of smart healthcare and IoT system design.

## Objectives

- Monitor patient health parameters using simulated sensors.
- Demonstrate concurrent task execution using FreeRTOS concepts.
- Implement role-based dashboards for medical staff and facility monitoring.
- Develop a smart medication dosage adjustment system.
- Enable remote bed elevation control.
- Adapt the monitoring sampling rate based on patient conditions.
- Demonstrate offline detection and fault-tolerant data handling.

## Technologies Used

- **Hardware Simulation:** ESP32
- **Simulation Platform:** Wokwi
- **Programming Language:** C/C++ (Arduino framework)
- **Communication Protocol:** MQTT
- **Dashboard Development:** HTML, CSS, JavaScript
- **Cloud/Data Communication:** MQTT broker
- **Version Control and Hosting:** GitHub and GitHub Pages

## Project Tasks and Wokwi Simulations

### Task 1: Multi-Sensor Expansion Using FreeRTOS
Demonstrates multi-sensor patient monitoring and concurrent task execution for processing health parameters, displaying readings, and generating alerts.

[Open Task 1 – Wokwi Simulation](https://wokwi.com/projects/477500208114662401)

### Task 2: Dual-Role IoT Monitoring System
Demonstrates separate dashboards for medical staff and facility monitoring, with MQTT-based data communication and role-specific information.

[Open Task 2 – Wokwi Simulation](https://wokwi.com/projects/477501273878078465)

### Task 3: Smart Medication Dosage Adjustment System
Demonstrates dosage-rate adjustment, status indication, threshold-based warnings, and confirmation for high dosage settings.

[Open Task 3 – Wokwi Simulation](https://wokwi.com/projects/477493418278614017)

### Task 4: Intelligent Remote Bed Elevation Control
Demonstrates remote bed-angle control with predefined positions for sleeping, breathing support, and emergency conditions.

[Open Task 4 – Wokwi Simulation](https://wokwi.com/projects/477565946960177153)

### Task 5: Smart Dynamic Sampling Rate
Demonstrates adaptive monitoring intervals based on patient readings, with automatic and manual sampling-rate control.

[Open Task 5 – Wokwi Simulation](https://wokwi.com/projects/477579397228683265)

### Task 6: Advanced Offline Detection
Demonstrates online, degraded, and offline system states, along with offline data buffering and synchronization when connectivity is restored.

[Open Task 6 – Wokwi Simulation](https://wokwi.com/projects/477581348485351425)

## Web Dashboards

The project includes four web dashboards for displaying monitoring information and interacting with the simulated systems.

1. **Medical Staff Dashboard:** Displays patient health parameters.
2. **Facility Monitoring Dashboard:** Displays environmental and facility information.
3. **Remote Bed Control Dashboard:** Provides remote bed-angle control and status monitoring.
4. **Additional Monitoring Dashboard:** Supports the corresponding monitoring task and its features.

**Live Website:** [[](https://github.com/harshinireddy1510/remote-patient-monitoringurl)]

## Project Demonstration

A demonstration video showing the project simulations and dashboards can be accessed here:

[[Watch the Project Demo](https://drive.google.com/file/d/1JUSmagq1MkZbQT_N70Tbr6MX_4mG8f7k/view?usp=drivesdk)]
## Expected Outcomes

- Demonstration of IoT-based healthcare monitoring.
- Real-time communication between simulated devices and dashboards where configured.
- Threshold-based alerts and status updates.
- Remote control and adaptive monitoring features.
- Improved understanding of fault tolerance and connectivity management in IoT systems.

## Conclusion

This project demonstrates how IoT technologies can be applied to remote patient monitoring through sensor simulation, MQTT communication, web dashboards, remote control, adaptive sampling, and offline detection. The six tasks provide practical exposure to embedded systems, connected healthcare applications, and reliable monitoring-system design.

## Author

**Harshini**

Project developed as part of the **Elevance Skills Internship**.

---

*Note: This project is an educational simulation and is not intended to replace certified medical devices or professional medical advice.*
