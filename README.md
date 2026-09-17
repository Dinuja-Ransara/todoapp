# Flutter ToDo App Lab

Welcome to the ToDo App practice lab! In this exercise, you will build a functional ToDo application. You will practice state management (`setState`), passing data and functions to custom widgets, handling text input, and filtering lists.

## 🚀 Getting Started

1. Clone this repository.
2. Add a profile picture to `assets/profile.png` and ensure the `assets` folder is declared in `pubspec.yaml`.
3. Run `flutter pub get`.
4. Open the project in your IDE.

## 📝 Your Tasks

Search for the `TODO` comments in the `lib` folder and build the app step-by-step.

*   **TODO 1 (`todo_item.dart`):** Build the UI for a single ToDo item using a `ListTile`. 
*   **TODO 2 (`home.dart`):** Render the list of ToDo items using a `ListView` or a `for` loop inside a `Column`. Pass the required callbacks for clicking and deleting.
*   **TODO 3 (`home.dart`):** Implement the `setState` logic to add a new item to the list and clear the text field. Ensure you use `DateTime.now().millisecondsSinceEpoch.toString()` for a unique ID.
*   **TODO 4 (`home.dart`):** Implement the search filtering logic so that typing in the search box updates the `_searchToDo` list.
