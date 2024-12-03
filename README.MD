# MLP Classifier on CoverType Dataset

## Description
This project uses a Multi-Layer Perceptron and the CoverType Dataset to predict forest cover types using cartographic variables for 30x30 meter cells, with data derived from USFS and USGS sources. It analyzes four wilderness areas in the Roosevelt National Forest, which reflect ecological processes with minimal human disturbance.

## Table of Contents

- [Getting Started](#getting-started)
- [Running The Code](#running-the-code)

## Getting Started
Clone the repository:<br>
`git clone https://github.com/tkjonesy/CoverType-MLP.git`

## Running the Code
1. Open `MLP.ipynb`.
2. Ensure all these packages are installed: <br>
    `pip install ucimlrepo sklearn matplotlib seaborn pandas numpy`
3. All training and experimenting took place with a `random_state=42`. Use this value to reproduce results.
4. Run all cells under the "Final Model" section. Be sure not to run the entire file, as the  "Hyper-Parameter Tuning" contains a lot of loops and will take a long time to run.
