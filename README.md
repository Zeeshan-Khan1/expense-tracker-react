# Expense Tracker Web Application

A ReactJS-based expense tracker application that helps you manage your income and expenses.

## Features

- **Balance Display**: Shows your current total balance
- **Income/Expense Summary**: Displays total income and expenses separately
- **Transaction History**: Lists all your transactions with visual indicators
- **Add Transactions**: Add new income (positive) or expense (negative) transactions
- **Delete Transactions**: Remove transactions by hovering and clicking the delete button
- **Local Storage**: All transactions are saved in browser's local storage

## Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

3. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build` folder.

## Project Structure

```
src/
  ├── components/
  │   ├── Header.js
  │   ├── Balance.js
  │   ├── IncomeExpenses.js
  │   ├── TransactionList.js
  │   ├── Transaction.js
  │   └── AddTransaction.js
  ├── App.js
  ├── App.css
  ├── index.js
  └── index.css
```

## Usage

1. Enter a description in the "Text" field
2. Enter an amount (positive for income, negative for expense)
3. Click "Add transaction" to add it to your list
4. Hover over a transaction to see the delete button
5. Click the "x" button to delete a transaction

## Technologies Used

- React 18.2.0
- React DOM 18.2.0
- CSS3

