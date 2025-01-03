# UI-Flutter-Project

```markdown
# Todo Application - Flutter

This is a simple Todo application built using Flutter. The app allows users to add tasks, view them in a list, and delete tasks.

## Features

- Add new tasks to the Todo list.
- View all added tasks.
- Delete tasks from the list.
- User-friendly interface with a clean and simple design.

## Getting Started

### Prerequisites

Before running the app, make sure you have the following installed on your system:

- **Flutter SDK**: [Flutter Installation Guide](https://flutter.dev/docs/get-started/install)
- A code editor like **VSCode**, **Android Studio**, or **IntelliJ IDEA**.

### Clone the repository

To clone this repository, run the following commands in your terminal:

```bash
git clone https://github.com/yourusername/flutter_todo_app.git
cd flutter_todo_app
```

Replace `yourusername` with your actual GitHub username if you're cloning from a personal repository.

### Install dependencies

Run the following command to install the required dependencies:

```bash
flutter pub get
```

This will fetch all the necessary packages for the project.

### Run the app

To run the app, use the following command in your terminal:

```bash
flutter run
```

Make sure that your emulator or connected device is running.

## App Screens

The app consists of a single screen with:

1. **AppBar (Header)**: Displays the title "Todo Application."
2. **Task List**: Displays the added tasks. Each task is shown in a `Card` widget with a delete button.
3. **Text Input Field**: Allows the user to enter new tasks.
4. **Add Button**: A button to add the entered task to the list.

## Code Structure

The code is organized as follows:

- **`main.dart`**: The entry point of the app. It contains the `MyApp` widget that sets up the `MaterialApp` and theme, as well as the `HomeScreen` widget which holds the UI logic.
  
- **`HomeScreen` Widget**: The main screen of the app that manages a list of tasks. It includes logic for adding and deleting tasks:
  - `addString(content)`: Updates the input value for creating a task.
  - `addList()`: Adds a new task to the `todoList`.
  - `deleteItem(index)`: Removes a task from the list.

## UI Design

### Home Screen Layout

- The app uses a simple layout where:
  - The AppBar displays the title "Todo Application" with a bold font.
  - The task list is displayed in a `ListView` with `Card` widgets for each task.
  - Each task is shown with a delete button (a circle button with a trash icon).
  - A `TextFormField` at the bottom allows the user to enter a task, and an "Add" button adds the task to the list.

### Styling

- The theme of the app uses a primary color of **indigo**.
- The tasks are displayed in **blue** `Card` widgets with white text.
- The input field is styled with rounded corners, and the "Add" button is an **ElevatedButton** with a simple label.

## Contributing

If you'd like to contribute to the project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Flutter** documentation and community for providing the framework and libraries.
- **Icons** used in the app are from the `flutter/material` package.
```

### Notes:
- Replace the GitHub URL in the "Clone the repository" section with the actual link to your repository.
- The `LICENSE` file mentioned in the license section should be added if you plan to make your project open source. If not, feel free to modify the licensing terms as needed.
