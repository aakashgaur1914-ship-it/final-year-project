# Personal Finance Management System

This project is a MERN-style personal finance dashboard built for a college demo.

It uses:

- React for the dashboard UI
- Express for the backend
- JSON file storage in `data/db.json` instead of MongoDB

## Main sections

- Dashboard
- Income
- Expenses
- Budget
- Reports / Analytics

## Run both together

```bash
npm --prefix client install
npm run dev
```

## Run separately

```bash
node server/index.js
```

```bash
cd client
npm install
npm run dev
```

## Flow

1. Signup with name, email, and password.
2. The account is saved in `data/db.json`.
3. Login with the same credentials.
4. The dashboard loads your saved finance data and lets you add income, expenses, and budgets.
