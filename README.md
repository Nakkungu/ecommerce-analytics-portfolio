# 🛒 Brazilian E-Commerce Analytics Portfolio

## 📊 Comprehensive Data Analysis of Olist E-Commerce Dataset

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)](https://github.com/yourusername/ecommerce-analytics-portfolio)

> **Advanced analytics and visualization of Brazilian e-commerce data with seasonal trends analysis, customer insights, and business intelligence dashboards.**

---

## 🎯 Project Overview

This portfolio project demonstrates end-to-end data analytics capabilities using the **Brazilian E-Commerce Public Dataset by Olist**. The analysis provides actionable business insights through comprehensive exploratory data analysis, seasonal trend identification, and interactive dashboards.

### 🔍 Key Features

- **Seasonal Trends Analysis** - Deep dive into peak shopping periods and holiday patterns
- **Customer Behavior Analytics** - Geographic distribution and purchasing patterns
- **Interactive Visualizations** - Professional charts with Matplotlib, Seaborn, and Plotly
- **Statistical Testing** - ANOVA, t-tests, and trend analysis for data validation
- **Business Intelligence** - Executive-ready insights and recommendations
- **Dashboard Ready** - Prepared datasets for Power BI and Tableau integration

---

## 📁 Project Structure

```
ecommerce-analytics-portfolio/
├── README.md                           # Project documentation
├── requirements.txt                    # Python dependencies
├── .env.example                       # Environment variables template
├── .gitignore                         # Git ignore rules
├── data/
│   ├── raw/                           # Original dataset files
│   │   ├── olist_customers_dataset.csv
│   │   ├── olist_orders_dataset.csv
│   │   ├── olist_order_items_dataset.csv
│   │   └── ...other raw files
│   └── processed/                     # Cleaned and transformed data
│       ├── cleaned_customers.csv
│       ├── cleaned_orders.csv
│       └── master_dataset.csv
├── notebooks/                         # Jupyter notebooks
│   ├── 01_data_exploration.ipynb      # Initial data exploration
│   ├── 02_data_cleaning_python.ipynb  # Data cleaning (Python)
│   ├── 03_data_cleaning_R.ipynb       # Data cleaning (R)
│   ├── 04_exploratory_analysis.ipynb  # Comprehensive EDA
│   └── 05_dashboard_prep.ipynb        # Dashboard preparation
├── scripts/                           # Python utility scripts
│   ├── data_cleaning.py               # Data cleaning functions
│   ├── data_validation.py             # Data quality checks
│   └── utils.py                       # Utility functions
├── reports/                           # Analysis reports and exports
│   ├── seasonal_analysis/             # Seasonal trends analysis results
│   ├── data_quality_before.html       # Pre-cleaning quality report
│   ├── data_quality_after.html        # Post-cleaning quality report
│   └── cleaning_documentation.pdf     # Data cleaning documentation
└── dashboards/                        # Dashboard files and screenshots
    ├── power_bi/                      # Power BI files
    ├── tableau/                       # Tableau workbooks
    └── screenshots/                   # Dashboard screenshots
```

---

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook/JupyterLab
- Git

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/ecommerce-analytics-portfolio.git
   cd ecommerce-analytics-portfolio
   ```

2. **Create and activate virtual environment** (recommended)

   ```bash
   python -m venv ecommerce_env
   source ecommerce_env/bin/activate  # On Windows: ecommerce_env\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**

   ```bash
   cp .env.example .env
   # Edit .env file with your configuration (optional for basic analysis)
   ```

5. **Launch Jupyter**

   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```

6. **Start with the analysis**
   - Open `notebooks/04_exploratory_analysis.ipynb` for comprehensive analysis
   - Or start from `notebooks/01_data_exploration.ipynb` for the full journey

---

## 📈 Analysis Phases

### ✅ Phase 1: Data Understanding & Cleaning

- **Data Exploration** - Initial dataset examination and profiling
- **Quality Assessment** - Missing values, outliers, and data integrity checks
- **Data Cleaning** - Standardization, transformation, and preparation
- **Validation** - Post-cleaning quality verification

### 🔥 Phase 2: Seasonal Trends & Peak Shopping Analysis (CURRENT)

- **Seasonal Patterns** - Brazilian seasonal shopping behavior (Summer, Autumn, Winter, Spring)
- **Peak Period Identification** - Statistical identification of high-demand periods
- **Holiday Impact Analysis** - Christmas, Black Friday, Mother's Day, and other Brazilian holidays
- **Intraday Patterns** - Hourly shopping trends and business hour analysis
- **Statistical Validation** - ANOVA tests, t-tests, and trend significance testing

### 🎯 Phase 3: Dashboard Development (UPCOMING)

- **Power BI Dashboards** - Executive and operational dashboards
- **Tableau Visualizations** - Interactive business intelligence reports
- **Streamlit Web App** - Self-service analytics platform

### 📊 Phase 4: Advanced Analytics (PLANNED)

- **Customer Segmentation** - RFM analysis and clustering
- **Predictive Modeling** - Demand forecasting and trend prediction
- **Geographic Analysis** - Regional performance and logistics optimization

---

## 🔍 Key Insights Discovered

### 🌍 Seasonal Trends

- 1. 🌍 Winter is the peak shopping season (30.7% of annual orders)
- 2. 📊 August is the peak shopping month (10.9% of annual orders)
- 3. 📉 September is the slowest month (4.3% of annual orders)

### ⏰ Shopping Patterns

- • Total Orders Analyzed: 99,441
- • Analysis Period: 773 days
- • Average Daily Orders: 129
- • Peak Single Day: 1,176 orders (2017-11-24 00:00:00)
- • Peak Days Identified: 32 days (95th percentile)

### 📊 Statistical Findings

- Trend Analysis (Linear Regression):
- R-squared: 0.2834
- Daily trend: +0.2675 orders per day
- Interpretation: Growing trend over time

---

## 🛠️ Technologies Used

### **Data Analysis & Processing**

- **Python 3.8+** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **SciPy** - Statistical analysis and hypothesis testing

### **Visualization & Reporting**

- **Matplotlib** - Static plotting and publication-quality charts
- **Seaborn** - Statistical data visualization
- **Plotly** - Interactive visualizations and dashboards

### **Development Environment**

- **Jupyter Lab/Notebook** - Interactive development
- **Git** - Version control with professional branching strategy
- **Virtual Environments** - Isolated dependency management

### **Business Intelligence**

- **Power BI** - Enterprise dashboards (upcoming)
- **Tableau** - Advanced visualizations (upcoming)
- **Streamlit** - Web application framework (upcoming)

---

## 📊 Dataset Information

### **Source**

- **Dataset**: Brazilian E-Commerce Public Dataset by Olist
- **Platform**: Kaggle
- **Size**: 100,000+ orders from 2016-2018
- **Geography**: Brazil (all states and major cities)

### **Key Tables**

- **Orders** (~100K records) - Order details, status, timestamps
- **Order Items** (~112K records) - Product details, pricing, shipping
- **Customers** (~99K records) - Customer location and demographics
- **Products** (~32K records) - Product categories, dimensions, descriptions
- **Sellers** (~3K records) - Seller information and location
- **Payments** (~103K records) - Payment methods, values, installments
- **Reviews** (~99K records) - Customer ratings and feedback

---

## 💡 Business Impact & Recommendations

### **Strategic Insights**

1. **Revenue Optimization** - Target [peak month] for maximum marketing ROI
2. **Inventory Planning** - Prepare for 297+ orders on identified peak days
3. **Customer Experience** - Optimize staffing for [peak hour] traffic
4. **Cost Management** - Implement dynamic strategies during low seasons

### **Operational Recommendations**

- **Marketing**: Focus campaigns on high-converting seasonal periods
- **Logistics**: Scale fulfillment capacity for 95th percentile demand ([X] orders/day)
- **Customer Service**: Staff optimization for peak hours and holiday periods
- **Pricing Strategy**: Implement demand-based pricing during peak periods

---

## 🎯 Portfolio Highlights

### **Technical Skills Demonstrated**

- ✅ **Statistical Analysis** - Hypothesis testing, ANOVA, trend analysis
- ✅ **Data Visualization** - Professional charts and interactive dashboards
- ✅ **Business Intelligence** - Executive-ready insights and recommendations
- ✅ **Project Management** - Structured phases with clear deliverables
- ✅ **Code Quality** - Clean, documented, reproducible analysis

### **Business Acumen**

- ✅ **Domain Knowledge** - E-commerce metrics and KPIs
- ✅ **Strategic Thinking** - Actionable business recommendations
- ✅ **Stakeholder Communication** - Clear, executive-level insights
- ✅ **Problem Solving** - Data-driven decision making

---

## 📈 Usage Examples

### **Quick Analysis**

```python
import pandas as pd
import matplotlib.pyplot as plt
from scripts.utils import load_processed_data, create_seasonal_analysis

# Load processed data
datasets = load_processed_data()

# Generate seasonal insights
insights = create_seasonal_analysis(datasets['orders'])

# Create visualizations
plt.figure(figsize=(15, 10))
# ... visualization code
```

### **Interactive Dashboard**

```python
import plotly.express as px
from scripts.dashboard_utils import create_interactive_timeline

# Create interactive seasonal timeline
fig = create_interactive_timeline(orders_data)
fig.show()
```

---

## 🤝 Contributing

This is a portfolio project, but suggestions and feedback are welcome!

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/enhancement`)
3. **Commit changes** (`git commit -m 'Add enhancement'`)
4. **Push to branch** (`git push origin feature/enhancement`)
5. **Open a Pull Request**

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact

