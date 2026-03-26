# 📊 Tesla and GameStop Stock & Revenue Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing historical stock prices and revenue data for Tesla and GameStop using Python. The goal is to explore trends, visualize financial performance, and gain insights by combining stock market data with company revenue data.

The project uses data extraction techniques such as API calls and web scraping, followed by data cleaning and visualization using Python libraries.

---

## ⚙️ Installation Instructions

To run this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/mrhamxo/Tesla-and-GameStop-Stock-Revenue-Analysis-Using-Python.git
```

2. Navigate to the project folder:

```bash
cd your-repo-name
```

3. Install required libraries:

```bash
pip install pandas matplotlib yfinance beautifulsoup4 requests
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📂 Data Sources

The project uses the following data sources:

* **Stock Data**: Extracted using the `yfinance` API
* **Revenue Data**: Collected through web scraping from financial websites

### Data Processing:

* Converted date columns to datetime format
* Cleaned revenue data (removed commas, symbols like `$`)
* Filtered data up to June 2021 for analysis

---

## 🗂️ Code Structure

* **Stock Data Webscraping.ipynb** → Extracts stock data using API
* **Extracting Data using Webscraping Library.ipynb** → Scrapes revenue data
* **Revenue Data and Building Dashboard.ipynb** → Data cleaning and visualization
* **make_graph function** → Creates stock vs revenue plots using Matplotlib

---

## 📈 Results and Evaluation

* Visualized historical stock prices and revenue trends for both companies
* Compared financial growth patterns between Tesla and GameStop
* Generated clear graphs showing:

  * Stock price trends over time
  * Revenue growth over time

These visualizations help identify patterns and relationships between market performance and company earnings.

---

## 🔮 Future Work

* Add more companies for comparison
* Use interactive dashboards (Plotly or Streamlit)
* Apply predictive models for stock forecasting
* Automate data updates in real-time

---

## 📜 License

This project is for educational purposes as part of the IBM Data Science course.

* Code: Open for learning and modification
* Data: Belongs to respective sources (Yahoo Finance and scraped websites)

---

## 🙌 Acknowledgment

This project is part of the **IBM Python Project for Data Science** course.
