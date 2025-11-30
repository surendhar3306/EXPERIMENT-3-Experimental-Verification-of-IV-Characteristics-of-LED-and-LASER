
# Exp 3 Experimental Verification of IV Characteristics of LED and LASER
# Fiber Optic LED Characteristics and Photo Detector Response

## 🎯 AIM
To study the characteristics of fiber optic LED and plot the graph of forward current versus optical power, and to study the photo detector response.

---

## 🧰 EQUIPMENTS REQUIRED
- Power supply  
- Patch chords  
- 1-meter fiber optic cable  
- Digital Multimeter (DMM)  

---

## 📚 THEORY

- **LEDs and LASER diodes** are commonly used sources in optical communication systems for both digital and analog transmission.
- A **linear electrical-to-optical converter** is essential for intensity modulation and high-quality analog transmission.
- LEDs exhibit a **linear optical output** with respect to forward current within a specific operating range.

---

## 🧪 PROCEDURE

1. Connect the power supply to the board.
2. Ensure all switched faults are in the ‘Off’ position.
3. Set emitter 1 block to **Digital Mode**.
4. Make the following connections:
   - Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
   - Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
5. Connect the DMM between +12V supply and TP6 (LED cathode) to measure **forward voltage (Vf)**.
6. Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.  
   - **Forward current (If)** = DMM reading / 1000 (in mA)
7. Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
8. Record values of Vf and If, and plot the characteristic curve between them.

---

## 🔌 CONNECTION DIAGRAM

<img width="773" height="485" alt="image" src="https://github.com/user-attachments/assets/43dc41da-70eb-44fc-87c0-5211ffdae836" />

---

## 📊 TABULATION

### LED Forward Characteristics

| Forward Voltage Vf (V) | Forward Current If (mA) |
|------------------------|-------------------------|
| 0.9 mV                 | 0.1 mA                  |
| 1.2 mV                 | 0.1 mA                  |
| 1.9 mV                 | 0.2 mA                  |
| 2.5 mV                 | 0.3 mA                  |
| 2.7 mV                 | 0.4 mA                  |
| 3.6 mV                 | 1.5 mA                  |
| 4.0 mV                 | 1.8 mA                  |
| 5.2 mV                 | 2.8 mA                  |
| 7.6 mV                 | 4.1 mA                  |
| 6.0 mV                 | 4.2 mA                  |
| 10.2 mV                | 7.2 mA                  |
| 12.5 mV                | 9.4 mA                  |
| 15 mV                  | 10.1 mA                 |

<img width="956" height="1100" alt="image" src="https://github.com/user-attachments/assets/c6f2d85f-7ee1-402f-bd93-abb041c83563" />


---

## 📈 MODEL GRAPH
![WhatsApp Image 2025-11-17 at 04 10 52_905e93c7](https://github.com/user-attachments/assets/b5206a1a-bf03-4444-9104-39b3f095ba83)


---

## ✅ RESULT
- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.
