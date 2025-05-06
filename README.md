# 📊 E-Commerce Sales Data Analysis

## 🔍 Project Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** on an e-commerce sales dataset. The goal is to uncover meaningful patterns in customer behavior, product performance, and sales trends to support data-driven business decisions in the e-commerce domain.

---

## 🎯 Objectives
- Analyze overall sales performance and revenue trends.
- Identify high-performing products and categories.
- Understand customer purchase behavior and time-based patterns.
- Visualize geographic distribution of orders (if applicable).

---

## 🧰 Libraries Used
- `pandas` – Data handling and manipulation.
- `numpy` – Numerical computations.
- `matplotlib` – Basic plotting and visualizations.
- `seaborn` – Advanced data visualization.
- `plotly` *(optional)* – Interactive plots.
- `datetime` – Date and time operations.
- `warnings` – To manage warning messages.

---

## 🧪 Methodology

### 1. Data Loading & Cleaning
- Imported dataset using `pandas`.
- Checked for and handled null values.
- Removed duplicates and standardized date formats.
- Converted necessary columns to `datetime` for time-based analysis.

### 2. Feature Engineering
- Created new columns such as:
  - `Month`, `Day`, `Hour` (from order date).
  - `Sales` = `Quantity` × `Unit Price`.

### 3. Descriptive Analysis
- Analyzed total sales, average order value, top selling items.
- Grouped data by product, category, time, and region.

### 4. Visualizations
- **Bar charts** for top products/categories.
- **Line charts** for daily and monthly revenue.
- **Heatmaps** for time-of-day and day-of-week purchase activity.
- **Pie charts** for categorical distribution.
- **Geo visualizations** (if location data was available).

---

## 📈 Key Insights
- Highest sales occurred in [insert top months or seasons].
- Top 3 selling products: [insert products if known].
- Peak order times were around [insert time range].
- Certain categories contributed disproportionately to revenue.

---

## 📂 Folder Structure
ecommerce-sales-analysis/
├ e commerce sales.ipynb # Jupyter Notebook with all analysis steps
├── dataset/ # Raw or processed dataset (optional)
├── images/ # Graphs and charts (if saved)
└── README.md # Project documentation
---

## ✅ Future Enhancements
- Create a dashboard using Streamlit or Tableau.
- Build predictive models to forecast future sales.
- Perform market basket analysis and customer segmentation.

---

## 🙌 Acknowledgments
Thanks to the dataset source and Python open-source community for powerful data analysis tools.

---

## 📌 Author
**[Sourabh Sharma]**  
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/tgsaurabhs) or check out more projects on [GitHub](https://github.com/tgsaurabhs).

