# 🎬 IMDb Movie Analysis & Rating Prediction
IMDb Movie Data Analysis, Rating Prediction using EDA, Statistical Testing, and Linear Regression

An end-to-end Data Science project involving Exploratory Data Analysis (EDA), statistical hypothesis testing, and Linear Regression modeling to analyze and predict IMDb movie ratings.

---

## 🚀 Project Overview

The goal of this project is to:
- Understand trends in movie ratings
- Analyze the relationship between runtime and ratings
- Perform hypothesis testing using statistical methods
- Build a predictive model using Linear Regression


## 📊 Exploratory Data Analysis (EDA)

Performed multiple visualizations to explore data patterns and extract insights:
- Histogram (Rating distribution)
- Line Chart (Average rating over years)
- Pie Chart (Movies by era)
- Box Plot (Runtime distribution)
- Scatter Plot (Runtime vs Rating)
- Heatmap (Correlation matrix)
- Pairplot (Feature relationships)
- KDE Plot (Density distribution)
- Bubble Plot (Enhanced visualization)


## 📈 Statistical Analysis

- Applied **Pearson Correlation**
- Tested hypothesis:
  - H₀: Runtime does not affect Rating
  - H₁: Runtime affects Rating
- Used p-value to determine statistical significance


## 🤖 Machine Learning Model

- Model: Linear Regression
- Input Feature: Runtime (minutes)
- Target Variable: Movie Rating


### 📌 Model Performance
- R² Score: 0.073
- Mean Absolute Error (MAE): 0.70
- The low R² score indicates that runtime alone has limited predictive power for movie ratings. However, the MAE suggests that predictions are reasonably close, with an average error of around 0.7 rating points.

This highlights that movie ratings are influenced by multiple factors such as genre, cast, and storyline, which are not included in this model.

## 📌 Key Insights

- Movie ratings show a relatively stable trend over the years  
- Runtime has a weak correlation with ratings  
- Most movies fall within a specific rating range (as seen in distribution plots)  
- Correlation between features is generally weak to moderate

## 🔗 Future Improvements

- Include additional features such as genre, actors, and budget  
- Use advanced models like Random Forest and XGBoost  
- Perform feature engineering for better predictions  
- Deploy the model as a web application  


## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## 🙌 Author
Aniketh  
Aspiring Data Scientist | Machine Learning Enthusiast
