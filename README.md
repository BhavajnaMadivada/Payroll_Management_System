# Restaurant Payroll Management System (C++, OOPS)

This project is a **Restaurant Payroll Management System** written in C++. It manages employee details such as ID, name, position, and daily wage. The program supports adding, removing, viewing employees, and calculating salaries with deductions like PF and ESI.

---

## Features

🔹 Console-based menu system with color-enhanced UI (Windows only)  
🔹 File-based storage (`Employees.txt`) for employee data  
🔹 Two login modes:
- **Administrator**
  - Add new employee
  - Remove existing employee
  - View employee list
- **Employee**
  - View personal salary and deductions based on days worked  

---

## Technologies Used

- **Language:** C++  
- **Headers Used:** `<iostream>`, `<fstream>`, `<vector>`, `<iomanip>`, `<windows.h>`, `<conio.h>`  
- **Platform:** Windows (due to use of `windows.h` and `SetConsoleTextAttribute` for colored output)  

---

## How to Compile and Run

### 🧾 Requirements

- A C++ compiler (like MinGW or MSVC)
- Windows OS (required for color and console functions)

### 🛠️ Compile

Using g++:

```bash
g++ -o PayrollSystem main.cpp
