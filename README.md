![Statistics](https://www.afponline.org/images/default-source/default-album/tips-for-using-statistics-well-_header-(750-250-px).png?sfvrsn=85e9136b_1)

# Applied Statistics Assignments (Winter 2024)  
**Author:** Lais Coletta Pereira  
**Lecturer:** Dr. Ian McLoughlin  

---

## Overview  
This repository contains coursework for the **Applied Statistics** module. It includes two Jupyter notebooks — one for practical tasks and another for the final project. Each file is structured with clear explanations, implementations, and conclusions to help reinforce statistical concepts.

### Learning Outcomes
- **Core Statistical Concepts**: Understand permutations, combinations, normal distribution, t-tests, and ANOVA in the weekly tasks stored in the tasks.ipynb.
- **Practical Python for Statistics**: Apply `numpy`, `pandas`, `scipy`, and `statsmodels` for data analysis, visualization, and testing.
- **Statistical Test Implementation**: Perform and interpret various t-tests (paired, independent, one-sample), and check assumptions (normality, independence).
- **ANOVA and Post-Hoc Testing**: Apply one-way ANOVA for multi-group comparisons and interpret results using post-hoc tests (e.g., Tukey's HSD).
- **Dataset Exploration and Descriptive Stats**: Wrangle and summarize datasets using descriptive statistics to understand data distribution.
- **Critical Evaluation of Results**: Interpret p-values, t-statistics, and F-statistics to assess the significance and validity of statistical findings.
- **Improved Visualization Skills**: Visualize data distributions with histograms, box plots, and Q-Q plots to support analysis.
- **Report Writing**: Effectively communicate statistical methods, findings, and conclusions in clear, structured reports.


---

## Repository Contents  
**All libraries used in the Jupyter notebooks are located at the top of the file**

- **`tasks.ipynb`** — Contains four core statistical tasks with detailed breakdowns:  
1. **Permutations and Combinations**  
2. **Normal Distribution with NumPy**  
3. **t-Test Calculations**  
4. **ANOVA (Analysis of Variance)**  

    **Tasks Plan:**  
    1. Break down each task into smaller tasks
    2. Explain each result and provide a brief analysis
    3. Provide the references at the end of each task  

- **`project.ipynb`** — A final project involving t-tests and ANOVA on the plantgrowth.csv dataset while describing the dataset and explaining the work done in the jupyter notebook.  

    **Project Plan:**  
   1. Download and Save the Dataset: Obtain and store the dataset in the repository.
   2. Describe the Dataset: Load the dataset, summarize its structure, and describe the variables (e.g., treatment groups).
   3. Explain the t-test: Define the t-test, its types (independent, paired, one-sample), assumptions (normality, independence, homogeneity of variance), and formula. 
   4. Perform t-test: Apply an independent t-test to compare treatment groups (trt1 vs. trt2). Report the t-statistic and p-value. Perform 
   5. ANOVA: Apply ANOVA to compare all three groups (ctrl, trt1, trt2). Report the F-statistic and p-value.
   6. Justify Using ANOVA: Explain why ANOVA is more appropriate than multiple t-tests for comparing more than two groups. 

---

## Technologies Used  
- **Python** 3.12.2  
- **Jupyter Notebook**  

---

## Dependencies  

### Required Python Version  
Python 3.8 or later  

### Libraries  
The following Python libraries are required for the project:  
- **`numpy`** — for numerical computations  
- **`pandas`** — for data manipulation  
- **`matplotlib`** — for data visualization  
- **`seaborn`** — for enhanced data visualization  
- **`scipy`** — for statistical testing and distributions  
- **`statsmodels`** — for statistical modeling and additional tests  

---

## Installation Instructions  

### Using `conda`  
To set up the required environment using `requirements.txt`, run:  
```bash
conda create --name <envname> --file requirements.txt
```

### Using `pip`  
Alternatively, you can install libraries individually with `pip`:  
```bash
pip install pandas numpy seaborn matplotlib scipy statsmodels
```

---

## Running The Code

1. Install [Anaconda](https://www.anaconda.com/download).  
2. Install [Visual Studio Code](https://code.visualstudio.com/).  
3. Clone the repository:  
   ```bash
   git clone https://github.com/LaisColetta/Applied-Statistics.git
   ```  
4. Open the cloned repository in Visual Studio Code.

---

## Usage Instructions

- `.ipynb` files contain the tasks and project implementations.
- Use **Markdown cells** for narrative text.
- Use **Code cells** for Python code.

---

## Support

For any issues or queries, contact:  
**Email:** G00411338@atu.ie

---
# END
