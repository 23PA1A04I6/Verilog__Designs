The Even‑Odd FSM is a digital sequential circuit designed to check whether the number of 1’s in a serial binary input stream is even or odd.
It’s a classic example of a finite state machine (FSM) often used in:

1.Serial parity checking
2.Simple error detection
3.Teaching FSM design concepts

This repository contains:
1.SystemVerilog/Verilog design of the FSM
2.Testbench to verify its functionality
3.Instructions to simulate and observe waveforms

 How It Works
The FSM starts in the Even state.
On every input bit:

1.If the bit is 1: it toggles the state (Even → Odd, Odd → Even).
2.If the bit is 0: state remains unchanged.

Output: usually indicates current parity (1 = Odd, 0 = Even) or flags parity errors.



