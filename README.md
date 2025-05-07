# NanoVNA Project

## 📡 Overview

This repository contains tools and resources for working with the **NanoVNA** (Vector Network Analyzer), a compact and affordable RF measurement device. It includes scripts for data acquisition, calibration routines, data visualization, and analysis of S-parameters across a range of frequencies.

The project is intended for RF enthusiasts, researchers, and engineers who want to expand the capabilities of their NanoVNA or automate measurements.

---

This document requires a file called "nanovna.py", which can be downloaded from the github repo:"ttreftech/NanoVNA/python/". this is a requirement.

Once the nanovna.py file has been imported into the folder the code is ready to run. 
Required Libraries:
1. numpy
2. matplotlib
3. pickle

---

This has 2 different jupyter notebooks,

1. nano_VNA_skill: this has the code to acquire and process the data. This has been set up for reflection measurements
2. plotter: this code snippet is for plotting and analysisng the data, it also can calculate the resonance frequency and quality factor of the spectroscopic data