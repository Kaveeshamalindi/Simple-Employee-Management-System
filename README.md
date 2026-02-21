# Simple-Employee-Management-System

<p align="justify"> Using Java Swing to strengthen my understanding of core concepts like GUI design and object-oriented programming. This system allows adding employee details, displaying added information, and managing basic attributes such as ID, Name, Gender, Birth Date, and Qualification. </p>

---

## 📌 Project Overview

### This application is built using:
- Java Programming language
- Java Swing (GUI)
- OOP Concepts (Encapsulation, Constructors, Objects, Getters/Setters)

### The system allows users to:
- Add employee details
- Validate input fields
- Display stored employee information
- Exit the application

---

## 🏗️ Project Structure

The project follows a simple layered structure.

```
Business/
    Employee.java
User/
    EmployeeUI.java
```

### 1️⃣ Business Layer
<code> Employee.java </code>

<B> This class represents the Employee entity and contains: </B>
- Employee ID (int)
- First Name (String)
- Last Name (String)
- Gender (String)
- Birth Date (java.sql.Date)
- Qualification (String)

<B> It includes: </B>
- Default constructor
- Parameterized constructor
- Getters and Setters for all attributes

This demonstrates Encapsulation in OOP.

### 2️⃣ User Interface Layer
<code> EmployeeUI.java </code> 

This class extends JFrame and provides the graphical interface.

<B> GUI Components: </B>
- Text Fields: Employee ID, First Name, Last Name, Birth Date
- Radio Buttons: Male, Female
- Combo Box: Certificate Course, Diploma, Higher Diploma, Degree
- Buttons: Add, Display, Cancel

---

## ⚙️ System Functionalities

### ✅ Add Employee

- Validates required fields (ID, First Name, Last Name, Birth Date)
- Creates an Employee object
- Stores the data in memory
- Shows confirmation message

### ✅ Display Employee

- Displays employee details using JOptionPane

### ✅ Cancel

- Closes the application

---

## 🎮 How to Run the Project

1. Using NetBeans (Recommended)
2. Open NetBeans IDE
3. Click File → Open Project
4. Select the project folder
5. Run the project

---

## 🎯 Learning Purpose

This project was created to strengthen the understanding of:
- Java Swing GUI design
- Event handling
- Object-Oriented Programming principles
- Basic form validation
- Java package structuring

---

<img src="https://media.giphy.com/media/ObNTw8Uzwy6KQ/giphy.gif" width="30px"> Don't forget to hit the ⭐ if you like this repo. <img src="https://media.giphy.com/media/ObNTw8Uzwy6KQ/giphy.gif" width="30px">


