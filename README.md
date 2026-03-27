## EX.NO:4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR RC Phase Shift and Wien Bridge oscillators 
## DATE:10.2.2026
## AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.

## THEORY:
## RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .


## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 

---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR

![WhatsApp Image 2026-03-27 at 10 33 40 PM](https://github.com/user-attachments/assets/aed81cf9-2903-470a-a720-d7d8c8b31396)

---

## MODEL GRAPH
![WhatsApp Image 2026-03-27 at 10 34 48 PM](https://github.com/user-attachments/assets/0e7ad41c-2a40-489d-9e91-a8185d97e467)

## DESIGN

## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ
![WhatsApp Image 2026-03-27 at 10 35 48 PM](https://github.com/user-attachments/assets/a2a0548f-8c21-4733-921b-6868f53ad12b)

---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION
![WhatsApp Image 2026-03-27 at 10 38 06 PM](https://github.com/user-attachments/assets/9a95c1dc-f728-4c72-858c-41ce1a9c0113)


## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2026-03-27 at 10 40 31 PM](https://github.com/user-attachments/assets/c172adff-cf0f-49a5-a1d6-cce1caaacb0c)

---
## WIEN BRIDGE
## THEORY
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR
![WhatsApp Image 2026-03-27 at 10 41 51 PM](https://github.com/user-attachments/assets/f9dafcef-81f6-4d35-9357-a6599ae338c9)
 

---
## MODEL GRAPH
![WhatsApp Image 2026-03-27 at 10 42 25 PM](https://github.com/user-attachments/assets/27293fa3-af1e-47b8-8000-ea8a233f6f93)

---

## DESIGN

## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ
![WhatsApp Image 2026-03-27 at 10 44 01 PM](https://github.com/user-attachments/assets/a35c562b-ced4-453f-a288-0fe534d8b46d)


## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION
![WhatsApp Image 2026-03-27 at 10 42 58 PM](https://github.com/user-attachments/assets/4ba3d952-5e56-4cca-ac99-c4297522fd1a)


## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2026-03-27 at 10 41 10 PM](https://github.com/user-attachments/assets/4f399a9f-2393-45e8-9bb1-64e3338d74cf)

---
## RESULT:

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
