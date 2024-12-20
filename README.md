![Statistics](https://www.afponline.org/images/default-source/default-album/tips-for-using-statistics-well-_header-(750-250-px).png?sfvrsn=85e9136b_1)

# Applied Statistics Assignments (Winter 2024)  
**Author:** Lais Coletta Pereira  
**Lecturer:** Dr. Ian McLoughlin  

---

## Repository Overview  
This repository contains coursework for the **Applied Statistics** module as part of the ATU Computer Science - Data Analytics Higher Diploma. It includes:

- Jupyter notebooks:  
  - **`tasks.ipynb`**: Focused on practical statistical tasks.  
  - **`project.ipynb`**: Dedicated to the final project.  
- The `plantgrowth.csv` dataset, used for hands-on statistical analysis in the project.  
- A `requirements.txt` file listing all necessary Python libraries to replicate the analysis.

Each notebook provides concepts explanations, step-by-step implementations, and insightful conclusions to reinforce key statistical concepts.

### Learning Outcomes
- **Core Statistical Concepts**: Understand permutations, combinations, normal distribution, t-tests, and ANOVA in the weekly tasks stored in the tasks.ipynb.
- **Practical Python for Statistics**: Apply `numpy`, `pandas`, `scipy`, and `statsmodels` for data analysis, visualization, and testing.
- **Statistical Test Implementation**: Perform and interpret various t-tests (paired, independent, one-sample), and check assumptions (normality, independence).
- **ANOVA and Post-Hoc Testing**: Apply one-way ANOVA for multi-group comparisons and interpret results using post-hoc tests (e.g., Tukey's HSD).
- **Dataset Exploration and Descriptive Stats**: Wrangle and summarize datasets using descriptive statistics to understand data distribution.
- **Critical Evaluation of Results**: Interpret p-values, t-statistics, and F-statistics to assess the significance and validity of statistical findings.
- **Improved Visualization Skills**: Visualize data distributions with histograms, box plots, and Q-Q plots to support analysis.
- **Report Writing**: Effectively write statistical methods using LaTex, findings, and conclusions in a clear, structured way.


---
## Repository Contents

**Note:**  
- All libraries used in the Jupyter notebooks are listed at the top of each respective file.  
- Bibliography references are included at the end of each task in the `tasks.ipynb` notebook and at the conclusion of the `project.ipynb` notebook.

### 1. **`tasks.ipynb`** — Statistical Tasks  
This notebook contains four statistical tasks with in-depth explanations and step-by-step analysis:  

- **Permutations and Combinations**  
- **Normal Distribution with NumPy**  
- **t-Test Calculations**  
- **ANOVA (Analysis of Variance)**  

**Task Plan:**  
1. **Task Decomposition**: Each task is divided into smaller sub-tasks for easier understanding.  
2. **Result Explanation**: Results are analyzed and explained in detail, providing context for the findings.  
3. **Bibliography**: All references used are listed at the end of each task for transparency and further reading.

### 2. **`project.ipynb`** — Final Project: Statistical Analysis on `plantgrowth.csv`  
This notebook applies statistical analysis techniques, including t-tests and ANOVA, on the `plantgrowth.csv` dataset. The dataset is described in detail, and the methodology is explained thoroughly.  

**Project Plan:**  
1. **Dataset**:  
   - Download and save the `plantgrowth.csv` dataset into the repository.  
2. **Dataset Overview**:  
   - Load the dataset, perform basic summarization, and describe the structure and key variables.  
3. **Explain the t-Test**:  
   - Define the t-test and describe its various types (independent, paired, and one-sample).  
   - List the assumptions (normality, independence, homogeneity of variance) and provide the t-test formula.  
4. **Perform the t-Test**:  
   - Conduct an independent t-test to compare two treatment groups (`trt1` vs. `trt2`). Report the t-statistic and p-value.  
5. **ANOVA Analysis**:  
   - Apply one-way ANOVA to compare the three groups (control, `trt1`, and `trt2`). Report the F-statistic and p-value.  
   - Explain why ANOVA is preferred over multiple t-tests when comparing more than two groups, and provide a rationale for its appropriateness in this context.


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
