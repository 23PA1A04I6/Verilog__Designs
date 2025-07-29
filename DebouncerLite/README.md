The Debouncer Lite is a simple digital circuit designed to filter out spurious transitions (bouncing) from mechanical switches or buttons.
It provides a clean, single-pulse output whenever the input signal changes state — making it ideal for:

1.FPGA or ASIC designs
2.Digital counters and finite state machines (FSMs)
3.Keypad and button interfaces

This repository includes:

1.RTL design files (SystemVerilog / Verilog)
2.Testbench files
3.Simulation instructions to run and view waveforms

How it works:
Mechanical switches don't produce perfect clean transitions:
When pressed or released, the signal may "bounce" and toggle multiple times quickly.

The Debouncer Lite:
1.Samples the noisy input signal
2.Waits for a configurable number of clock cycles to confirm signal stability
3.Outputs a clean, single edge or level after the signal is stable
