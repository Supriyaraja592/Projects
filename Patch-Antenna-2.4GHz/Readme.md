# 📡 Patch Antenna for Wi-Fi & Bluetooth

## 📌 Introduction
With the rapid growth of wireless communication, compact and high-performance antennas are essential for modern devices. This project involves the **design, simulation, and fabrication** of a microstrip patch antenna tailored for operation in the **2.4 GHz ISM band**.

The design utilizes specific modifications, including an increased substrate height and a copper reflector, to achieve high directional gain and improved radiation efficiency.

---

## 🛠️ System Overview
1. **Design Specifications**:
   * **Operating Frequency**: 2.4 GHz, covering the full ISM band used by Wi-Fi and Bluetooth.
   * **Substrate Material**: FR-4 base with a dielectric constant ($\epsilon_r$) of 4.3.
   * **Feed Type**: 50 $\Omega$ Microstrip line feed for effective power transfer.
2. **Simulation (CST Microwave Studio)**:
   * Optimized patch dimensions of $36 \times 28.68 \text{ mm}$.
   * Performance analysis focused on Return Loss ($S_{11}$), VSWR, and Radiation Patterns.
3. **Fabrication**:
   * Prototype developed using a standard copper-layer PCB process.
   * Integrated a **Copper Reflector** to minimize back radiation and enhance forward gain.

---

## 📊 Key Performance Metrics
| Parameter | Simulated/Measured Value |
| :--- | :--- |
| **Resonant Frequency** |2.4 GHz|
| **Return Loss ($S_{11}$)** | Better than -25 dB |
| **VSWR** | 1.125 (Simulated) / 1.16 (Measured) |
| **Peak Gain** | 2.811 dBi  |
| **Main Lobe Direction** | 0.0 deg (Broadside) |

---

## 🎯 Applications
* **Wi-Fi & Bluetooth Systems**: Routers, wireless modules, and smart devices
* **IoT & Smart Homes**: Connectivity for sensors, automation units, and appliances
* **Medical Devices**: Patient tracking and wearable health modules
* **Robotics**: Command and data transmission for drones and autonomous systems

---

## 📝 Report
The detailed report includes all design equations, CST simulation parameters, and comparisons between simulated and fabricated results.
[PatchAntenna_Report.pdf](https://github.com/supriyaraja592/Projects/blob/main/Patch-Antenna-2.4GHz/14_Patch%20Antenna%20for%20Wifi%26Bluetooth_REPORT3_.pdf)

---

## 👩‍💻 Author
**Supriya R** [GitHub](https://github.com/supriyaraja592)
