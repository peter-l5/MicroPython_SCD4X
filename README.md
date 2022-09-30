# MicroPython_SCD4X
MicroPython driver for Sensirion SCD40 and SCD41 with I2C interface. Derived from the Adafruit CircuitPython version.

## Usage
A usage example can be found in the code. 

## Implementation Notes
The `scd4x.py` module provides a helper class `SCD4X()` that enables I2C interaction with a SCD40 or SCD41 sensor.

Details of the adafruit breakout board for the sensor and the methods provided by the `SCD4X()` class.

The SCD41 sensor provides additional low power/ lower sampling rate commands that are not implemented in this driver. See the Sensirion datasheet for the sensors for details.
