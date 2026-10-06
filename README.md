# -Online-Retail-Dataset-UCI-Machine-Learning-Repository-
This project focuses on analyzing the Online Retail Dataset (UCI Machine Learning Repository) and building predictive models to extract valuable business insights.

# Online Retail Data Analysis: RFM, Forecasting & Recommendations

## 📌 Overview
This project leverages the **Online Retail Dataset** from the UCI Machine Learning Repository to extract actionable business intelligence. The notebook (`UCI Machine Learning Repository-RFM_Sales_Recommendation_Analysis.ipynb`) walks through an end-to-end data science workflow, focusing on customer segmentation, time-series sales forecasting, and building a product recommendation engine.

## 🚀 Key Features & Sections
1. **Data Cleaning & Preprocessing:** 
   - Handling missing values, removing duplicates, and formatting data for analysis.
2. **Customer Segmentation (RFM Analysis):** 
   - Calculating Recency, Frequency, and Monetary (RFM) scores.
   - Clustering customers using **K-Means** (evaluated via the Elbow Method) and **Hierarchical Clustering** (visualized with Dendrograms).
3. **Sales Trend Analysis & Forecasting:** 
   - Visualizing daily sales trends with 7-day rolling averages and seasonal decomposition.
   - Forecasting future sales using time-series models like **ARIMA**, **Facebook Prophet**, and **LSTM**.
4. **Product Recommendation System:** 
   - **Collaborative Filtering:** Finding similar customers using Cosine Similarity.
   - **Market Basket Analysis:** Identifying frequently bought-together items using the **FP-Growth** and **Apriori** algorithms (Support, Confidence, and Lift).
5. **Business Insights:** 
   - Actionable marketing strategies tailored to distinct customer segments (e.g., rewarding loyalists vs. re-engaging inactive users).

## 🛠️ Tech Stack
* **Languages:** Python
* **Data Manipulation:** `pandas`, `numpy`, `dask`
* **Machine Learning & Stats:** `scikit-learn`, `scipy`, `statsmodels`, `mlxtend`
* **Visualization:** `matplotlib`, `seaborn`

## 📊 How to Run
1. Ensure you have the [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail) downloaded as `Online Retail.xlsx`.
2. Install the required dependencies: `pip install pandas numpy scikit-learn statsmodels mlxtend matplotlib seaborn openpyxl`
3. Run the Jupyter Notebook cell-by-cell.
