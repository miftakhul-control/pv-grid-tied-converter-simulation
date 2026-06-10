# PV Grid-Tied Converter Simulation

## Objective

Develop a cascaded PV grid-connected converter in MATLAB/Simulink.

System architecture:

PV → Boost Converter → DC Bus → Single Phase Inverter → Grid

## Features

- Boost converter
- DC bus voltage regulation
- Grid synchronization PLL
- Current control loop
- Transient response analysis

## Current Status

- [x] Inverter model
- [x] PLL synchronization
- [x] DC bus control
- [ ] MPPT
- [ ] Anti-islanding

## Target Performance

- Stable synchronization
- Unity power factor
- THD < 5%

## Notes

This repository documents the development process, simulation results, design decisions, and lessons learned during implementation.