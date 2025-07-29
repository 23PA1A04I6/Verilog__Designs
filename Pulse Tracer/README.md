A Pulse Tracer is a small digital circuit that:
  1.Detects a short input pulse (which may be as narrow as one clock cycle, or even asynchronous).
  2.Converts it into a pulse or signal that lasts longer (usually a fixed number of clock cycles).
  3.This stretched output makes it easy to observe on waveform viewers or capture with slower logic.

How it works (common design):
1.Monitor pulse_in on every clock cycle.
2.When a pulse is detected, start a counter.
3.While the counter is > 0, keep pulse_out high.
4.After the counter expires, pulse_out goes back to 0.
5.This stretches the original pulse to N clock cycles

