
# ☀️ ML-Powered Solar Tracking System

A **Machine Learning-powered Solar Tracking System** built using **Streamlit**, designed for **real-time solar energy optimization** and **predictive solar panel orientation**.

---

## 🔍 Overview

This project aims to **enhance the efficiency of solar panels** by using ML algorithms to:
- Predict the optimal panel angle/orientation.
- Dynamically adjust panel positioning based on solar intensity, time, weather, and geographic data.
- Maximize energy output in real-time.

The Streamlit interface offers a **user-friendly dashboard** for monitoring performance, uploading data, and visualizing predictions.

---

## 🚀 Features

- 📊 Real-time prediction of solar panel orientation.
- ⚙️ ML model training and evaluation (Regression/Classification).
- 📈 Data visualization of sunlight, angles, and energy efficiency.
- 🧠 Supports models like Linear Regression, Random Forest, XGBoost, etc.
- 🌐 Interactive Streamlit web interface.

---

## 🧠 Machine Learning Models Used

- **Linear Regression** – For predicting panel angles based on time and location.
- **Random Forest Regressor** – To model non-linear relationships in weather & solar data.
- **XGBoost** – High-performance predictions with improved accuracy.
- **KNN or SVM** *(optional)* – For classification-based scenarios (e.g., tilt-angle bins).

---

## 📁 Folder Structure

```
solar-tracker-ml/
│
├── data/                    # Training datasets (weather, solar intensity)
├── models/                  # Saved ML models (pickle or joblib)
├── notebooks/               # Jupyter Notebooks for experimentation
├── app/                     # Streamlit app scripts
│   ├── main.py              # Entry point for Streamlit app
│   ├── utils.py             # Helper functions
│
├── README.md                # Project overview
├── requirements.txt         # Python dependencies
├── train_model.py           # Script to train & save models
```

---

## 🖥️ How to Run

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/solar-tracker-ml.git
cd solar-tracker-ml
```

2. **Install Requirements**
```bash
pip install -r requirement.txt
```

3. **Launch Streamlit App**
```bash
streamlit run app/main.py
```

---

## 🔧 Requirements

- Python 3.8+
- scikit-learn
- pandas
- numpy
- matplotlib / seaborn
- streamlit
- xgboost

---

## 📊 Sample Inputs

| Time | Latitude | Longitude | Solar Intensity | Weather |
|------|----------|-----------|-----------------|---------|
| 10:00 AM | 28.6 | 77.2 | 750 W/m² | Clear |
| 1:00 PM | 28.6 | 77.2 | 920 W/m² | Sunny |

---

## 💡 Use Cases

- Residential solar energy systems
- Smart grid energy optimization
- Renewable energy forecasting
- Educational or industrial IoT applications

---

## 📬 Contact

For queries or collaboration:  
📧 your.email@example.com  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile)  
🐙 [GitHub](https://github.com/your-username)

---

## 📝 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
