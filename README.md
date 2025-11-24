SpendWise – Personal Finance Tracker (Android App)

SpendWise is a modern personal finance management app built using Kotlin, MVVM architecture, Room Database, and Material Design 3.
It helps users track daily expenses, manage budgets, set savings goals, and visualize spending patterns — all in a clean and user-friendly UI with full Light/Dark Mode support.

✨ Features
🔐 Authentication

Welcome, Login, Register, Forgot Password, and Reset Password screens

Email + password validation

Secure Logout functionality that clears user session

💸 Transactions Management

Add Income & Expense transactions

Categories via dropdown

Date picker for accurate tracking

View full transaction list

Automatic dashboard updates

“Latest Transactions” preview on Dashboard

Edit & Delete options for each transaction

📊 Dashboard & Insights

Total income vs expenses

Recent transactions

Category-wise visualization

Material 3 card layout

Fully responsive UI

📁 Categories

Add custom categories

Manage and store categories in Room DB

Integrated with Transactions & Budgets

📅 Budgets

Create monthly budgets per category

Automatic calculation of:

Spent

Remaining

Utilization percentage

Real-time updates as user adds transactions

🎯 Savings Goals

Add goals with target amounts

Track progress with dynamic progress bars

Tap goal → add saved amount

Long press → delete goal

🌓 Theme Support

Full Dark Mode using Material Design 3 colors

Settings switch to toggle theme

Screens fully updated to use theme-aware colors

🧭 Navigation

Uses Jetpack Navigation Component

Bottom Navigation with 5 sections:

Home

Transactions

Budgets

Chatbot

Settings

🛠️ Tech Stack
Languages & Frameworks

Kotlin

XML

Material Design 3

Architecture

MVVM

LiveData

ViewModel

Repository Pattern

Room Database (DAO + Entities)

Libraries

Jetpack Navigation Component

Material Components

Room Database

RecyclerView

📂 Project Structure
SpendWise/
│
├── data/
│   ├── dao/
│   ├── entity/
│   ├── repository/
│   └── AppDatabase.kt
│
├── ui/
│   ├── dashboard/
│   ├── transactions/
│   ├── budgets/
│   ├── goals/
│   ├── settings/
│   └── authentication/
│
├── viewmodel/
│
├── res/
│   ├── layout/
│   ├── values/
│   └── navigation/
│
└── MainActivity.kt

🚀 Setup & Installation

Clone the repository:

git clone https://github.com/your-username/SpendWise.git


Open the project in Android Studio.

Let Gradle sync and install dependencies.

Run the app on:

Emulator

Physical Android device

🧪 Testing the App

Use the app as follows:

Register a new account

Add categories

Add income & expense transactions

Set budgets

Create savings goals

Toggle Light/Dark mode

Logout and re-login

All data persists via Room Database
