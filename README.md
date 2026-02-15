Project Overview

This application enables users to manage daily tasks efficiently through a simple terminal interface. Tasks are stored in a local text file, ensuring persistence across multiple executions.

The project was developed as part of a Python Developer Internship assessment, focusing on practical implementation of file handling and data structures.

✨ Key Features

➕ Add new tasks

📋 View all existing tasks

❌ Remove tasks by index

💾 Automatic file-based persistence

⚠️ Input validation and basic error handling

🧹 Clean and structured code design

🛠 Technical Implementation
🔹 Data Storage

Tasks are stored in a Python list during runtime.

Data is persisted using a text file (tasks.txt).

🔹 File Handling

Utilized open() with appropriate file modes (r, w).

Implemented context managers (with statement) for safe file operations.

Handled file absence gracefully.

🔹 Core Concepts Applied

Lists and list manipulation (append(), pop())

Loops and conditional statements

Functions for modular design

Exception handling (try-except)

String manipulation (.strip())

Enumerations using enumerate()
