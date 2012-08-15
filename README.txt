DESCRIPTION
===========

F4Dev is a small (5x5 cm) development board for the STM32F4 microcontrollers,
it contains a wide gamut of sensors and communications interfaces:

  + 10 DoF Inertial Measurement Unit (IMU)
    - Accelerometer (3 DoF)
    - Magnetometer (3 DoF)
    - Gyroscope (3 DoF)
    - Barometer (1 DoF)

  + Omnidirectional MEMS microphone

  + UART <-> BlueTooth

  + UART <-> USB

  + LED indicators

  + 6 pin JTAG connector (VDD, GND, TDI, TDO, TMS, TCK)

  + Pin breakout

For an overview of the connections see connection.ods

DEPENDENCIES
============

This work uses the latest official KiCad library available at:

https://code.launchpad.net/~KiCad-lib-committers/KiCad/library

This work also uses the footprint from libKiCad available at:

https://github.com/JorgeAparicio/libKiCad

These libraries and this work must be in the same path, as shown below:

  <someFolder>
    F4Dev
      F4Dev.pro
      F4Dev.sch
      F4Dev.brd
      ...
    libKiCad
      3d
      footprint
      ...
    library (Official KiCad library)
      library
      module
      ...

LICENSE
=======

This work is licensed under the following license:

Creative Commons Attribution-ShareAlike 3.0 Unported (CC-BY-SA 3.0)

For more information see LICENSE.txt

