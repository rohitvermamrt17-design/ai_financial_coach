# ₹ AI Financial Coach

An AI-powered financial coaching application built with Python, Streamlit, Google ADK, and Gemini AI.

The application analyzes income, expenses, savings, and debts and provides personalized financial recommendations through multiple specialized AI agents.

## 🚀 Features

- ₹ Monthly income and household information
- 💳 Manual expense entry
- 📊 CSV transaction upload
- 📈 Spending analysis and visualizations
- 💵 Personalized savings recommendations
- 🏦 Emergency fund planning
- 💳 Debt reduction strategies
- 📉 Debt payoff comparison
- 🤖 Multiple specialized AI agents
- ⚡ Google ADK sequential agent workflow
- 🔐 Secure API key management using .env

## 🤖 AI Agent Architecture

### 1. Budget Analysis Agent

Analyzes income, transactions, expenses, spending categories, spending patterns, and potential areas for savings.

### 2. Savings Strategy Agent

Creates personalized savings plans, emergency fund recommendations, savings allocations, and automated savings techniques.

### 3. Debt Reduction Agent

Analyzes debts and creates debt payoff recommendations using the Avalanche and Snowball methods.

## 🛠️ Technologies Used

- Python
- Streamlit
- Google ADK
- Gemini AI
- Pandas
- Plotly
- Pydantic
- python-dotenv

## 📁 Project Structure

```text
ai-financial-coach/
│
├── ai_financial_coach_agent.py
├── .env.example
├── .gitignore
├── requirements.txt
├── README.md
└── LICENSE
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/rohitvermamrt17-design/ai_financial_coach.git
```
```bash
cd ai-financial-coach
```

### 2. Create a virtual environment

Windows:

```bash
python -m venv .venv
```

Activate it:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

## 🔑 API Key Setup

Create a file named .env in the project folder.

Add your Google API key:

GOOGLE_API_KEY= your_actual_google_api_key

## ▶️ Run the Application

```bash
streamlit run ai_financial_coach_agent.py
```

The application will open in your browser.

## 📊 CSV Format

The application supports CSV transaction uploads.

Required columns:

- Date — Transaction date
- Category — Expense category
- Amount — Transaction amount

Example:

Date,Category,Amount
2024-01-01,Housing,1200.00
2024-01-02,Food,150.50
2024-01-03,Transportation,45.00

## 💡 Supported Expense Categories

- Housing
- Utilities
- Food
- Transportation
- Healthcare
- Entertainment
- Personal
- Savings
- Other

## 🔐 Privacy & Security

The application is designed to process financial information provided by the user during the session.

Never commit API keys, passwords, or other sensitive credentials to GitHub.

Use environment variables for sensitive information.

## ⚠️ Disclaimer

This application provides AI-generated financial guidance for educational and informational purposes only.

It is not professional financial, investment, tax, accounting, or legal advice. Users should consult a qualified financial professional before making important financial decisions.

## 👨‍💻 Author

Rohit Verma

GitHub: https://github.com/rohitvermamrt17-design

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐ on GitHub.
