# 🚗 US Accidents Data Analysis (2016–2023)

This project analyzes motor vehicle accidents in the United States from 2016 to 2023 using a dataset containing over **7 million records**, sourced from [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents). The goal is to explore patterns related to location, weather, and time, and to gain insights for accident prevention.

---

## 📁 Dataset Overview

The dataset includes key features such as:

- 📍 **Location**: City, State, Latitude, Longitude  
- 🕒 **Time**: Start Time, End Time  
- 📊 **Severity**: Scale from 1 (least severe) to 4 (most severe)  
- 🌦️ **Weather**: Conditions, Temperature, Wind Speed, Visibility  
- 🚧 **Road Features**: Presence of bumps, curves, junctions  
- 🚦 **Traffic Influence**  

> ⚠️ **Note**: Data for **New York City** is missing.

---

## 🧹 Data Cleaning

- Removed columns with excessive missing values.
- Handled missing temperature, visibility, and wind data.
- Converted time columns to datetime format.
- Filtered out invalid entries and outliers.

---

## 📊 Exploratory Data Analysis (EDA)

### Key Discoveries

- **City Distribution**: A few cities account for most accidents, while **1000+ cities** recorded only one accident.
- **Time of Day**: Peak accidents happen between **6–10 AM** and **3–6 PM**.
- **Weekdays vs Weekends**: Accidents are more frequent on **weekdays**.
- **Weather**: Most accidents happen in **clear weather**.
- **Temperature**: Accident severity has minor correlation with temperature.

---

## ❓ Questions Explored

1. Are there more accidents in warmer or colder areas?
2. Which five states have the highest number of accidents?
3. Is New York City in the dataset?
4. Among the top 100 cities with most accidents, which states are represented?
5. What are the most accident-prone times of day?
6. How do weekdays compare with weekends in terms of accident frequency?
7. What are the peak months for accidents?
8. What are the trends year by year?
9. When are accidents per traffic volume highest?
10. How are hourly accident rates distributed?
11. How does weather affect accident occurrence?
12. Is there a correlation between temperature and accident severity?

---

## 📈 Data Visualization (Tableau)

Visualizations created:

- 🗺️ **Heat Maps**: Accident density using lat/lon data.
- 📊 **Bar Charts**: Accidents by state, city, and weather.
- 📉 **Line Graphs**: Yearly/monthly trends of accidents.

---

## 🧰 Tools & Technologies

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Tableau for interactive dashboards
- Jupyter Notebook for analysis

---

## 📎 License

This project is for educational purposes. The dataset is publicly available on [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents).

---

## 🙌 Acknowledgments

Thanks to the open-source community and Kaggle for providing accessible, high-quality data.

---

