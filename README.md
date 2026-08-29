# PADP — Portable Automotive Development Platform

PADP is a portable, modular development and test platform for automotive embedded systems. It is intended for developing, integrating, observing, and validating embedded nodes using real microcontrollers, physical signals, and CAN communication.

## Current Development

The first development stage is **PADP-NET v0.1**, which will provide a basic CAN communication and logging platform.

The initial system consists of:

* an STM32 NUCLEO-G474RE used as the PADP-NET Gateway;
* a second STM32 NUCLEO-G474RE used as a Reference Node;
* SN65HVD230 CAN transceivers;
* USB communication between the Gateway and a host computer;
* Classical CAN communication between the two embedded nodes.

The current milestone is the initial bring-up of the Gateway board, starting with a minimal LED blink firmware.

## Project Status

Early development / hardware bring-up.
