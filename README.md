# Machine Data Analysis - V0.3

## Overview

This project involves analyzing data from three machines used in an elementary parts manufacturing plant. The machines are used to manufacture the same part type, and data has been collected across different runs. The analysis includes quality control checks, machine performance tracking, and the calculation of Overall Equipment Effectiveness (OEE).

### Data Files
The dataset consists of multiple files:
- **PartMeasurement.xlsx**: Contains the measurements of parts after manufacturing.
- **PartTolerances.xlsx**: Contains the upper and lower bounds for measurements.
- **MachineHeadInstallations.xlsx**: Contains timestamps indicating when a specific machine head was installed on a machine.
- **MachineRunData**: Contains JSON files corresponding to individual machine runs.

### Objective
The goal is to combine, manipulate, and analyze these datasets to answer several questions regarding machine performance, quality control, and overall efficiency.

## Requirements
- **Python 3.x**
- **pandas**
- **matplotlib**
- **seaborn**

Install required packages using pip:

```bash
pip install pandas matplotlib seaborn
