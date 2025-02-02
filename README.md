# A-B-Testing-Marketing-Campaign
This project evaluates the effectiveness of different marketing promotions on sales using **A/B testing** techniques. The goal is to determine which promotion drives the highest sales and optimize marketing strategies accordingly.

## 🎯 Objectives
- Compare the sales performance of different promotions.
- Identify statistically significant differences in sales using **Kruskal-Wallis tests**.
- Evaluate underperforming locations and market segments for better targeting.
- Provide actionable insights for future marketing campaign optimizations.

## 📊 Dataset Description
The dataset includes:
- **Promotion Type**: Categorical variable representing different promotional campaigns.
- **Sales in Thousands**: Numeric variable indicating total sales per campaign.
- **Market Size**: Classification of regions (Small, Medium, Large).
- **Location ID**: Unique identifier for each store location.
- **Week**: Time variable to track weekly trends.

## 🛠 Methodology
1. **Data Cleaning & Preprocessing**
   - Handling missing values, removing outliers using **IQR method**.
   - Data transformations for consistency.

2. **Exploratory Data Analysis (EDA)**
   - Sales distribution across promotions and market sizes.
   - Identifying sales trends over time.
   - Highlighting high and low-performing locations.

3. **A/B Testing & Statistical Analysis**
   - **Kruskal-Wallis test** to determine if sales differ significantly across promotions.
   - **Dunn’s post-hoc test** to identify which promotions perform best.
   - **Effect size calculation (Eta-Squared)** to measure impact.

4. **Visualization & Insights**
   - Box plots and heatmaps to show sales distribution.
   - Line charts to observe weekly trends.
   - Bar plots to highlight underperforming locations.

## 🔍 Key Findings
- Promotion **X** performed significantly better, increasing sales by **Y%**.
- Promotion **Z** underperformed, especially in **Medium-sized markets**.
- Certain locations consistently had low sales, indicating potential areas for improvement.

## 🚀 Conclusion & Recommendations
- Invest more in **high-performing promotions** while modifying or discontinuing weaker ones.
- Improve targeting in **underperforming locations** with tailored marketing efforts.
- Consider seasonal variations and test new strategies with further **A/B experiments**.

## 📌 Technologies Used
- **Python** (NumPy, Pandas, Matplotlib, Seaborn, SciPy)
- **Jupyter Notebook**
- **Statistical Analysis (Kruskal-Wallis, Dunn’s Test)**
- **Data Visualization (Seaborn, Matplotlib)**
- **GitHub for Version Control**

## ✨ Future Work
- Extend A/B testing to additional **marketing variables** like discount levels, ad types, and messaging styles.
- Incorporate **time series forecasting** to predict future sales trends.
- Expand dataset with external factors (economic indicators, seasonality effects).

## 💡 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Bsetia1/A-B-Testing-Marketing-Campaign.git
