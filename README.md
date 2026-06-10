# Student management system

##  One Kick Heroes Academy

### Project Overview
One Kick Heroes Academy is a Windows Forms application developed in **C#** as part of the **PRG 282** module requirements. The system is designed to manage superhero records through an easy-to-use graphical interface while demonstrating the use of layered architecture principles.

The application allows users to maintain superhero information, generate reports, and perform common data management tasks through dedicated forms and supporting business logic components.

---

## Objectives

The purpose of this project is to demonstrate:

- Object-Oriented Programming principles
- Layered application design
- File handling and data persistence
- Windows Forms development using C#
- Separation of concerns between presentation, business, and data layers

---

## Technologies Used

- **Language:** C#
- **Framework:** .NET Framework (Windows Forms)
- **IDE:** Microsoft Visual Studio
- **Data Storage:** Text Files
- **Architecture:** Three-layer architecture approach

---

## Project Structure

```text
One_Kick_Heroes_Academy/
│
├── BusinessLogicLayer/
│   ├── SuperHero.cs
│   └── SummaryReport.cs
│
├── DataLayer/
│   ├── DataManager.cs
│   └── FileHandler.cs
│
├── Forms/
│   ├── Dashboard.cs
│   ├── AddNewHero.cs
│   ├── Edit Hero Details.cs
│   ├── View.cs
│   └── Report.cs
│
├── bin/
│   └── Debug/
│       ├── superheroes.txt
│       └── Users.txt
│
├── Form1.cs
├── App.config
└── One_Kick_Heroes_Academy.csproj
```

---

## System Features

### User Authentication
The system provides user access functionality through stored user information.

### Dashboard
Acts as the central navigation point of the application, allowing users to access all major features.

### Add New Hero
Enables users to capture and save new superhero records into the system.

### Edit Hero Details
Allows modification and updating of existing superhero information.

### View Heroes
Displays stored superhero records for review and management purposes.

### Generate Reports
Produces summary reports based on the superhero data maintained by the system.

### Data Persistence
The application stores information using text files, ensuring that records remain available between application sessions.

---

## Layer Responsibilities

### Presentation Layer (Forms)
Responsible for interacting with the user through graphical interfaces.

### Business Logic Layer
Contains the application's rules and processes, including superhero management and report generation.

### Data Layer
Handles all file operations, including reading and writing data to text files.

---

## How to Run the Application

1. Open the solution file in **Microsoft Visual Studio**.
2. Restore any missing dependencies if prompted.
3. Build the solution using:

   ```text
   Build → Build Solution
   ```

4. Run the application by pressing:

   ```text
   F5
   ```

   or selecting:

   ```text
   Debug → Start Debugging
   ```

---

## Data Files

The following files are required for the application to function correctly:

| File | Purpose |
|--------|-----------|
| `superheroes.txt` | Stores superhero information |
| `Users.txt` | Stores user account information |

Ensure these files are present in the application's output directory before execution.

---

## Educational Concepts Demonstrated

- Classes and Objects
- Encapsulation
- Layered Architecture
- File Input and Output
- Event-Driven Programming
- Windows Forms Development
- Data Validation
- Report Generation

---

## Notes

- This project was developed for academic purposes as part of the **PRG 282** module.
- The application uses file-based storage rather than a database system.
- The design emphasizes maintainability through the separation of presentation, business, and data responsibilities.

---
