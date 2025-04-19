# 📝 Taking Notes App

A simple Android notes app built in Java that allows users to add, edit, and delete notes. It also includes persistent storage using Room Database and SharedPreferences for offline access.

## 📱 Features

- **Create**: Add new notes
- **Read**: View all notes in a list
- **Update**: Edit existing notes
- **Delete**: Delete notes with confirmation
- Save notes locally using **Room Database** and **SharedPreferences**
- Splash screen on app startup
- Simple and clean user interface


## 🏗️ Built With

- **Java** (Android)
- **Room Database** – for local data storage
- **SharedPreferences** – for quick note persistence
- **RecyclerView** – for displaying notes in a list
- **Material Design** – UI components

## 📂 Project Structure

```plaintext
com.muqaddas.takingnotesapp
│
├── MainActivity.java           # Main screen to handle notes
├── SplashActivity.java         # Splash screen at startup
├── Note.java                   # Data entity for Room
├── NoteDao.java                # Data Access Object for Room
├── NotesAdapter.java           # RecyclerView Adapter
├── NotesDatabase.java          # Room database instance
├── activity_main.xml           # Layout for MainActivity
└── AndroidManifest.xml         # App manifest and activity declarations
