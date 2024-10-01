# RFM Analysis for Online Cosmetics Store

## Project Overview

This project focuses on analyzing sales data from an online cosmetics store, using Python's `pandas` library for Exploratory Data Analysis (EDA), data cleaning, and analysis. The project applies the RFM (Recency, Frequency, Monetary) model to classify customers into different segments. Visualization is achieved using the `pyecharts` library.

The dataset used in this project comes from a Chinese online store, offering valuable insights into customer purchasing behaviors in the cosmetics industry.

## Dataset

The dataset contains the following key fields:
- 订单编码 (Order ID)
- 订单日期 (Order Date)
- 客户编码 (Customer ID)
- 所在区域 (Area)
- 所在省份 (Province)
- 所在城市 (City)
- 商品编号 (commodyID)
- 订购数量 (saleAmount)
- 金额 (Amount)
- 商品名称 (Name)
- 商品小类 (Type1)
- 商品大类 (Type2)
- 销售单价 (commodyPrice)

## Key Technologies

- **Python**
- **pandas** for data analysis
- **numpy** for numerical operations
- **pyecharts** for data visualization
- **matplotlib** for additional visualizations (if needed)

## Workflow

1. **Data Loading and Cleaning**: Load the sales data, handle missing values, and remove duplicates.
2. **EDA (Exploratory Data Analysis)**: Analyze customer behaviors, such as monthly sales trends and product popularity.
3. **Visualization**: Use `pyecharts` to create interactive charts showing sales trends, customer spending habits, etc.
4. **RFM Model**:
   - **Recency**: Days since the last purchase.
   - **Frequency**: Number of transactions within a specified period.
   - **Monetary**: Total amount spent by the customer.
5. **Customer Segmentation**: Based on RFM scores, customers are classified into groups such as "Important Value Customer" and "General Growth Customer".

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

   Or install manually:

   ```bash
   pip install pandas numpy pyecharts
   ```

3. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   Execute the steps in `data analysis.ipynb` to perform the analysis and customer segmentation.

## Results

Using the RFM model, customers are segmented into various groups based on their purchasing behavior. This helps the business in identifying valuable customers and tailoring marketing strategies accordingly.

## Acknowledgment

The dataset used in this analysis is sourced from a Chinese online store, focusing on the cosmetics industry.
