# DC-to-DC-Converter
I designed an electronic circuit board with a 5V input that can provide a 12V output

🚀 5V to 12V DC-DC Boost Converter (MT3608)
A compact, highly efficient, and industrial-grade DC-DC Step-Up (Boost) Converter PCB designed to step up a standard 5V input to a stable 12V output. This project demonstrates the practical implementation of high-frequency closed-loop power electronics using the MT3608 IC.

📖 Project Overview
This project was born out of the need to bridge the gap between theoretical circuit analysis and practical, commercial-grade hardware design.

While fundamental boost converters can be simulated using discrete components (like external MOSFETs and signal generators in open-loop configurations), this board utilizes a highly integrated, closed-loop architecture. By utilizing the MT3608 IC, the design achieves high-frequency switching (1.2MHz), extreme compactness, and reliable voltage regulation regardless of load fluctuations.

✨ Key Features
Integrated Architecture: Replaces bulky discrete MOSFETs and external oscillators with a 6-pin SOT23 IC.

Closed-Loop Regulation: Features a precision feedback network to lock the output at exactly 12V.

High Frequency (1.2MHz): Allows the use of tiny, low-profile inductors (22µH) and ceramic capacitors, minimizing the PCB footprint.

Industrial Grade Components: Uses an SS34 Schottky diode for fast recovery and minimal forward voltage drop, maximizing efficiency.

Optimized PCB Layout: Designed with strict adherence to power electronics layout guidelines (minimized SW node area, thick power traces, and massive GND copper pours for thermal and EMI management).

⚙️ Hardware Specifications

Parameter                   Value
Input Voltage (Vin​),        5V DC
Output Voltage (Vout​),      12V DC
Controller IC,              MT3608 (SOT23-6)
Switching Frequency,        1.2 MHz
Inductor,                   22µH (SMD Power Inductor)
Diode,                      "SS34 (Schottky, 40V, 3A)"




Schematic The complete schematic designed in EasyEDA.

PCB Layout (2D)Optimized trace routing: Thick traces (25 mil) for high-current paths and a solid GND copper pour for thermal dissipation.

3D Render Final 3D visualization of the assembled board.

🛠️ Bill of Materials (BOM)

1x MT3608 Boost Converter IC (SOT23-6)

1x 22µH SMD Power Inductor

1x SS34 Schottky Diode

2x 22µF Ceramic Capacitors (Input & Output Filters)

1x 190k SMD Resistor (1% Tolerance)

1x 10k SMD Resistor (1% Tolerance)

2x 2-Pin Screw Terminal Blocks (5.08mm pitch)

👨‍💻 About the Author
Barış Erişen Electrical and Electronics Engineering Student at Istanbul Kultur University

I am passionate about circuit analysis, PCB design, and bringing theoretical electronics into the physical world. This project serves as a practical exploration of power electronics and compact layout design.

Feel free to explore the design files, use them in your own projects, or reach out if you have any questions!
