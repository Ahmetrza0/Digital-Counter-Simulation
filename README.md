# Digital Counter Circuit

<img width="1491" height="645" alt="Counting Clock Display (2)" src="https://github.com/user-attachments/assets/5fcad676-1a2a-43ba-a7e1-dc47e6c611f7" />
<br>
<br>

A fully functional simulation of a digital counter designed to process clock pulses into a decimal output, featuring custom-engineered logic to adapt to component constraints. (See the simulation below)

Built using sequential logic, utilizing dual J-K Flip-Flops to handle the binary counting sequence.
Utilized a 7-segment decoder to translate the binary flip-flop outputs into readable decimal values on a common cathode display.

Due to inherent display limitations in the specific 7-segment decoder variation used, certain decimal values did not render correctly. To resolve this, I engineered a supplemental combinational logic circuit (with Quad AND & Quad OR gates) to override these hardware constraints and ensure an accurate display.
<br>
<br>

https://github.com/user-attachments/assets/e066a226-f1fa-454a-9193-2f9c2b556e99



## Components Used
* 2x Dual J-K Flip-Flops
* 1x 7-Segment Decoder
* 1x Cathode 7-Segment Display
* 1x Dual 4-Input NAND gate
* 1x Quad AND gate
* 1x Quad OR gate
* 1 Hz Square Wave Function Generator
