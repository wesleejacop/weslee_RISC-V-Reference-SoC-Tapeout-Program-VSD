# Day 1: Kickoff to Verilog RTL Design & Synthesis Journey

Welcome to the first day of my RTL design workshop! Today marked the start of my exploration into digital circuit design, where I dove into Verilog coding, simulated my circuits with the open-source tool **Icarus Verilog (iverilog)**, and took the initial steps into logic synthesis using **Yosys**. This report captures all my hands-on labs, crucial insights, and the practical knowledge I gained building a foundation in RTL design.

---

## 📚 Contents at a Glance

- [My Learning Highlights: Simulator, Design Logic, and Testbenches](#1-my-learning-highlights-simulator-design-logic-and-testbenches)  
- [Getting Up and Running with Icarus Verilog](#2-getting-up-and-running-with-icarus-verilog)  
- [Hands-On Lab: Simulating a 2-to-1 MUX](#3-hands-on-lab-simulating-a-2-to-1-mux)  
- [Dissecting My Verilog Source Code](#4-dissecting-my-verilog-source-code)  
- [Intro to Yosys & Gate Libraries](#5-intro-to-yosys--gate-libraries)  
- [The Role of .lib Files and Variations in Gate Cells](#6-the-role-of-lib-files-and-variations-in-gate-cells)  
- [Synthesis Lab Walkthrough with Yosys](#7-synthesis-lab-walkthrough-with-yosys)  
- [Confirming Synthesis Accuracy](#8-confirming-synthesis-accuracy)  
- [Wrapping Up: What I Achieved Today](#9-wrapping-up-what-i-achieved-today)  

---

## 1. My Learning Highlights: Simulator, Design Logic, and Testbenches

### 🚀 Simulator Insight  
I came to understand that a **simulator** acts like a virtual environment where digital circuits can be tested by feeding inputs and observing outputs before physical implementation. This step is vital to catch logical bugs early.

### 💡 What is Design?  
My **design** is essentially the Verilog code that describes the logical behavior of the circuit — in essence, writing down what the circuit *should* do.

### 🧪 Testbench Essentials  
I deepened my understanding of the **testbench**, which creates a simulation environment to apply various scenarios to my design and check for correct behavior.

---

## 2. Getting Up and Running with Icarus Verilog

Icarus Verilog, or **iverilog**, is the open-source tool I used to compile and simulate my Verilog code. The workflow I followed was:

