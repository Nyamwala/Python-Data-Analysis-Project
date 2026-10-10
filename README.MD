# 🌍 Global Alcohol Consumption & Socioeconomic Study

Welcome to the **Global Alcohol Consumption & Socioeconomic Study**, a multi-page data analytics project examining the relationships between annual alcohol consumption, economic wealth (GDP per capita), beverage pricing, geographic distance, and religious demographics across countries.

---

## 📂 Project Structure

The project is structured into a clean, reproducible analytics architecture:

```text
global-alcohol-study/
│
├── data/
│   └── dataset.csv                            # Raw global socioeconomic & alcohol dataset
│
├── notebooks/
│   ├── 01_Home.ipynb                          # Landing page, executive KPIs & distribution summaries
│   ├── 02_Analysis.ipynb                      # Exploratory Data Analysis (EDA), correlations & outliers
│   └── 03_Solutions.ipynb                     # Strategic risk tier segmentation, policy matrices & reporting
│
├── outputs/
│   └── global_alcohol_solutions_comprehensive_report.csv # Enriched exported data
│
├── README.md                                  # Project documentation (this file)
└── PROJECT_TEMPLATE.md                        # Master architectural blueprint & guidelines
```

---

## 📊 Analytical Pipeline & Notebook Workflow

The project is divided into three sequential Jupyter notebooks:

1. **`01_Home.ipynb` (Executive Overview & Baseline KPIs)**
   * Automated dataset loading and metadata validation.
   * High-level descriptive statistics for key metrics (`alcperpeson`, `gdppercapita`, `beveragepriceindex`).
   * Baseline distribution visualizations (histograms and boxplots).

2. **`02_Analysis.ipynb` (Exploratory Data Analysis & Deep Dives)**
   * Correlation matrix and heatmaps identifying socioeconomic linkages.
   * Ordinary Least Squares (OLS) regression plots analyzing wealth vs. consumption trends.
   * Outlier detection and thresholding using Interquartile Range (IQR) analysis.

3. **`03_Solutions.ipynb` (Strategic Frameworks & Risk Tiers)**
   * Benchmark analysis extracting top 5 highest and bottom 5 lowest consumers.
   * Strategic risk tier segmentation categorizing nations into:
     * `1. Low Risk (< 3L)`
     * `2. Moderate Risk (3L - 9L)`
     * `3. High Risk (> 9L)`
   * Demographic policy pivot tables comparing consumption and beverage pricing across religion factors.
   * Automated executive reporting exporting enriched data to CSV.

---

## ⚙️ Installation & Setup Instructions

### 1. Prerequisites
Ensure you have **Python 3.8+** installed on your system.

### 2. Clone or Download Repository
Navigate to your local project directory:
```bash
cd global-alcohol-study
```

### 3. Install Required Dependencies
Install the required data science and visualization packages via pip:
```bash
pip install pandas numpy matplotlib seaborn
```

### 4. Run the Jupyter Notebooks
Launch Jupyter Lab or Jupyter Notebook:
```bash
jupyter lab
```
Execute the notebooks in numerical order starting from `01_Home.ipynb` through `03_Solutions.ipynb`.

---

## 🚀 Key Insights & Policy Recommendations

* **Elasticity & Taxation:** High-risk consumer nations display distinct pricing thresholds, suggesting that progressive excise taxation on high-ABV products can effectively regulate consumption.
* **Preemptive Economic Growth Health Policies:** Positive correlations between GDP per capita and alcohol consumption highlight the need for developing nations to establish proactive public health frameworks.
* **Demographic-Tailored Outreach:** Variations across religious demographic factors indicate that community-partnered initiatives yield superior public health outcomes compared to blanket national mandates.

---

## 📝 License & Contributing
This project is open-source and available under the MIT License. Contributions, feedback, and pull requests are welcome!