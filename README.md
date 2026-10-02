# 💰 SpendWise

<p align="center">
  <b>Track your money. Organize your tasks. Stay in control.</b>
</p>

<p align="center">
  A clean and simple Flutter application for managing daily expenses and tasks in one place.
</p>

---

## ✨ Overview

**SpendWise** is a Flutter-based personal productivity app that combines **expense tracking** and **To-Do management** into a single, easy-to-use interface.

Track where your money goes, organize your daily tasks, and get a quick overview of your spending and productivity through the built-in dashboard.

The application uses **local storage**, so your expenses and tasks remain available when you reopen the app.

---

## 🚀 Features

### 💸 Expense Tracker

- Add expenses with title, amount, category, and date
- Categorize expenses into:
  - 🍔 Food
  - 🚗 Transport
  - 🎮 Fun
- View total spending
- View today's spending
- Filter expenses by date
- Swipe left to delete expenses
- Validation for invalid titles and amounts

### ✅ To-Do List

- Add daily tasks
- Mark tasks as completed
- Track completed vs total tasks
- Swipe left to delete tasks
- Prevent empty tasks from being added
- Automatically track when tasks were created

### 📊 Dashboard

Get a quick overview of your activity with:

| Metric | Description |
|---|---|
| 💰 Total Spent | Total amount spent across all expenses |
| 📅 Today's Spending | Amount spent today |
| ✅ Tasks Done | Completed tasks compared to total tasks |
| 📋 Tasks Added Today | Tasks created today |

---

## 💾 Local Data Persistence

SpendWise uses **SharedPreferences** to store expense and To-Do data locally.

Data is converted to JSON before being stored and restored when the application starts.

This means your data can persist between app sessions without requiring a backend or database.

---

## 🎨 UI & Design

SpendWise uses Flutter's **Material 3** design system with:

- Clean and minimal interface
- Google Poppins typography
- Reusable UI components
- Responsive layouts
- Date pickers and dropdown controls
- Swipe-to-delete interactions
- Dashboard metric cards

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Flutter** | Application framework |
| **Dart** | Programming language |
| **Material 3** | UI & design system |
| **SharedPreferences** | Local data persistence |
| **Intl** | Date formatting |
| **Google Fonts** | Typography |
| **Cupertino Icons** | Icon support |

---

## 📂 Project Structure

```text
lib/
│
├── main.dart
│
├── models/
│   ├── expense.dart
│   └── todo.dart
│
├── screens/
│   ├── expense_screen.dart
│   ├── todo_screen.dart
│   └── dashboard_screen.dart
│
└── widgets/
    ├── dashboard_metric_card.dart
    ├── expense_card.dart
    └── todo_tile.dart

assets/
└── logo.png
```

<p align="center">
  🚀 Made using Flutter & Dart
</p>
