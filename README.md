# 📝 Simple Flutter ToDo App

A minimal Flutter ToDo app with **Slidable swipe-to-delete**, checkboxes, and a simple text input field.  
Built using `StatefulWidget` and Flutter’s built-in state management.

---

## ✅ Features

- Add new ToDo items
- Mark tasks as completed
- Swipe to delete tasks (using `flutter_slidable`)
- Clean and responsive UI
- Uses local in-memory state

---

## 📂 Project Structure

```

lib/
├── main.dart            # App entry point
├── pages/
│   └── home\_page.dart   # Home screen with task list & input
├── utils/
│   └── todo\_list.dart   # Reusable list item widget with Slidable

````

---

## 🧩 Packages Used

- [flutter_slidable](https://pub.dev/packages/flutter_slidable)

---

## 🚀 Getting Started

1️⃣ **Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/flutter_todo_slidable.git
cd flutter_todo_slidable
````

2️⃣ **Install dependencies**

```bash
flutter pub get
```

3️⃣ **Run the app**

```bash
flutter run
```

---

## 🗂️ How it works

* `HomePage` holds your task list (`List<List<dynamic>>`) in local state.
* The `TodoList` widget displays each task with a checkbox and swipe-to-delete action.
* Tasks are stored in memory only — closing the app clears them.

---

## 📌 Next steps

* Add `Provider` for state management
* Add local storage (Hive, SharedPreferences)
* Support task editing

---

## 📜 License

This project is licensed under the MIT License.

---

## ✨ Author

Built with ❤️ by [Amal Anan](https://github.com/amalanan/)

```

---
