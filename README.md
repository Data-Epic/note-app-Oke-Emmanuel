Smart Notes Manager

Overview
Smart Notes Manager is a Python-based command-line application that allows users to create, manage, and delete text and reminder notes efficiently. The application provides functionalities such as adding text and reminder notes, searching notes by keywords, displaying all saved notes, and deleting specific notes by their unique ID.

Features
- Add Text Notes: Simple notes with only text content.
- Add Reminder Notes: Notes with a specified reminder date and time.
- View All Notes: Display a list of all stored notes.
- Search Notes: Find notes that contain a specific keyword.
- Delete Notes: Remove a note by its unique ID.
- User-Friendly Menu: Interactive command-line interface for easy usage.

Installation
To use the Smart Notes Manager, ensure you have **Python 3.x** installed on your system. No external libraries are required.

Steps to Install & Run:
1. Clone or download this repository.
2. Open a terminal and navigate to the project directory.
3. Run the script using:
   bash
   python smart_notes.py
   

Usage Guide
After running the script, you will be presented with a menu of options:

1. Add a Text Note: Enter text content to save it as a note.
2. Add a Reminder Note: Enter text content along with a reminder date and time in the format `YYYY-MM-DD HH:MM AM/PM`.
3. Show All Notes: Displays all stored notes with their details.
4. Search Notes: Enter a keyword to find matching notes.
5. Delete a Note: Enter the note ID to remove it.
6. Exit: Close the application.

Example Usage
Adding a text note:
```bash
Enter your choice: 1
Enter note content: Meeting at 3 PM
Note added successfully! Note ID: 1
```

Adding a reminder note:
```bash
Enter your choice: 2
Enter reminder content: Doctor's appointment
Enter reminder time (YYYY-MM-DD HH:MM AM/PM): 2024-08-20 09:30 AM
Note added successfully! Note ID: 2
```

Deleting a note:
```bash
Enter your choice: 5
Enter Note ID to delete: 1
Note ID 1 deleted successfully!
```



