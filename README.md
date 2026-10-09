# FPGA-Lab-5
ECE 128 Lab 5 – Latches, Flip-Flops, Counters, and Clock Divider

Project Description

This project implements the basic sequential logic building blocks in Verilog: an SR latch and SR flip-flop, a posedge-triggered D flip-flop with synchronous and asynchronous reset, a posedge-triggered T flip-flop, a 3-bit counter built from T flip-flops, and a clock divider that produces a 25 MHz output clock. Each design has its own testbench, and the simulated waveforms are used to verify correct behavior, including the difference between level-sensitive and edge-triggered storage, the timing difference between synchronous and asynchronous reset, toggle behavior, binary counting from 0 to 7 with wraparound, and the clock division ratio.

Simulation

1. Open the project in Vivado.
2. Add the desired module (SR latch/flip-flop, D flip-flop, T flip-flop, 3-bit counter, or clock divider) as a design source.
3. Add the corresponding testbench as a simulation source.
4. Set the testbench as the simulation top module.
5. Run Behavioral Simulation.
6. Verify from the waveform that the outputs match the expected behavior: set, reset, and hold for the SR designs; D following the input on each rising edge and the reset timing for the D flip-flop; holding and toggling for the T flip-flop; counting from 0 to 7 and wrapping for the 3-bit counter; and one output clock period for every four input clock periods for the clock divider.
