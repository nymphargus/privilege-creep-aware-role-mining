# Privilege Creep Aware Role Mining (RM)
A role mining method that addresses privilege creep in Role-Based Access Control (RBAC) systems.
## About
This repository contains the implementation of algorithms developed to identify and mitigate excessive permissions in organizational access control systems. The method incorporates privilege creep detection directly into the RM process.
It also contains the implementation of a new parameterizable synthetic data generator that aims to build realistic RM datasets, able to inject noise and privilege creep related to common enterprise scenarios.
## Note on Format
The code is currently provided in a Jupyter Notebook format due to constraints from our industrial partner, as the code was meant to run on Databricks. As of now, it has not been refactored into a proper library structure. Future work will include converting this into a modular Python package.
## Acknowledgments
This implementation uses the RoleMiner algorithm implementation by James Bonifield as a base for exact role mining :
```
Bonifield, J. (2020). RoleMiner: Python Implementation of various algorithms 
for solving the Role Mining Problem. GitHub repository. 
https://github.com/jbonifield3/RoleMiner
```
