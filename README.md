````markdown
# LTspice Tutorial Work

A collection of LTspice simulation files, notes, and small circuit exercises completed while learning circuit simulation.

This repository is not meant to be a polished research project or a production hardware design library. It is a learning archive: a place to document my progress with LTspice, basic circuit analysis, analog behavior, and simulation workflows.

## Purpose

I am using this repository to build practical comfort with circuit simulation as part of my broader electrical engineering development. My long-term interests sit around embedded systems, biomedical sensing, signal processing, and hardware-aware machine learning, so understanding circuits at the simulation level is an important foundation.

The goal is to practice:

- building circuits in LTspice
- running transient, AC, and DC simulations
- interpreting voltage and current waveforms
- understanding passive and active circuit behavior
- debugging simulation errors


## Topics Covered

This repository may include tutorial circuits involving:

* Ohm’s law and resistive networks
* voltage dividers
* RC charging and discharging
* RL and RLC transient response
* diode I-V behavior
* half-wave and full-wave rectifiers
* Zener diode regulation
* BJT switching and amplification
* MOSFET switching
* op-amp gain circuits
* active and passive filters
* AC sweep analysis
* transient simulation
* basic noise and signal-conditioning concepts

## Why LTspice?

LTspice is useful because it lets me test circuit behavior before physically building anything. It also helps connect classroom circuit theory to real waveforms, component behavior, and design tradeoffs.

For someone interested in embedded sensing and biomedical signals, this matters because the quality of a signal is not only determined by the algorithm. It is also shaped by the sensor, analog front end, filtering, amplification, noise, and power constraints.

## File Types

Typical LTspice files include:

```text
.asc   LTspice schematic file
.raw   simulation output file
.log   simulation log file
.plt   plot settings file
.lib   component/library file
.sub   subcircuit model file
```

I may avoid committing large `.raw` files unless they are necessary, since they can make the repository unnecessarily large.

## How to Open the Simulations

1. Install LTspice.
2. Clone this repository.
3. Open any `.asc` file in LTspice.
4. Click **Run** to simulate the circuit.
5. Probe nodes and components to view voltages and currents.

## Connection to My Broader Work

This repository supports my broader interest in embedded and biomedical systems. Projects involving physiological signals, such as ECG or PPG, depend heavily on signal acquisition quality before any machine learning model is applied.

Learning LTspice helps me better understand:

* analog signal conditioning
* filtering before digitization
* sensor interface circuits
* noise and distortion
* hardware constraints behind embedded ML systems

## Status

Ongoing learning repository.

Most files here are tutorial-based and exploratory. The purpose is to build fluency, not to present final designs.

## Future Additions

Possible future additions include:

* PPG analog front-end simulation
* ECG filtering examples
* op-amp based signal conditioning
* photodiode sensor circuit examples
* active band-pass filters
* comparator circuits
* power supply and regulation simulations
* notes connecting simulation behavior to embedded sensing applications

## Disclaimer

These circuits are for learning and simulation practice. They should not be used directly in safety-critical, medical, or production hardware without proper design review, validation, and testing.

```
```
