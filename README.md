# Applied Statistics (Winter 2024)

## Author: Lais Coletta Pereira  
Email: G00411338@atu.ie  

---

## Overview

This repository contains the tasks and project for the module **Applied Statistics** (Instructor: Dr. Ian McLoughlin).

---

## Features

### **tasks.ipynb**
This Jupyter notebook includes four tasks:  
1. **Permutations and Combinations**  
2. **numpy's Normal Distribution**  
3. **t-Test Calculation**  
4. **ANOVA**

---

### **project.ipynb**
This Jupyter notebook is dedicated to the project titled **"Analysis of Plantgrowth Data Set"**. It includes a detailed breakdown of the project, along with all references.  

### Project Contents:  

#### **PROJECT TITLE:**  
**Analysis of Plantgrowth Data Set**  

#### **Project Description**  

#### **Abstract**  

1.0 **Plan**  

2.0 **Methods and Implementation**  
- **2.1** Download and save the dataset  
- **2.2** Describe the dataset  
- **2.3** Describe what a t-test is, how it works, and its assumptions:  
  - **2.3.1** T-test definition  
  - **2.3.2** How a t-test works  
  - **2.3.3** Assumptions:  
    - **Continuous Data:**  
      - Histogram  
      - Box Plot  
    - Sample size  
    - Independence and Random Sampling  
    - Homogeneity of Variance (Levene's Test)  
    - Test for Normality (Shapiro-Wilk Test):  
      - Q-Q Plot  
      - Shapiro-Wilk Test  

- **2.4** Perform a t-test to determine whether there is a significant difference between the two treatment groups (trt1 and trt2):  
  - **2.4.1** Independent Two-Sample T-test  

- **2.5** Perform ANOVA to determine whether there is a significant difference between the three treatment groups (ctrl, trt1, and trt2):  
  - **2.5.1** One-way ANOVA  

- **2.6** Explain why ANOVA is more appropriate than multiple t-tests for analyzing more than two groups.  

3.0 **Conclusion**  

4.0 **References**  

---

## Technologies Used
- Python 3.11.5  

---

## Dependencies

### Required Python Version
Python 3.8 or later  

### Libraries:
- `numpy` - for numerical computations  
- `pandas` - for data manipulation  
- `matplotlib` - for data visualization  
- `seaborn` - for data visualization  
- `scipy` - for statistical tests and distributions  
- `statsmodels` - for additional statistical models and tests  

---

## Installation Instructions

1. Create an environment:  
   ```bash
   conda create --name <envname> --file requirements.txt
