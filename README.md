# 📚 Sleigh Squad Book Management System

The **Sleigh Squad Book Management System** is a user-friendly, text-based application designed to help individuals track and manage their personal book collections with ease. Whether you're an avid reader or simply want to organize your bookshelf, this Python-powered tool allows you to add, edit, remove, view, and search book entries — all stored in a local `.txt` file for convenience and persistence.

---

## 🚀 Features

- **➕ Add a Book**  
  Enter book details such as a 13-digit ISBN, author, title, genre, and purchase information with built-in input validation.

- **📝 Edit or Update Existing Book**  
  Modify any book field by searching with ISBN or a combination of author and title.

- **🗑️ Delete a Book**  
  Remove books from your list when they're no longer needed.

- **📋 Display Book Collection**  
  View all books in your current library in a neatly formatted table.

- **🔍 Search for a Book**  
  Easily find a book by ISBN, author name, or title — even partial matches.

- **🧹 Clear Screen**  
  Optional screen clearing after actions to keep the console uncluttered.

- **💾 Save and Exit**  
  Automatically stores all changes in `books.txt` before safely exiting.

---

## 📁 Data Management

All records are stored in a plain text file named **`books.txt`**, loaded every time the program starts. This ensures that your book collection remains consistent and up-to-date between sessions.

Each record includes:

- 🔢 ISBN (13 digits)
- ✍️ Author
- 📖 Title
- 🏢 Publisher
- 🏷️ Genre
- 📆 Year Published
- 📅 Date Purchased (dd-mm-yyyy)
- 📗 Status (`read`/`to-read`)

---

## 🖥️ How It Works

### 1. 📦 Set Up the Files
- Ensure that both `book_management_system.py` and `books.txt` are in the same folder.

### 2. 💻 Run the Program
- Open the project folder and run.

### 3. 📜 Navigate the Menu
- Once the program starts, you’ll see the following menu:
1. Add Book Record(s)
2. Delete Book Record(s)
3. Update/Edit Book Record(s)
4. Display
5. Search for Book(s)
6. Exit
7. Clear screen

### 4. 🎯 Choose an Option
- Enter the corresponding number to perform an action.
- The program will guide you with step-by-step prompts and input validation.

### 5. 💾 Save and Exit
- All changes are automatically saved to `books.txt` when you exit using option 6.

---

## 💡 Highlights

- 🧠 Smart validation with user-friendly prompts
- 🆗 Case-insensitive input handling
- 🖥️ Cross-platform compatibility (Windows, macOS, Linux)
- 👀 Clear output formatting for better readability
