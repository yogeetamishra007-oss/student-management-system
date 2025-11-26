# Student Management System

A simple and beginner-friendly Python Student Management System demonstrating basic CRUD operations using **SQLite**, wrapped in a clean **Tkinter GUI**.

## Features

- User authentication (hardcoded for demo purposes)  
- Add, view, update, and delete student records  
- Simple graphical interface built with Tkinter  
- Modular code: separate backend (database logic) and GUI (frontend interface)  
- SQLite database created automatically on first run

## Getting Started

### Prerequisites

Ensure you have the following installed:

- **Python 3.x**  
- **Tkinter**
  - Windows/macOS: included automatically  
  - Linux: install using  
    ```bash
    sudo apt install python3-tk
    ```
- **SQLite** (built into Python)

## Setup & Running the Project

### 1. Run the Backend

This step initializes the SQLite database and prepares the CRUD functions.

```bash
python backend.py
```

### 2. Launch the GUI

```bash
python gui.py
```

## Usage

### Login Credentials

```
Username: admin
Password: 123
```

These credentials are hardcoded for learning purposes.

## Main Application Features

- **Add Student** — Enter name, age, and course  
- **View Students** — Displays all student records  
- **Update Student** — Modify existing student data  
- **Delete Student** — Remove student by ID  
- **Logout** — Return to login screen  

## Code Structure

```
project/
│
├── backend.py
├── gui.py
└── README.md
```

## Future Improvements

- Replace hardcoded username/password  
- Add registration  
- Improve GUI styling  
- Add data export/import  
- Add search/filter features  

## License

This project is for educational use.
