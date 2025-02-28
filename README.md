# 3-8-Decoder
This repository contains a 3-to-8 Decoder implemented in Verilog HDL. A decoder is a combinational circuit that takes a 3-bit binary input and activates one of the 8 output lines based on the input value. The circuit includes an enable signal to control its functionality.
# Features
✅ Implements a 3-to-8 line decoder using case statements
✅ Enable signal to control output activation
✅ Testbench included for simulation
✅ Designed for Icarus Verilog (IVerilog) simulation
# Output
![image](https://github.com/user-attachments/assets/fcb5ba8d-5ceb-4ccb-8602-a1c19be07d85)
# How It Works
When enable = 1, the decoder maps the 3-bit input (in) to one of the 8 output lines (out).
When enable = 0, all outputs remain inactive (0).
