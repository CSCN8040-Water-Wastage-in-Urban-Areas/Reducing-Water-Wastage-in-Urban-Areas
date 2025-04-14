
# Reducing Water Wastage in Urban Areas

This repository documents a project aimed at revolutionizing urban water management by reducing water wastage using a data-driven approach inspired by the Toyota A3 8-Step process. The project focuses on tackling the root causes of water leakage in urban distribution networks by integrating AI-based leak detection, predictive maintenance, and smart infrastructure investments.

## Project Overview

Urban water distribution systems in Egypt currently suffer from significant inefficiencies, with 58.17% of distributed water lost annually—equating to approximately 21 billion cubic meters of water (Pardo & Tekinerdogan, 2023). The ideal target is to reduce this loss to 8%, or 2.88 billion cubic meters per year, based on a total distribution volume of 36.1 billion cubic meters. This project aims to close the 18.12 billion m³/year gap between the current and ideal states by achieving a 50.17% reduction in water loss, bringing Egypt in line with international standards of water efficiency.

### Key Objectives

- **Reduce Water Loss:** Address leakage in distribution networks, currently a major contributor to water wastage.
- **Improve Infrastructure:** Replace outdated materials and enhance maintenance practices.
- **Integrate Technology:** Utilize AI and IoT sensors for real-time leak detection and predictive maintenance.
- **Reallocate Budget:** Influence municipal budgeting to prioritize sustainable water infrastructure improvements.

## Team Members

- **Gonuguntla, Keerthi** – Team Leader & AI/ML Coordinator (Conestoga College)  
- **Karunanithi, Ranjan** – Data Analyst
- **Pallothu, Maruthi Venkata Manikanta Chowdary** – Quality Assurance
- **Prathap, Sreehari** – Developer
- **Tuppari, Shri Vardhan Reddy** – Developer

## Timeline

- **Start Date:** January 6, 2025
- **Planned Duration:** 4 Months

## Problem Statement

Inefficient urban water distribution systems result in significant water wastage. The primary causes include:
- **Aging Pipelines:** Contributing to approximately 1.402 billion cubic meters/year of loss.
- **Poor Maintenance:** Contributing to roughly 0.935 billion cubic meters/year of loss.
  
Additional factors include outdated infrastructure, insufficient budget allocation, and lack of real-time monitoring systems.

## Target & Sub-Targets

- **Overall Water Wastage:**
  - **Current:** 2.337 billion cubic meters/year
  - **Target Reduction:** 70% (down to 0.701 billion cubic meters/year)
- **Aging Pipelines:**
  - **Current Loss:** 1.402 billion cubic meters/year
  - **Target Reduction:** 67% (down to 0.468 billion cubic meters/year)
- **Poor Maintenance:**
  - **Current Loss:** 0.935 billion cubic meters/year
  - **Target Reduction:** 75% (down to 0.234 billion cubic meters/year)

## Root Cause Analysis

A detailed 5-Why Analysis identified:
1. **Leakage Causes:** Aging pipelines and poor maintenance.
2. **Aging Pipelines:** Due to outdated materials and insufficient infrastructure investment.
3. **Budget Constraints:** Limited upgrades from low prioritization of water infrastructure.
4. **Lack of Data-Driven Decisions:** Municipal planning suffers from inadequate real-time monitoring.

## Proposed Countermeasures

1. **AI-Based Leak Detection:** Deploy IoT sensors to monitor leaks and optimize repair schedules.
2. **Smart Infrastructure Investment:** Replace aging pipelines with high-density polyethylene (HDPE) pipes and other advanced materials.
3. **Predictive Maintenance:** Utilize machine learning to forecast failures and schedule proactive repairs.
4. **Budget Reallocation:** Advocate for data-driven budget adjustments to better support water infrastructure improvements.

## Research Hypothesis

*Implementing AI-based leak detection and predictive maintenance will achieve a water wastage reduction of at least 70% in urban distribution networks.*

- **Dependent Variable:** Water wastage reduction (both in percentage and cubic meters).
- **Independent Variable:** Adoption of AI-based monitoring and smart maintenance strategies.

## Data Sources

- **Water Leak Dataset:** Available on [Kaggle](https://www.kaggle.com/datasets/ziya07/water-leak-dataset).

## Prerequisites:
### 1  Clone the repository
git clone https://github.com/CSCN8040-Water-Wastage-in-Urban-Areas/Reducing-Water-Wastage-in-Urban-Areas.git
cd Reducing-Water-Wastage-in-Urban-Areas

### 2  Install the required libraries
python -m pip install --upgrade pip
pip install pandas numpy scipy matplotlib seaborn scikit-learn imbalanced-learn jupyterlab

### 3.Launch JupyterLab:
jupyter lab
### 4.Navigate to the notebook
In the left sidebar, double-click Reducing_Water_Wastage.ipynb
### 5.Run the entire notebook
Menu → Run ► Run All Cells
### The notebook will:
- load water_leak_detection_1000_rows.csv
- generate the correlation heat‑map, leak/burst bar‑plots, and the three box‑plots
- execute the T‑test, Wilcoxon test and Spearman correlation and print the p‑values

## References

1. Picazo, M. Á. P., & Tekinerdogan, B. (2024). *Urban water distribution networks: Challenges and solution directions.* [DOI](https://doi.org/10.1016/b978-0-323-99330-2.00005-2)
2. Un-Water. (2022). *UN World Water Development Report 2022.* [UN-Water](https://www.unwater.org/publications/un-world-water-development-report-2022)
3. SoppeGerhardus, N. A. M. S. (n.d.). *Water Utility Turnaround Framework: A Guide for Improving Performance.* [World Bank](https://documents.worldbank.org/en/publication/documents-reports/documentdetail/515931542315166330/water-utility-turnaround-framework-a-guide-for-improving-performance)

## Additional Information

This repository includes project documents, analysis reports, and data files. For more detailed insights into the project methodology and results, please refer to the project documentation.

---