# Op-Amp PID Controller Simulation

## Project Overview
This project involves building a Proportional-Integral-Derivative (PID) Controller circuit using Operational Amplifier (Op-Amp) ICs in [Tinkercad](https://www.tinkercad.com/). The goal is to process specific input waveforms and document the signal modifications through each stage of the PID controller.

## Reference Materials
Please review the following documentation and tutorials on PID controllers and Operational Amplifiers:
*   [PID Controller Basics](https://www.youtube.com/watch?v=tFVAaUcOm4I)
*   [Op-Amp Basics](https://www.youtube.com/watch?v=idJEMYhrIfs)

## Hardware Requirements
*   Op-Amp ICs
*   Function Generator (for input waveforms)
*   Oscilloscope (for reading output waveforms)
*   Assorted Resistors and Capacitors (calculated to achieve P, I, and D behaviors)

## Testing Parameters
You must test the circuit using the function generator with the following three input configurations:

1.  **Sine Wave Test:**
    *   Frequency: 100 Hz
    *   Amplitude: 2.0 V
    *   DC Offset: 0.0 V
    *   Function Type: Sine
2.  **Square Wave Test:**
    *   Frequency: 50 Hz
    *   Amplitude: 2.5 V
    *   DC Offset: 0.0 V
    *   Function Type: Square
3.  **Sawtooth/Triangle Wave Test:**
    *   Frequency: 100 Hz
    *   Amplitude: 2.0 V
    *   DC Offset: 0.0 V
    *   Function Type: Triangle

## Deliverables
For each of the three test inputs, you must measure the waveform on the oscilloscope after it passes through:
1.  The Proportional (P) stage individually.
2.  The Integral (I) stage individually.
3.  The Derivative (D) stage individually.
4.  The final, combined PID output.

## Submission:
* Compile the oscilloscope screenshots into a single Word Document. Ensure every image is properly labeled with the input type (Sine, Square, Triangle) and the corresponding circuit stage (P, I, D, or combined PID, also add in your tinkercad link.
* Follow the submission guidelines on the main repository.
