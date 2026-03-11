# BudgetWise – AI-Based Expense Forecasting Tool

BudgetWise is a web-based personal finance management application that helps users track daily expenses, manage monthly budgets, and analyze spending patterns using visual dashboards.

The system allows users to record income and expenses, automatically categorize transactions, and view spending insights through charts. BudgetWise provides a simple and intuitive interface to help users understand their financial habits and maintain better budget control.

---

## Features

* User authentication and secure login
* Set and manage monthly budgets
* Add daily income and expense transactions
* Automatic expense categorization
* Dashboard with financial overview
* Category-wise spending visualization (Pie Chart)
* Expense history with month-based filtering
* Real-time budget tracking and remaining balance

---

## Tech Stack

**Backend**

* Python
* Flask
* SQLAlchemy
* Pandas

**Frontend**

* HTML
* CSS
* JavaScript

**Database**

* SQLite

**Data Visualization**

* Chart.js

**Authentication**

* Flask-JWT-Extended

---

## Project Structure

```
BudgetWise/
│
├── app.py
├── models.py
├── categorizer.py
│
├── templates/
│   ├── index.html
│   ├── dashboard.html
│   ├── history.html
│   ├── edit_profile.html
│   ├── profile.html
│   └── settings.html
│
├── static/
│   ├── dashboard.css
│   ├── dashboard.js
│   └── icon.png
│
├── database.db
└── README.md
```

---

## Installation

Clone the repository

```
git clone https://github.com/your-username/BudgetWise.git
```

Navigate to project directory

```
cd BudgetWise
```

Install dependencies

```
pip install -r requirements.txt
```

Run the application

```
python app.py
```

Open the browser and visit

```
http://127.0.0.1:5000
```

---

## Future Improvements

* AI-based expense prediction
* Monthly spending trend analysis
* Export financial reports (PDF/Excel)
* Mobile responsive interface
* Smart budget recommendations

---

## Author

Chetana Korivi
B.Tech – Artificial Intelligence & Data Science
