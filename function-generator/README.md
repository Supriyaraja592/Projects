## 🔊 Function Generator (LM324 Based)

A low-cost **Function Generator** circuit designed using the **LM324 operational amplifier**.  
The circuit is capable of generating **sine, square, and triangular waveforms** at variable frequencies.

### 🔹 Working Principle
- The LM324 op-amp is configured to operate as an oscillator.  
- Different stages of the circuit generate:
  - **Square Wave** – directly from the op-amp oscillator output.  
  - **Triangular Wave** – obtained by integrating the square wave.  
  - **Sine Wave** – shaped from the triangular waveform using a wave-shaping network.  

### 🔹 Features
- Generates **Sine, Square, and Triangular** signals.  
- Frequency range adjustable by tuning RC components.  
- Simple, affordable design using widely available components.

### Circuit Diagram
<img width="610" height="312" alt="image" src="https://github.com/user-attachments/assets/e75dcf04-46fa-4ed7-b7d8-9e91678aa11b" />

### LT Spice Simulation 
Circuit
<img width="615" height="345" alt="image" src="https://github.com/user-attachments/assets/114e01a1-bb73-42cb-a0dc-3590135e6e5b" />

Output
<img width="659" height="405" alt="image" src="https://github.com/user-attachments/assets/fac37fbb-71f5-44f1-9317-5d82c2b32062" />


### 🔹 Components Used
- LM324 (Quad Op-Amp IC)  
- Resistors  
- Capacitors  
- Potentiometers (for tuning frequency)  
- Power supply

### Output
<img width="609" height="372" alt="image" src="https://github.com/user-attachments/assets/9d44a025-1bab-4629-ae51-a745a7ac9a2c" />

<img width="533" height="587" alt="image" src="https://github.com/user-attachments/assets/aba00fe7-a45e-4e41-ab1b-5b8cbb33ad4a" />


### 🔹 Applications
- Signal source for testing electronic circuits.  
- Educational tool for studying waveforms.  
- Useful in labs where a simple, low-cost function generator is required.
