# AI Fraud Detection

This is a desktop based application created using PyQT5 which uses credicard transation files to show case frauds using algorithm of machine learning.

---

## Features

1. Checks fraudueltan transaction using machine learning algorithms.
2. Visualze outcome with comfusion matrix and graph.
3. you can export result in pdf and excel format also you can download jpg of graphs.
4. Easy-to-use graphical interface for interacting with the system.

---

## Requirements

To run this project, you need:

- Python 3.8 or later
- Libraries: PyQt5, pandas, scikit-learn, tensorflow, bcrypt, matplotlib, seaborn, reportlab, sqlite3

---

## How to Run

1. Installation

   - Install Python: python.org.

2. Clone the repository:

   - git clone https://gitlab.com/rezacourses/engi9837_2024/aifrauddetect/aifrauddetection.git
   - cd aifrauddetection

3. Set up a virtual environment:

   - python -m venv venv
   - source venv/bin/activate # Windows: venv\Scripts\activate

4. Install dependencies:

   - pip install -r requirements.txt

5. Run the application:
   - python app1.py

---

## Usage

Login/Registration: Register or log in to access features.
Upload Data: Browse and upload a CSV file with Time, Amount, and Class columns.
Select Model: Choose Logistic Regression or Neural Network for analysis.
View Insights: Analyze graphs, fraud trends, and confusion matrices.
Export Results: Save results as PDF, Excel, or image files.

---

## Technologies Used

Frontend: PyQt5
Backend: SQLite, pandas, scikit-learn, tensorflow
Visualization: matplotlib, seaborn
Reports: reportlab

---

## Troubleshooting

"No file selected": Upload a valid CSV file.
"Invalid dataset": Ensure required columns are present in the dataset.
Check Fraud-Analyzer.log for detailed errors.

---
