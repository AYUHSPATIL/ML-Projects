# ✈ Flight Price Prediction

## 📌 Overview
This project aims to predict flight ticket prices based on various factors such as airline, source, destination, duration, and date of journey. The dataset includes both training and test sets, allowing for model evaluation and refinement. By leveraging machine learning techniques, we aim to build an efficient model that can provide accurate predictions for flight prices.

## 📊 Dataset Analysis
- 📂 **Loaded datasets** (`Data_Train.xlsx`, `Test_set.xlsx`) and merged them for preprocessing.
- 🔍 **Performed initial exploration** using `.head()`, `.info()`, `.describe()` to understand the dataset structure.
- 🏷 **Analyzed categorical features** such as `Airline`, `Source`, `Destination`, `Route`, and `Total Stops` to understand their impact on price.
- 🧹 **Identified and handled missing values** effectively to ensure data integrity.

## 🛠 Data Preprocessing
- 📅 **Extracted `Date`, `Month`, and `Year`** from `Date_of_Journey` to create new time-based features.
- ⏳ **Converted `Arrival_Time` and `Dep_Time`** into numerical values for better feature extraction.
- 🔄 **Applied one-hot encoding and label encoding** to categorical variables such as `Airline`, `Source`, and `Destination`.
- 🧑‍💻 **Dropped unnecessary columns** that do not contribute significantly to price prediction.

## 📈 Exploratory Data Analysis (EDA)
- 📊 **Visualized feature distributions** using `matplotlib` and `seaborn`.
- 📌 **Created correlation heatmaps** to identify relationships between numerical features.
- 📉 **Analyzed price trends** based on different airlines, sources, and destinations.
- ⏰ **Examined the effect of flight duration** on ticket prices.

## 🚀 Model Evaluation
- 🏗 **Applied multiple machine learning models**, such as:
  - **Linear Regression**
  - **Decision Tree**
  - **Random Forest**
  - **XGBoost**
- 📊 **Evaluated model performance** using:
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**
  - **R² Score**
- 🔬 **Tuned hyperparameters** to improve model accuracy and reduce overfitting.

## 📌 Conclusion
- 🎯 **The model effectively predicts flight prices** with reasonable accuracy.
- 📢 **Identified key factors** that significantly influence ticket prices, such as airline, travel time, and number of stops.
- 🔍 **Further improvements can be made** by adding external data such as weather conditions and demand trends.

## ⚙ Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/flight-price-prediction.git
   cd flight-price-prediction
2. pip install pandas numpy matplotlib seaborn scikit-learn xgboost

## Run the Jupyter Notebook to preprocess data and train models.

## 🔮 Future Scope
- 🤖 Improve model accuracy with deep learning techniques (e.g., Neural Networks).
- 🌐 Deploy the model as a web application for real-time price prediction.
- 📡 Integrate external APIs for real-time flight data updates.
- 📊 Enhance feature engineering with additional insights such as flight demand trends.
