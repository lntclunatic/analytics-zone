# Analytics Zone

Welcome to **Analytics Zone**! :)

This repository is a collection of small-scale data analytics projects and experiments.  
Think of it as my personal playground to explore datasets, test methods, and share insights.  

---

## Projects

### 1. Solar Energy Data Analysis
- **Focus:** Exploring the relationship between weather conditions and solar panel electricity output.  
- **Highlights:**

  ✅ Descriptive statistics of irradiance, temperature, humidity, and solar output.

  ✅ Handling missing values and outliers.
  
  ✅ Correlation analysis and interpretation.
- **Result:** Irradiance has the strongest positive correlation with solar output, while humidity shows a weak negative effect.

### 2. Solar Energy Regression Analysis
- **Focus:** Building regression models to predict solar panel electricity output.  
- **Methods:**
  
  ✅ Simple Linear Regression (Irradiance → Solar Output) → R² = 0.659 (significant)  
  ✅ Linear Regression (Day Number → Solar Output) → R² ≈ 0.001 (not significant)  
  ✅ Multiple Linear Regression (Irradiance, Temperature, Humidity → Solar Output) → R² = 0.660  
- **Evaluation:**
  
  ✅ MAE  : 0.1421  
  ✅ RMSE : 0.1731  
  ✅ MAPE : 16.43%  
- **Insight:**
  
  ✅ Irradiance is the most significant predictor of solar output.  
  ✅ Day Number has almost no effect.  
  ✅ The multivariate model slightly improves accuracy compared to the simple model.

  ### 3. Solar Energy Interactive Regression Dashboard
- **Focus:** Extending regression analysis with an interactive dashboard.  
- **Methods:**

  ✅ Multiple Linear Regression (Irradiance, Temperature, Humidity → Solar Output)  
  ✅ Evaluation Metrics:
  
    => MAE  : ~0.14  
    => RMSE : ~0.17  
    => MAPE : ~16%  
- **Dashboard Features:**

  ✅ Built with **Plotly** and **ipywidgets**.  
  ✅ Dropdown menu to select specific dates.  
  ✅ Interactive scatter plots showing **Predicted vs Actual Solar Output**.  
- **Insight:**  
  ✅ Irradiance remains the most influential factor in predicting Solar Output.  
  ✅ The dashboard makes it easier to explore model performance on specific dates.

  ⚠️ Note: This notebook contains interactive widgets that may not render properly on GitHub.  
If you’d like to explore the full interactive version, feel free to reach out to me directly 😉
    
*(More mini projects will be added soon!)*

---

## Tools & Tech
- Python
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter/Google Colab  

---

## Author
- **Selvi Rizki Agustin**  
- Passionate about **Data Analytics & Machine Learning**  
- This repo is a space for continuous learning and sharing 🌱✨

---
