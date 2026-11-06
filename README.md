# 🚗 Car Sales Analysis

### Product & Sales Performance Analysis | Python · Power BI

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-4B0082)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

An end-to-end car sales analytics project combining **Python-based exploratory data analysis** with an **interactive Power BI dashboard** to evaluate sales performance, product mix, brand and model performance, dealer and regional contribution, and pricing patterns.


![Dashboard Overview](powerbi/screenshots/overview.png)

---

## 📌 Table of Contents
- [Business Problem](#business-problem)
- [Project Objectives](#project-objectives)
- [Dataset](#dataset)
- [Key KPIs](#key-kpis)
- [Analysis Performed](#analysis-performed)
- [Dashboard](#dashboard)
- [Key Insights](#key-insights)
- [Business Recommendations](#business-recommendations)
- [Tools & Technologies](#tools--technologies)
- [Repository Structure](#repository-structure)
- [How to Reproduce](#how-to-reproduce)
- [Author](#author)

---

## Business Problem

The business needs to understand which products, brands, regions, and price segments contribute most to sales performance in order to support better commercial and product-focused decisions.

## Project Objectives

- Evaluate sales performance over time.
- Identify high-performing brands and individual car models.
- Compare dealer and regional sales performance.
- Analyze vehicle characteristics and product mix.
- Understand how different price segments contribute to revenue and unit volume.
- Present the findings through an interactive Power BI dashboard.

## Dataset

The dataset contains **23,906 car sales transactions** covering **2022–2023**. Each row represents one transaction and includes:

| Group | Fields |
|---|---|
| Transaction | Transaction date, selling price |
| Customer | Customer attributes |
| Dealer | Dealer information, dealer region |
| Vehicle | Company, model, engine, transmission, body style, color |

> The raw dataset is not included in this repository. See [`data/README.md`](data/README.md) for dataset and redistribution notes.

## Key KPIs

| KPI | Value |
|---|---:|
| Total Sales | $671.5M |
| Cars Sold | 23.9K |
| Average Selling Price | $28.1K |
| 2023 Sales Growth | 23.6% |

## Analysis Performed

### 🐍 Python (Jupyter Notebook)
- Data inspection and quality assessment
- Data cleaning and standardization
- Missing-value handling
- Numerical validation and outlier assessment
- Time-based sales analysis
- Company and model performance
- Dealer and regional analysis
- Vehicle characteristic analysis
- Price-segment analysis
- Business insights and recommendations

### 📊 Power BI
- Sales KPI overview
- Monthly sales trends
- Company performance
- Regional sales performance
- Body-style analysis
- Detailed transaction view
- Interactive filtering

## Dashboard

### Overview
![Overview](powerbi/screenshots/overview.png)

### Transaction Details
![Details](powerbi/screenshots/details.png)

## Key Insights

1. **Sales grew 23.6% in 2023**, while cars sold grew 24.6%. Average selling price declined by less than 1%, so growth was **primarily volume-driven**.
2. **Chevrolet recorded the highest total sales**, approximately $47.7M.
3. **Austin was the strongest region**, with approximately $117.2M in sales.
4. **The $25K–$50K price segment generated the largest share of revenue**, about 44% of total sales.
5. **A higher average selling price does not necessarily mean higher total sales**, which highlights the difference between unit volume and price mix.

> These findings are descriptive and reflect patterns in the analyzed dataset; they do not establish causal relationships.

## Business Recommendations

- Prioritize commercial focus and availability for high-performing brands and models, subject to inventory validation.
- Give focused attention to the $25K–$50K price segment when planning product and marketing activities.
- Benchmark high-performing regions to identify practices that could be replicated elsewhere.
- Monitor unit growth alongside average selling price so growth does not come with an undesirable shift in price mix.

## Tools & Technologies

| Category | Tools |
|---|---|
| Analysis | Python: Pandas, NumPy, Matplotlib, Seaborn (Jupyter Notebook) |
| BI & Reporting | Power BI, DAX |
| Version control | Git, GitHub |

## Repository Structure

```
Car-Sales-Analysis/
├── README.md
├── python/
│   └── Car_Sales_Analysis.ipynb
├── powerbi/
│   ├── Car_Sales_Dashboard.pbix
│   └── screenshots/
│       ├── overview.png
│       └── details.png
├── data/
│   └── README.md
└── .gitignore
```

## How to Reproduce

1. Obtain the dataset as described in [`data/README.md`](data/README.md) and place the file in the `data/` folder.
2. Install the dependencies: `pip install pandas numpy matplotlib seaborn jupyter`
3. Open `python/Car_Sales_Analysis.ipynb` and run all cells.
4. Open `powerbi/Car_Sales_Dashboard.pbix` in Power BI Desktop and update the data source path if prompted.

## Author

**Abdelrahman Mohamed** · Data Analyst
[LinkedIn](https://www.linkedin.com/in/abdelrahman-abodeep) · [GitHub](https://github.com/Apodeep) · abdulrhmanapodeep@gmail.com
