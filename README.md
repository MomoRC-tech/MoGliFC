# MoGliFC – flight controller and generic CAN-FD interface
powered by

<img src="/documentation/images/MOMORC-logo.jfif" width="60"> <img src="/documentation/images/gliwa-logo.svg" width="90"> <img src="/documentation/images/t1_timing.svg" width="60">

# Overview
MoGliFC is an STM32H743-based flight controller for quadcopters ('drones') as well as aircraft with wings.
Winged aircraft typically require servos to be connected to the flight controller while copters
typically have no such requireemnt. 
### Quadcopter and Wing
MoGliFC addresses both use-cases by providing a scored extension board for the servo connectors which 
also holds the BEC for the servos. When removed, the signal outputs remain on the flight controller and 
are available e.g. as GPIOs, UARTs or PWM outputs.
To enable a "Full Stack" solution for drones incorporating also a dedicated ESC daughter board, the design 
goal of MoGliFC is such that off-the-shelf ESC boards can be used. (outlook: custom ESC board for MoGliFC with advanced features)    

![PCB mechanical concept](documentation/images/PCB_concept.svg "PCB mechanical concept")

[edit online with draw.io](https://app.diagrams.net/#HMomoRC-tech%2FMoGliFC%2Fmain%2Fdocumentation%2Fimages%2FPCB_concept.svg)


### CAN-FD and Debug
The second extension option is a larger frame which allows the MoGliFC to be placed in a BOPLA ALUBOS housing
with the USB interface as well es the CAN/CAN-FD externally available turning the MogliFC into a general
purpose CAN-FD interface. This second extension also holds a SWD (single wire debug) interface for easy debugging.

![BOPLA ALUBOS housing](documentation/images/BOPLA_ALUBOS.png "BOPLA ALUBOS housing")

# Features

...

# Documentation
## Setup, installation
> ...

## Hardware

## Software

## Tools
> ...

# Contributing
Contributions are welcome and encouraged.  You can contribute in many ways:

* Documentation updates and corrections.
* How-To guides - received help?  help others!
* Bug fixes.
* New features.
* Telling us your ideas and suggestions.
* Buying your hardware from this <TBD>

Github issue tracker is a good place to search for existing issues or report a new bug/feature request:
Before creating new issues please check to see if there is an existing one!

# Developers

Main developers are:
* Peter, https://www.gliwa.com/
* Manuel, MomoRC

# Targets
- [x] set up github space
- [ ] set up development environment
- [ ] develop and prototype board
- [ ] develop inav branch
- [ ] final prototype testing
- [ ] ingest MoGliFC as supported INAV and Betaflight
- [ ] series production

