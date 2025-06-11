# 💄 Cosmetics Data Analysis Project

This repository contains the full statistical analysis pipeline for a clinical or consumer-based cosmetics study. The project includes raw data processing, statistical testing, visualizations, and report writing using a Jupyter Notebook environment.

---

## 📦 Project Structure

cosmetics-data-analysis/

├── data/

│ └── Cosmetics_Raw_Data.xlsx # Source data (anonymized)

│

├── notebooks/

│ └── 30346642.ipynb # Main analysis notebook (R or Python kernel)

│

├── reports/

│ ├── Statistical_Analysis_Report.docx # Final report

│ ├── Tables_and_Figures.docx # Supporting visual summaries

│ └── Notes_on_Study.docx # Variable definitions, instructions

│

├── LICENSE

├── .gitignore

└── README.md


---

## 🧪 Analysis Workflow

1. **Data Import & Cleaning**  
   Load Excel data, inspect structure, and preprocess columns (e.g., categorical conversion, outlier handling).

2. **Descriptive Statistics**  
   Calculate means, medians, standard deviations, and distributions across treatment groups or timepoints.

3. **Statistical Testing**  
   Conduct hypothesis testing (e.g., t-tests, ANOVA, non-parametric tests) to compare product performance or user response metrics.

4. **Visualization**  
   Generate charts such as bar plots, boxplots, and line charts to support visual interpretation of results.

5. **Reporting**  
   Consolidate findings into tables and export into a DOCX report for delivery or publication.

---

## ▶️ How to Run

1. Install required packages:
   - For Python:
     ```bash
     pip install pandas matplotlib seaborn openpyxl
     ```
   - For R:
     ```r
     install.packages(c("tidyverse", "readxl", "ggplot2", "psych"))
     ```

2. Launch Jupyter:
   ```bash
   jupyter notebook

🙌 Acknowledgments
Data and structure anonymized for public release.
