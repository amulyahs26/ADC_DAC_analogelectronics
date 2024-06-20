An operational amplifier is a DC-coupled electronic voltage amplifier with a differential input, a single-ended output,and an extremely high gain.
Electronic symbol of Op-Amp <img width="172" alt="image" src="https://github.com/amulyahs26/ADC_DAC_analogelectronics/assets/170850147/c54616a3-07d1-4512-b01c-5968c451304c">

Implementation of an Op-Amp using Cadence virtuoso software 

Schematic
<img width="690" alt="image" src="https://github.com/amulyahs26/ADC_DAC_analogelectronics/assets/170850147/b8df505d-cc1e-47f1-975d-ee969c60c856">

Testbench
<img width="346" alt="image" src="https://github.com/amulyahs26/ADC_DAC_analogelectronics/assets/170850147/1f1514e3-ca8c-4ba3-af43-c6d13c86b869">

Output waveform
<img width="741" alt="image" src="https://github.com/amulyahs26/ADC_DAC_analogelectronics/assets/170850147/fe4fafb4-ef7d-43cf-a3c4-f1f95b15d234">


Operational amplifiers (op-amps) are widely used in electronic circuits due to their versatility and performance. Two common configurations for op-amp amplifiers are the inverting and non-inverting amplifiers. 

1. Inverting Amplifier:
In an inverting amplifier configuration, the input signal is applied to the inverting input of the op-amp through a resistor 
𝑅in, while the non-inverting input is connected to ground. The feedback resistor Rf,  is connected between the output and the inverting input. This configuration provides an output that is 180 degrees out of phase with the input signal.


The voltage gain Av, of the inverting amplifier is given by the ratio of the feedback resistor to the input resistor:
Av=-Rf/Rin

The negative sign indicates that the output is inverted relative to the input.

Implementation of Inverting amplifier:

Schematic:

<img width="490" alt="image" src="https://github.com/amulyahs26/ADC_DAC_analogelectronics/assets/170850147/a5d279e6-cc1b-46a9-ab3f-52a84095aa2b">

Waveform:

<img width="737" alt="image" src="https://github.com/amulyahs26/ADC_DAC_analogelectronics/assets/170850147/15cda0e6-ede6-419a-89f0-bc2d025581af">

2.Non-Inverting Amplifier:

In a non-inverting amplifier configuration, the input signal is applied to the non-inverting input of the op-amp. The inverting input is connected to a voltage divider network formed by resistors R1 and Rf that are connected between the output and ground. This configuration provides an output that is in phase with the input signal.

Formula
The voltage gain Av,
  of the non-inverting amplifier is given by:
  Av= 1+(Rf/R1)
  
This formula shows that the output is amplified but not inverted relative to the input.

Implementation of Non-Inverting amplifier:


Schematic :

<img width="469" alt="image" src="https://github.com/amulyahs26/ADC_DAC_analogelectronics/assets/170850147/b1aff290-4f2e-4d3e-828d-12054167f82b">


Waveform:

<img width="725" alt="image" src="https://github.com/amulyahs26/ADC_DAC_analogelectronics/assets/170850147/58f50c79-5c67-4cf4-aeca-50bc8dfd17c2">



