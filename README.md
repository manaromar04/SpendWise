#  SpendWise – Personal Finance Tracker (Android App)

SpendWise is a modern personal finance management app built using **Kotlin**, **MVVM architecture**, **Room Database**, and **Material Design 3**.  
It helps users track daily expenses, manage budgets, set savings goals, and visualize spending patterns — all in a clean and user-friendly UI with full **Light/Dark Mode** support.

---

##  Features

###  Authentication
- Welcome, Login, Register, Forgot Password, and Reset Password screens  
- Email + password validation  
- Secure Logout functionality that clears user session

###  Transactions Management
- Add Income & Expense transactions  
- Categories via dropdown  
- Date picker for accurate tracking  
- View full transaction list  
- “Latest Transactions” widget on Dashboard  
- Edit & Delete actions per transaction

###  Dashboard & Insights
- Total income vs expenses  
- Recent transactions  
- Category-based spending visualization  
- Material 3 card layout  
- Responsive and intuitive UI

###  Categories
- Add custom categories  
- Integrated seamlessly with Transactions & Budgets  
- Stored in Room Database

###  Budgets
- Create monthly budgets per category  
- Auto-calculates:
  - Spent  
  - Remaining  
  - Utilization percentage  
- Updates live when transactions are added

###  Savings Goals
- Add goals with target amounts  
- Visual progress with progress bars  
- Tap goal → add saved amount  
- Long press → delete goal

###  Theme Support
- Full **Dark Mode** using Material Design 3 dynamic surfaces  
- Settings toggle to switch theme  
- All screens fully theme-aware

###  Navigation
- Jetpack Navigation Component  
- Bottom Navigation with:
  - Home
  - Transactions
  - Budgets
  - Chatbot
  - Settings

---

##  Tech Stack

### Languages & Frameworks
- Kotlin  
- XML  
- Material Design 3  

### Architecture
- MVVM  
- LiveData  
- ViewModel  
- Repository Pattern  
- Room Database (DAO + Entities)

### Libraries
- Jetpack Navigation Component  
- Material Components for Android  
- Room Database  
- RecyclerView  

---

##  Project Structure

SpendWise/
│
├── data/
│ ├── dao/
│ ├── entity/
│ ├── repository/
│ └── AppDatabase.kt
│
├── ui/
│ ├── dashboard/
│ ├── transactions/
│ ├── budgets/
│ ├── goals/
│ ├── settings/
│ └── authentication/
│
├── viewmodel/
│
├── res/
│ ├── layout/
│ ├── values/
│ └── navigation/
│
└── MainActivity.kt
