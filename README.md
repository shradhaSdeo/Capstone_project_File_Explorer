 🗂️ File Explorer – C++ Capstone Project

 📖 Project Description
The File Explorer is a C++ command-line based application that works like a simple file management system.  
It allows users to perform various file and folder operations — such as listing, creating, deleting, copying, moving, and searching — directly from the terminal.

The project is built using modern C++17, mainly the `<filesystem>` library, to manage directories, handle files, and control permissions securely and efficiently.

---

 🎯 Objective
The main objective of this project is to:
- Understand the use of the C++17 `<filesystem>` library**
- Implement file I/O and directory traversal
- Simulate a command-line based file explorer
- Learn error handling and command parsing in C++

---

 ⚙️ Features
✅ List files and folders (`ls`)  
✅ Create files and directories (`mkfile`, `mkdir`)  
✅ Delete files or folders (`rm`)  
✅ Copy and move files/folders (`cp`, `mv`)  
✅ View file content (head/tail) (`cathead`, `cattail`)  
✅ Search files using regex (`search`)  
✅ Change file permissions (`chmod`)  
✅ Navigate directories (`cd`, `pwd`)  
✅ Display help menu (`help`)  
✅ Exit the program (`exit`)

---

 🧠 Novelty of the Project
This project is unique because it combines multiple real-world file operations into a single, simple C++ command-line program.  
It uses the C++17 `<filesystem>` library, regex search, and permission management, which are not commonly implemented in beginner-level projects.  
It provides a complete mini file explorer experience through the terminal.

---

 🧩 Technologies Used
- Language: C++17  
- Libraries:
  - `<filesystem>` – for file and folder operations  
  - `<fstream>` – for file I/O  
  - `<regex>` – for searching  
  - `<iomanip>`, `<sstream>`, `<deque>` – for formatted output and parsing

---

 🖥️ Example Usage
```bash
> help
> pwd
> ls
> mkfile notes.txt
> mkdir projects
> cp notes.txt projects/notes_copy.txt
> search . "notes"
> chmod notes.txt 755
> exit
