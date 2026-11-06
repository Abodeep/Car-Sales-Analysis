# Car Sales Analysis

## Product & Sales Performance Analysis

An end-to-end car sales analytics project combining **Python-based exploratory data analysis** with an **interactive Power BI dashboard** to evaluate sales performance, product mix, brand and model performance, dealer and regional contribution, and pricing patterns.

---

## Dashboard
 ![Overview](powerbi/screenshots/overview.png)
 ![Details](powerbi/screenshots/details.png)

---

## Business Problem

The business needs to understand which products, brands, regions, and price segments contribute most to sales performance in order to support better commercial and product-focused decisions.

---

## Project Objectives

- Evaluate sales performance over time.
- Identify high-performing brands and individual car models.
- Compare dealer and regional sales performance.
- Analyze vehicle characteristics and product mix.
- Understand how different price segments contribute to revenue and unit volume.
- Present the findings through an interactive Power BI dashboard.

---

## Dataset

The dataset contains **23,906 car sales transactions** covering **2022–2023**.

Each row represents one car sales transaction and includes information about:

- Transaction date
- Customer attributes
- Dealer information
- Vehicle company and model
- Engine and transmission
- Body style and color
- Selling price
- Dealer region

The raw dataset is not included in this repository. Please refer to `data/README.md` for dataset and redistribution notes.

---

## Key KPIs

| KPI | Value |
|---|---:|
| Total Sales | $671.5M |
| Cars Sold | 23.9K |
| Average Selling Price | $28.1K |
| 2023 Sales Growth | 23.6% |

---

## Analysis Performed

### Python

The Python analysis includes:

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

### Power BI

The Power BI dashboard provides:

- Sales KPI overview
- Monthly sales trends
- Company performance
- Regional sales performance
- Body-style analysis
- Detailed transaction view
- Interactive filtering

---

## Key Insights

1. **Sales increased by 23.6% in 2023**, while cars sold increased by 24.6%. Average selling price declined by less than 1%, indicating that growth was primarily volume-driven.

2. **Chevrolet recorded the highest total sales**, generating approximately $47.7M.

3. **Austin was the strongest region**, generating approximately $117.2M in sales.

4. **The $25K–$50K price segment generated the largest share of revenue**, contributing approximately 44% of total sales.

5. **Higher average selling price does not necessarily translate into higher total sales**, highlighting the difference between unit volume and price mix.

---

## Business Recommendations

- Prioritize commercial focus and availability for high-performing brands and models, subject to inventory validation.
- Give focused attention to the $25K–$50K price segment when planning product and marketing activities.
- Benchmark high-performing regions to identify practices that could potentially be replicated elsewhere.
- Continue monitoring unit growth alongside average selling price to ensure growth does not come with an undesirable change in price mix.

---

## Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Power BI**
- **DAX**
- **GitHub**

---

## Repository Structure

```text
Car-Sales-Analysis/
│
├── README.md
│
├── python/
│   └── Car_Sales_Analysis.ipynb
│
├── powerbi/
│   ├── Car_Sales_Dashboard.pbix
│   └── screenshots/
│       ├── overview.png
│       └── details.png
│
├── data/
│   └── README.md
│
└── .gitignore