**Your Name**

- 📧 Email: angella.nakkungu@outlook.com
- 💼 LinkedIn: [linkedin.com/in/angella-nakkungu](https://linkedin.com/in/yourprofile)
- 🐙 GitHub: [@Nakkungu](https://github.com/Nakkungu)
- 📊 Portfolio: [Nakkungu](https://sites.google.com/u/0/d/174MUiqhvNuuaXU5D7CMMlTX6g-laImLz/preview)

---

## 🙏 Acknowledgments

- **Olist** - For providing the comprehensive Brazilian e-commerce dataset
- **Kaggle** - For hosting and maintaining the dataset platform
- **Python Community** - For the amazing data science ecosystem
- **Open Source Contributors** - For the tools and libraries that made this analysis possible

---

## 🔄 Project Status & Roadmap

### **Current Status: Phase 2 Complete** ✅

- [x] Data exploration and cleaning
- [x] Seasonal trends analysis
- [x] Peak shopping period identification
- [x] Statistical validation
- [x] Business insights and recommendations

### **Next Steps: Phase 3** 🎯

- [ ] Power BI dashboard development
- [ ] Tableau visualization creation
- [ ] Streamlit web application
- [ ] Interactive user interface

### **Future Enhancements: Phase 4** 🚀

- [ ] Customer lifetime value analysis
- [ ] Predictive demand forecasting
- [ ] Machine learning models
- [ ] Real-time analytics pipeline

---

**⭐ If you find this project helpful, please consider giving it a star!**

---

_Last Updated: [08.09.2025]_
_Version: 2.0 - Seasonal Analysis Complete_
