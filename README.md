# 📊 Exploratory Data Analysis: NHANES Dataset

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-ffffff?style=for-the-badge&logo=matplotlib)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **Minor Project Submission** for **Corizo Edutech Pvt. Ltd.** Internship.

---

## 📝 Project Overview
This project involves a comprehensive **Exploratory Data Analysis (EDA)** of anthropometric (body measurement) data from the **National Health and Nutrition Examination Survey (NHANES)**. 

The primary objective was to process raw data for adult males and females to identify physiological trends, compute health risk indicators, and visualize statistical distributions using Python.

### 🎯 Key Objectives
* **Data Cleaning:** Preprocessing raw CSV data to handle metadata and missing values (`NaN`).
* **Statistical Analysis:** Computing measures of central tendency, dispersion, skewness, and kurtosis.
* **Feature Engineering:** Deriving advanced health metrics including **BMI**, **Waist-to-Height Ratio (WHtR)**, and **Waist-to-Hip Ratio (WHR)**.
* **Visualization:** Creating comparative histograms, boxplots, and correlation heatmaps to detect sexual dimorphism in body shape.
* **Standardization:** Using Z-score normalization to compare variables across different scales.

---

## 📂 Dataset Details
The analysis is based on two datasets extracted from the NHANES 2020 survey:
* `nhanes_adult_male_bmx_2020.csv`
* `nhanes_adult_female_bmx_2020.csv`

**Key Variables Analyzed:**

| Variable | Description | Unit |
| :--- | :--- | :--- |
| **BMXWT** | Weight | kg |
| **BMXHT** | Standing Height | cm |
| **BMXARML** | Upper Arm Length | cm |
| **BMXLEG** | Upper Leg Length | cm |
| **BMXWAIST** | Waist Circumference | cm |
| **BMXHIP** | Hip Circumference | cm |

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`
* **UI/Presentation:** Custom HTML/CSS (Embedded in Jupyter Notebook for reporting)

---

## 🔍 Key Findings & Insights
Through detailed visualization and statistical testing, the following insights were derived:

1.  **Weight Distribution:** Both male and female weight distributions are **right-skewed**, indicating a "long tail" of individuals with higher body mass (outliers).
2.  **Sexual Dimorphism in Ratios:** * **WHR (Waist-to-Hip Ratio):** showed a significant difference. Males typically exhibit an "Apple" shape (higher ratio), while females exhibit a "Pear" shape (lower ratio).
    * **WHtR (Waist-to-Height Ratio):** proved to be a more gender-neutral metric for assessing central obesity.
3.  **Correlation Analysis:** * Height and BMI showed near-zero correlation, confirming that BMI effectively normalizes weight for height.
    * Waist circumference showed the strongest correlation with Weight ($r \approx 0.9$).

---

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/NHANES-Exploratory-Data-Analysis.git](https://github.com/YOUR_USERNAME/NHANES-Exploratory-Data-Analysis.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the Notebook:**
    Launch Jupyter Notebook and open `NHANES_Analysis.ipynb`.
    ```bash
    jupyter notebook
    ```

> **Note:** For the best viewing experience of the animated Intro/Outro cards, view the notebook via [NBViewer](https://nbviewer.org/).

---

## 👨‍💻 Author
**Priyanshu** *Data Science Intern* **Corizo Edutech Pvt. Ltd.**

---

*This project was developed as part of the internship curriculum to demonstrate proficiency in Data Science and Python Programming.*
