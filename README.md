# code-nema23-tb6600

[![Arduino](https://img.shields.io/badge/platform-Arduino-blue?logo=arduino)](https://www.arduino.cc/)
[![Stepper](https://img.shields.io/badge/device-Stepper%20Motor-orange)](https://en.wikipedia.org/wiki/Stepper_motor)
[![Driver](https://img.shields.io/badge/driver-TB6600-red)](https://www.toshiba.com/tic/datafiles/docs/TB6600HQ.pdf)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Sample codes and documentation for controlling a NEMA23 stepper motor with a TB6600 driver using Arduino.

## Project Structure

```
code-nema23-tb6600/
├── code stepper nema 23 (Koordinat X dan Y)/
│   ├── 1600_pulse/1600_pulse.ino   # Example for 1600 pulses/rev (X/Y axis)
│   └── 200_pulse/200_pulse.ino     # Example for 200 pulses/rev (X/Y axis)
├── code stepper nema 23 (Koordinat Z)/
│   ├── 1600_pulse/1600_pulse.ino   # Example for 1600 pulses/rev (Z axis)
│   └── 200_pulse/200_pulse.ino     # Example for 200 pulses/rev (Z axis)
└── README.md
```

## Example Codes

### X and Y Axis
- `code stepper nema 23 (Koordinat X dan Y)/1600_pulse/1600_pulse.ino`  
	Runs 934 steps at 1600 pulses/rev, 400μs pulse width.
- `code stepper nema 23 (Koordinat X dan Y)/200_pulse/200_pulse.ino`  
	Runs 2548 steps at 200 pulses/rev, 400μs pulse width.

### Z Axis
- `code stepper nema 23 (Koordinat Z)/1600_pulse/1600_pulse.ino`  
	Runs 7473 steps at 1600 pulses/rev, 47μs pulse width.
- `code stepper nema 23 (Koordinat Z)/200_pulse/200_pulse.ino`  
	Runs 7473 steps at 200 pulses/rev, 47μs pulse width.

Each code prints the process duration to Serial Monitor.

## Features
- Example Arduino codes for NEMA23 + TB6600
- Wiring diagrams and tips
- Easy to use and modify

## Usage
1. Open the desired `.ino` file in Arduino IDE.
2. Adjust wiring according to your hardware and code comments.
3. Upload to your Arduino board.
4. Open Serial Monitor to view process duration.

## License
MIT

---
