# Person Management System

A Java OOP project for managing persons and multiple person management groups.

This project demonstrates clean architecture, object-oriented design principles, and safe handling of user input.

---

## 🚀 Features

- Create and manage persons
- Support for multiple person management groups (e.g. PV Linz, PV Codersbay)
- Immutable `Address` value object
- `Gender` enum with safe parsing from user input
- UUID-based identity for each person
- Input validation and error handling (no crashes on invalid data)

---

## 🧠 Architecture

The project is structured using clear OOP principles:

- **Person** → Entity with unique identity (`UUID`)
- **Address** → Immutable value object
- **Gender** → Enum with parsing logic
- **PersonManagement** → Manages a list of persons
- **PersonManagementSystem** → Manages multiple groups

---

## 🛠 Technologies

- Java
- Object-Oriented Programming (OOP)
- Collections (`List`, `Map`)
- `UUID`
- `LocalDate`

---

## ▶️ How to Run

Run the `Main` class.

The application simulates user interaction and demonstrates all core features.

---

## 📌 Example Output

=== PERSON MANAGEMENT DEMO ===

System: PersonManagementSystem{size=2}
Management count: 2

=== ALL MANAGEMENTS ===
PersonManagement{name='PV Linz', size=2}
PersonManagement{name='PV Codersbay', size=2}

=== PERSONS IN PV LINZ ===
Jack Smith, Unknown
Anna Mayer, Female, 1998-05-14

=== FIND PERSON BY ID ===
Found person: Lukas Huber, Male, 1995-11-03, 4040 Linz, Hauptstrasse 10

=== REMOVE PERSON ===
Removed Jack Smith: true
PV Linz size after removal: 1


---

## 💡 Key Concepts Demonstrated

- Entity vs Value Object
- Immutability (`Address`)
- Encapsulation
- Method overloading (`createPerson`)
- Defensive copying (returning new lists)
- Validation and error handling

---

## 📂 Project Structure
personenverwaltung/
│
├── Address.java
├── Gender.java
├── Person.java
├── PersonManagement.java
├── PersonManagementSystem.java
└── Main.java


---

## 👨‍💻 Author

Vladyslav Petryshyn
