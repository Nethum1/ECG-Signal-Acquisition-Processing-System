# ECG-Signal-Acquisition-Processing-System
This project presents a complete Electrocardiogram (ECG) signal acquisition system, covering both analog front-end design and digital signal processing.

## Key Features
- 📡 Real-time ECG signal acquisition
- 🔊 Low-noise analog front-end design
- ⚙️ Instrumentation amplifier implementation
- 📉 Analog filtering (HPF + LPF)

📊 ECG Signal Basics
<img width="1002" height="872" alt="image" src="https://github.com/user-attachments/assets/d98c8e04-45ef-4af2-a2be-e698c1c63078" />

- P Wave – Atrial depolarization
- QRS Complex – Ventricular depolarization
- T Wave – Ventricular repolarization

## 🔌 Analog Front-End Design

```
Electrodes
   ↓
Instrumentation Amplifier
   ↓
High Pass Filter (0–0.05 Hz)
   ↓
Low Pass Filter (< 40 Hz)
   ↓
Voltage Level Shifter
   ↓
Clean ECG Output
```
## Circuit 
