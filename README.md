💰 Expense Tracker App

A modern and responsive Expense Tracker Web Application built with React and Vite that helps users easily track their daily income and expenses, calculate balance automatically, and manage financial records in a clean UI.

🌟 Why This Project?

Managing personal finance is important but often confusing.
This app solves that by providing a simple, fast, and user-friendly interface to:

Track where your money goes

Monitor income vs expenses

Always know your available balance

🚀 Live Preview

(Add your deployed link here)
👉 https://your-live-link.netlify.app

🖼️ Application Preview

🔥 Key Features

✔ Add income & expense transactions
✔ Auto calculation of:

Total Income

Total Expense

Remaining Balance
✔ Real-time search filter
✔ Clean and minimal UI
✔ Responsive on all devices
✔ Fast performance using Vite

🧠 How It Works
| Type    | Input           | Result                |
| ------- | --------------- | --------------------- |
| Income  | Positive amount | Added to balance      |
| Expense | Negative amount | Deducted from balance |


The app automatically updates totals whenever a new transaction is added.

🛠️ Technologies Used
| Technology | Purpose         |
| ---------- | --------------- |
| React JS   | UI development  |
| Vite       | Fast build tool |
| JavaScript | Logic handling  |
| CSS        | Styling         |


📂 Folder Structure
src/
│
├── components/
│   ├── AddTransaction.jsx
│   ├── OverviewComponent.jsx
│   ├── Tracker.jsx
│   ├── TransactionItem.jsx
│   └── TransactionsContainer.jsx
│
├── App.jsx
├── globalStyles.js
└── main.jsx

⚙️ Installation Steps
git clone https://github.com/your-username/expense-tracker-app.git
cd expense-tracker-app
npm install
npm run dev