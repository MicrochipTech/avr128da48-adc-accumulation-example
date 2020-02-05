# AVR128DA48 ADC Acumulation Example

This repository provides an Atmel Studio solution with a bare metal code example for ADC accumulation. 

In the main loop, the program reads the value of the AIN3 analog channel (PD3 pin).

## Configurations

PD3 pin - Configured as analog input (AIN3)

ADC0 - Configured in Free Run Mode to accumulate 64 samples

VREF - Reference voltage for ADC0 set to 2.048V

## Required Tools 

Software: ATMEL Studio and AVR-DA Device Packs

Hardware: AVR128DA48 Curiosity Nano

## Compatibility
The source code is compatible with the following devices: AVR128DA28, AVR128DA32, AVR128DA48, and AVR128DA64.
