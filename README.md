# Karnataka District Development Index (DDI)
## A Data-Driven ML Analysis of 31 Districts

![Python](https://img.shields.io/badge/Python-3.12-blue)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![ML](https://img.shields.io/badge/Machine-Learning-green)
![SQL](https://img.shields.io/badge/SQL-SQLite-orange)

---

## 📌 Project Overview
This project presents a comprehensive data-driven 
analysis of socioeconomic development across all 
31 districts of Karnataka using 7 government 
datasets from 2024-26.

A composite District Development Index (DDI) was 
constructed and Machine Learning models were applied 
to predict and classify district development levels.

**Author:** Rohan Shetty  
**Qualification:** MSc Business Analytics  
**Date:** September 2026  

---


## 🎯 Research Objectives
1. Analyze socioeconomic indicators across 31 Karnataka districts
2. Build a composite District Development Index
3. Apply ML models to predict development levels

---

## 🔑 Key Findings
- 📊 Bengaluru Urban scores **79.79** vs Kalaburagi **9.82** — 70 point gap
- 📊 **65% of Karnataka districts** are Underdeveloped
- 📊 Coastal Karnataka DDI (63.24) is **2x** North Karnataka (27.05)
- 📊 Per Capita Income drives **60.6%** of development variation
- 📊 Education improvement gives **2x more impact** than income growth
- 📊 All 31 districts declined in PUC pass rate in 2025

---

## 🛠 Tech Stack
| Tool | Purpose |
|------|---------|
| Python 3.12 | Data cleaning, EDA, ML |
| Pandas, NumPy | Data manipulation |
| Scikit-learn | K-Means, Random Forest |
| Statsmodels | OLS Regression |
| Matplotlib, Seaborn | Visualizations |
| SQLite3 | Database |
| Power BI | Interactive Dashboard |
| Jupyter Notebook | Development |

---

## 📂 Datasets Used
| Dataset | Source | Year |
|---------|--------|------|
| GDDP and Per Capita Income | data.opencity.in | 2025-26 |
| MSME Industries and Employment | data.opencity.in | 2025 |
| Housing Completed | data.opencity.in | 2025-26 |
| Yuvanidhi Scheme | data.opencity.in | 2025 |
| eShram Portal | data.opencity.in | 2025 |
| SSLC Pass Percentage | data.opencity.in | 2024-25 |
| PUC Pass Percentage | data.opencity.in | 2024-25 |

---

## 🤖 ML Models
| Model | Type | Result |
|-------|------|--------|
| K-Means Clustering | Unsupervised | 3 tiers identified |
| Random Forest Regression | Supervised | R²=0.9826 |
| Random Forest Classification | Supervised | 100% accuracy |
| OLS Regression | Statistical | All p < 0.001 |

---

## 📊 DDI Rankings

**Top 5 Most Developed:**
| Rank | District | DDI Score |
|------|----------|-----------|
| 1 | Bengaluru Urban | 79.79 |
| 2 | Dakshina Kannada | 75.23 |
| 3 | Udupi | 69.80 |
| 4 | Kodagu | 54.77 |
| 5 | Chikkamagaluru | 54.40 |

**Bottom 5 Least Developed:**
| Rank | District | DDI Score |
|------|----------|-----------|
| 27 | Bidar | 25.92 |
| 28 | Belagavi | 25.83 |
| 29 | Raichur | 19.03 |
| 30 | Yadagiri | 15.55 |
| 31 | Kalaburagi | 9.82 |

## 📁 Repository Structure
├── Karnataka_DDI_Final.ipynb — Main Python notebook
├── master_dataset_final.csv — Final clean dataset
├── karnataka_powerbi.xlsx — Power BI data file
├── Karnataka_DDI_Dashboard.pbix — Power BI dashboard
├── karnataka_development.db — SQL database
├── Karnataka_DDI_Report.pdf — Research report
├── data/ — Raw government datasets
└── visualizations/ — All 13 charts

---

## 🚀 How to Run
1. Clone the repository
```bash
git clone https://github.com/Rohan5205/Karnataka-District-Development-Index.git
```

2. Install required libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels openpyxl
```

3. Open notebook
```bash
jupyter notebook Karnataka_DDI_Final.ipynb
```

4. Run all cells in order

---

## 📬 Contact
**Rohan Shetty**  
📧 shettyrohan890@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/rohan2134/)

---

*© 2026 Rohan Shetty | MSc Business Analytics*  
*Data Source: Karnataka Economic Survey 2025-26 | data.opencity.in*
