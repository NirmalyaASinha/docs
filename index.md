
# ExpenseAI Documentation

> **ExpenseAI**: AI-powered expense monitoring, anomaly detection, and actionable insights for finance teams.

---

## Problem Statement
Finance teams struggled to track company spending.

**Problem:** Finance teams spent hours reviewing expenses, invoices, and subscriptions, but it was difficult to quickly spot unusual or unnecessary spending.

**Build:** An agent that monitors company expenses, detects unusual transactions, categorizes spending patterns, and suggests areas where costs could be reduced.

---

## System Flow
1. **Dashboard Landing:**
   - Minimal UI with a central "Start New" button.
   - Top-right: Login icon and History access.
   - Clicking these redirects to login or history pages.

2. **Start New Session:**
   - Smooth transition animation reveals a search/input box (1/4 from top).
   - User can:
     - Write expenses in natural language (NLP)
     - Upload expenses as PDF or Excel
   - The AI reads the file or text, updates the SQL database accordingly:
     - Create new expense list
     - Update existing list
     - Replace previous data for a given month

3. **Infographic Output:**
   - After processing, the system displays results as simple, clear infographics.

---

## Input Flexibility
- Accepts Excel, PDF, or plain text input.
- Supports commands like:
  - "Show wasteful expenses for last third month."
  - "Add these expenses to this month."
- System updates infographics in real time based on user input/commands.

---

## AI Capabilities
- Categorizes expenses
- Detects unusual transactions
- Suggests areas for cost optimization

---

## Features
- GitHub authentication
- Secure, session-based analysis
- File upload and NLP input
- AI-powered categorization and anomaly detection
- Infographic/stat card dashboard
- History tracking

---

## Getting Started
1. Clone the repo: `git clone git@github.com/NirmalyaASinha/Fin_AI.git`
2. Install dependencies: `npm install`
3. Set up your `.env.local` file (see `.env.example`)
4. Run the app: `npm run dev`

---

## Usage
1. Sign in with GitHub
2. Start a new analysis session
3. Upload or write your expenses
4. View insights and suggestions on the dashboard

---

## API Reference
See [api-reference.md](api-reference.md) for details on API endpoints.

---

For more, see the sidebar or visit the [GitHub repo](https://github.com/NirmalyaASinha/Fin_AI).
