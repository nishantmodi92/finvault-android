# FinMate – Personal Finance & Expense Tracking App

## 🚀 Overview
FinMate is a smart finance tracker for expenses, budgets, category insights, charts, reminders, and offline storage.

---

## 🛠 Tech Stack
- Kotlin  
- Compose  
- Room  
- WorkManager  
- Hilt  
- Clean Architecture  

---

## ⭐ Features
- Add & track expenses  
- Category-based insights  
- Monthly budgets  
- Offline mode  
- Background backup sync  
- Analytics dashboard  

---

## Room Schema
```kotlin
@Entity(tableName = "expenses")
data class Expense(
  @PrimaryKey val id: String,
  val category: String,
  val amount: Double,
  val timestamp: Long
)
Performance

Cached analytics

Compose charts
