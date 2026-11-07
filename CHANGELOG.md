# Personal Budget Management App

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:11998E,100:38EF7D&height=220&section=header&text=Personal%20Budget%20Management%20App&fontSize=50&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Take%20Control%20Of%20Your%20Finances%20With%20Clarity&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-3.2.0-38EF7D?style=for-the-badge&logo=git&logoColor=black)
![Downloads](https://img.shields.io/badge/downloads-96.4K-11998E?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-android%20%7C%20ios%20%7C%20web-00C9FF?style=for-the-badge&logo=react&logoColor=white)

</div>

---

## 💰 Why Another Budget App?

There are hundreds of budgeting apps on the market. Most of them are bloated with ads, require expensive subscriptions, or force you to link your bank account—which many users are uncomfortable with. **Personal Budget Management App** is the open-source alternative you have been waiting for.

This is a privacy-first, fully offline application. It does not connect to your bank; you manually log your expenses (or import a CSV). Because it is open-source, you can audit the code and verify that your financial data never leaves your device. It is lightweight, incredibly fast, and works perfectly on older phones.

But this app is more than just a ledger. It is a powerful financial tool. It includes a dynamic envelope budgeting system, where you allocate your income into categories (Rent, Groceries, Savings) and track your spending against those limits. It generates beautiful, interactive charts that show you exactly where your money is going each month. It is the perfect tool for taking control of your finances.

<img width="1280" height="691" alt="1635178887672" src="https://github.com/user-attachments/assets/7c43f57c-7de2-4fa8-b541-5ec4be1a6541" />


---

## 📱 The App Experience

We have designed the app to be intuitive and stress-free. Here is a quick tour of the core screens.

### 1. The Dashboard
The moment you open the app, you see your financial health at a glance. A large, circular progress bar shows your remaining budget for the current month. Below it, you see your total income and total expenses. The colors change dynamically—green if you are under budget, yellow if you are close to the limit, and red if you have overspent.

### 2. The Quick Log
Logging an expense takes exactly 3 taps. Tap the "Plus" button, type the amount, select a category, and hit save. That's it. The interface is designed to be frictionless, so you actually remember to log your morning coffee.

### 3. The Analytics Screen
Navigate to the reports tab to see detailed breakdowns. You can view your spending by category (pie chart), your spending over time (line chart), or your income vs. expenses (bar chart). You can filter by date range—week, month, year, or custom.

---

<div align="center">

### 🔗 Ready to manage your money?

[![Get App](https://img.shields.io/badge/💰_GET_APP-11998E?style=for-the-badge&logoColor=white)](https://share.google/09smkx8m8jaoQnoiO)

</div>

---

## ✨ Feature Highlights

| Feature | Description |
| :--- | :--- |
| **Offline First** | All data is stored locally in SQLite—no internet required |
| **Envelope Budgeting** | Allocate funds to specific categories and track usage |
| **Recurring Transactions** | Automatically log rent, subscriptions, and salary |
| **CSV Import/Export** | Backup your data or migrate from other apps |
| **Multi-Currency** | Track finances in different currencies with manual rates |
| **Biometric Lock** | Protect your app with fingerprint or Face ID |
| **Dark Mode** | A stunning dark theme for late-night expense logging |

---

## 🧠 Under The Hood: The Database Schema

A budget app is only as good as its data structure. We use a relational SQLite database with three core tables.

The `accounts` table stores your different wallets (Checking, Savings, Cash). Each account has a balance. The `categories` table stores your budget envelopes (Groceries, Rent, Entertainment). Each category has a monthly limit. The `transactions` table is the heart of the system. Every transaction has a type (income or expense), an amount, a date, an account ID, and a category ID.

When you log an expense, the app automatically deducts the amount from the account balance and the category limit. This means your dashboard is always up-to-date in real-time. We use SQLite transactions to ensure that if the app crashes mid-log, the database remains consistent.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-38EF7D?style=for-the-badge&logoColor=black)](https://share.google/09smkx8m8jaoQnoiO)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Reanimated](https://img.shields.io/badge/Reanimated-FF6B6B?style=flat-square&logo=react&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

Personal finance is a deeply personal topic, and we believe the tools to manage it should be transparent and accessible. If you have ideas for new features, found a bug in the budgeting logic, or want to help translate the app, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-chart`).
3. **Commit** your changes (`git commit -m 'Add new chart'`).
4. **Push** to the branch (`git push origin feature/new-chart`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your budgeting tips, ask for help with the app, and discuss the latest trends in personal finance.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@personal-budget.dev.

---

<div align="center">

### ⭐ If this app helps your finances, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/personal-budget-management-app)

---

### 🚀 Start managing your money today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-00C9FF?style=for-the-badge&logoColor=white)](https://share.google/09smkx8m8jaoQnoiO)

<sub>Crafted with precision and ❤️ by the Personal Budget Management App community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:38EF7D,100:11998E&height=120&section=footer)

</div>
