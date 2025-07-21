
# 🏡 House Price Prediction System

This is a web-based machine learning project built using **Flask** that predicts house prices in **Bangalore**, India. The model takes the following user inputs:

- 📍 Location (in Bangalore)
- 🛁 Number of Bathrooms
- 🛏️ Number of BHK (Bedrooms, Hall, Kitchen)
- 📐 Total Square Feet

It then returns an estimated **house price (in ₹ lakhs)** using a trained regression model.

---

## 🚀 Features

- Interactive web UI using **HTML + Bootstrap**
- Real-time predictions using a **trained Ridge Regression model**
- Model pipeline includes **OneHotEncoding**, **StandardScaling**, and regression
- Inputs validated via form submission

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, Bootstrap
- **Model**: scikit-learn (`Ridge,Lasso Regression`)
- **Data**: Cleaned dataset of Bangalore house listings

---

## 🔧 Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/house-price-predictor.git
cd house-price-predictor
````

### 2. Create and activate a virtual environment

```bash
python -m venv env
env\Scripts\activate  # On Windows
# source env/bin/activate  # On Linux/Mac
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the app

```bash
python main.py
```

App will be live at: `(http://127.0.0.1:7000/)`

---

## 📂 Project Structure

```
house-price-predictor/
│
├── main.py                # Flask application
├── RidgeModel.pkl         # Trained ML model (pickled)
├── Cleaned_data.csv       # Preprocessed dataset
├── templates/
│   └── index.html         # Web form UI
├── static/                # (Optional) CSS/JS files
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## 📊 Model Pipeline

1. One-hot encoding on `location`
2. Numerical features: `total_sqft`, `bath`, `bhk`
3. Scaled using `StandardScaler`
4. Trained with `Ridge Regression`

---

## 💡 Screenshots
<img width="1912" height="907" alt="image" src="https://github.com/user-attachments/assets/6d903a09-d971-4e98-afa2-89a097158227" />
<img width="1918" height="964" alt="Screenshot 2025-07-22 030659" src="https://github.com/user-attachments/assets/e56b62c7-65cf-43c3-af36-f6b887844bcd" />

---

## 🙋‍♂️ Author

**Aryaman Dev Kumar**
B.Tech CSE, NIT Delhi
Feel free to reach out for suggestions or collaborations!



