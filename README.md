# 📱 Socially – CS4039 Assignment 1

A social networking mobile app built in **Kotlin** with **Android Studio** as part of **CS4039 – Software for Mobile Devices** coursework.

The project demonstrates modern Android development practices, UI design, and smooth user interactions.

---

## 🚀 Features

- 👤 **User Profiles** – basic profile setup and viewing
- 🖼️ **Photo Sharing** – upload and display images
- 📰 **Social Feed** – scrolling posts with likes & comments (UI only for this assignment)
- 📖 **Stories (UI)** – temporary media preview layout
- ✉️ **Direct Messaging (UI)** – messaging screen design
- 🔔 **Real-Time Notifications (UI)** – mock notifications layout
- ➡️ **Navigation** – smooth transitions with back stack support

---

## 🎨 UI Highlights

- Pixel-perfect implementation of the provided **Socially UI.pdf**
- Consistent color scheme, typography, and spacing
- Responsive layouts for both **portrait** and **landscape**
- Accessibility-friendly (readable fonts, strong contrasts)

---

## 🛠️ Tech Stack

- **Language:** Kotlin
- **Framework:** Android SDK
- **UI Components:** ConstraintLayout, ScrollView, CardView, Material Widgets
- **Version Control:** Git + GitHub
- **Testing:** Espresso (basic UI tests)

---

## 📂 Project Structure

```
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/yourpackage/socially/
│   │   │   │   ├── activities/          # Main activities
│   │   │   │   ├── adapters/            # RecyclerView adapters
│   │   │   │   ├── models/              # Data models
│   │   │   │   └── utils/               # Utility classes
│   │   │   ├── res/
│   │   │   │   ├── layout/              # XML layout files
│   │   │   │   ├── drawable/            # Images and icons
│   │   │   │   ├── values/              # Colors, strings, styles
│   │   │   │   └── mipmap/              # App icons
│   │   │   └── AndroidManifest.xml
│   │   └── androidTest/                 # Espresso tests
│   └── build.gradle
├── README.md                            # Project documentation
└── build.gradle                         # Project-level build file
```

---

## ✅ Evaluation Coverage

- **UI Accuracy (30%)** – replicated given designs
- **Component Integration (15%)** – CardView, ScrollView, Widgets
- **Smooth Navigation (15%)** – working buttons, proper back stack
- **Accessibility & Responsiveness (5%)** – responsive layouts
- **Version Control (10%)** – regular commits with meaningful messages
- **Test Cases (5%)** – 2 Espresso tests for navigation & button clicks
- **Live Demo (20%)** – app ready for presentation

---

## 🧪 Test Cases

1. **Navigation Test:** verifies switching between main feed and profile screen
2. **Button Click Test:** validates like button functionality in the feed

---

## 📸 Screenshots

*Screenshots will be added here showing:*
- Main feed with posts
- User profile screen
- Stories preview
- Direct messaging interface
- Notifications screen

---

## 📌 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SerenitysSlave/SmdAss1.git
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an existing project"
   - Navigate to the cloned folder and select it

3. **Setup and Build**
   - Sync Gradle and build the project
   - Ensure you have Android SDK API level 26+ installed

4. **Run the App**
   - Connect a physical device or start an emulator (Android 8.0+)
   - Click the "Run" button or press Shift + F10

---

## 🔧 Requirements

- **Android Studio:** Arctic Fox or newer
- **Minimum SDK:** API 26 (Android 8.0)
- **Target SDK:** API 34 (Android 14)
- **Kotlin:** 1.8+

---

## 📝 Commit Strategy

- Each screen/feature = separate commit
- Descriptive commit messages (e.g., "Added profile screen layout", "Implemented feed navigation")
- Progressive development history showing clear milestones

---

## 🤝 Contributing

This is an academic project for CS4039. If you're a fellow student:
- Feel free to reference the structure and approach
- Please don't copy code directly (academic integrity)
- Consider this as inspiration for your own implementation

---

## 📋 Assignment Checklist

- [x] UI Implementation matching provided design
- [x] Navigation between screens
- [x] Responsive layouts (portrait/landscape)
- [x] Material Design components
- [x] Accessibility considerations
- [x] Version control with meaningful commits
- [x] Espresso test cases
- [x] Project documentation

---

## 👨‍💻 Author

**Abdullah Azeem** (22I-1186)  
CS4039 – Software for Mobile Devices  
*NUCES FAST* | *2022*

---

## 📄 License

This project is created for academic purposes as part of CS4039 coursework.

---

*Last updated: [Current Date]*
