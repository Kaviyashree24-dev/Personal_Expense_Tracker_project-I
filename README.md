# Personal Expense Tracker System

## Project Overview
The Personal Expense Tracker System is a web-based application developed to help users manage their daily expenses efficiently. The system allows users to register, log in, add expenses, categorize spending, view expense history, and generate reports. It provides a simple and user-friendly interface for tracking financial activities and improving money management.

---

## Problem Statement
Many individuals struggle to keep track of their daily expenses using traditional methods such as notebooks or spreadsheets. These methods are time-consuming and often lead to inaccurate records. Therefore, there is a need for a digital expense tracking system that enables users to record, organize, and monitor their expenses effectively.

---

## Objectives
* Provide an easy way to record daily expenses.
* Help users manage and monitor their spending habits.
* Categorize expenses for better financial management.
* Generate expense reports and summaries.
* Track monthly and yearly expenses effectively.
* Improve personal budgeting and financial planning.
* Store and manage expense records securely.

---

## Scope of the Project
* User Registration and Login
* Dashboard Management
* Expense Management
* Category Management
* Expense Tracking
* Report Generation
* Secure Data Storage

---

## Module List

### 1. User Authentication Module
* User Registration
* Login and Logout
* Password Validation

### 2. Dashboard Module
* View Expense Summary
* View Total Expenses
* Quick Navigation
* Recent Transactions

### 3. Expense Management Module
* Add Expense
* Edit Expense
* Delete Expense
* View Expense Details

### 4. Category Management Module
* Add Categories
* View Categories
* Organize Expenses

### 5. Reports Module
* Monthly Reports
* Category Wise Reports
* Expense Analysis
* Total Expense Calculation

### 6. Expense Tracking Module
* Daily Expense Tracking
* Monthly Expense Tracking
* Expense History

---

## Requirement Gathering

### Functional Requirements
* User Registration and Login
* Add, View, Edit, and Delete Expenses
* Manage Categories
* Generate Reports
* Logout

### Non-Functional Requirements
* User-Friendly Interface
* Fast Response Time
* Data Security
* Easy Navigation
* Reliability

---

## Use Case Diagram (User Activities)
* Register Account
* Login
* Add Expense
* Edit Expense
* Delete Expense
* View Expenses
* Manage Categories
* View Reports
* Logout

---

## Technology Stack
* **Front End:** HTML, CSS, JavaScript, Bootstrap
* **Back End:** JavaScript, Browser Local Storage
* **Database:** Local Storage
* **Development Tools:** Visual Studio Code (VS Code), GitHub, Google Chrome

---

## Database Schema Creation

### 1. User Table
* `user_id` (INT) - Primary Key
* `name` (VARCHAR(50))
* `email` (VARCHAR(100))
* `password` (VARCHAR(50))

### 2. Category Table
* `category_id` (INT) - Primary Key
* `category_name` (VARCHAR(50))

### 3. Expense Table
* `expense_id` (INT) - Primary Key
* `user_id` (INT) - Foreign Key
* `category_id` (INT) - Foreign Key
* `amount` (DECIMAL(10,2))
* `description` (VARCHAR(255))
* `expense_date` (DATE)

---

## Project Files Structure
* `index.html`
* `signup.html`
* `login.html`
* `dashboard.html`
* `add-expense.html`
* `view-expenses.html`
* `categories.html`
* `reports.html`
* `logout.html`
* `style.css`
* `script.js`

---

## Expected Outcome
The Personal Expense Tracker System will help users maintain accurate financial records, monitor expenses, analyze spending patterns, and improve budgeting through a simple and effective web application.

---

---

## 🔮 Future Enhancements
* **AI-Powered Insights:** Implement machine learning algorithms to predict future monthly expenses and give smart budgeting recommendations.
* **Receipt Scanner:** Integrate Optical Character Recognition (OCR) to allow users to scan physical receipts and automatically fill in expense details.
* **Data Visualization:** Add dynamic charts and graphs (using libraries like Chart.js) to show visual spending patterns on the dashboard.
* **Currency Converter:** Include multi-currency support with live exchange rates for users who travel internationally.
* **Export Options:** Enable users to download their expense logs and reports as PDF or Excel CSV files.

---

## ✍️ Author
* **Name:** Kaviyashree M
* **Department:** Artificial Intelligence and Data Science (AIDS)
* **GitHub Profile:** [@Kaviyashree24-dev](https://github.com/Kaviyashree24-dev)
