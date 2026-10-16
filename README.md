Here is the updated README.md with standard emoji icons to give it a fresh and modern look! 🚀

📝 Smart Notes Application
A desktop note-taking application built with Python 3 🐍 and PyQt5 🎨. This project allows users to create, view, edit, delete, and tag notes with persistent JSON storage 💾.

✨ Features
📝 Note Management: Create, edit, save, and delete notes dynamically.

🏷️ Tag System: Add and detach tags to organize your notes effortlessly.

🔍 Tag Search: Filter notes based on selected tags.

💾 Auto-Save & Persistence: Notes are saved locally in notes_data.json.

💻 Clean GUI: Minimalist dual-column layout powered by PyQt5.

📋 Prerequisites
Make sure you have Python 3.x installed on your machine.

🚀 Installation & Setup
Clone or download the project files to your local machine.

Install PyQt5 via pip:

Bash
pip install PyQt5
Run the application:

Bash
python main.py
📁 Project Structure
📜 main.py — Main Python script containing GUI layouts, event bindings, and JSON file handling.

📄 notes_data.json — Automatically generated file storing your notes and tags in JSON format.

⚙️ How It Works
🎯 Launch: Running the program checks for notes_data.json. If missing, default welcome notes are generated.

📌 Select Note: Click any note in the list on the right to load its content into the text area and populate its tags.

✏️ Create / Edit / Save: Click "Створити замітку" to add a new note or "Зберегти замітку" to save updates.

🏷️ Tags: Add or detach tags using the action buttons under the tag list.
