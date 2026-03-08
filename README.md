# Expense Tracker

A simple and modern **Flutter expense tracking application** that helps users monitor spending, track their remaining balance, and visualize expenses.

The app focuses on **clean UI, smooth user experience, and offline functionality** using local storage.

---

## Features

- Add and store daily expenses
- Automatically update remaining balance
- Visualize spending with charts
- Simple and intuitive UI
- Offline storage (no internet required)
- Option to reset stored expense data

---

## Tech Stack

- **Framework:** Flutter
- **Language:** Dart
- **Local Storage:** SQLite / SharedPreferences
- **Charts:** Flutter chart libraries

---

## Project Structure

```
lib/
│
├── models/
│   Data models used in the application.
│   Example: expense objects and data structures.
│
├── screens/
│   All UI screens of the application.
│   Example: home screen, add expense screen, settings screen.
│
├── storage/
│   Handles data persistence and local database logic.
│
├── utils/
│   Utility files such as constants, helpers, and reusable logic.
│
└── main.dart
    Application entry point.
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/atishayvidyarthi-ux578/Expense-Tracker.git
cd Expense-Tracker
```

### 2. Install dependencies

```bash
flutter pub get
```

### 3. Run the app

```bash
flutter run
```

Make sure you have **Flutter installed** and an **Android emulator or physical device** connected.

---

## Purpose of the Project

This project was built to:

- Practice Flutter development
- Learn about local data storage
- Improve UI/UX design skills
- Build a functional personal finance tool

---

## Future Improvements

Possible enhancements:

- Expense categories
- Budget limits
- Dark mode
- Monthly analytics
- Export expense data
- Cloud sync and backup

---

## License

This project is open source and available under the **MIT License**.