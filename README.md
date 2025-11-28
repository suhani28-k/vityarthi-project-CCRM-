# Vityarthi Project (Campus Course & Records Manager)

## Description
This project manages campus courses, students, teachers, and enrollments.
It allows you to view students, courses, and their enrollments.
It is built using Java and uses CSV files (optional) for test data.
The project follows a clean layered architecture and includes fully documented design artifacts such as UML diagrams, ER diagram, sequence diagram, flowcharts, and architecture diagrams.

## Features
- Manage students, courses, and teachers
- View and list student enrollments
- Add or update records (optional)
- Uses CSV files for test data (optional)

## Project Structure
vityarthi_proj/
├── src/                  # Java source code
│   └── edu/
│       └── ccrm/
│           └── domain/   # Your classes
│               ├── Person.java
│               ├── Student.java
│               ├── Teacher.java
│               └── Course.java
├── test-data/            # CSV files for testing
│   ├── students.csv
│   ├── courses.csv
│   └── enrollments.csv

├── docs/                  # All diagrams
│   ├── er_diagram.png
│   ├── class_diagram.png
│   ├── sequence_diagram.png
│   ├── system_architecture.png
│
├── project_report.pdf
├── statement.md  
└── flowchart.png
├── README.md            # Project documentation
└── USAGE.md              # Instructions to run the project


## Requirements
- Java JDK 11 or higher
- IDE like IntelliJ IDEA or Eclipse
- (Optional) CSV files for test data

  ##Functional Requirements
-Manage student records
-Manage teachers and departments
-Manage courses and semesters
-Enroll students into courses
-Record grades and performance
-Generate detailed student transcripts
-List all students, teachers, courses, and enrollments

## How to Run
1. Open the project in your IDE
2. Make sure `test-data/` folder is present (if using CSV files)
3. Run the `Main` class
4. Check console output for students, courses, and enrollments

## Screenshots
  # System Architecture
  ![image alt](https://github.com/suhani28-k/vityarthi-project-CCRM-/blob/a5ef57bec8a9c85abb849b28fb0d4369a8218a6b/Architectural%20Overview.png)
  image are icluded in project report 
  

### Java Version
![Java Version]([screenshots/java_version.png](https://github.com/suhani28-k/vityarthi-project-CCRM-/blob/cf774eaa1fff7c21f75389a95d0d92bc58853f30/java_version.png))

### IDE Setup
![IDE Setup]([screenshots/intellij_setup.png](https://github.com/suhani28-k/vityarthi-project-CCRM-/blob/ee9666a75830841bee4009ba53b835d518bf7bf1/intellij_setup.png))

### Program Running
![image alt](https://github.com/suhani28-k/vityarthi-project-CCRM-/blob/6b39af1832fca62991e50287c9f223fdf82e17ca/Output%201.png)
![image alt](https://github.com/suhani28-k/vityarthi-project-CCRM-/blob/9200873034472f01211012772da2d158465d238a/output%202.png)

##Testing
The project includes:
CSV test-data
Manual validation test cases
Input edge-case handling
Test scenarios include:
Enrollment validation
Missing student/course error
Duplicate enrollment prevention

## Author
Suhani Manishankar Katare
