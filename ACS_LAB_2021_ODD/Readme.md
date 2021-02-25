# Introduction to optical communication systems simulation

## Optsim software package by Rsoft Corporation

**(www.rsoftdesign.com)**

## Design
- Single channel point-to-point optical communication link
- Single channel passive optical network (PON)
- Wavelength division multiplexed (WDM) point-to-point optical communication link

# Overview
## Design of optical communication systems involves optimizing a large number of parameters

- transmitters, optical fibers, amplifiers, receivers
- optical multiplexers, optical demultiplexers, optical filters, optical cross connects, optical add drop multiplexers
## Computer-aided design techniques if used appropriately
- optimize entire system
- provide optimum values of system parameters
- Design goals are met with minimal time and cost
## Commercially available design software packages
- Optiwave, VPITransmission Maker, Optisim

**Since mid-90’s, computer simulations have been used to realistically model optical communication systems**

# Optical Simulation Software

## Used to design and optimize
- DWDM and CWDM amplified systems
- FTTX/PON systems
- OTDM systems
- CATV digital/analog systems
- optical LANs
- ultra long-haul terrestrial and submarine systems
- free space optics (FSO) systems
### Optsim uses block-orientated simulation methodology:

- optical communication system is represented by an interconnected set blocks
- Each block models a component or subsystem 
- Each block model is presented graphically as an icon, has own set of parameters which can be modified by user Signal data is passed between block models during simulation run

### Each block model is simulated independently of the others
based only on signals passed into it and its own set of
parameters

### Each block model is presented graphically as an icon, has
own set of parameters which can be modified by user

### Extensive model library
- optical sources, optical modulators
- electrical and optical amplifiers
- fibers
- optical receivers
- optical cross connects, OADM
- data display tools (spectra, eye diagrams, BER)


# SIMULATION APPROACHES

- Optsim supports two simulation engines
- Block mode simulation engine: signal data is represented as one block of data and is passed between block to block
- Sample mode simulation engine: signal data is represented as single samples that is passed between block to block

# SIMULATION METHODS

**Four steps to setting up a simulation of a communication systems
- Create Optsim project and set simulation parameters
- Draw the schematic diagram, set parameter values of block models
- Run simulation
- View results with data display tools

## LAB Experiment Rules

- This is team assignment (2 persons) and the deadline is the day before next lab session
# EXPERIMENT - 1 [DATED : 04/02/2021]

- To familiarize with RSOFT-OPTISIM simulation tool

# EXPERIMENT - 2 [DATED : 11/02/2021]

### Single Channel Point-Point Link

![alt text](https://github.com/NANOPHOTONIC-RESEARCH-SOCIETY-AT-PEC/CAD-SIMULATIONS-OPTICS-LAB/blob/master/ACS_LAB_2021_ODD/RAW/POINT%20TO%20POINT%20LINK.PNG)

- Observe the optical spectrum at output of transmitter
- Measure received optical power
- Observe the electrical signals before and after transmission
- Observe the electrical eye diagrams before and after transmission

# EXPERIMENT - 3 [DATED : 18/02/2021]

### WDM Point-to-point Link

![alt text](https://github.com/NANOPHOTONIC-RESEARCH-SOCIETY-AT-PEC/CAD-SIMULATIONS-OPTICS-LAB/blob/master/ACS_LAB_2021_ODD/RAW/Capture.PNG)

- Observe the optical spectrum at output of transmitter
- Measure received optical power
- Observe the electrical signals before and after transmission
- Observe the electrical eye diagrams before and after transmission

# EXPERIMENT - 4 [DATED : 25/02/2021]
**Design a 4 channel WDM system with the following specifications:**
-Channel spacing = 100 GHz (total bandwidth 6.4 THz)
-Transmission line rate = 10 Gb/s
-NRZ modulation format, 215-1 PRBS pattern length
-Transmission link length = 400 km
-The design goal is to achieve error free transmission (BER < 10-9) for all channels
- Design the transmitter and receiver modules, use of different ypes and combinations of fibers, location and number of EDFAs
deployed are your choice

**l parameters values must adhere to existing specifications in
data sheets which can be found on-line**

- Your report (max. 10 pages) must include
- a printout of the schematic diagram of the system
- the design methodology in order to achieve error free
transmission (BER < 10-9) for all channels
- printouts of the optical spectra of the multiplexed 64
channels at the 0 km, 200 km and 400 km mark
- printouts of BER plots (BER vs received optical power) of
the four channels, Channel 1, Channel 17, Channel 39
and Channel 64, and their corresponding eye diagrams at
BER = 10-9
- and any additional measurements to support your design
methodology

# EXPERIMENT - 5 [DATED : 04/03/2021]

## PASSIVE OPTICAL NETWORK

![alt text](https://github.com/NANOPHOTONIC-RESEARCH-SOCIETY-AT-PEC/CAD-SIMULATIONS-OPTICS-LAB/blob/master/ACS_LAB_2021_ODD/RAW/PON.PNG)

- Point-to-multipoint topology
- Fiber plant is typically 20-25 km and unpowered
- May include one or more splitting stages depending on location of ONUs
