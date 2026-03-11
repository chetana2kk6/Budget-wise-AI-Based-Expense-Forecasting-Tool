BudgetWise – AI-Based Expense Forecasting Tool

BudgetWise is a web-based personal finance management application that helps users track expenses, manage budgets, and analyze spending patterns through interactive dashboards and visual analytics. The system automatically categorizes transactions and provides insights to help users better understand their financial habits.

The platform allows users to set monthly budgets, record daily expenses or income, and monitor financial progress in real time. With visual charts and categorized expense tracking, BudgetWise simplifies financial management and promotes better budgeting practices.

Features

Secure user authentication using JWT

Monthly budget setup and management

Add and track daily expenses and income

Automatic expense categorization based on transaction notes

Dashboard with financial overview

Category-wise spending visualization using pie charts

Expense history with month-based filtering

Real-time calculation of remaining budget

Tech Stack

Backend

Python

Flask

SQLAlchemy

Pandas

Frontend

HTML

CSS

JavaScript

Database

SQLite

Visualization

Chart.js

Authentication

Flask-JWT-Extended

Project Structure
BudgetWise
│
├── app.py
├── models.py
├── categorizer.py
│
├── templates
│   ├── dashboard.html
│   ├── history.html
│   ├── index.html
│   └── profile.html
│
├── static
│   ├── dashboard.css
│   ├── dashboard.js
│   └── icon.png
│
└── database.db
Installation

Clone the repository

git clone https://github.com/your-username/BudgetWise.git

Navigate to project folder

cd BudgetWise

Install dependencies

pip install -r requirements.txt

Run the application

python app.py

Open in browser

http://127.0.0.1:5000
Future Improvements

AI-based spending prediction

Expense trend analysis

Export reports as PDF or Excel

Mobile responsive UI

Smart budgeting recommendations
