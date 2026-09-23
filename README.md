# Employee Payroll System

A simple Java-based Employee Payroll System developed to practice
Object-Oriented Programming (OOP) concepts and the basic Java Collection
Framework.

## Features

- Add employees to the payroll system
- Remove employees using employee ID
- Display employee details
- Calculate salary for full-time employees
- Calculate salary for part-time employees
- Manage multiple employees using `ArrayList`

## OOP Concepts Practiced

- **Abstraction** – Using an abstract `Employee` class
- **Encapsulation** – Using private fields with getter methods
- **Inheritance** – `FullTimeEmployee` and `PartTimeEmployee` extend `Employee`
- **Polymorphism** – Overriding the `calculateSalary()` method
- **Method Overriding** – Different employee types provide their own salary calculation
- **Constructors** – Initializing employee objects
- **`super` keyword** – Calling the parent class constructor
- **`toString()` method** – Displaying employee information

## Collection Framework

This project uses the basic Java Collection Framework to manage employee
objects dynamically.

- `List` interface
- `ArrayList` implementation

The `ArrayList` is used to store, add, remove, and display multiple
employee objects.

## Project Structure

```text
Employee-Payroll-System-Java/
├── src/
│   ├── Employee.java
│   ├── FullTimeEmployee.java
│   ├── PartTimeEmployee.java
│   ├── PayrollSystem.java
│   └── Main.java
├── .gitignore
└── README.md


## Learning Note

This project was developed while following a Java OOP tutorial as a hands-on learning project.

The main purpose of this project was to understand and practice important Java concepts by implementing them in a practical application. I worked with concepts such as abstraction, encapsulation, inheritance, polymorphism, method overriding, constructors, and the Java Collection Framework.

I also practiced organizing a Java project by separating different classes into individual files and managing the project using Git and GitHub.