---
title: "Interfacing Linux and IP blocks on FPGA platforms"
collection: topics
permalink: /topics/linux-fpga
excerpt: 'Design of userspace libraries and device drivers for IP block interface.'
date: 2019-03-08

---

## Project goal

Goal of the project is develop userspace librarires and device drivers 
for communication with custom IP blocks on FPGA hardware for digital 
signal processing. Developed tools have to enable user to transfer data 
between PS (Processing system) and PL (Programmable Logic) parts of the 
device.

* research of existing tools,
* determine MPSoC platform with FPGA for testing (ZCU102 is suggested),
* demonstrate functionalities of developed toolbox on practical examples,
* compare performance of models generated using toolbox to their implementations for GPU.

## Requirements

Requirements:

* C 
* Embedded Linux
* VHDL, Verilog