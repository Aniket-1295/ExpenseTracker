# Expense Tracker

## Overview

Expense Tracker is a web application built with React.js for tracking personal expenses. It allows users to add, edit, delete expenses, and manage their wallet balance. Users can view summaries of their expenses through various charts and keep track of spending trends.

## Features

- **Wallet Balance Management**: Start with a default balance of ₹5000. Users can add funds to their wallet.
- **Expense Management**: Add new expenses with details like title, amount, category, and date. Edit or delete existing expenses.
- **Expense Summary**: View a summary of expenses categorized by type using pie charts.
- **Expense Trends**: Analyze spending trends based on categories using bar charts.
- **Responsive Design**: The application is designed to be usable on various devices.

## Technologies Used

- **Frontend**: React.js, HTML, CSS, JavaScript
- **Libraries**:
  - [Recharts](https://recharts.org/en-US) for charts
  - [React-Modal](https://reactcommunity.org/react-modal/) for modals
  - [Notistack](https://notistack.com/getting-started) for notifications
  - [React Icons](https://react-icons.github.io/react-icons/) for icons

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Aniket-1295/ExpenseTracker.git
   cd EXPENSE-TRACKER
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Run the Application**:

   ```bash
   npm start
   ```

   This will start the development server, and you can view the application in your browser at `http://localhost:3000`.

## Usage

1. **Add Balance**: Click on the "Add Balance" button to increase your wallet balance.
2. **Add Expense**: Use the "Add Expense" form to add new expenses. You can categorize your expenses and select the date.
3. **Edit Expense**: Click the "Edit" button on an expense to modify its details.
4. **Delete Expense**: Click the "Delete" button to remove an expense.
5. **View Summary**: Check out the pie chart to see your total expenses categorized by type.
6. **View Trends**: Use the bar chart to analyze spending trends based on categories.

## Local Storage

- **Wallet Balance**: The wallet balance and list of expenses are stored in `localStorage` to persist data across page refreshes.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

## Contact

For any questions or suggestions, please contact [Aniketr](aniketkamble1642002@gmail.com).
