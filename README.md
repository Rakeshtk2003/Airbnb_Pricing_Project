# 🏠 Airbnb Dynamic Pricing Recommendation Engine  

## 📌 Overview  
This project analyzes historical Airbnb data to recommend **optimal listing prices**.  
It combines **machine learning (regression model)** and **interactive dashboards** to help Airbnb hosts maximize revenue while ensuring competitive pricing.  


## 🛠 Tools & Technologies  
- Python (Pandas, Scikit-learn, Matplotlib/Seaborn)  
- Power BI for dashboards  
- Excel for initial exploration  

---

## 🚀 Approach  
1. **Data Preparation** – Cleaned and structured the Airbnb dataset.  
2. **Model Development** – Built a regression model to predict listing prices.  
3. **Prediction Output** – Generated predicted prices and calculated price gaps.  
4. **Visualization** – Designed interactive dashboards for market insights and recommendations.  

---

## 🔑 Key Insights  
- **London & Paris** → Highest predicted prices.  
- **Entire Homes/Apts** → Earn significantly more than private/shared rooms.  
- **Superhost Status** → Positive impact on achievable pricing.  
- **Barcelona** → Shows largest mispricing gap (underpriced compared to predictions).  

---

## 💡 Recommendations  
- Adjust prices upwards in **London/Paris**; keep **Berlin/Budapest** competitive.  
- Promote **entire homes/apts** as premium offerings.  
- Encourage hosts to achieve **Superhost status** for higher trust & pricing power.  
- Implement **seasonal and weekend-based dynamic pricing**.  
- Use **alerts for underpriced listings** (predicted > actual).  

📌 Example: The model recommended an **optimal price of €687.42** for one listing, balancing location, reviews, and capacity with market trends.  

---

## 📊 Deliverables  
- **Python Script** → Data cleaning & ML-based pricing engine (`airbnb_pricing_engine.ipynb`)  
- **Datasets** → `cleaned_airbnb_dataset.csv`, `listing_predictions.csv`  
- **Power BI Dashboards** → Market Overview & Price Recommendation  
- **Final Report (PDF)** → Insights + Recommendations for Airbnb hosts/platform  

---

## 📷 Dashboard Snapshots  
- Market Overview → City-wise pricing, room type trends  
- Price Recommendation → Actual vs Predicted price, Suggested pricing strategy  
