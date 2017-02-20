# [Carloop](https://www.carloop.io)
## OBD-II CAN adapter for the Particle Photon/Electron and RedBear Duo

<img src="images/Photo2_750.png" width="355">

The WiFi-capable Particle Photon or better yet the cellular Particle
Electron can turn your car into a cloud connected device!

Carloop's PCB connects your car's CAN bus network to the Photon, Electron and Duo. It also provides battery power and a GPS to track location.

# Particle Photon Example

![Carloop Photon Pinout](images/Carloop_Photon_Pinout_small.png)

# [Check out the Carloop Store](https://store.carloop.io/)


## Features

* High-speed CAN transceiver [adapted from the OpenXC project](https://github.com/openxc/reference-vi/blob/gh-pages/electrical/design/can.mkd)
* Get power from the OBD-II port using [a robust circuit adapted from the OpenXC project](https://github.com/openxc/reference-vi/blob/gh-pages/electrical/design/power.mkd)
* GPS connector
* Stacked components for a more compact development kit than a
traditional 90-degrees PCB mount OBD-II connector.
* Powered by the Particle platform!

## Images

PCB

<img src="images/Photo1_750.png" width="355">

Assembled adapter

* [With Photon](images/detail-photon.jpg)
* [With Electron](images/detail-electron.jpg)
* [Front view](images/front.png)
* [Side view](images/detail-side.jpg)
* [Back view](images/back.png)
* [Angle view](images/angle.png)

## Hardware

There are a few hardware variants

Here are the PCB design files for the Revision 2.3, the one sold on the [Carloop store](https://store.carloop.io)

* [Schematic (PDF)](Carloop.v2/Carloop-v2.3.pdf)
  [(Eagle)](Carloop.v2/Carloop-v2.3.sch)
* [Layout](Carloop.v2/Carloop-v2.3-pcb-combined.pdf)
  [(top)](Carloop.v2/Carloop-v2.3-layout-top.pdf)
  [(bottom)](Carloop.v2/Carloop-v2.3-layout-bottom.pdf)
  [(Eagle)](Carloop.v2/Carloop-v2.3.brd)
* [Bill of materials](Carloop.v2/Carloop-v2.3_BOM.csv)
* [OSH Park order page](https://oshpark.com/shared_projects/ir8I9vT6)

Here are the PCB design files for the extended version that fits a Particle Electron. It is a prototype.

* [Schematic (Eagle)](CarloopXL.v3/Carloop-v3.1.sch)
* [Layout (Eagle)](CarloopXL.v3/Carloop-v3.1.brd)
* [Bill of materials](CarloopXL.v3/Carloop-v3.1_BOM.csv)

Here are the PCB design files for a "retro" variant with a K-Line transceiver contributed by [Alan R](https://github.com/cyclin-al).

* [Schematic (Eagle)](CarloopRetro.v0/CarloopRetro-v0.1.sch)
* [Layout (Eagle)](CarloopRetro.v0/CarloopRetro-v0.1.brd)

## Software

The [Carloop Library](https://github.com/carloop/carloop-library) is available on Particle's Web IDE.  You will need to flash a [Particle Photon](https://store.carloop.io/products/particle-photon), [Particle Electron](https://store.carloop.io/products/particle-electron) or [RedBear Duo](https://store.carloop.io/products/redbear-duo) with an example app which can ben found in Carloop Library.   See 'Getting Started' instructions here: [https://community.carloop.io/t/getting-started-with-carloop/23](https://community.carloop.io/t/getting-started-with-carloop/23)

## License

Copyright 2016 1000 Tools, Inc.

Licensed under the GPL v3
