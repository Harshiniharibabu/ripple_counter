4-BIT-RIPPLE-COUNTER
AIM:

To implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

4 Bit Ripple Counter

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

<img width="602" height="320" alt="image" src="https://github.com/user-attachments/assets/0a6466f0-c6e4-4d65-866d-65b0486739df" />


In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

<img width="356" height="271" alt="image" src="https://github.com/user-attachments/assets/90a60184-53a3-47ea-9cbe-34c73d98eb15" />




<img width="254" height="198" alt="image" src="https://github.com/user-attachments/assets/81497492-ef68-46bc-8010-f23731d0899c" />


Procedure

/* write all the steps invloved */

PROGRAM

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

Developed by:HARSHINI H

RegisterNumber: 25012984


RTL LOGIC FOR 4 Bit Ripple Counter

TIMING DIGRAMS FOR 4 Bit Ripple Counter

RESULTS
