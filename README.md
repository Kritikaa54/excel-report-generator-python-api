# 📊 Excel Report Generator + API Data Fetcher

## 🔍 Problem
Business teams manually fetch data from APIs or Excel sources, then format and share reports — leading to delays and inconsistencies.

## 🎯 Solution
Automate the collection of data from a public API and generate a styled Excel report using Python.

## 🛠️ Tech Stack
- Python
- `requests` (API integration)
- `pandas` (data manipulation)
- `openpyxl` (Excel formatting)
- `schedule` (optional: auto-run the script)

## 🚀 Features
- Pulls data from a real-world API (e.g., weather, currency, stock market)
- Cleans and structures data using pandas
- Exports a styled and formatted Excel report
- Can be scheduled to run daily/weekly
- Beginner-friendly and production-scalable


## 📁 Folder Structure
📂 excel-report-generator-python-api/
├── main.py
├── report_template.xlsx
├── README.md
├── requirements.txt



## ▶️ How to Run
```bash
pip install -r requirements.txt
python main.py
