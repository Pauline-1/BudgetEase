# 📊BudgetEase– Personal Budget Tracker App

**BudgetEase** 
Budget Ease is a Kotlin-based Android application designed to help users manage their personal finances. The app includes secure login and registration, allowing users to track their income and expenses. All data is stored locally using Room Database, making it ideal for offline use.

---


## 🚀 Features

- 📋 **Register & Login** – Secure authentication system for user access
- 💸 **Add Expense** – Add an expense with description, category, date, and optional photo
- 🗂️ **View Expenses** – Displays all expenses in a RecyclerView card layout
- 📅 **Set Budget Goals** – Users can set monthly spending limits
- 📈 **View Summary** – Filter and summarize spending by category, month, or date range

---

## 🛠️ Tech Stack

- **Language**: Kotlin
- **IDE**: Android Studio
- **UI Framework**: Android Views (XML-based)
- **Database**: SQLite (via `SQLiteOpenHelper`)
- **Navigation**: Intents between Activities
- **Image Upload**: Optional image picker per expense

---

## 📂 Project Structure

BudgetEase/
├── app/
│ ├── java/com/example/bytebalance/
│ │ ├── activities/
│ │ │ ├── LoginActivity.kt
│ │ │ ├── RegisterActivity.kt
│ │ │ ├── DashboardActivity.kt
│ │ │ ├── AddExpenseActivity.kt
│ │ │ ├── ViewExpensesActivity.kt
│ │ │ └── ViewSummaryActivity.kt
│ │ ├── database/
│ │ │ └── DBHelper.kt
│ │ ├── model/
│ │ │ └── Expense.kt
│ │ └── adapter/
│ │ └── ExpenseAdapter.kt
│ ├── res/
│ │ ├── layout/
│ │ │ ├── activity_login.xml
│ │ │ ├── activity_register.xml
│ │ │ ├── activity_dashboard.xml
│ │ │ ├── activity_add_expense.xml
│ │ │ ├── activity_view_expenses.xml
│ │ │ └── activity_view_summary.xml
│ │ └── drawable/
│ │ └── button_green.xml

