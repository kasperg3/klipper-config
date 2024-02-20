# Klipper Configuration for Ender 3 with SKR v1.4 and TMC2209 Stepper Motor Drivers

This repository contains the Klipper configuration files for an Ender 3 3D printer running on an SKR v1.4 board with TMC2209 stepper motor drivers.

## Prerequisites

Before using this configuration, make sure you have the following:

- Ender 3 3D printer
- SKR v1.4 board
- TMC2209 stepper motor drivers

## Installation

To use this configuration, follow these steps:

1. Clone or download this repository.
2. Copy the `printer.cfg` file to your Klipper configuration directory.
3. Modify the configuration file according to your specific setup (e.g., bed size, thermistor type, etc.).
4. Save the changes and restart Klipper.

## Usage

Once you have installed the configuration, you can start using Klipper with your Ender 3. Make sure to adjust the printer settings in your slicer software to match the configuration (e.g., bed size, nozzle diameter, etc.).

## Pin reference

![Image](https://teamgloomy.github.io/images/skr_1.4.png)

## Calibration

Configuration checks:
- Endstops command: QUERY_ENDSTOPS
- <https://www.klipper3d.org/Config_checks.html>
- PID tuning
- extruder rotation distance: <https://www.klipper3d.org/Rotation_Distance.html#calibrating-rotation_distance-on-extruders>

Calibration measures:
- Calibrating z endstop <https://www.klipper3d.org/Manual_Level#calibrating-a-z-endstop>
- retraction calibration <https://teachingtechyt.github.io/calibration.html#retraction>
- Pressure advance <https://www.klipper3d.org/Pressure_Advance.html>
- Input shaper (Maybe?)

## G-Code references

* <https://www.klipper3d.org/G-Codes.html>

## Contributing

If you have any improvements or suggestions for this configuration, feel free to contribute by submitting a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
