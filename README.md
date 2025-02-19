# dnanexus-workshop

**Date:** 2025-02-20 14:00
**Lecturer:** Dr. Cris Van Hout and Dr. Claudia Gonzaga (LIIGH UNAM).

This repository contains the code for excercises and some notes for the workshop: "Using DNANexus for Genetic Analyses".

Main notes are located in the "PhD Notes" (*private*) repository (https://github.com/rolvhdez/phd-notes).

## Learning goals
1. Explain basic project structure of the platform
2. Create and administer a project
3. Add and manage data in your project
4. List the advantages to interacting with platform via command line interface
5. List the functions of the SDK and the API
6. Describe the purpose of the dx-toolkit
7. Apply frequently used dx-toolkit commands to execute common use cases
8. Execute and Monitor an app on a dataset
9. Create a multi-step workflow
10. Execute and Monitor a workflow with public resources

## Requirements
1. Verify that you have a functional terminal application on your laptop. (Ask a friend.)
2. Install Python3, https://www.python.org/downloads/
3. Install the DNANexus Software Development Kit, dx-toolkit,
https://documentation.dnanexus.com/downloads
4. Create a DNANexus account at https://platform.dnanexus.com using an institutional
email address & forward your user name and email to cvanhout@liigh.unam.mx no later
than February 25.

## Initialize

Run the next commands. in your Linux terminal to: 

1. Create a virtual environment.

```shell
python -m venv env
```
2. Activate it
```shell
source env/bin/activate
```
3. Install the necesary libraries (`dxpy` and `pandas`):
```shell
pip install -r requirements.txt
```
