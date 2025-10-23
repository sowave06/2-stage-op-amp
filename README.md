# Design-and-Layout-Implementation-of-Two-stage-Opamp-using-180nm-Technology
Design and Layout implementation of a high-performance two-stage Operational Amplifier (OPAMP) using 180nm semiconductor technology. Achieved required gain, bandwidth, and power efficiency through simulation and characterization.

# Circuit Diagram
![image](https://github.com/HardikJainGit/2-Stage-OTA-Design/assets/133627261/fd03d133-7bf2-4968-94f2-d9ede6ea3de4)

# Design-Specification
Vdd = 1.8V <br>
DC Gain = 60dB <br>
GBW = 5MHz <br>
PM >=60 degree <br>
Slew rate = 10V/u sec <br>
ICMR(+) = 1.6V <br>
ICMR(-) = 0.8V <br>
CL = 10pF <br>
Cc >= 3pF <br>
Power Dissipation = 170 uW <br>

# Design Process 
(W/L) ratio of M3,M4 is found using ICMR(+) <br> 
(W/L) ratio of M1,M2 is found using GBW <br>
I5 is found using Slew Rate <br>
(W/L) ratio of M5 is found using ICMR(-) <br>
(W/L) ratio of M6 is found from location of zero<br>

# Technology Used
LTspice (tsmc018.lib)
