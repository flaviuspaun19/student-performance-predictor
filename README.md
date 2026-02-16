# Student Academic Performance Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Pandas](https://img.shields.io/badge/Data%20Analysis-Pandas-green)

## 📋 Project Overview
This project applies **Machine Learning** to identify and quantify the behavioral factors that drive academic success. Using a dataset of student habits, I developed a predictive model to estimate final exam scores, providing a tool for data-driven academic intervention.

### Objectives:
* **Predictive Modeling:** Estimate student scores using a Linear Regression framework.
* **Behavioral Insights:** Identify which habits (e.g., study hours, attendance) have the highest impact on performance.
* **Optimization:** Simulate "improved student" scenarios to validate recommended habit changes.

---

## 🛠️ Technical Methodology
* **Language:** Python
* **Libraries:** `Pandas` for data preprocessing, `Matplotlib` for Exploratory Data Analysis (EDA), and `Scikit-learn` for model development.
* **Workflow:** Following the standard data science lifecycle, the project includes data cleaning, feature selection, 80/20 train-test splitting, and performance evaluation.



---

## 📈 Key Results & Insights
The final model achieved an **$R^2$ score of 0.64**, meaning that 64% of the variance in exam scores can be explained by the behavioral features tracked.

### Critical Findings:
* **Primary Drivers:** Study hours and tutoring sessions demonstrated the strongest positive correlation with score increases.
* **Foundation Factor:** Consistent attendance was identified as a critical baseline requirement; without it, other improvements showed diminishing returns in predictions.

---

## 🚀 Getting Started

### Prerequisites
* Python 3.8+
* VS Code or Jupyter Notebook

### Installation & Execution
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/flaviuspaun19/student-performance-predictor.git](https://github.com/flaviuspaun19/student-performance-predictor.git)

2. **Run Analysis:**
   Open the `student_performance_analysis.ipynb` file in VS Code or Jupyter Notebook and execute all cells to reproduce the results and visualizations.

### 📂 Project Structure

* **student_performance_analysis.ipynb**: The core Jupyter Notebook containing Exploratory Data Analysis (EDA), model training, and performance evaluation.
* **StudentPerformanceFactors.csv**: The primary dataset containing behavioral and academic metrics used for model training.
* **student.html**: The exported `.html` file of the code.
* **requirements.txt**: A comprehensive list of Python library versions required to ensure environment reproducibility.
