# Global Digital Payment Gender Gap Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Data](https://img.shields.io/badge/Data-Global_Findex_2021-green.svg)](https://www.worldbank.org/en/publication/globalfindex)

## 📌 Project Overview
This repository contains a comprehensive data analysis project exploring the gender disparities in digital payments and financial technology adoption across global economies. Using the **World Bank's Global Findex Database (2017 and 2021)**, this project investigates the systematic socio-economic drivers behind the digital payment gender gap and its implications for global financial inclusion.

This project was completed as part of a university assignment.
## 📁 Repository Structure & File Descriptions

Below is a detailed breakdown of every file included in this repository and its specific purpose within the project:

### 1. The Code & Analysis
* **`Findex.ipynb`**
  * **Purpose:** This is the core Jupyter Notebook containing the entire data science pipeline. 
  * **Contents:** It includes data loading, cleaning, exploratory data analysis (EDA), and statistical modeling. The code specifically filters data for 2017 and 2021, constructs the `DigitalPaymentGenderGap` variable, and utilizes libraries like `pandas`, `seaborn`, and `statsmodels` to extract insights.
  * **Note:** To run this notebook, you will need the raw dataset (`DatabankWide.xlsx`), which must be placed in the same directory.

### 2. The Final Output
* **`Reflection_of_the_Global_Digital_Payment_Gender_Gap.pdf`**
  * **Purpose:** The final critical reflection paper and research report.
  * **Contents:** This document synthesizes the findings from the Jupyter Notebook into a formal academic report. It discusses the context of global digitalization, analyzes the persistence of the 9% global gender gap in account ownership, details the methodology used, and offers critical insights and future recommendations based on the data.

### 3. Documentation & Context
* **`Findex_description.pdf`**
  * **Purpose:** The original project brief and assignment instructions.
  * **Contents:** Details the overarching goals of the group project, expectations for data preparation and ML/statistical modeling, and provides background information on the Global Findex 2021 dataset's role in tracking financial resilience during the COVID-19 pandemic.
* **`GlobalFindex2021-MicrodataCodebook.pdf`**
  * **Purpose:** The official data dictionary for the dataset.
  * **Contents:** An essential reference document that maps out all variable names, survey questions, and definitions (e.g., economy codes, demographic data, financial indicators) used within the Global Findex 2021 microdata. Use this to understand the raw variables referenced in the Jupyter Notebook.

## 🛠️ Methodology & Tech Stack
* **Language:** Python
* **Libraries:**
  * `pandas` & `numpy` for data manipulation
  * `matplotlib` & `seaborn` for data visualization
  * `statsmodels` for statistical analysis and linear modeling
* **Key Metrics Analyzed:** * Percentage of males vs. females (age 15+) making or receiving digital payments.
  * Year-over-year changes (2017 to 2021) in the gender gap.

## 🚀 How to Use This Repository

1. **1. Clone the repository:**
   ```bash
   git clone https://github.com/mylestande/Findex.git
   ```

2. **Install dependencies:**

Ensure you have Jupyter installed along with the required Python packages. You can install them via pip:
  ```bash
  pip install pandas numpy matplotlib seaborn statsmodels openpyxl
```

3. **Acquire the Data:**

    Download the Global Findex dataset from the repo.

    Ensure the dataset file is named DatabankWide.xlsx (as expected by the script).

    Place this file directly in the root directory of this cloned repository (assuming you cloned the repo, there is no need for any of this in Step 3).

4. **Run the Notebook:**

Launch Jupyter Notebook and open the analysis file to run the cells and reproduce the findings:
```bash
jupyter notebook Findex.ipynb
```

## 📄 License
Data provided by the World Bank Group.

