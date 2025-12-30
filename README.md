# Inheritance-C#
C# Inheritance Examples

This repository contains basic C# examples demonstrating Single Inheritance.
Each example shows how a child class inherits properties and methods from a parent class, promoting code reusability and clean design.

📌 Concepts Covered

Single Inheritance

Parent and Child Classes

Code Reusability

IS-A Relationship

Console Output

🧑 Example 1: Person → Student
📖 Description

The Student class inherits from the Person class.
It reuses the common attributes (Name, Age) and adds its own property (RollNumber).

🏗 Class Structure

Person (Parent Class)

Fields: Name, Age

Method: DisplayPerson()

Student (Child Class)

Field: RollNumber

Method: DisplayStudent()

🔍 Output
Name: Rahul
Age: 18
Roll Number: 101

🚗 Example 2: Vehicle → Car
📖 Description

The Car class inherits from the Vehicle class.
It uses the parent’s Speed property and adds its own Brand information.

🏗 Class Structure

Vehicle (Parent Class)

Field: Speed

Method: ShowSpeed()

Car (Child Class)

Field: Brand

Method: ShowCar()

🔍 Output
Speed: 120 km/h
Brand: Toyota

👨‍🏫 Example 3: Employee → Teacher
📖 Description

The Teacher class inherits from the Employee class.
It uses the employee salary and adds subject information specific to teachers.

🏗 Class Structure

Employee (Parent Class)

Field: Salary

Method: ShowSalary()

Teacher (Child Class)

Field: Subject

Method: ShowTeacher()

🔍 Output
Salary: 45000
Subject: Math

🔑 Key Learning Points

A child class can access public members of its parent class

Inheritance supports code reuse

Demonstrates IS-A relationship

Student is a Person

Car is a Vehicle

Teacher is an Employee

Improves maintainability and scalability

🛠 How to Run

Open the project in Visual Studio or any C# IDE

Run each example separately (each has its own Main() method)

View output in the Console window

