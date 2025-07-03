# 🎾 tennis-prize-predictor

This project analyzes how professional tennis players' ranking points and personal characteristics affect their tournament earnings (prize money). Using a cleaned dataset of the top 500 male tennis players, we build a statistical model to predict prize money based on factors such as best rank, current rank, age, dominant hand, and backhand style.

## 📌 Research Question

**How can we use ranking points and player characteristics to predict the prize money a tennis player receives?**

## 📊 Dataset

- **Source:** Ultimate Tennis Statistics (based on Jeff Sackmann’s open-source ATP data)
- **Size:** 407 players (after cleaning)
- **Variables used:**
  - `prize_money` (US dollars)
  - `best_rank`
  - `current_rank`
  - `age`
  - `dominant_hand` (converted to dummy variable)
  - `backhand_style` (converted to dummy variable)

## 🔧 Methods

- Data cleaning and wrangling in **R**
- Removal of missing values
- Transformation of categorical variables into dummy variables
- Linear regression model for predicting prize money
- Summary statistics and visualizations
