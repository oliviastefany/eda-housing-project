# eda-housing-project

## 📌 Project Description
The main objective of this case study is to apply EDA techniques using both 1D and 2D visualizations to gain insights and identify patterns within the housing price data.


## 🗂️ Dataset

- Dataset: `train_house.csv`  
- Number of records: 1460 rows × 80 columns
  

## 🔧 Project Steps

### Data Preparation
- Import necessary libraries (`pandas`, `matplotlib`, `seaborn`, etc.)
- Load the dataset
- Drop NaN values
- Separate numerical and categorical features for visualization

### 1D Visualization
- Bar charts for categorical variables:
  - `Utilities`
  - `HouseStyle`
  - `ExterQual`
- Histograms for numerical variables:
  - `SalePrice`
  - `GrLivArea`
  - `PoolArea`
- Apply log-10 transformation to numerical variables to analyze distributions more clearly

### 2D Visualization
- Scatter plots for relationships between variables:
  - `GrLivArea` vs `SalePrice`
  - `GarageArea` vs `SalePrice`
- Analyze correlations between key variables



## 📊 Findings & Insights

- `SalePrice` shows a right-skewed distribution, meaning most homes are priced below the mean.
- Scatter plots show a positive correlation between `GrLivArea` and `SalePrice`, as well as between `GarageArea` and `SalePrice`.
> **Insight:** Homes with one or two finished floors generally offer moderate to good quality and a good balance between cost and value. These types of homes are more affordable to build and tend to be more attractive to buyers, making them popular and profitable choices.



## ✅ Conclusion
EDA reveals key patterns in housing data. Factors such as `GrLivArea` (above-ground living area) and `GarageArea` have a strong correlation with house prices. These insights can support future predictive modeling or inform real estate business strategies.


## 📎 Libraries and Packages : Pandas, Numpy, Matplotlib, Seaborn, etc.


