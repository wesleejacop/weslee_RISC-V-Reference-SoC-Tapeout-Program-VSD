 # Week 0 - Essential EDA Tools Setup  🛠️🛠️

Welcome to the initial phase of the project where we configure and install the core open-source EDA tools required for RTL-to-GDSII design flow.

### **System Requirements**
- 6 GB RAM
- 50 GB HDD
- Ubuntu 20.04 or higher
- 4 vCPU

This documentation covers the installation and basic verification of three vital tools:

- **Yosys** (RTL synthesis and optimization)
- **GTKWave** (waveform viewing and signal analysis)
- **Iverilog** (Verilog simulation and compilation)

---

## Installation Guide

### Setting Up Yosys ✅

Yosys is a powerful open-source synthesis tool that converts RTL Verilog code into gate-level representation. It plays a crucial role in optimizing designs before physical implementation.

To install Yosys on Ubuntu:
```bash
# Day 0 - Tools Installation
## Yosys

$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys 
$ sudo apt install make # (If make is not installed please install it) 
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make 
$ sudo make install
```
Verify the installation by running:
```bash
yosys
```
<p align="center">
  <img src="https://github.com/wesleejacop/weslee_RISC-V-Reference-SoC-Tapeout-Program-VSD/blob/c969b615081da6f91484c131e60b40889df08e27/week%200/Screenshot%20(118).png " 
       alt="Yosys Installed" width="600"/>
</p>



## **Iverilog Installation** ✅
```bash
$ sudo apt-get install iverilog
```
Verify the installation by running:
```bash
$ iverilog
```
<p align="center">
  <img src="https://github.com/wesleejacop/weslee_RISC-V-Reference-SoC-Tapeout-Program-VSD/blob/c969b615081da6f91484c131e60b40889df08e27/week%200/Screenshot%202025-09-20%20204857.png " 
       alt="Yosys Installed" width="600"/>
</p>



### Installing GTKWave ✅

GTKWave is a waveform viewer that helps debug and visualize simulation results from Verilog or VHDL.

Installation commands:
```bash
$ sudo apt update
$ sudo apt install gtkwave
```
Verify the installation by running:
```bash
$ gtkwave
```

<p align="center">
  <img src="https://github.com/wesleejacop/weslee_RISC-V-Reference-SoC-Tapeout-Program-VSD/blob/b9bd525dc2760eb73e85ce488612c69129df6d39/week%200/Screenshot%202025-09-20%20205203.png" 
       alt="Yosys Installed" width="600"/>
</p>

<div align="center">


## Summary

| Tool    | Purpose                        | Installation Status |
|---------|-------------------------------|---------------------|
| Yosys   | RTL synthesis & optimization  | ✅ Installed        |
| GTKWave | Waveform viewing & analysis   | ✅ Installed        |
| Iverilog| Verilog compilation & simulation | ✅ Installed     |

