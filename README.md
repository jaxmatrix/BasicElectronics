# Basic Electronics Tutorial

In this section we will discuss about simulation of circuits in linux.
We do have simplified tools for simulations but going through the non-graphical
will help us understand the details of spice simulaiton.

This Tutorial will include 

1. Making Netlist ( Circuit Diagram using text file)
2. AC simulation
3. Transient Simulation 
4. Few Practical projects that will help you setup your own lab with very basic resource.

## Installation of gEDA and Ngspice 

(Please note this tutorial is only for Ubuntu users, tutorials for other linux distribution will be made available depending upon the requestes for that particular distribution)

### gEDA

gEDA is schematic and PCB design package that enables to make PCBs and schematics.

Use the following command to install the package

```
sudo apt-get update
sudo apt-get install -y geda
```

### Ngspice 

Ngspice is a terminal spice simulator, we are using a terminal based spice simulator in order to facilitate understanding of the spice simulations and working of different simulation models.

```
sudo apt-get update && sudo apt-get install -y ngspice 
```

## Tutorials Steps

1. Learn how to use Github, bug reporting and collaboration in the github

2. Make a git public repository and follow these steps

   1. Fill up the [this](https://forms.gle/JpP41yySP91QphrL7) form 
   2. Download Typora and learn Markdown
   3. Make a README.md file and document all the steps used for simulations
   4. Write issues that you faced in the README.md documentation
   5. Commit you work after every exercise and maintain a directory for every simulation section 
   6. In case of doubts raise issues/bugs in this repository

3. Follow the steps given in the [this](<http://ngspice.sourceforge.net/ngspice-tutorial.html>) link in order to learn spice simulation

4.  #### Using Eeschema for spice simulation 

   Follow the steps given in [this](http://ngspice.sourceforge.net/ngspice-eeschema.html) link for simulation using Eeshema

5. Obtain a copy Microelectronics by Neamen

### Advance tutorial 

Tutorial link for using eeschema for ngspice simulation
https://www.linuxjournal.com/article/8438

KiCad Docs for making the circuit
http://docs.kicad-pcb.org/5.1.2/en/getting_started_in_kicad/getting_started_in_kicad.html

# Construction of the circuits for simulations

This part will consists of part theory, part simulation and if possible part practical. In this section we will be following Microelectronics by Neamen. 

First we will learning the theory about the electronics component. This shall be completed by going through the first four chapters of the book.
When you are through those chapters complete the following tasks.

## Clipping and Clamping

!-- Clipping circuit diagram 

!-- Code for simulation in spice 

!-- Clamping circuit diagram 

!-- Code for spice simulation 

## Simple Amplifiers and setting up the dc point of the circuit 

Do the following exercise and examples from the book

## Simulation : Integrator Cirucit 

!-- Circuit Diagram

!-- Desired output from the simulation

## Simulation : DIfferentiator Circuit

!-- Circuit Diagram 

!-- Desire Output  

## Practical : Sqare wave generation cirucit with variable frequency

!-- 555 Timer circuit

!-- Taking output using arduino

## Practical : Integrator and Differentiator Circuit

!-- Generation of triangular waves block diagram

!-- Wave transformation

## Simulation : Joule Theif Circuit 

!-- Circuit diagram 

!-- Theory 

!-- Simulation hints 


## Practical : Joule Theif Circuit 

!-- Impulsive increase in the voltage of the circuit --Theory

!-- Testing by generation of small sparks using the joule theif circuit

# Practical Project : Making a frequency generator till 1Mhz for simulation of the circuit

!-- The link for making the frequency generator for the testing in room using STM
