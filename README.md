# namer_app
# Namer App

A simple and responsive Flutter application that generates cool-sounding random names and allows users to save their favorite names.

This project was built as part of Google's **Build Apps with Flutter** codelab to learn the fundamentals of Flutter and understand how to build a complete application from a single codebase.

## 📱 About the Project

The **Namer App** generates random word combinations such as:

* `newstay`
* `lightstream`
* `mainbrake`
* `graypine`

Users can:

* 🎲 Generate a new random name
* ❤️ Favorite the current name
* ⭐ View all saved favorite names
* 📱 Use the application across different screen sizes
* 🧭 Navigate between the Home and Favorites pages

## 🛠️ Technologies Used

* **Flutter**
* **Dart**
* **Provider** — State management
* **english_words** — Random word-pair generation
* **Material Design**

## ✨ Features

### Random Name Generation

The application generates a new random word pair whenever the **Next** button is pressed.

### Favorites

Users can favorite the currently displayed name using the **Like** button.

### Favorites Page

All saved favorite names are displayed on a separate page. If there are no favorites, the application displays:

> No favorites yet.

### Responsive UI

The application adapts its layout based on the available screen width. The navigation rail becomes extended on larger screens, making the application suitable for different screen sizes.

## 📚 What I Learned

Through this project, I learned:

* The basics of how Flutter works
* How to create layouts using Flutter widgets
* How widgets work together to build a UI
* How to connect user interactions such as button presses to application behavior
* How to manage application state using `ChangeNotifier` and `Provider`
* How to organize Flutter application code
* How to create responsive layouts for different screen sizes
* How to maintain a consistent Material Design look and feel
* How to use external Dart/Flutter packages

## 📂 Project Structure

```text
namer_app/
├── android/
├── ios/
├── lib/
│   └── main.dart
├── test/
├── web/
├── windows/
├── macos/
├── linux/
├── pubspec.yaml
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

* Flutter SDK
* Dart SDK
* Android Studio or VS Code
* An emulator, physical device, or supported desktop/web environment

### Clone the Repository

```bash
git clone https://github.com/aryabhi-hrishith/namer_app.git
```

Navigate into the project:

```bash
cd namer_app
```

Install the dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

## 🎯 Purpose

The purpose of this project was to gain practical experience with Flutter by building a complete application rather than only studying individual concepts.

It helped me understand Flutter widgets, layouts, state management, navigation, user interactions, package usage, and responsive design.

## 🔮 Future Improvements

Possible improvements include:

* Adding animations when generating names
* Adding the ability to remove individual favorites
* Persisting favorites after closing the application
* Adding search functionality
* Improving the visual design
* Adding more customization options

## 📜 Credits

This project was created while following Google's **Build Apps with Flutter** learning codelab.

Built with ❤️ using Flutter.
