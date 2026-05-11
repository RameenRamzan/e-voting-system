# 🗳️ E-Voting Machine

A console-based electronic voting system built in C as a Programming Fundamentals semester project. The system supports two roles — Admin and Voter — and manages the complete election lifecycle from registration to winner announcement.

---

## 📌 Features

### 👤 Voter
- Register with name, date of birth, roll number, email, and password
- Age validation — must be 18 or older to register
- Auto-generated unique Registration ID
- Secure login to cast vote
- One vote per voter (duplicate voting prevented)

### 🔐 Admin
- Password-protected admin panel
- Register and manage candidates with party names
- Start and end the voting session
- View all registered voters and candidates
- Generate election report
- Announce winner

### ⚙️ System
- Data saved to files (`voter.txt`, `candidate.txt`) so it persists between runs
- Dynamic memory allocation using `malloc` and `realloc`
- Input validation for email, password, date of birth, and roll number
- Max login attempts (3) for security

---

## 🛠️ Tech Stack

- **Language:** C
- **Concepts Used:** Structs, File I/O, Dynamic Memory Allocation, String Handling, Pointers

---

## 🚀 How to Run

1. Make sure you have a C compiler installed (e.g. GCC)
2. Clone the repo:
   ```bash
   git clone https://github.com/RameenRamzan/evoting-machine-cpp.git
   cd evoting-machine-cpp
   ```
3. Compile:
   ```bash
   gcc "Project VF.c" -o evoting -lm
   ```
4. Run:
   ```bash
   ./evoting
   ```

> **Note:** `candidate.txt` and `voter.txt` must be in the same folder as the executable for data to load correctly.

---

## 🗂️ Project Structure

```
├── Project VF.c       # Main source code
├── candidate.txt      # Stores candidate data
├── voter.txt          # Stores voter data
└── README.md
```

---

## 👩‍💻 Developed By

Rameen Ramzan — BS Computer Science
Programming Fundamentals — Semester Project
