# Restaurant Management System

## Overview

The Restaurant Management System is a Java-based application developed to simplify restaurant operations such as customer management, table reservations, and payment processing. The system provides an organized way to manage restaurant data using file handling and object-oriented programming concepts.

## Features

- Customer Management
  - Add and store customer details
  - Retrieve customer information

- Table Management
  - Manage restaurant tables
  - Check table availability

- Reservation System
  - Create reservations
  - Store reservation details
  - Track reservation schedules

- Payment Management
  - Process customer payments
  - Maintain payment records

- File Handling
  - Store and retrieve data from files
  - Persistent data management

## Technologies Used

- Java
- Maven
- Object-Oriented Programming (OOP)
- File Handling

## Project Structure

```text
Restaurant-Management-System/
│
├── src/
│   └── Main.java
│   └── Customer.java
│   └── Restaurant.java
│   └── Reservation.java
│   └── Table.java
│   └── Payment.java
│   └── Timeslot.java
│   └── FileManager.java
│
├── data/
│   └── Data files
│
├── pom.xml
├── README.md
└── .gitignore
```

## Classes Description

| Class | Description |
|---------|------------|
| Main | Entry point of the application |
| Customer | Stores customer information |
| Restaurant | Manages restaurant operations |
| Table | Represents restaurant tables |
| Reservation | Handles reservation details |
| Timeslot | Manages reservation timing |
| Payment | Handles payment processing |
| FileManager | Performs file operations |

## How to Run

### Prerequisites

- Java JDK 8 or above
- Maven

### Steps

1. Clone the repository

```bash
git clone <repository-url>
```

2. Navigate to the project directory

```bash
cd Restaurant-Management-System
```

3. Compile the project

```bash
mvn clean compile
```

4. Run the application

```bash
mvn exec:java
```

## Learning Outcomes

This project demonstrates:

- Object-Oriented Programming
- Class Design
- File Handling
- Data Persistence
- Maven Project Structure
- Real-world Application Development

## Future Enhancements

- Graphical User Interface (GUI)
- Database Integration (MySQL)
- Online Reservation Support
- User Authentication
- Report Generation


