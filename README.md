# Automatic-Solar-Day-Night-LED-Switching-Circuit
Dual-Source Automatic Day/Night LED Control Using Zener  Reference and BJT Switching 

Designed and implemented a dual-source LED control circuit using BJTs and a Zener voltage reference.

The system automatically switches between a simulated solar source and a battery supply depending on voltage level.

Used 2N5401 (PNP) and 2N2222A (NPN) transistors to create a voltage threshold-based switching mechanism with LED indication.

This project strengthened my understanding of transistor biasing, voltage reference design, and practical analog electronics.

<img width="1090" height="1008" alt="image" src="https://github.com/user-attachments/assets/42a1fa03-e9ab-4d61-a0c7-5fbefea17ab3" />

<img width="1090" height="1046" alt="image" src="https://github.com/user-attachments/assets/9b6ac8b9-0626-45f1-82e3-a6adba6e68f2" />

<img width="965" height="687" alt="image" src="https://github.com/user-attachments/assets/01f12187-d037-4c50-8693-c0919ec3ef2b" />

<img width="1090" height="793" alt="image" src="https://github.com/user-attachments/assets/bd29cfd8-e039-4903-ad9d-42b0c62ca50c" />

<img width="578" height="1027" alt="image" src="https://github.com/user-attachments/assets/597097ce-30fa-4374-bab7-4c2b8fda8e9f" />

<img width="578" height="1027" alt="image" src="https://github.com/user-attachments/assets/b225a555-adcb-481a-bb06-f7bb1dabb8c4" />

Day Mode (High Voltage – Above ~7V)
•	When the left source voltage increases (simulating strong sunlight),
•	The Zener diode (1N759 – 12V) creates a voltage reference.
•	The PNP transistor (2N5401) turns ON.
•	The red LED string (D2–D6) lights up.
•	The right-side transistor stage remains OFF.
•	Blue LEDs are OFF.
•	This simulates daytime operation.
Night Mode (Low Voltage – Below ~7V)
•	When the left source voltage drops (simulating sunset),
•	The Zener no longer maintains conduction.
•	The PNP transistor turns OFF.
•	The control voltage through D7 and R2 activates the NPN transistor (2N2222A).
•	The blue LED string (D8–D10) starts lighting.
•	As voltage decreases further, brightness increases gradually.
•	This simulates automatic night lighting powered by a battery (8V source on the right).

What I Learned From This Project
•	How to use a Zener diode as a voltage reference
•	Using diodes for isolation and signal steering
•	Voltage threshold detection and automatic switching

Key Components Used
•	PNP Transistor: 2N5401
•	NPN Transistor: 2N2222A
•	Zener Diode: 1N759 (12V)
•	Standard Silicon Diodes
•	Series LED arrays
•	Current limiting resistors
•	Dual DC sources (Solar simulation + Battery)

 Real-World Applications
•	Solar garden lighting
•	Automatic street lighting
•	Battery backup systems
•	Voltage threshold indicators
•	Renewable energy switching systems


