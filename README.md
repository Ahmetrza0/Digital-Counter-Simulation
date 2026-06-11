# Digital-Counter-Simulation
# 4-Bit Digital Counter Circuit & Custom Display Logic

Counting Clock Display (2).png

A fully functional simulation of a digital counter designed to process clock pulses into a decimal output, featuring custom-engineered logic to adapt to component constraints.

## Technical Specs & Custom Logic
* Built using sequential logic, utilizing dual J-K Flip-Flops to handle the binary counting sequence.
* Utilized a 7-segment decoder to translate the binary flip-flop outputs into readable decimal values on a common cathode display.
* **Custom Logic Integration:** Due to inherent display limitations in the specific 7-segment decoder variation used, certain decimal values did not render correctly. To resolve this, I engineered a supplemental combinational logic circuit to override these hardware constraints and ensure an accurate display.

Recording 2026-06-11 221048.mp4

## Components Used
* 2x Dual J-K Flip-Flops
* 1x 7-Segment Decoder
* 1x Cathode 7-Segment Display
* Logic Gates: Dual 4-Input NAND, Quad AND, Quad OR
* 1 Hz Square Wave Function Generator
