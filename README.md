#Python Object-Oriented Programming Assignment
This GitHub repository contains the Python code for an assignment that implements various Object-Oriented Programming (OOP) concepts such as polymorphism, encapsulation, constructors, and inheritance. The assignment consists of several tasks outlined below.

Task 1: Create a Python Class - Person
Properties
name: Represents the name of the person.
age: Represents the age of the person.
gender: Represents the gender of the person.
Constructor
__init__(self, name, age, gender): Initializes the name, age, and gender properties.
Methods
say_hello(self): Prints a greeting message from the person.
is_adult(self): Returns True if the person's age is 18 or above, otherwise returns False.
Task 2: Implement Inheritance - Student
The Student class is a subclass of the Person class and has the following additional properties:

Additional Properties
student_id: Represents the student's identification number.
course: Represents the course the student is enrolled in.
Additional methods should be implemented as needed to represent a student.

Task 3: Implement Polymorphism - Teacher
The Teacher class is another subclass of the Person class and has the following additional properties:

Additional Properties
teacher_id: Represents the teacher's identification number.
subject: Represents the subject the teacher teaches.
The say_hello() method in the Teacher class should be different from the one in the Person and Student classes to demonstrate polymorphism.

Task 4: Encapsulation
In the Person class, the age property is made private, and a method is created to allow access to it. This is an example of encapsulation, as it restricts direct access to the age property.
