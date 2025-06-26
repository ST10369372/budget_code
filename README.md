Github: https://github.com/ST10369372/budget_code.git
Youtube:  https://www.youtube.com/shorts/33wKvL_6MQY?si=xk0kBLQAJMxbKnf9

# budget_code – Android Budget Tracking App

## 💡 Overview

BudgetEase is a Kotlin-based Android app that helps users easily track their income, expenses, savings goals, and visualize spending with clean graphs. This version features a modern design with optimized layouts and responsive components to enhance the user experience.

---

## 🚀 Latest Updates

### 🔄 June 2025 Updates
- ✅ Redesigned Savings Goal layout for better visibility (larger input fields, 48dp height).
- ✅ Buttons repositioned beside relevant input fields for cleaner UI.
- ✅ Removed unnecessary padding and unused views to improve layout spacing.
- ✅ Integrated dynamic Expense Graph view:
  - Monthly spending breakdown
  - Color-coded category bars
  - Budget goal tracking
- ✅ Added HTML-based monthly report preview in `ExpenseGraphActivity`.
- ✅ Inputs now validated before being saved.
- ✅ All data is now persisted using **Room Database**.

---

## 📱 Features

- **Dashboard**: View total income, expenses, and quick access to all features.
- **Add Entry**: Add income or expense with custom category and description.
- **Expense Graph**: Visualize spending by category with timeline selection.
- **Savings Sheet**: Set financial goals with target amount and timeline.
- **History**: Browse past entries and progress towards goals.
  

---

## 🔧 How to Use

### 🏁 Getting Started
1. Clone the repository to your local machine.
2. Open the project in **Android Studio**.
3. Sync Gradle and run the app on your emulator or Android device.

### 👤 Usage Flow
1. **Login/Register** from the main screen.
2. On the **Dashboard**, tap:
   - ➕ *Add Entry* to log expenses/income.
   - 📊 *View Graph* to analyze spending.
   - 🎯 *Savings Sheet* to set & track goals.
   - 📖 *History* to view past data.

3. All data is stored locally using Room DB.

---

## 🛠 Tech Stack

- Kotlin
- XML Layouts (Material Design)
- Room Database
- AndroidX
- MPAndroidChart (or native `Canvas` for graphs if you opted out of GitHub libraries)

---

