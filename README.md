# Box Office Revenue & Movie Success Prediction 🎬📊

This project applies **machine learning models** to predict a movie’s financial success and estimate its box office revenue. By analyzing key metadata such as budget, popularity, runtime, genre, IMDb ratings, and votes, the system can classify movies into categories (Hit, Flop, Classic) and forecast revenue with high accuracy.  

---

## 🚀 Features
- 🎯 **Classification** – categorize movies as Hit, Flop, or Classic.  
- 💰 **Regression** – predict exact box office revenue values.  
- 🛠️ **Feature Engineering** – includes profit ratios, budget-to-runtime ratios, and custom “Classic Score” for cult/critical hits.  
- 📈 **Model Evaluation** – uses accuracy, F1, MAE, RMSE, and R² for performance tracking.  
- ⚡ **Ensemble Learning** – compares tree-based and boosting models for optimal accuracy.  

---

## 🛠️ Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-Learn, XGBoost, LightGBM, CatBoost, Matplotlib, Seaborn  
- **Data Sources:** TMDB datasets, OMDB APIs, IMDb ratings and metadata  

---

## 📊 Results
- Achieved **98% classification accuracy** for Hit/Flop/Classic labels.  
- Gradient Boosting delivered best regression results with **lowest RMSE (~$65M)**.  
- Feature engineering improved model interpretability and reduced overfitting.  
- Provided insights into key drivers of box office success (budget, votes, IMDb ratings).  

---
