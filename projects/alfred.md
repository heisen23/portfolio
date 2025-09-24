---
layout: project
type: project
image: img/alfred/alfred_core.png
title: "ALFRED"
date:
published: true
labels:
  - LFR
  - OpenMC
summary: "Neutronic analysis of the ALFRED reactore core."
---

<div align="center">
  <img src="../img/alfred/alfred_core.png" width="75%">
</div>
## Overview

For my undergraduate thesis i wanted to study Lead Cooled Fast Reactors and chose the [ALFRED](https://www.sciencedirect.com/science/article/abs/pii/S0029549314004361) model to condcuct a neutronics analysis. ALFRED is a prototype for next-generation Lead-Cooled Fast Reactors (LFRs). It aims to demonstrate enhanced safety and efficiency for nuclear energy.

In this project i designed the ALFRED core using [OpenMC](https://docs.openmc.org/en/stable/) and conducted analysis on several parameters such as criticality (keff), neutron flux, power distribution, fuel burnup, actinide production and coolant activation. This work provided insights into the reactor’s performance and validated its design. 

## Snapshots:

<div style="display: flex; justify-content: space-around; flex-wrap: wrap;">
  <div style="text-align: center; width: 45%;">
    <img src="../img/alfred/alfred_rad_nflux.png" alt="Radial neutron flux distribution in ALFRED" width="100%">
    <p><strong>Radial Neutron Flux</strong></p>
  </div>
  <div style="text-align: center; width: 45%;">
    <img src="../img/alfred/alfred_ax_nflux.png" alt="Axial neutron flux distribution in ALFRED" width="100%">
    <p><strong>Axial Neutron Flux</strong></p>
  </div>
  <div style="text-align: center; width: 45%;">
    <img src="../img/alfred/alfred_th_nflux.png" alt="Thermal neutron flux in ALFRED" width="100%">
    <p><strong>Thermal Neutron Flux</strong>: Observed around the reflector region.</p>
  </div>
  <div style="text-align: center; width: 45%;">
    <img src="../img/alfred/alfred_power.png" alt="Power distribution in ALFRED" width="100%">
    <p><strong>Power Distribution</strong></p>
  </div>
</div>

## Code and Resources

Explore some of the detailed codebase and analysis on [GitHub](https://github.com/SShuddho/neutronics-alfred).
