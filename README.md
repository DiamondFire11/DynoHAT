# DynoHAT
DynoHAT is a HAT PCB for the Raspberry Pi. It aims to combine three PCBs into one single HAT.

![DynoHAT Top](https://github.com/DiamondFire11/DynoHAT/blob/main/docs/render/DynoHAT%20Top.PNG?raw=true)
![DynoHAT Bottom](https://github.com/DiamondFire11/DynoHAT/blob/main/docs/render/DynoHAT%20Bottom.PNG?raw=true)

## Integrated features
- Robotis U2D2 Power Hub board
- 12V -> 5V / 3A buck converter for Raspberry Pi power
- +12V output for miscellaneous functionality, controllable via GPIO output on the Raspberry Pi

While all the circuits have been rated for 12V, the recommended battery voltage is 11.1V by Robotis is (3S Li-Po).


# Planned Features
## To be added (v1.1)
- Full HAT passthrough
- OVP for protection against battery arrays over 12V

## Planned for future
- USB-PD charging for LiPo Battery
- Battery Charger and Management IC
