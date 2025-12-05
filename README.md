# Insurance-Risk-Analytics-Predictive-Modeling

This repository contains the implementation of Insurance Risk Analytics and Predictive Modeling tasks, focusing on data-driven insights for risk assessment and profitability analysis.

## Project Structure

- `data/`: Contains the dataset files managed with DVC.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and modeling.
- `src/`: Source code for utilities and models.
- `test/`: Unit tests for the codebase.
- `dvc_storage/`: DVC-managed data storage.

## Task 1: Git and GitHub Setup & Project Planning

### 1.1 Git and GitHub

**Tasks:**

- Create a git repository for the week with a comprehensive README.
- Implement Git version control for tracking changes and collaboration.
- Set up CI/CD with GitHub Actions for automated testing and deployment.

**Key Performance Indicators (KPIs):**

- Dev Environment Setup: Ensure the repository includes necessary configuration files (e.g., `.gitignore`, `requirements.txt`) for easy setup.
- Relevant Skill in the Area Demonstrated: Showcase proficiency in Git workflows, branching strategies, and CI/CD pipelines.

This repository demonstrates best practices in version control, with commits reflecting iterative development, branches for features, and GitHub Actions for continuous integration.

### 1.2 Project Planning - EDA & Stats

**Develop a foundational understanding of the data, assess its quality, and uncover initial patterns in risk and profitability.**

**Tasks:**

- Data Understanding: Load and inspect the insurance dataset (`MachineLearningRating_v3.txt`).
- Exploratory Data Analysis (EDA): Perform statistical summaries, visualizations, and correlation analysis.

**Guiding Questions:**

- What is the overall Loss Ratio (TotalClaims / TotalPremium) for the dataset?

The EDA is implemented in `notebooks/01_task1_eda_v2.ipynb`, which includes:

- Loading and basic info of the data.
- Numeric summaries for key columns (TotalPremium, TotalClaims, SumInsured, CustomValueEstimate).
- Histograms and boxplots for distributions and outliers.
- Correlation heatmap for relationships.
- Calculation of LossRatio and grouping by categories (Province, VehicleType, Gender).
- Monthly trends in Premiums vs Claims.

## Task 2

[Placeholder for Task 2 details. To be updated as the project progresses.]

## Setup

1. Clone the repository: `git clone <https://github.com/Bekamgenene/Insurance-Risk-Analytics-Predictive-Modeling.git>`
2. Install dependencies: `pip install -r requirements.txt`
3. Run notebooks: Use Jupyter to execute `notebooks/01_task1_eda_v2.ipynb`

# contributor
Bekam Genene

