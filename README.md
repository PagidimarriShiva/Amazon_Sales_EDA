# 📊 Amazon Sales Data Analysis - Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4+-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-red.svg)

## 📌 Project Overview

This project performs comprehensive **Exploratory Data Analysis (EDA)** on Amazon sales data to uncover business insights, identify sales trends, and provide actionable recommendations for business growth. The analysis covers multiple dimensions including regional performance, product analysis, sales channels, and temporal patterns.

### 🎯 Business Objectives

- Identify sales trends and patterns across different time periods
- Analyze regional and country-wise performance
- Evaluate product performance and profitability
- Compare sales channel effectiveness (Online vs Offline)
- Detect outliers and anomalies in sales data
- Provide data-driven business recommendations

---

## 📂 Dataset Information

**Source:** Amazon Sales Dataset  
**Records:** 10,000+ transactions  
**Time Period:** 2010-2017

### Features:
- **Region:** Geographic region (Europe, Asia, Sub-Saharan Africa, etc.)
- **Country:** Specific country
- **Item Type:** Product category (Office Supplies, Cosmetics, Household, etc.)
- **Sales Channel:** Online or Offline
- **Order Priority:** Low, Medium, High, Critical
- **Order Date:** Date of purchase
- **Ship Date:** Date of shipment
- **Units Sold:** Quantity sold
- **Unit Price:** Price per unit
- **Unit Cost:** Cost per unit
- **Total Revenue:** Total sales amount
- **Total Cost:** Total cost
- **Total Profit:** Profit earned

---

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualizations
- **Missingno** - Missing data visualization

---

## 📊 Analysis Performed

### 1. **Data Quality Assessment**
- Missing value analysis
- Duplicate detection
- Data type validation
- Outlier detection using IQR method

### 2. **Time Series Analysis**
- Monthly revenue trends
- Quarterly performance
- Seasonality patterns
- Day-of-week analysis

### 3. **Geographic Analysis**
- Regional revenue contribution
- Top 15 countries by revenue
- Regional + Channel cohort analysis

### 4. **Product Performance**
- Revenue by product type
- Profitability analysis
- Best and worst performing products

### 5. **Sales Channel Comparison**
- Online vs Offline performance
- Channel-wise profit margins
- Order distribution by channel

### 6. **Correlation Analysis**
- Relationship between numerical variables
- Profit margin drivers
- Delivery time impact

### 7. **Outlier Detection**
- Revenue outliers identification
- Statistical bounds calculation

---

## 🔑 Key Findings

### 📈 Financial Metrics
Total Revenue: $137,348,768.31
   Total Profit: $44,168,198.40
   Total Cost: $93,180,569.91
   Overall Profit Margin: 32.16%

### 🏆 Top Performers
- **Best Region:** [Sub-Saharan Africa] (39672031.43of total revenue)
- **Best Product:** [Cosmetics]  (36601509.60)
- **Best Channel:** [Offline] (79094809.20)
- **Peak Month:** [August] (mean-1.870317e+06)

### 💡 Business Insights
1. **Regional Concentration:** Top 3 regions contribute 60%+ of total revenue
2. **Product Mix:** 20% of products generate 80% of revenue (Pareto principle)
3. **Channel Performance:** [Offline] outperforms by 79094809.20
4. **Seasonality:** Strong seasonal patterns identified with peaks in [August]
5. **Delivery Performance:** Average delivery time of  1.911735e+06 day

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8 or higher
pip (Python package installer)
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/amazon-sales-eda.git
cd amazon-sales-eda
```

2. **Install required packages**
```bash
pip install -r requirements.txt
```

3. **Run the analysis**
```bash
python src/analysis.py
```

Or open the Jupyter notebook:
```bash
jupyter notebook notebooks/amazon_sales_eda.ipynb
```

---

## 📋 Requirements

Create a `requirements.txt` file:
```txt
pandas==1.5.3
numpy==1.24.3
matplotlib==3.7.1
seaborn==0.12.2
missingno==0.5.2
jupyter==1.0.0
```

---

## 📊 Sample Visualizations

### Monthly Revenue Trend
![Monthly Trend](visualizations/monthly_trend.png)

### Regional Performance
![Regional Performance](visualizations/regional_performance.png)

### Product Analysis
![Product Analysis](visualizations/product_analysis.png)

### Correlation Heatmap
![Correlation](visualizations/correlation_heatmap.png)

---

## 💡 Business Recommendations

Based on the analysis, here are key recommendations:

1. **Inventory Management**
   - Increase stock for top 10 products
   - Reduce inventory for low-performing items
   - Prepare for seasonal demand spikes

2. **Marketing Strategy**
   - Focus campaigns on top 3 regions
   - Promote high-margin products
   - Leverage best-performing sales channel

3. **Operational Efficiency**
   - Optimize delivery times (current avg: X days)
   - Streamline processes in high-volume regions
   - Improve supply chain efficiency

4. **Revenue Growth**
   - Expand successful products to new markets
   - Cross-sell complementary products
   - Target underperforming regions with tailored strategies

---

## 📈 Future Work

- [ ] Predictive modeling for sales forecasting
- [ ] Customer segmentation analysis
- [ ] Market basket analysis
- [ ] Time series forecasting using ARIMA/Prophet
- [ ] Interactive dashboard using Plotly/Dash
- [ ] A/B testing framework for marketing campaigns

---

## 👨‍💻 Author

**Shiva Pagidimarri**

- 📧 Email: ppagidimarrishiva@gmail.com
- 💼 LinkedIn: [linkedin.com/in/shiva-pagidimarri](https://linkedin.com/in/shiva-pagidimarri)
- 🔗 GitHub: [github.com/PagidimarriShiva](https://github.com/PagidimarriShiva)
- 🌐 Portfolio: [https://shiva-analytics-portfolio.lovable.app/projects]

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Dataset: Amazon Sales Dataset
- Inspiration: Real-world business analytics problems
- Tools: Python data science ecosystem

---

## 📞 Contact

For any questions or suggestions, feel free to reach out!

**Happy Analyzing! 📊✨**

---

## ⭐ If you found this project helpful, please give it a star!
