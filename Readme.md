# 💼 Employee Payroll System

A **Java-based Employee Payroll System** built using core **Object-Oriented Programming (OOP)** principles. This project demonstrates how abstraction, encapsulation, inheritance, and polymorphism work together in a real-world use case.

---

## 📖 Overview

The Employee Payroll System manages employee details and calculates salaries for **full-time** and **part-time** employees. It is designed to clearly showcase OOP concepts through clean class design and method overriding.

---

## 🚀 Features

* **Abstraction** – Common employee structure defined using an abstract class
* **Encapsulation** – Employee data protected using private fields with public getters
* **Inheritance** – Specialized employee types inherit from a base Employee class
* **Polymorphism** – Salary calculation varies based on employee type
* **Modular & readable code structure**

---

## 🏗️ Class Design

### 🔹 Employee (Abstract Class)

Represents a generic employee.

**Fields:**

* `name` – Employee name
* `id` – Employee ID

**Methods:**

* `getName()` – Returns employee name
* `getId()` – Returns employee ID
* `calculateSalary()` – Abstract method for salary calculation
* `toString()` – Returns employee details

---

### 🔹 FullTimeEmployee

Represents a full-time employee.

**Fields:**

* `monthlySalary` – Fixed monthly salary

**Methods:**

* `calculateSalary()` – Returns the monthly salary

---

### 🔹 PartTimeEmployee

Represents a part-time employee.

**Fields:**

* `hoursWorked` – Number of hours worked
* `hourlyRate` – Pay per hour

**Methods:**

* `calculateSalary()` – Calculates salary based on hours worked

---

### 🔹 PayRollSystem

Manages employees and payroll operations.

**Fields:**

* `employeeList` – ArrayList of employees

**Methods:**

* `addEmployee(Employee employee)` – Adds a new employee
* `removeEmployee(int id)` – Removes an employee by ID
* `displayEmployees()` – Displays all employee details

---

## ▶️ Usage

1. Create instances of `FullTimeEmployee` and `PartTimeEmployee`
2. Add them to the `PayRollSystem`
3. Display employee details
4. Remove employees using their ID

---

## ⚙️ Getting Started

1️⃣ **Clone the repository**

```bash
git clone https://github.com/harshiii456/REPO_NAME.git
```

2️⃣ **Compile the Java files**

```bash
javac *.java
```

3️⃣ **Run the application**

```bash
java Main
```

---

## 🎯 Learning Outcomes

* Strong understanding of Java OOP concepts
* Hands-on experience with abstraction & polymorphism
* Clean and maintainable class design

---

## 📌 Future Enhancements

* Add persistence using files or a database
* Implement employee search functionality
* Add salary slips generation
* Improve user interaction with a menu-driven interface

---

## 👩‍💻 Author

**Harshita**
B.Tech Student | Java & DSA Enthusiast

* GitHub: [@harshiii456](https://github.com/harshiii456)

---

## 📄 License

This project is licensed under the **MIT License**.

⭐ *If you found this project helpful, give it a star!* 🚀
