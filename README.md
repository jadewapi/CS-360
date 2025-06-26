# CS 360 Final Mobile App – Weight Tracking App

## 📱 App Overview
This app was designed to help users log their daily weight, set a goal weight, and visually track their progress over time. The main goal was to create a simple and intuitive experience that encourages consistent weight tracking through a user-friendly interface and feedback.

## 🧠 User Needs & UI Design
Users needed:
- A way to **securely log in**
- A **clear way to enter daily weight**
- A way to **set and monitor goal weight**
- A way to receive **SMS alerts when goals are reached**

To support this, I created:
- A **login screen** with account creation
- A **weight tracking screen** with input and a data grid
- A **goal weight screen** with progress bar
- An **SMS permission screen** with fallback handling

I focused on bold labels, minimal inputs, and clear navigation with a bottom nav bar. The UI was designed using Material Design principles to guide users through the app flow with minimal friction.

## 💻 Development Strategy
I followed an iterative approach: First I implemented login + database shell, then the CRUD operations for weight entries. I used **SQLiteOpenHelper** for data handling and a **RecyclerView adapter** for the weight grid. I built everything in small pieces and tested each feature as I went.

## 🧪 Testing & Debugging
I used the Android Emulator and tested every flow: user creation, login, add/edit/delete weights, and SMS permission handling. I used toasts to verify functionality and fixed bugs step-by-step when errors occurred. This helped me make sure everything worked as intended.

## 💡 Problem Solving
One major challenge was resolving Gradle source layout conflicts, which initially prevented my click listeners from firing. I learned to restructure the `kotlin/` folder and sync Gradle properly. Another issue was handling multiple class declarations—cleaning up helped eliminate redeclaration errors.

## 🌟 Highlight
One of my strongest areas was implementing full CRUD functionality and dynamic data updates with `RecyclerView`. This part really showed how much I’ve grown in writing functional Kotlin code and designing interactive, real-world Android screens.
