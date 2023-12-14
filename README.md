# DynoHAT
DynoHAT is a HAT PCB for the Raspberry Pi. It aims to combine three PCBs into one single HAT.

![DynoHAT Top](https://github.com/DiamondFire11/DynoHAT/blob/main/docs/render/DynoHAT%20Top.PNG?raw=true)
![DynoHAT Bottom](https://github.com/DiamondFire11/DynoHAT/blob/main/docs/render/DynoHAT%20Bottom.PNG?raw=true)

## Integrated features
- Robotis U2D2 Power Hub board
- 12V -> 5V / 3A buck converter for Raspberry Pi power
- +12V output for miscellaneous functionality, controllable via GPIO output on the Raspberry Pi

While all the circuits have been rated for 12V, the recommended battery voltage is 11.1V by Robotis (3S Li-Po).

If you would prefer full GPIO passthrough please use a stacking header like the one provided below:
https://www.adafruit.com/product/1979?gad_source=1&gclid=Cj0KCQiAyeWrBhDDARIsAGP1mWQjpbdQu-CfnqCebVS8EbuVlxs6_i75mS9qwJ7w5Ec_8nMz-CcyH1kaAna9EALw_wcB

# Planned Features
## To be added (v1.1)
- USB-PD charging for LiPo Battery
- Battery Charger and Management IC
