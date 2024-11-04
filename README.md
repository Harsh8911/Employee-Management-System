

# Employee Management System

An Employee Management System developed in Java with a graphical user interface (GUI) using Java Swing and AWT libraries. This system allows users to add, view, update, and delete employee information, making it easy to manage employee records efficiently.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)


## Features

- **Add Employee:** Easily add new employees with details such as name, date of birth, salary, address, phone number, email, and more.
- **View Employee Details:** Retrieve and view employee details using their unique employee ID.
- **Update Employee Information:** Edit and update existing employee records.
- **Delete Employee:** Remove employee records from the system.
- **GUI:** Developed using Java Swing for an improved GUI experience over AWT. Some AWT components are used for additional functionality.

## Technologies Used

- **Java** - Core programming language.
- **Java Swing** - For creating a rich and interactive GUI.
- **Java AWT** - Used for certain components where necessary.
- **JCalendar** - A Java library for date selection in forms.

## Installation

### Prerequisites

1. **Java JDK**: Ensure you have Java JDK 8 or above installed. You can download it from [here](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html).
2. **JCalendar Library**: Download the JCalendar library for date selection.
   - Download the JAR file from [JCalendar on SourceForge](https://sourceforge.net/projects/jcalendar/).
   - Place the JAR file in the `lib` folder of the project.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/employee-management-system.git
   cd employee-management-system
   ```

2. **Set Up the Project in Your IDE**:
   - Open the project in your favorite Java IDE (e.g., VS Code, IntelliJ IDEA, Eclipse).
   - Add the `JCalendar` JAR file to your project’s classpath.

3. **Compile and Run**:
   - Compile the code by navigating to the `src` folder and running:
     ```bash
     javac -cp ".;lib/jcalendar-1.4.jar" microproject/*.java
     ```
   - Run the application:
     ```bash
     java -cp ".;lib/jcalendar-1.4.jar" microproject.AddEmployee
     ```

## Usage

1. Launch the **Employee Management System** application.
2. Use the **Add Employee** form to input new employee information.
3. View employee details by entering the employee ID.
4. Update or delete employee information as required.

