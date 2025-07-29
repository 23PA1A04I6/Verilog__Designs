The Light Chaser is a digital circuit that sequentially lights up a series of LEDs in a pattern that creates a “running” or “chasing” light effect.
It’s often used in:

1.Decorative lighting
2.Introductory FPGA or Verilog projects
3.Car headlight animations (like Knight Rider / KITT light
4.Embedded and hobby electronics

This repository includes:

1.Verilog / SystemVerilog design files
2.Testbench files to verify functionality
3.Instructions to simulate and view waveforms

How It Works
1.A shift register or FSM sequentially activates one LED at a time.
2.After reaching the last LED, it either loops back or reverses direction.
3.Clock signal controls the speed of the chase.
4.Reset signal initializes the LEDs to a known state.



