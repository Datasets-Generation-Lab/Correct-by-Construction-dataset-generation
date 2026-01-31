# Energy-Harvesting IoT Dataset

## Overview
This repository provides datasets for energy-harvesting IoT systems. The data is designed to be **reliable and representative** of real-world IoT environments.

## Objective
The goal of this dataset is to support simulation, analysis, and machine learning research in energy-harvesting IoT systems, capturing realistic operational variability and system dynamics.

## System Specification
The dataset relates to an energy-harvesting system based on the architecture illustrated in the visual below:

![Energy-Harvesting System Architecture](https://github.com/Datasets-Generation-Lab/Correct-by-Construction-dataset-generation/blob/main/IoT%20system%20architecture.png)

## Usage
```python
# Example: Load the dataset
import pandas as pd

data = pd.read_csv('path/to/dataset.csv')
print(data.head())
