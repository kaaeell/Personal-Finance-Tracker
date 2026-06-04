# Finwise – Personal Finance Manager

Finwise is a Python-powered web and desktop application that helps you take control of your personal finances. It simplifies tracking income and expenses, automatically categorizes transactions, visualizes spending patterns, and helps you set and monitor monthly budgets—so you can make smarter financial decisions.

## ✨ Features

| Category | Features |
|----------|----------|
| 💰 Transaction Tracking | Manual & automatic income/expense logging |
| 🏷️ Smart Categorization | Auto-categorization with ML rules (scikit-learn/pandas) |
| 📊 Analytics | Interactive charts (Matplotlib/Plotly), spending breakdowns |
| 🎯 Budgeting | Monthly budget creation & real-time monitoring |
| 🔔 Alerts | Desktop/email notifications when nearing budget limits |
| 📅 Reports | Daily, weekly, and monthly financial summaries (PDF/Excel export) |
| 📂 Import | CSV/Excel bank statement import with pandas auto-parsing |
| 🔍 Search & Filter | Find transactions by keyword, date, category, or amount |
| 🌙 Dark Mode | Comfortable viewing day or night |
| 🔐 Security | Secure user authentication (Django Auth / Flask-Login) + password hashing |


## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Backend | Python 3.10+ with Django / Flask / FastAPI |
| Database | SQLite (dev) / PostgreSQL (prod) |
| Data Processing | Pandas, NumPy |
| Visualization | Plotly / Matplotlib / Altair |
| Auto-Categorization | Scikit-learn / Rule-based engine |
| Web Frontend | HTML + Tailwind CSS + HTMX / Vue.js |
| Desktop UI | Tkinter / Flet / PyQt6 |
| Desktop Packaging | PyInstaller / Briefcase |
| Auth | Django Auth / Flask-Login + JWT + bcrypt |
| Reporting | ReportLab / OpenPyXL (Excel export) |

## 📦 Installation

### Prerequisites

- Python 3.10 or higher
- pip (Python package manager)
- virtualenv (recommended)
