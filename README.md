# Flutter Todo App

A simple and elegant todo list application built with Flutter. The app features a clean Material Design interface and uses Hive for persistent local storage.

## Features

- ✨ Clean and intuitive Material Design interface
- 📱 Cross-platform (iOS, Android, Web, Desktop)
- ✅ Create, read, update, and delete tasks
- 💾 Persistent local storage using Hive
- ⚡ Fast and lightweight
- 🎨 Beautiful yellow-themed UI
- 📲 Swipe-to-delete functionality

## Getting Started

### Prerequisites

- Flutter SDK (>=3.2.5)
- Dart SDK (>=3.2.5)

### Installation

1. Clone the repository
```bash
git clone [your-repo-url]
cd todo
```

2. Install dependencies
```bash
flutter pub get
```

3. Run the app
```bash
flutter run
```

## Usage

- Tap the + button to add a new task
- Tap the checkbox to mark a task as complete
- Swipe a task to delete it
- Tasks are automatically saved to local storage

## Dependencies

- `flutter` - UI framework
- `hive: ^2.2.3` - Local storage
- `hive_flutter: ^1.1.0` - Flutter integration for Hive
- `flutter_slidable: ^1.2.0` - Swipeable list tiles

## Development

This project uses Hive for data persistence. The main data structure is a list of tasks, where each task has:
- Task name (String)
- Completion status (bool)

The app follows a simple structure:
```
lib/
  ├── data/
  │   └── database.dart    # Hive database operations
  ├── pages/
  │   └── home_page.dart   # Main UI screen
  ├── util/
  │   ├── dialog_box.dart  # New task dialog
  │   ├── my_button.dart   # Custom button widget
  │   └── todo_tile.dart   # Task list item widget
  └── main.dart           # App entry point
```

## Contributing

Feel free to open issues and pull requests!

## License

This project is open source and available under the [MIT License](LICENSE).
