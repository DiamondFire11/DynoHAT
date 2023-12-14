# DynoHAT
DynoHAT is a HAT PCB for the Raspberry Pi 3 and 4. It aims to combine three PCBs into one single HAT.

![DynoHAT Top](https://github.com/DiamondFire11/DynoHAT/blob/main/docs/render/DynoHAT%20Top.PNG?raw=true)
![DynoHAT Bottom](https://github.com/DiamondFire11/DynoHAT/blob/main/docs/render/DynoHAT%20Bottom.PNG?raw=true)

## Integrated features
- Robotis U2D2 Power Hub board
- 12V -> 5V / 3A buck converter for Raspberry Pi power
- +12V output for miscellaneous functionality, controllable via GPIO output on the Raspberry Pi

If you would prefer full GPIO passthrough please use a stacking header like this one from Adafruit:
[2x20 Female Stacking Header](https://www.adafruit.com/product/1979)


##### Do not use a battery that exceeds 12V as it will damage the board.
While all the circuits have been rated for 12V, the recommended battery voltage is 11.1V by Robotis (3S Li-Po).

## Planned Features (v1.1)
- Redesign the current power switch solution
- I2C version to support more than one switched 11.1V output.
