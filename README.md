# Machine-learning

🌫️ **AQI Prediction Using Machine Learning**

This project focuses on predicting the Air Quality Index (AQI) using various machine learning models. It utilizes real-world environmental data from Indian cities, including multiple pollutant indicators.

---

## 📁 Project Structure

- `AQI Prediction.ipynb` – Main Jupyter notebook containing data analysis, preprocessing, model training, and evaluation.

- 📚 **Algorithms used**:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor

---

## 📌 Key Features

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Model Training & Evaluation (MAE, R² Score)
- Feature Importance Visualization

---

## 🧾 Dataset Description

The dataset contains the following features:

- **Pollutant indicators:** `PM2.5`, `PM10`, `NO2`, `SO2`, `CO`, `O3`
- **Target:** `AQI` (Air Quality Index)
- **Location/City-based measurements** from across India
- Time span: 2015–2020 (if applicable)

---

## 🛠️ Tools Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📊 Results

Among all models tested, the **Random Forest Regressor** gave the best performance in terms of prediction accuracy and robustness across features.

---

## 🧠 Use Case

Useful for:

- Urban air pollution monitoring and management
- Health risk assessment based on pollution levels
- Government policy formulation and alert systems
- Smart city data analysis dashboards

---

## 🚀 Run the Project

```bash
# Clone the repository
git clone https://github.com/yourusername/aqi-prediction.git

# Install required packages
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
