# Project-Tsukuyomi

## Zine
<img width="1410" height="2000" alt="𝓜𝓪𝓷𝓰𝓮𝓴𝔂ō 𝓢𝓱𝓪𝓻𝓲𝓷𝓰𝓪𝓷" src="https://github.com/user-attachments/assets/cb38e4b5-bba9-497d-9c0a-de4376cd07d8" />

## What It Is & Why I Made It

A LED Chaser PCB in the form of a 'Sharingan' from the anime Naruto. I honestly did whatever and tried to do everything relatively simple and looked back at the Stasis starter project for reference. Though this was a lot different in the sheer aspect of number of LEDs I used.

Everytime, I make a new project, I do two things: Make it some media related, and add something new everytime. I have always loved Naruto, and I was wondering how I could implement something from Naruto into a PCB, and also make it something really fun. I honestly have never worked with a lot of LEDs like this but there's a first for everything! Also the first thing I ever learned to make in hardware was a LED chaser from Stasis so roughly tried to do what I remember from there and it was very fun overall!

## How To Use It

1. Connect a 5V power source (USB or other regulated 5V supply) to the power input on the PCB.
2. Once poewr is applied, the circuit starts automatically and the LEDs begin their programmed lighting sequence.
3. The CD4017 counter and timing circuit control the LED pattern, causing the LEDs to illuminate in sequencearound the board.
4. Place the PCB on a flat surface, or display it as desired while powered.
5. If the LEDs do not light up, verify that the power supply is providing 5V and the polarity is correct.
6. If only some LEDs operate, inspect the corresponding LED, resistor, and transitor's solder joints for assembly issues.

## Schematic
<img width="1099" height="772" alt="image" src="https://github.com/user-attachments/assets/5c824c05-8c77-4cc0-9ae5-ca9c59937761" />

## PCB
<img width="960" height="530" alt="image" src="https://github.com/user-attachments/assets/41e6a669-9e85-4128-b8d1-9b85d58453e5" />

## 3D View
<img width="912" height="757" alt="image" src="https://github.com/user-attachments/assets/b1fc6213-10db-4c3d-9ad2-581efe6c91c0" />

## Bill of Materials (BOM)

| Component | Designator | LCSC Part # | Qty | Unit Price | Line Total |
|-----------|------------|-------------|-----|------------|------------|
| LED 5mm Red THT | D2-D31, D36 | C84256 | 31 | $0.0072 | $0.22 |
| 1N4007 Rectifier Diode DO-41 | D1 | C402311 | 1 | $0.0105 | $0.01 |
| 2N2222A NPN Transistor TO-92 | Q1-Q3 | C358533 | 3 | $0.0143 | $0.04 |
| CD4017BE CMOS Decade Counter DIP-16 | U1 | C34519 | 1 | $0.2793 | $0.28 |
| NE555P Timer IC DIP-8 | U2 | C46749 | 1 | $0.0950 | $0.10 |
| 74HC595D 8-bit Shift Register DIP-16 | U3 | C5947 | 1 | $0.1026 | $0.10 |
| Resistor 470Ω 1/4W 5% THT Axial | R1-R7 | C134767 | 7 | $0.0100 | $0.07 |
| Capacitor 100uF 25V Electrolytic Radial | C1 | C134099 | 1 | $0.0680 | $0.07 |
| Male Pin Header 2.54mm 1x05 Straight | J1 | C124378 | 1 | $0.0196 | $0.02 |

**Total Cost: $0.91**

# JLCPCB

<img width="1880" height="621" alt="image" src="https://github.com/user-attachments/assets/f810186d-4a77-49d2-ade5-d756b6246aa6" />

