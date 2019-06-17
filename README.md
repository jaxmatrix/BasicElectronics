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

1. Follow the steps given in the [this](<http://ngspice.sourceforge.net/ngspice-tutorial.html>) link in order to learn spice simulation

2.  #### Using Eeschema for spice simulation 

   Follow the steps given in [this](http://ngspice.sourceforge.net/ngspice-eeschema.html) link for simulation using Eeshema

### Advance tutorial 

Tutorial link for using eeschema for ngspice simulation
https://www.linuxjournal.com/article/8438

KiCad Docs for making the circuit
http://docs.kicad-pcb.org/5.1.2/en/getting_started_in_kicad/getting_started_in_kicad.html

# Construction of the circuits for simulations

## Simulation : Integrator Cirucit 

## Simulation : DIfferentiator Circuit 

## Practical : Sqare wave generation cirucit with variable frequency

## Practical : Integrator and Differentiator Circuit

## Simulation : Joule Theif Circuit 

## Practical : Joule Theif Circuit 

# Practical Project : Making a frequency generator till 1Mhz for simulation of the circuit

