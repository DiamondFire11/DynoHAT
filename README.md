# DynoHAT
DynoHAT is a HAT PCB for the Raspberry Pi 3 and 4. It aims to combine three PCBs into one single HAT.

![DynoHAT Bottom](https://github.com/DiamondFire11/DynoHAT/blob/main/docs/render/DynoHAT%20Top.PNG?raw=true)
![DynoHAT Bottom](https://github.com/DiamondFire11/DynoHAT/blob/main/docs/render/DynoHAT%20Bottom.PNG?raw=true)
## CAN-FD IS A PLANNED FEATURE COMING SOON
While the badging for CAN-FD is on the board, it is not yet implemented and still being tested. I placed the watermark so I do not forget to add it.

## Integrated features
- Robotis U2D2 Power Hub board
- 12V -> 5V / 3A buck converter for Raspberry Pi power
- +12V output for miscellaneous functionality, controllable via GPIO output on the Raspberry Pi
- Qwiic by SparkFun

If you would prefer full GPIO passthrough please use a stacking header like this one from Adafruit:
[2x20 Female Stacking Header](https://www.adafruit.com/product/1979)


##### Do not use a battery that exceeds 12V as it will damage the board.
While all the circuits have been rated for 12V, the recommended battery voltage is 11.1V by Robotis (3S Li-Po).

## Version History

#### V1.0 - Initial Release
Added:
  - Integrated power features of U2D2 Power Hub board while increasing the maximum current that can be supplied to Dynamixel servos
  - +11.1V supply for powering external loads (ON-OFF) switchable via Raspberry Pi
  - +11.1V to +5V 4A supply for backpowering a Raspberry Pi via GPIO

#### V1.1 - SparkFun Qwiic Integration
Added:
  - Broke out I2C bus from Raspberry Pi for integration with Qwiic
      - Qwiic is powered via its own 3.3V LDO capable of up to 300mA of current
  - 2 Qwiic connectors for daisy-chaining

## Planned for Future Release
- CAN-FD and CAN-FD driver
- Li-Ion/Li-PO over voltage protection (tentative)
