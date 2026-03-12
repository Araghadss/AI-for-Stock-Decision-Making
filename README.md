# 📈 AI for Stock Decision Making

## 🔍 Project Overview

This project applies **Machine Learning and Deep Learning techniques** to historical stock market data to support **investment decision-making**.

Instead of only predicting stock prices, the system focuses on transforming predictions into **actionable insights** by generating clear investment recommendations:

**Buy** or **Not Buy**

The model analyzes time-series stock behavior across multiple companies and sectors to identify patterns that help investors make more informed decisions.

---

## 🎯 Problem Statement

Stock market prices are highly volatile and influenced by many economic and market factors.
For individual investors, manually analyzing stock trends can be difficult and unreliable.

**The challenge:**
How can historical stock data be used with AI models to predict future movements and convert those predictions into practical investment decisions?

---

## 💡 Proposed Solution

This project builds an AI-driven pipeline that:

1. Processes historical stock market data
2. Creates time windows to capture temporal patterns
3. Trains multiple machine learning models
4. Converts predictions into **Buy / Not Buy** decisions
5. Compares model performance to determine the best approach

The project focuses on **decision-oriented AI**, not only price prediction.

---

## 📊 Dataset Description

* Real historical stock market data
* **10 sectors included**
* **10 companies per sector**
* Up to **4 years of historical data**
* Time-series stock price information
* Data organized by sector and company

This dataset structure enables both **cross-sector analysis** and **time-series modeling**.

---

## ⚙️ Tools & Technologies

**Programming Language**

* Python

**Environment**

* Jupyter Notebook

**Libraries**

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

---

## 🔎 Methodology

### 1️⃣ Data Cleaning & Preprocessing

* Handling missing values
* Feature selection
* Formatting data for time-series analysis
* Preparing structured datasets for modeling

---

### 2️⃣ Time Window Construction

Instead of analyzing single-day prices, the project builds **time windows** representing stock behavior across multiple consecutive days.

This allows models to learn:

* Market trends
* Price volatility
* Temporal dependencies

---

### 3️⃣ Model Development

Three models were implemented and evaluated:

**Linear Regression**

* Used as a baseline model

**Random Forest**

* Captures non-linear relationships
* Effective for classification tasks

**LSTM (Long Short-Term Memory)**

* Deep learning model designed for time-series data
* Captures long-term temporal patterns

---

### 4️⃣ Decision Classification

Predicted stock movements are converted into:

* **Buy**
* **Not Buy**

This step transforms numerical predictions into practical investment decisions.

---

### 5️⃣ Model Evaluation

Models were evaluated using:

* Accuracy
* ROC Curve
* Comparative performance analysis

The best-performing model was selected based on prediction reliability and decision accuracy.

---

## 📈 Results & Insights

Key observations include:

* Time-series models outperform simple regression approaches
* LSTM captures temporal stock behavior effectively
* Decision-based classification provides clearer investment guidance than raw price prediction
* The system demonstrates potential for real-world investment decision support

---

## 🚀 Live Testing

The project includes a live testing stage where:

* Trained models are loaded
* Next-day stock prices are predicted
* **Buy / Not Buy** decisions are generated automatically

This demonstrates the system’s potential beyond academic experimentation.

---

## 📝 Conclusion

This project shows how AI can bridge the gap between **data analysis and financial decision-making**.

By combining **machine learning, deep learning, and time-series analysis**, the system provides a structured approach for supporting stock investment decisions.

---

## ▶️ How to Run

1. Clone the repository
2. Install required Python libraries
3. Open the Jupyter Notebook
4. Run the cells sequentially

---

## 👥 Contributors

This project was developed as a **collaborative academic project**.

My contribution focused on:

* Data preprocessing
* Model development
* Performance evaluation

Information Technology – Artificial Intelligence & Data Science
King Saud University
