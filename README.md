# ECG signal acquisition: Analog front-end 
This project presents a complete Electrocardiogram (ECG) signal acquisition system, covering both analog front-end design and digital signal processing.

Electrocardiography (ECG) is the electrical measurement of heartbeat activity. ECG test can be performed 
easily since the electrical signals produced by the cardiac muscles are much higher than the other 
Electrophysiological signals. The ECG waveform can be used to reliably determine the anomalies of a 
heartbeat by analyzing various frequency components of the signal. For a healthy person, the normal 
heart rate is between 60 to 100 beats per minute.  
This continuous electrical activity during the heartbeats can be non-invasively recorded by attaching three 
disposable adhesive Ag/AgCl electrodes on the chest region as depicted in Figure 1. Amplifier signal input 
and the reference are attached approximately 10 cm apart while the ground electrode is placed a few 
centimeters below the right shoulder

<img width="522" height="259" alt="image" src="https://github.com/user-attachments/assets/6cca93aa-0830-49c4-b80e-40213ed1dff4" />


## Key Features
- 📡 Real-time ECG signal acquisition
- 🔊 Low-noise analog front-end design
- ⚙️ Instrumentation amplifier implementation
- 📉 Analog filtering (HPF + LPF)

## 📊 ECG Signal Basics
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
---
![ecg](https://github.com/user-attachments/assets/2540f141-797e-495d-babc-103a5eadc84e)

