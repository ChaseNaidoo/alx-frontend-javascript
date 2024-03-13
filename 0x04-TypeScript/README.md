# task_0
Write your code in the main.ts file:
- Write an interface named Student that accepts the following elements: firstName(string), lastName(string), age(number), and location(string)
- Create two students, and create an array named studentsList containing the two variables
- Using Vanilla Javascript, render a table and for each elements in the array, append a new row to the table
- Each row should contain the first name of the student and the location

# task_1
Create a directory task_1 and copy these configuration files into this folder: package.json, tsconfig.json, webpack.config.js
- firstName(string) and lastName(string). These two attributes should only be modifiable when a Teacher is first initialized
- fullTimeEmployee(boolean) this attribute should always be defined
- yearsOfExperience(number) this attribute is optional
- location(string) this attribute should always be defined
- Add the possibility to add any attribute to the Object like contract(boolean) without specifying the name of the attribute

# task_2
Create the DirectorInterface interface with the 3 expected methods:
- workFromHome() returning a string
- getCoffeeBreak() returning a string
- workDirectorTasks() returning a string

Create the TeacherInterface interface with the 3 expected methods:
- workFromHome() returning a string
- getCoffeeBreak() returning a string
- workTeacherTasks() returning a string

Create a class Director that will implement DirectorInterface
- workFromHome should return the string Working from home
- getToWork should return the string Getting a coffee break
- workDirectorTasks should return the string Getting to director tasks

Create a class Teacher that will implement TeacherInterface
- workFromHome should return the string Cannot work from home
- getCoffeeBreak should return the string Cannot have a break
- workTeacherTasks should return the string Getting to work

Create a function createEmployee with the following requirements:
- It can return either a Director or a Teacher instance
- It accepts 1 arguments:
  - salary(either number or string)
- if salary is a number and less than 500 - It should return a new Teacher. Otherwise it should return a Director

# task_3
The first part of will require that you build an interface and a type. Inside a file named interface.ts:
- Create a type RowID and set it equal to number
- Create an interface RowElement that contains these 3 fields:
  - firstName: string
  - lastName: string
  - age?: number

# task_4
- Create a file Teacher.ts and write a Teacher interface in a namespace named Subjects.
  - the interface requires firstName and lastName as string
- Create a file Subject.ts and write a Subject class in the same namespace named Subjects.
  - the class has one attribute teacher that implements the Teacher interface
  - the class has one setter method setTeacher that accepts a teacher in argument (and as setter, set the instance attribute teacher with it)
- Create a file Cpp.ts and make the following modifications in the same namespace.
  - Using declaration merging, add a new optional attribute experienceTeachingC (number) to the Teacher interface
  - Create a class Cpp extending from Subject
  - Write a method named getRequirements that will return a string Here is the list of requirements for Cpp
  - Write a method named getAvailableTeacher that will return a string Available Teacher: <first name of teacher>
  - If the teacher doesn’t have any experience in teaching C, then the method should return a string No available teacher
- Create a file React.ts and write a React Class in the same namespace.
  - Add a new attribute experienceTeachingReact? (number) to the Teacher interface
  - In the class, write a method named getRequirements that will return a string Here is the list of requirements for React
  - Write a method named getAvailableTeacher that will return a string Available Teacher: <first name of teacher>
  - If the teacher doesn’t have any experience in teaching React, then the method should return a string No available teacher
- Create a file Java.ts and write a Java Class in the same namespace.
  - Add a new attribute experienceTeachingJava? (number) to the Teacher interface
  - In the class, write a method named getRequirements that will return a string Here is the list of requirements for Java
  - Write a method named getAvailableTeacher that will return a string Available Teacher: <first name of teacher>
  - If the teacher doesn’t have any experience in teaching Java, then the method should return a string No available teacher

# task_5
Create two interfaces MajorCredits and MinorCredits in task_5/js/main.ts:
- Each interface defines a number named credits
- Add a brand property to each interface in order to uniquely identify each of them

Create two functions named sumMajorCredits and sumMinorCredits in task_5/js/main.ts:
- Each function takes two arguments subject1 and subject2
- sumMajorCredits returns MajorCredits value and sumMinorCredits returns MinorCredits value
- Each function sums the credits of the two subjects

