#  PUMA Sales Analysis and Visualization 📊

This project provides an interactive data visualization dashboard to explore PUMA's sales and profit performance across different dimensions such as time, region, product, and sales methods.

## 📁 Dataset
The dataset is sourced from an Excel file and contains structured data on:
- Invoice Dates
- Sales Method
- Region, State, City
- Product
- Total Sales
- Operating Profit

## 📈 Visualizations Included

1. **Line Chart** – Trends of Monthly Total Sales & Operating Profit  
2. **Grouped Bar Chart** – Sales vs Profit by Sales Method  
3. **Pie Chart** – Product-wise Sales Distribution  
4. **Heatmap** – Product-wise Sales across States  
5. **TreeMap** – Hierarchical Sales Breakdown (Region → State → City)  
6. **Race Bar Chart** – Animated Sales Race by City over Time  
7. **Horizontal Bar Chart** – Top 10 Cities by Operating Profit

All charts are built using **Plotly Express** and **Plotly Graph Objects** for interactivity and beauty 🎨

## 🛠 Tools & Libraries
- Python 🐍
- Pandas
- Plotly
- Seaborn
- Matplotlib
- Jupyter / VS Code (Run & Test Environment)

## 💻 How to Run
1. Clone the repo  
2. Open the `.ipynb` file in VS Code or Jupyter  
3. Install dependencies (if needed):
   ```bash
   pip install pandas plotly matplotlib seaborn openpyxl
