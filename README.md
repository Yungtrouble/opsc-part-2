# opsc-part-2

https://github.com/Yungtrouble/opsc-part-2


YOUTUBE LINK: https://youtu.be/ipMONJiy0b8

# 💰 Budget Buddy

Budget Buddy is a mobile budgeting app built with **Jetpack Compose** for Android. It helps users track expenses, set monthly budget goals, and visualize spending through a simple and intuitive interface.

## 📱 Features

- 🔐 **User Authentication** – Register and log in with an email and password.
- 📊 **Track Expenses** – Add expenses with optional descriptions.
- 🎯 **Set Budget Goals** – Define monthly limits to stay on track.
- 📈 **Visual Reports** – Graphical insights into your spending patterns.
- 🧠 **User-Friendly Design** – Built with Compose for a smooth UI experience.

## 🛠️ Technologies Used

- Kotlin
- Jetpack Compose
- Android Jetpack (Navigation, ViewModel, LiveData)
- RoomDB (for local storage)
- Git + GitHub (version control)
- GitHub Actions (for CI/CD testing)

## 📂 Project Structure

├── MainActivity.kt
├── ui/
│ ├── theme/
│ └── components/
├── screens/
│ ├── LoginScreen.kt
│ ├── RegisterScreen.kt
│ ├── HomeScreen.kt
│ ├── SetBudgetGoalScreen.kt
│ └── TrackExpenseScreen.kt
├── data/
│ ├── User.kt
│ └── AppDatabase.kt
├── viewmodel/
│ ├── UserViewModel.kt
│ └── UserViewModelFactory.kt
└── repository/
└── UserRepository.kt          


Open in Android Studio.

Set the minimum SDK to API 21 or higher.

Run the app on your emulator or device.

🧪 Testing
🧪 Testing
GitHub Actions are configured for automated testing on every push.

Unit tests cover basic authentication logic and database operations.

👤 Authors
Tumelo Sekobane – ST10335989

Gontse Mphaka -ST10390951 

📅 Submission
This repository is submitted for the OPSC Part 2 assignment as a working prototype of the Budget Buddy mobile application.
