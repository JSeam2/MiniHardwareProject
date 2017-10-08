# Mini Hardware Project 
### 50.002 Computational Structure course at SUTD

1. Build on Mojo FPGA dev board.
2. Uses Lucid, a Hardware Description Language (HDL)

The goal of this project is a simple experiment to test the functionalities of an FPGA, using it to control a one-bit full adder. 
Using various counters of different periods (28, 29, 30 bits) we generate signals from the FPGA to be fed to the strip board.
Thus, we cycle through the 2^3 = 8 possible cases: 000, 001, 010, 011, 100, 100, 101, 111.
The the signal from the fpga is visualized by the lit LED strips found on the IO Shield. 
