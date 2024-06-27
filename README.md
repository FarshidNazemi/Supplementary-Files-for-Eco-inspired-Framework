# Supplementary Files for:

## Ecologically Inspired Metrics for Transitioning to a Sustainable and Resilient Circular Economy with Application to Multilayer Plastic Films

### Description

This repository contains supplementary files for the journal manuscript titled *Ecologically Inspired Metrics for Transitioning to a Sustainable and Resilient Circular Economy with Application to Multilayer Plastic Films*. The supplementary files include an Excel file and a Jupyter Notebook that support the findings and methodologies discussed in the manuscript.

### Contents

1. **Results.xlsx**: This Excel file contains the results for the indicators for the multilayer plastic film example discussed in the paper. It also includes the calculations for greenhouse gas (GHG) emissions.

2. **Source code.ipynb**: This Jupyter Notebook contains the network analysis and  detailed calculations of Eco-inspired indicators related to the multilayer film. The notebook uses various CSV files for input data, which are located in the `data` folder.

3. **data**: This folder contains all the CSV files (network flow data) used by the Jupyter Notebook for the calculations and analysis for multilayer films.
4. **Eco-inspired-tool.ipynb** This Jupyter Notebook is designed to calculate Eco-inspired metrics for a network provided by the user. The instructions for using this notebook are included within the file.

### Instructions

1. **Results.xlsx**: Open this file with any spreadsheet software (e.g., Microsoft Excel, Google Sheets) to view the results and GHG emissions calculations.

2. **Jupyter Notebook**:
   - Ensure you have Python and Jupyter Notebook installed. You can install Jupyter Notebook using Anaconda or pip.
   - Navigate to the directory containing the `Source code.ipynb` file.
   - Launch Jupyter Notebook by running the following command in your terminal or command prompt:
     ```bash
     jupyter notebook
     ```
   - Open the `Source code.ipynb` file in Jupyter Notebook.
   - Execute the cells to reproduce the network analysis. The notebook reads the required data from the CSV files in the `data` folder.

### Dependencies

The Jupyter Notebook requires the following Python packages:
- numpy
- pandas
- math (standard library)
- scipy.special

You can install these packages using pip:
```bash
pip install numpy pandas scipy
```
### Contact
For any questions or further information, please contact fnazemi@asu.edu.

