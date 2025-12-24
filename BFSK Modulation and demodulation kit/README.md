# 📟 Binary Frequency Shift Keying (BFSK) Modulation & Demodulation Kit

## 📌 Introduction
Binary Frequency Shift Keying (BFSK) is a digital modulation technique where the frequency of a carrier signal is varied according to the binary input (0s and 1s). This project features a hardware kit designed to demonstrate real-time data encoding and recovery.

The circuit is designed for simplicity and stability, offering high noise immunity and zero amplitude fluctuations, making it ideal for low-speed digital communication.

---

## 🛠️ System Overview
The project is divided into two main functional sections:

### 1. Modulator Section
* **Carrier Generation**: Uses two sine wave generators to produce distinct carrier frequencies ($F_1$ for '0' and $F_2$ for '1').
* **Input Source**: A square wave generator provides the binary data to be transmitted.
* **Frequency Selection**: Transistors (BC547 and BC557) act as switches to select the high or low frequency based on the input logic.

### 2. Demodulator Section
* **PLL Detection**: Employs the **NE565 Phase-Locked Loop (PLL) IC** to lock onto incoming frequencies and convert them into varying DC voltage levels.
* **Signal Regeneration**: Uses an **IC 741 Op-Amp** as a comparator to convert the DC levels back into a clean digital square wave, matching the original input.

---

## 📂 Components Used
* **IC 741**: Operational Amplifier used for signal comparison and wave shaping.
* **NE565**: Phase-Locked Loop (PLL) IC for frequency demodulation.
* **BC547 / BC557**: NPN/PNP transistors for modulation switching.
* **Potentiometer**: For fine-tuning frequency deviation and calibration.

---

## 📊 Technical Specifications
| Parameter | Value (Approx.) |
| :--- | :--- |
| **Carrier Frequency 1 ($F_1$)** | 4 kHz (Binary '0') |
| **Carrier Frequency 2 ($F_2$)** | 6 kHz (Binary '1') |
| **Message Frequency ($F_m$)** | 22 kHz |

---

## 🎯 Applications
* **Low-Speed Modems**: Early telephone data transmission standards.
* **Telemetry**: Remote data links for satellites and weather balloons.
* **Marine Communication**: Reliable communication in noisy environments.

---

## 📝 Report
The complete project documentation, including circuit diagrams, working principle, and component descriptions, is available here:
[Download Project Report](./Report/DC_REPORT_1.pdf)

## 📷 Hardware and Outputs
The following images showcase the hardware implementation and the resulting waveforms captured during the modulation and demodulation process.

### Project Hardware
The physical BFSK Modulation and Demodulation kit implementation.
![BFSK Project Kit](./Hardware%20Images%20and%20outputs/kit%20image.png)

### Waveform Analysis
Real-time signals captured from the Digital Storage Oscilloscope (DSO):

* **Input Message Signal**: The digital binary data (square wave) to be modulated.
![Input Waveform](./Hardware%20Images%20and%20outputs/input%20wave%20form.png)

* **Carrier Signals**: Two clean sine waves representing binary '1' and '0'.
![Carrier Signals](./Hardware%20Images%20and%20outputs/carrier.png)

* **BFSK Modulated Waveform**: The output signal switching between two frequencies.
![Modulated Waveform](./Hardware%20Images%20and%20outputs/Modulated%20waveform.png)


* **Demodulated Output**: The recovered digital signal after passing through the PLL and comparator.
![Demodulated Waveform](./Hardware%20Images%20and%20outputs/Demodulated%20waveform.png)
