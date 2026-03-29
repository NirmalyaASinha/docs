# API Reference

## Analyze Expenses
- **POST** `/api/analyze`
  - Request: `{ text: string, sessionLabel: string }`
  - Response: `{ success: boolean, expenses: array, ... }`

## Get Expenses
- **GET** `/api/expenses?session=SESSION_LABEL`
  - Response: Array of expenses for the session

## Delete Expenses
- **DELETE** `/api/expenses?session=SESSION_LABEL`
  - Deletes all expenses for the session

## Get Sessions
- **GET** `/api/sessions`
  - Response: Array of session summaries for the user

---

For authentication, all endpoints require a valid GitHub login session.
