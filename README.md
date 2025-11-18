# 📚 BookHub – Android Book Library App

BookHub is an Android application built as part of my college coursework.  
The app allows users to browse books, view descriptions, mark favourites, and navigate through different sections using a clean and simple UI.

This project demonstrates my early exposure to software development and mobile app architecture using **Kotlin**, **Android SDK**, **Room Database**, and **API/JSON parsing**.

---

## ⭐ Features

### 📖 Browse Books
- Displays a list of books with title, author, rating, and price.
- Uses **RecyclerView** for smooth scrolling and list display.

### 📚 Book Details Page
- Shows detailed information about each book.
- Includes book description, image, and rating.

### ❤️ Favourites Section
- Allows users to mark/unmark books as favourites.
- Uses **Room Database** for local data storage.

### 🧭 Navigation Drawer
- Home
- Favourites
- Profile
- App Info
- Logout

### 🔍 Sorting & Filtering
- Sort books based on rating or price.

### 🌐 API/JSON Integration
- Loads book list via a JSON API or static JSON structure (depending on build).

### 🎨 Clean UI
- Custom icons  
- Android XML layouts  
- Adaptive design  

---

## 🛠️ Tech Stack

**Language:** Kotlin  
**UI:** XML Layouts, RecyclerView  
**Database:** Room (Local Storage)  
**Networking:** JSON parsing / API Fetching  
**Android Architecture:**  
- Activities  
- Adapters  
- Models  
- Fragments (if used)  
- Navigation Drawer  

**Tools:**  
- Android Studio  
- Gradle  
- Android Emulator

---

## 🗂️ Project Structure

app/
├── src/
│ ├── main/
│ │ ├── java/com/internshala/bookhub/
│ │ │ ├── activity/
│ │ │ ├── adapter/
│ │ │ ├── database/
│ │ │ ├── fragment/
│ │ │ ├── model/
│ │ ├── res/
│ │ │ ├── layout/
│ │ │ ├── drawable/
│ │ │ ├── menu/
│ │ │ ├── values/
│ │ ├── AndroidManifest.xml
├── build.gradle
├── gradle.properties
└── app-release.apk

yaml
Copy code

---

## 📱 APK Included
The repository includes a **compiled APK (app-release.apk)** so the app can be installed and tested directly on an Android device.

---

## 📌 Note
This project was originally created as a **college assignment**, and I have uploaded it to showcase my learning journey and exposure to application development.  
I am not actively developing Android apps today, but this project reflects my ability to work with structured codebases and modern development tools.

---

## 👩‍💻 Author

**Maryam Suhana**  
Technical Support Engineer | Cloud & SaaS Enthusiast  
📍 NSW, Australia  
🔗 LinkedIn: www.linkedin.com/in/maryam-suhana-222a57195
