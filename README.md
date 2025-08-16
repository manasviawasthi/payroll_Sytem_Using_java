# Employee Payroll System (Java)

## Overview
The Employee Payroll System is a Java-based desktop application designed to manage employee details, departmental information, payroll calculations, and user authentication. It combines a Swing-based GUI with a database backend for storing and retrieving information. The system can be executed directly using the provided JAR file or compiled from source code.

---

## Project Structure
```

Employee-Payroll-System/
│
├── Executable JAR/       # Contains compiled .jar file to run the application directly
│
├── sources/              # Contains Java source code
│   └── org/payroll/
│       ├── departments/        # Department management classes
│       ├── employees/          # Employee management classes
│       ├── preferences/        # User preferences and settings
│       ├── DatabaseManager.java  # Database connectivity and queries
│       ├── LoginFrame.java       # Login GUI
│       ├── Main.java             # Application entry point
│       └── MainFrame.java        # Main GUI after login

````

## Features
- **User Authentication** – Secure login interface  
- **Employee Management** – Add, update, and delete employee records  
- **Department Management** – Organize employees by departments  
- **Payroll Processing** – Calculate and manage salaries and deductions  
- **Preferences** – Store user settings in the application  
- **Database Integration** – Centralized database operations via JDBC  

---

## Technologies Used
- **Programming Language:** Java (Swing for GUI)  
- **Database:** JDBC-compatible (e.g., MySQL, SQLite)  
- **Executable Format:** Runnable JAR file  
- **IDE Support:** Compatible with IntelliJ IDEA, Eclipse, NetBeans  

---

## How to Run

### Option 1: Using JAR
1. Navigate to the `Executable JAR` folder.  
2. Run the JAR file using:  
   ```bash
   java -jar EmployeePayrollSystem.jar

### Option 2: Using Source Code

1. Open the `sources` folder in your preferred IDE.
2. Configure the database connection inside `DatabaseManager.java`.
3. Compile and run `Main.java`.

---

## Future Enhancements

* PDF report generation for salary slips
* Role-based access control (Admin, HR, Accountant)
* Migration to JavaFX or Spring Boot for enhanced UI and scalability

---


