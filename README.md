

\# Student Class Diagram



Name: Kemal Emre Sarın



Student ID: 20222012



Course: AII003 - Principles of Software Engineering



\## Project Description



This project is about converting a Student class diagram into

Java code. The Student class keeps student information and

allows students to register and drop courses.



\## Class Diagram



```mermaid

classDiagram

&#x20;   class Student {

&#x20;       -int studentId

&#x20;       -String name

&#x20;       -String department

&#x20;       -List\~String\~ courses

&#x20;       +Student(int studentId, String name, String department)

&#x20;       +getStudentId() int

&#x20;       +getName() String

&#x20;       +getDepartment() String

&#x20;       +registerCourse(String course) boolean

&#x20;       +dropCourse(String course) boolean

&#x20;       +displayInfo() void

&#x20;   }

```



\## Design to Code



The attributes in the class diagram are private variables

in Java. The operations are public methods.



The constructor creates a student with an ID, name and

department. An ArrayList is used to store the courses.



In the Main class, I create a student object and test the

program by adding and removing courses.



\## How to Run



Compile the code:



```bash

javac -encoding UTF-8 Student.java Main.java

```



Run the program:



```bash

java Main

```



\## Resources



\- AII003 Software Design Specification lecture notes

\- Java Documentation: https://docs.oracle.com/en/java/

\- ChatGPT assistance with code examples and explanations



