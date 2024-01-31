# rpi_cpu_fan_py
## Description
Implementing lgpio (Ubuntu) library for PWM fan control with systemd service.

### References
A lot of help putting this together via:
[PWM Regulated Fan Based on CPU Temperature for Raspberry Pi](https://www.instructables.com/PWM-Regulated-Fan-Based-on-CPU-Temperature-for-Ras/)
The resource above would have been sufficient if the implementation was with Rapsbian. Since Ubuntu 22 LTS is the Linux flavor of choice, the [lgpio](https://ubuntu.com/tutorials/gpio-on-raspberry-pi#1-overview) library was the most optimal choice. 

## Hardware Setup

### Supply List

- Raspberry Pi
- Transistor
- Diode
- 1Kohm Resistor
- 3.3v-5v Fan (two wire)

\* If you you need a setup for a Fan that has three wires -> PWM control built in, this library is *not* for you!

### Wiring Together

1. Step 1
.
.
5. Step 5

## Software Setup

### Image the Rasberry Pi

## Initializing Fan Service (code from this library)

### Running Installation Script


