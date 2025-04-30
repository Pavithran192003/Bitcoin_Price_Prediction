
# 📈 Bitcoin Price Prediction App

A GUI-based application built with Python that predicts the future price of Bitcoin using historical data and machine learning, with support for currency conversion across multiple countries.

## 🚀 Features

- **Bitcoin Price Prediction** using Random Forest Regression
- **Date-based forecasting**: Predict prices for specific dates
- **Multi-currency support**: Convert predicted prices to INR, CAD, BRL, CNY, and EUR
- **Interactive GUI** built using Tkinter
- **Visual Analysis** of Bitcoin trends over time
- **Currency Selection** from a country list
- **R² Accuracy Score Display** after prediction

---

## 📊 Data Source

- Historical Bitcoin price dataset (`bit.csv`) containing:
  - Date
  - Open, High, Low, Close, Adj Close prices
  - Volume
- The dataset contains data from **2015 to March 2024**

---

## 📸 Screenshots

> *(Insert GUI screenshot here if available)*

---

## 🔧 Technologies Used

- **Python** 3.x
- **Tkinter** – for GUI development
- **Pandas, NumPy** – data manipulation
- **Matplotlib, Seaborn** – visualizations
- **Scikit-learn** – Linear Regression, Random Forest
- **Pillow (PIL)** – image loading in GUI

---

## 📁 Project Structure

```
bitcoin-price-prediction/
│
├── bit.csv                       # Bitcoin historical price dataset
├── bitcoin_prediction.py         # Main Python script with GUI and ML logic
├── images.jpeg                   # Background image for GUI
├── README.md                     # Project documentation
└── requirements.txt              # Required libraries
```

---

## 🧠 How It Works

1. The dataset is preprocessed (cleaned, formatted, indexed by date).
2. A Random Forest Regressor is trained on historical data.
3. Users can enter a date to predict the Bitcoin price on that day.
4. Select a country to view the price in local currency (via static conversion rates).
5. Displays prediction and model accuracy using **R² Score**.

---

## 🌍 Supported Currencies

| Country   | Currency | Example Conversion Rate |
|-----------|----------|--------------------------|
| USA       | USD      | 1.00                     |
| India     | INR      | 75.00                    |
| Canada    | CAD      | 1.25                     |
| Brazil    | BRL      | 5.20                     |
| China     | CNY      | 6.45                     |
| Europe    | EUR      | 0.85                     |

---

## 🧪 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/bitcoin-price-prediction.git
cd bitcoin-price-prediction
```

### 2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

*Contents of `requirements.txt`:*

```
pandas
numpy
matplotlib
seaborn
scikit-learn
pillow
```

### 4. Run the app

```bash
python bitcoin_prediction.py
```

---

## 📈 Model Performance

- **Linear Regression**: R² ≈ 0.41  
- **Random Forest Regressor**: R² ≈ **0.997**

> The Random Forest model is highly accurate for the dataset used.

---

## 📬 Feedback & Contributions

I’d love to hear your feedback and ideas for improvement.  
Feel free to open issues or pull requests!

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙋‍♂️ Author

**Pavithran S**  
[LinkedIn](https://www.linkedin.com/in/s-pavithran-07b871264)
