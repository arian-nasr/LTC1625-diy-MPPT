# LTC1625-diy-MPPT
Hacking a LTC1625 based buck-boost converter to enable maximum power point tracking for PV installation

Uses perturb & observe algorithm to maximize the voltage differential across the module's onboard shunt resistor, thus maximizing the power from the PV cell to the load (assuming load keeps voltage fairly constant i.e. a battery)

Control of module is achieved through voltage injection on LT1625's feedback pin using ESP32 onboard DAC. Very low external component count.

<img width="4032" height="3024" alt="IMG_3083" src="https://github.com/user-attachments/assets/9ffe6dc3-0691-433e-ab26-f34207abbfd5" />
