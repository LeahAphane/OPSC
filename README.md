# OPSC
ByteBalance Android Application

ByteBalance is a powerful and user-friendly Android budgeting app that helps users track expenses, set goals, upload receipts, and improve financial habits through gamification and insights.

 How to Run the App

 Option 1: Android Studio (Developers & Testers)

1. Clone the repository:
   git@github.com:LeahAphane/OPSC.git

2. Open the project in Android Studio.

3. Add Firebase Configuration:
   - Download `google-services.json` from your Firebase Console.
   - Place it inside the `app/` directory.

4. Sync Gradle and wait for dependencies to load.

5. Connect an emulator or Android device, then click Run.

 
### How to Use ByteBalance

### 1. Sign Up / Login
- Sign in with email and password.
- New users can register directly in the app using Firebase Authentication.

### 2. Add Expenses
- Tap the “+” button to add a new expense.
- Enter amount, category, optional note, and date.
- Tap Save to log the transaction.

### 3. Set Budget Goals
- Navigate to the "Budget Goals" section.
- Set limits by category or total monthly spending.
- Track your spending progress in real time.

### 4. Upload Receipts
- When logging an expense, attach a photo or screenshot of the receipt.
- Receipts are securely stored using Firebase Storage.

### 5. View Dashboards
- Analyze your financial habits using charts and graphs.
- Visualize where your money is going over days, weeks, and months.

### 6. Earn Rewards
- Unlock badges by:
  - Staying under budget
  - Logging expenses daily
  - Achieving savings goals

### 7. Get Smart Notifications
- Receive helpful alerts and reminders:
  - Budget nearing/exceeded
  - Goal progress
  - Daily logging reminders

### 8. Emergency Fund Tracker
- Set a custom savings goal for emergencies.
- Monitor your progress and adjust as needed.

### 9. Payment Integration
- Supports linking with Google Pay, PayPal, or Apple Pay.
- Auto-log supported transactions (with permission).

### 10. Manage Account Settings
- Edit your profile
- Export your financial data
- Reset password or log out

---

## 📦 Tech Stack

- Frontend: Kotlin, Android Studio
- Backend: Firebase (Auth, Firestore, Storage)
- Charts: MPAndroidChart
- Payment Integration: Google Pay / PayPal / Apple Pay

---

##  Testing

- Unit testing and UI testing with Espresso (WIP)
- GitHub Actions for CI/CD


This project is licensed under the MIT License.

---

## 🙋 Need Help?

Open an issue on the repository or contact the developer via email.
