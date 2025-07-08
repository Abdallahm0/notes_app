 📝 Flutter Note App

A clean and minimal note-taking application built with **Flutter** and **SQLite**. The app allows users to create, read, update, and delete notes (CRUD operations), all stored locally on the device. It features a responsive UI, custom models, and seamless local database integration using `sqflite`.

 🚀 Features

- 📄 View a list of all notes sorted by creation time
- ➕ Create new notes with title and content
- 📝 Edit existing notes
- 🗑️ Delete notes with confirmation
- 💾 Data stored locally using SQLite via `sqflite` package
- 🕒 Notes display creation timestamp
- 📱 Responsive and user-friendly UI using Flutter widgets

 🛠️ Tech Stack

- **Flutter & Dart**
- **State Management:** `setState`
- **Database:** `sqflite` (SQLite for Flutter)
- **Local Storage Integration:** `path_provider`
- **UI:** Material Design

 📂 Project Structure

 lib/
├── main.dart                # App entry point and MaterialApp setup
├── notes_screen.dart        # Main screen showing list of notes and navigation to edit screen
├── edit_note_screen.dart    # Screen for creating and editing notes
└── notes_database.dart      # Note model and SQLite database handler (CRUD operations)

📸 Screenshots

![WhatsApp Image 2025-07-08 at 03 15 18_ec806ad9](https://github.com/user-attachments/assets/cae9ba7a-bcdd-4d3b-ba1a-2902f0e37e6b)
![WhatsApp Image 2025-07-08 at 03 15_b4ec2a32](https://github.com/user-attachments/assets/23aac75b-db7a-4b96-aa9c-f7033d9d9b32)
![WhatsApp Image 2025-07-08 at 03 15 18_e1857ea4](https://github.com/user-attachments/assets/df0aebfd-52a2-4d53-90e6-b227d1bcf845)


