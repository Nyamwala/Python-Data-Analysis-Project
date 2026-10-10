# 🌍 Global Alcohol Consumption & Socioeconomic Study: Project Blueprint

Welcome to the official project documentation and structural template for the **Multi-Page Analytics & Solutions Hub**. This document serves as the master blueprint for our data architecture, exploratory data analysis workflows, strategic risk-tier frameworks, and reproducible notebook pipelines.

---

## 📂 Project Directory Structure

```text
global-alcohol-study/
│
├── data/
│   └── dataset.csv                            # Raw global socioeconomic & alcohol dataset
│
├── notebooks/
│   ├── 01_Home.ipynb                          # Landing page, executive KPIs & distribution summaries
│   ├── 02_Analysis.ipynb                      # Deep EDA, correlation heatmaps & outlier detection
│   └── 03_Solutions.ipynb                     # Strategic risk tier segmentation, policy matrices & reporting
│
├── outputs/
│   └── global_alcohol_solutions_comprehensive_report.csv # Enriched exported data
│
├── README.md                                  # Project overview and installation instructions
└── PROJECT_TEMPLATE.md                        # Master architectural blueprint (this file)
```

---

## 📊 Notebook Specifications & Workflow

Our project is divided into three sequential, cohesive modules designed for clean execution:

### 1. `01_Home.ipynb` (Executive Overview & Baseline KPIs)
* **Objective:** Introduce stakeholders to the study's scope, metadata schema, and high-level health indicators.
* **Core Components:**
  * Automated data ingestion & missing value checks.
  * Summary statistics for consumption (`alcperpeson`), GDP per capita (`gdppercapita`), and beverage pricing (`beveragepriceindex`).
  * Baseline distribution histograms and boxplots.

### 2. `02_Analysis.ipynb` (Exploratory Data Analysis & Deep Dives)
* **Objective:** Uncover hidden statistical relationships and socioeconomic correlations.
* **Core Components:**
  * Multi-variable correlation matrices and heatmaps.
  * OLS regression plots examining the relationship between economic wealth and alcohol consumption.
  * Outlier identification using Interquartile Range (IQR) thresholding.

### 3. `03_Solutions.ipynb` (Strategic Frameworks & Risk Tiers)
* **Objective:** Translate statistical findings into actionable public health policies and risk management frameworks without complex machine learning.
* **Core Components:**
  * **Benchmark Analysis:** Automated extraction of top 5 highest and bottom 5 lowest consuming nations.
  * **Strategic Risk Tier Segmentation:** Categorization of countries into:
    * `1. Low Risk (< 3L)`
    * `2. Moderate Risk (3L - 9L)`
    * `3. High Risk (> 9L)`
  * **Demographic Policy Matrix:** Grouping metrics by religious demographic factors with side-by-side comparative visualizations.
  * **Automated Executive Reporting:** Exporting enriched datasets directly to CSV for stakeholder review.

---

## ⚙️ Execution & Setup Instructions

### Prerequisites
Ensure you have Python 3.8+ installed along with the core data science libraries:
```bash
pip install pandas numpy matplotlib seaborn
```

### Running the Notebooks
Launch Jupyter Lab or Jupyter Notebook from your root project directory:
```bash
jupyter lab
```
Execute the notebooks in numerical order (`01_Home.ipynb` $\rightarrow$ `02_Analysis.ipynb` $\rightarrow$ `03_Solutions.ipynb`).

---

## 📝 Governance & Contribution Guidelines
* **Code Style:** Follow standard PEP 8 naming conventions for Python variables and functions.
* **Visualizations:** All charts must include descriptive titles, labeled axes, gridlines, and clean font pairings (`DejaVu Sans`).
* **Documentation:** Every new analytical module must include a corresponding Markdown narrative cell explaining the business or policy rationale behind the code.