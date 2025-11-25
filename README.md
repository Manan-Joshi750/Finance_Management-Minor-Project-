# 📊 Finance Dashboard – Minor Team Project

This project is a collaborative minor team project, built with the goal of creating a modern, intuitive, and feature-rich Finance Management Dashboard. Our team designed and developed this application using React.js and Tailwind CSS, focusing on clean UI, seamless user experience, and insightful financial visualizations.
The dashboard helps users track income and expenses, visualize spending patterns, and manage transactions efficiently — all in one place.

## ✨ Features

### Dashboard
- Real-time financial summary
- Interactive charts for expense tracking
- Recent transactions overview
- Responsive design for all devices

### Transaction Management
- Add/Edit/Delete transactions
- Filter and sort functionality
- Categorization of expenses
- Date range filtering

### AI-Powered Financial Assistant
- 🤖 **AI Chatbot**
  - Get instant answers to financial queries
  - Receive personalized budget recommendations
  - Ask questions about your spending patterns
  - Get financial tips and guidance

### Data Visualization
- Interactive charts using Chart.js
- Category-wise spending analysis
- Income vs. Expense comparison
- Monthly/Yearly trends

## 🏗️ Project Structure

```
Finance_Management/
├── public/                 # Static files
├── src/
│   ├── assets/             # Images and icons
│   ├── components/         # Reusable UI components
│   │   ├── Navbar.js       # Navigation bar
│   │   ├── SummaryCard.js  # Dashboard summary cards
│   │   ├── TransactionForm.js # Add/Edit transaction form
│   │   ├── TransactionTable.js # Transaction listing
│   │   └── TopCategoriesChart.js # Expense visualization
│   │
│   ├── pages/              # Application views
│   │   ├── Dashboard.js    # Main dashboard
│   │   ├── AddTransaction.js # Add new transaction
│   │   └── TransactionHistory.js # Transaction history
│   │
│   ├── data/               # Mock data
│   ├── App.js              # Main application component
│   └── index.js            # Application entry point
├── .gitignore
├── package.json
├── README.md
└── tailwind.config.js
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or later)
- npm (v8 or later) or Yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Finance_Management
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## 🛠️ Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm run build`

Builds the app for production to the `build` folder.

## 📸 Screenshots

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin: 20px 0;">
  <div style="flex: 1; min-width: 300px; max-width: 400px;">
    <h4>Dashboard</h4>
    <img width="1920" height="878" alt="image" src="https://github.com/user-attachments/assets/4a830b4d-bc0a-41ca-9f5d-3ddc9d5381f9" />
  </div>
  
  <div style="flex: 1; min-width: 300px; max-width: 400px;">
    <h4>Add Transaction</h4>
    <img width="1920" height="879" alt="image" src="https://github.com/user-attachments/assets/b56add77-4d76-4f41-9c2e-f955a2e131b9" />
  </div>
  
  <div style="flex: 1; min-width: 300px; max-width: 400px;">
    <h4>Transaction History</h4>
    <img width="1920" height="880" alt="image" src="https://github.com/user-attachments/assets/87a44c28-b29a-4018-83a2-34e30c6140d5" />
  </div>
</div>

## 🚀 Future Enhancements

### Backend Integration
- [ ] **User Authentication**
  - JWT-based authentication
  - Social login (Google, GitHub)
  - User profiles and preferences

- [ ] **Database**
  - MongoDB/PostgreSQL integration
  - Data persistence
  - Backup and restore functionality

### AI/ML Features
- [ ] **AI Financial Assistant**
  - Advanced natural language processing for financial queries
  - Personalized financial advice based on spending patterns
  - Interactive financial health assessments
  - Proactive budget alerts and suggestions

- [ ] **Smart Categorization**
  - Automatic transaction categorization using NLP
  - Machine learning for pattern recognition
  - Custom category suggestions

- [ ] **Financial Insights**
  - Predictive analytics for future expenses
  - Budget optimization suggestions
  - Anomaly detection in spending

### Advanced Features
- [ ] **Multi-Currency Support**
  - Automatic currency conversion
  - Support for cryptocurrency
  - Exchange rate history

- [ ] **Mobile App**
  - React Native version
  - Offline functionality
  - Biometric authentication

- [ ] **Reports & Exports**
  - PDF/Excel report generation
  - Custom report builder
  - Email reports

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 🙏 Acknowledgments

- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Chart.js](https://www.chartjs.org/)
- [React Icons](https://react-icons.github.io/react-icons/)

---
