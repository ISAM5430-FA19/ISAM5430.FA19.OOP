# ISAM 5430 C# Object-Oriented Programming Assignments

This is an Object-Oriented Programming (OOP) practice assignment, allowing you to practice applying the four principles of object-oriented programming, as follows:

1. **Encapsulation**: hiding data and implementations through the use of private/protected/internal access modifiers.
2. **Inheritance**: allowing classes to be inherited from another class, forming a class hierarchy.
3. **Abstraction**: working towards coding by contracts and interfaces rather than implementations.
4. **Polymorphism**: enabling instances of classes or objects to declare as another type (e.g. an interface or a base class). This can reduce the number of messy if-statements.

# Problems
Each problem is a console application project based on .NET Core 2.1. It includes a pdf file, describing what you need to do for the problem. Based on the description, you are to modify specific class files. For instance, when it asks you to create an Account class, you are to add your codes into the Account.cs file in order to satisfy the requirements in the PDF file.

Through a dependency to nunit, each project contains a Tests folder with some unit test classes. These classes may encompass codes that verify correct class structures in addition to blackbox testing.

Finally, each project includes a Program class with a static Main method, which is the entry-point to the console application. You should be adding Main routines, allowing you to instantiate the classes you've created. This way, you'll be able to acknowledge how Abstraction and Polymorphism work through the creation of your own classes.

## Account Hierarchy
This is the first problem you should be working on. It should be relatively straightforward, as you only need to create one abstract class and two derived classes.

## Housing
This should be the second problem you should be working on. It uses an interfacefor abstraction, followed by three other derived classes. As one knows, interfaces are like abstract classes without the luxury of data and implementations. 

## Shape Hierarchy
This should be the third problem you should be working on. It includes several abstract and concrete classes, forming a hierarchy of the shape. The goal is to calculate volume and area of a given shape. Make sure that you have fully written your test codes for this hierarchy.

## Averages
This should be the fourth problem you should be working on. It takes an array or a list via an abstract class to perform some mathematical operations (e.g. average, sum, and counting).

## Two Three Calc
This should be the last problem you should be working on. This is a grouping problem. Given a class of students, how do we group our students into teams of two or three students? We would also like to have at most two groups with two students. In this case, you need to create an interface and a few derived classes that can perform calculations on two or three numbers. Then, there is another derived class that basically combines several instances of classes dealing with either two or three numbers, as described earlier.
