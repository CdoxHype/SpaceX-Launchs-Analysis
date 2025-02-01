# 🚀 Falcon 9 Landing Prediction – IBM Data Science Capstone

## 📌 Project Overview
This project focuses on **predicting the landing success of SpaceX's Falcon 9 first stage** using machine learning and data analysis techniques. By integrating real-world launch data, performing exploratory analysis, and building predictive models, we gained valuable insights into **factors influencing landing success** and SpaceX’s cost efficiency.

## 🛠 Technologies & Tools
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium, BeautifulSoup, Plotly Dash  
- **Data Storage & Processing:** SQLite, CSV, SQL queries  
- **Web Scraping & API:** SpaceX API, BeautifulSoup (Wikipedia)  
- **Machine Learning Models:** Logistic Regression, SVM, Decision Trees, K-Nearest Neighbors  
- **Dashboard & Visualization:** Plotly Dash, Folium, Matplotlib  

## 📊 Methodology
### 🔹 Data Collection & Processing
- Extracted launch data from **SpaceX's REST API** and **web scraped Wikipedia** using `requests` and `BeautifulSoup4`.  
- Cleaned and preprocessed data using `Pandas`, handling missing values and encoding categorical features.  
- Stored structured datasets in **CSV and SQLite** databases for analysis.  

### 🔹 Exploratory Data Analysis (EDA)
- Used **SQL queries** to analyze launch outcomes and trends.  
- Created **interactive maps** with `Folium` to visualize **launch sites & their proximity** to infrastructure.  
- Identified key launch success patterns using `Matplotlib` and `Seaborn`.  

### 🔹 Machine Learning & Predictive Modeling
- Split data (80/20) and **standardized features** for training.  
- Trained **Logistic Regression, SVM, Decision Tree, and KNN** models.  
- Applied **GridSearchCV** for hyperparameter tuning.  
- **Best Model:** **Decision Tree Classifier** (88.89% accuracy).  
- Evaluated models using **confusion matrices & classification reports**.  

### 🔹 Interactive Dashboard with Plotly Dash
- Built a **dynamic dashboard** to explore launch success probabilities.  
- Implemented **dropdowns, pie charts, scatter plots**, and **range sliders** for deeper analysis.  

## 🎯 Key Insights & Achievements
- **Landing Success Factors:** **Payload mass, orbit type, launch site, booster version, and grid fin usage** influence Falcon 9 landing success.  
- **Cost Efficiency:** **SpaceX’s reusable rockets ($62M) significantly reduce launch costs** compared to competitors ($165M).  
- **Technological Progress:** Success rates **improved from <50% (2010) to >90% (2020)**, showcasing SpaceX’s advancements.  


