# 🎓 Student Management System (Python CLI)

A **file-based Student Management System** built using Python that allows users to add, view, search, update, and delete student records through a command-line interface.

This project demonstrates **file handling, data structures, input validation, and CRUD operations** in Python.

---

## 🚀 Features

* ➕ Add new student details
* 📋 View all students
* 🔍 Search student by ID
* ✏️ Update student information
* ❌ Delete a student record
* 💾 Persistent data storage using text file
* 🧠 Input validation & error handling

---

## 🛠️ Tech Stack

| Component | Technology                   |
| --------- | ---------------------------- |
| Language  | Python 3                     |
| Storage   | Text File (`stud_file.txt`)  |
| Interface | Command Line Interface (CLI) |

---

## 📂 Project Structure

```
student-management/
│── main.py
│── stud_file.txt
│── README.md
```

---

## ⚙️ Installation & Setup

1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/student-management.git
cd student-management
```

2️⃣ Make sure Python is installed

```bash
python --version
```

3️⃣ Run the program

```bash
python main.py
```

---

## 💡 How It Works

The system stores student records in this format:

```
S.No:1,Name: John,ID: 101,Age: 20,Course: BCA
```

Each time the program runs:

* Data is loaded from `stud_file.txt`
* Changes are saved automatically

---

## 🖥️ Menu Options

| Choice | Action            |
| ------ | ----------------- |
| 1      | Add Student       |
| 2      | View All Students |
| 3      | Search Student    |
| 4      | Update Student    |
| 5      | Delete Student    |
| 6      | Exit              |

---

## 🔒 Input Validation

✔ Only alphabets allowed in Name
✔ Student ID must be unique
✔ Age must be positive
✔ Course restricted to valid list

---

## 🔮 Future Improvements

* GUI version using Tkinter
* Database integration (SQLite/MySQL)
* CSV export feature
* Admin login system
* Search by Name or Course

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create your feature branch
3. Commit changes
4. Push and open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

Developed as a Python learning project to practice real-world data management concepts.
