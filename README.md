# 📱 WhatsApp Clone (Jetpack Compose)

A **WhatsApp Clone** built using **Jetpack Compose** and **Firebase** that replicates the essential features and design of WhatsApp.  
This project demonstrates modern Android app development using **Kotlin**, **Jetpack libraries**, and **MVVM architecture** with **real-time messaging**.

---

## 🚀 Features

✅ **User Authentication** – Sign up and log in using Firebase Authentication  
✅ **Real-time Chat** – Send and receive messages instantly using Firebase Realtime Database  
✅ **User Status** – Online/offline indicators and last seen feature  
✅ **Profile Management** – Update username, profile picture, and about section  
✅ **Chat List** – View all conversations with timestamps and previews  
✅ **Media Sharing** – Send and receive images in chats  
✅ **Dark Mode** – Fully supports system dark/light themes  
✅ **Push Notifications** – Real-time message alerts via Firebase Cloud Messaging (FCM)

---

## 🛠️ Tech Stack

| Category | Technology Used |
|-----------|-----------------|
| **Language** | Kotlin |
| **UI Framework** | Jetpack Compose |
| **Architecture** | MVVM (Model-View-ViewModel) |
| **Database** | Firebase Realtime Database |
| **Authentication** | Firebase Authentication |
| **Storage** | Firebase Storage |
| **Dependency Injection** | Hilt |
| **Async Tasks** | Kotlin Coroutines, Flow |
| **Navigation** | Jetpack Navigation Component |

---

## 🧩 Project Structure

```
com.example.whatsappclone/
│
├── data/                # Firebase data models and repositories
├── ui/                  # Jetpack Compose screens (Login, Chat, Profile, etc.)
├── viewmodel/           # ViewModels managing UI logic
├── utils/               # Helper classes and constants
└── MainActivity.kt      # App entry point
```

---

## ⚙️ Setup & Installation

Follow these steps to set up the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/saquibbinhalim/whatsapp-clone-jetpack.git
   cd whatsapp-clone-jetpack
   ```

2. **Open in Android Studio**
   - Open the cloned project in Android Studio (Arctic Fox or newer).

3. **Setup Firebase**
   - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).  
   - Add your `google-services.json` file inside the `/app` directory.  
   - Enable **Authentication**, **Realtime Database**, and **Storage** in Firebase.

4. **Build and Run**
   - Connect your Android device or start an emulator.  
   - Click **Run ▶️** in Android Studio.

---

## 🧠 Learning Objectives

- Learn modern **Jetpack Compose** UI development.  
- Implement **real-time chat** using Firebase.  
- Apply **MVVM architecture** for cleaner code management.  
- Use **Hilt** for dependency injection.  
- Handle **asynchronous operations** with Coroutines and Flow.  
- Integrate **Firebase Cloud Messaging** for notifications.

---

## 🧑‍💻 Author

**Saquib Bin Halim**  
💼 Computer Science Engineering Student | Android Developer  
📧 [saquibbinhalim@example.com](mailto:saquibbinhalim.365@example.com)  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/saquib-halim-1b481724b/)
