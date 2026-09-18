# SSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB

## AIM

To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** The baseband signal that will be modulated.
* **Carrier Signal:** A high-frequency signal used for modulation.
* **Analytic Signal:** Constructed using the Hilbert transform to get the in-phase and quadrature components.

### 3. SSBSC Modulation:

* **Modulated Signal:** Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.

### 4. SSBSC Demodulation:

* **Mixing:** Multiply the SSBSC signal with the carrier to retrieve the message signal.
* **Low-pass Filtering:** Apply a low-pass filter to remove high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## TABULATION
<img width="816" height="1280" alt="WhatsApp Image 2026-09-18 at 21 20 18" src="https://github.com/user-attachments/assets/58d7f300-e1c4-4de0-ac04-91223f5c1b24" />



## Calculation
<img width="1600" height="1538" alt="WhatsApp Image 2026-09-18 at 21 22 50" src="https://github.com/user-attachments/assets/7b5b7590-ba52-45aa-80fc-93e2c2a40d7c" />

## Output
<img width="1071" height="634" alt="image" src="https://github.com/user-attachments/assets/57b83a14-26e3-4792-a5e9-9a7df15ce809" />

## Result
Successfully performed SSBSC modulation and demodulation using SCI LAB.








