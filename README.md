# Week-1-java
What is Java?
Java is a general-purpose programming language that is class-based, object-oriented, and designed to have as few implementation dependencies as possible.

Java Components
Java Virtual Machine (JVM): JVM is an integral part of the Java Runtime Environment (JRE) and is responsible for executing Java bytecode. It provides platform independence by allowing Java programs to run on any device with a JVM.
Java Development Kit (JDK): JDK is a software development kit used for developing Java applications. It includes the Java Compiler (javac), debugger, and other tools needed for Java development.
Java Standard Edition (Java SE): Formerly known as J2SE, Java SE is the core Java platform that includes the basic libraries, APIs, and the Java Virtual Machine. It is used for developing desktop, server, and command-line applications.
Java Enterprise Edition (Java EE): Formerly known as J2EE, Java EE is a set of specifications that extends the Java SE platform to provide enterprise-level features such as distributed computing and web services. Java EE is used for building large-scale, multi-tiered enterprise applications.
JavaFX: JavaFX is a set of graphics and media packages that enables developers to design, create, test, debug, and deploy rich client applications that operate consistently across diverse platforms.
Swing: Swing is a GUI toolkit for Java. It provides a set of lightweight components that can be used to create graphical user interfaces (GUIs) for Java applications.
AWT (Abstract Window Toolkit): AWT is the original Java GUI toolkit. It provides a set of classes for building platform-independent graphical user interfaces.
Java Database Connectivity (JDBC): JDBC is a Java-based API that allows Java applications to interact with relational databases. It provides a standard interface for connecting to databases, executing SQL queries, and handling results.
Servlets and JSP (JavaServer Pages): Servlets are Java classes that handle HTTP requests and generate responses. JSP is a technology used for creating dynamic web pages using Java. Together, they form the basis of Java web development.
Spring Framework: Spring is a comprehensive framework for Java development that provides support for building enterprise-level applications. It simplifies the development of complex systems by offering features such as dependency injection, aspect-oriented programming, and more.
Java Beans: Java Beans are reusable software components for Java that can be manipulated visually in a builder tool. They are used to encapsulate many objects into a single object (the bean).
Multithreading: Java supports multithreading, allowing concurrent execution of multiple threads within a program. This is useful for improving the performance of applications and handling concurrent tasks.

Main Java features
Platform-Independent: Java achieves platform independence by using the concept of the Java Virtual Machine (JVM). Java source code is compiled into an intermediate form called bytecode, which can run on any device that has a JVM. This allows Java applications to be written once and run anywhere.
Object-Oriented: Java follows the principles of object-oriented programming (OOP), emphasizing concepts such as encapsulation, inheritance, and polymorphism. Everything in Java is an object, and programs are designed by creating and manipulating these objects.
Simple: Java was designed to be easy to use and to eliminate complexities that can be error-prone. It includes automatic memory management (garbage collection) and eliminates features like explicit pointers and operator overloading, which can be sources of complexity and bugs.
Robust: Java is designed to be robust by including features like strong memory management, exception handling, and type checking. The JVM checks for many potential errors during runtime, reducing the likelihood of crashes or other unexpected behavior.
Secure: Java provides a secure execution environment through features like the bytecode verifier, which ensures that code loaded onto the JVM adheres to certain rules. Additionally, the Java Security Manager allows fine-grained control over the resources a Java program can access.
Multithreading: Java supports multithreading, allowing multiple threads of execution to run concurrently. This is useful for improving the performance of applications by handling multiple tasks simultaneously.

Setting up the environment
Platform-Independent: Java achieves platform independence by using the concept of the Java Virtual Machine (JVM). Java source code is compiled into an intermediate form called bytecode, which can run on any device that has a JVM. This allows Java applications to be written once and run anywhere.
Object-Oriented: Java follows the principles of object-oriented programming (OOP), emphasizing concepts such as encapsulation, inheritance, and polymorphism. Everything in Java is an object, and programs are designed by creating and manipulating these objects.
Simple: Java was designed to be easy to use and to eliminate complexities that can be error-prone. It includes automatic memory management (garbage collection) and eliminates features like explicit pointers and operator overloading, which can be sources of complexity and bugs.
Robust: Java is designed to be robust by including features like strong memory management, exception handling, and type checking. The JVM checks for many potential errors during runtime, reducing the likelihood of crashes or other unexpected behavior.
Secure: Java provides a secure execution environment through features like the bytecode verifier, which ensures that code loaded onto the JVM adheres to certain rules. Additionally, the Java Security Manager allows fine-grained control over the resources a Java program can access.
Multithreading: Java supports multithreading, allowing multiple threads of execution to run concurrently. This is useful for improving the performance of applications by handling multiple tasks simultaneously.

How to install Netbeans
Install on windows
Run the installer by double-clicking the installer.
At the Welcome page of the installation wizard, click Next.
At the License agreement page, review the license agreement, click the acceptance check box, and click Next.
Accept the default installation directory for the NetBeans IDE
Accept the default JDK installation to use with the NetBeans IDE
Click Next.
If the GlassFish Server Open Source Edition installation page opens, accept the default installation directory
Click Next.
Click Install to begin the installation.
Click Finish.

Typical Structure of a Java program
Package declaration
A class in Java can be placed in different directories/packages based on the module they are used. For all the classes that belong to a single parent source directory, a path from source directory is considered as package declaration. Keyword package is used on package declaration statement
Import statements
There can be classes written in other folders/packages of our working java project and also there are many classes written by individuals, companies, etc which can be useful in our program. To use them in a class, we need to import the class that we intend to use. Many classes can be imported in a single program and hence multiple import statements can be written. Keyword import is used on import statement
Comments
The comments in Java can be used to provide information about the variable, method, class or any other statement. There are two ways to write comments in Java:
Single line comment - used to comment single line of code. It uses double forward slash (//) e.g. // this is a single line comment
Multiline comment -used to comment multiple lines of code e.g. /*This is multiline  
               comment */
Class Definition
A name should be given to a class in a java file. This name is used while creating an object of a class, in other classes/programs. Keyword class is used on Class Definition
Main Method
Execution of a Java application starts from the main method. In other words, it’s an entry point for the class or program that starts in Java Run-time.
Methods/Behaviours
A set of instructions which form a purposeful functionality that can be required to run multiple times during the execution of a program. To not repeat the same set of instructions when the same functionality is required, the instructions are enclosed in a method. A method’s behaviour can be exploited by passing variable values to a method.

What is a variable?
A variable is a name given to a memory location. It is the basic unit of storage in a program.
The value stored in a variable can be changed during program execution.
A variable is only a name given to a memory location; all the operations done on the variable effects that memory location.
In Java, all the variables must be declared before use.
which is created by specifying the data type then follow with the variable name, you can also assign a value to the variable in the same line or do it in different lines.
we have local variables, instance variables and static variables,
local variables: Local variables in Java are variables that are declared within a method, constructor, or block of code. Unlike instance variables, local variables have limited scope and are only accessible within the block of code where they are declared. They do not persist beyond the execution of that block.
Instance variables: Instance variables in Java are variables that are associated with an instance of a class. They are also sometimes referred to as member variables or attributes. These variables represent the state of an object, and each instance of the class has its own copy of these variables.
static variables: Static variables in Java are also known as class variables. Unlike instance variables, which are associated with instances of a class, static variables are associated with the class itself. This means that there is only one copy of a static variable, regardless of how many instances of the class are created. Static variables are declared using the static keyword.

Data types in Java
Primitive data types: A primitive data type specifies the size and type of variable values, and it has no additional methods.
boolean, numeric data types
boolean: true or false
numeric: char, long, int, float, double, short and byte.

non-primitive data types: These are the datatypes which have instances like objects. Hence, they are called reference variables. 
string, array

Casting is the process of converting a value from one data type to another. This is necessary when you want to assign a value of one data type to a variable of another data type or when performing operations that involve different data types. There are two types of casting in Java: implicit casting (also known as widening or automatic casting) and explicit casting (also known as narrowing or manual casting).

Implicit Casting (Widening):
Implicit casting occurs when you assign a smaller data type to a larger data type.
Java automatically performs the conversion without requiring any explicit casting syntax.

Explicit Casting (Narrowing):
Explicit casting is necessary when you want to assign a larger data type to a smaller data type.
It involves using the cast operator to explicitly specify the target data type.
Explicit casting may result in data loss if the value being cast cannot be accurately represented in the target type.

Operators in Java
Java supports a variety of operators that are used to perform operations on variables and values.

Arithmetic Operators:
+ (addition)
- (subtraction)
* (multiplication)
/ (division)
% (modulo, returns the remainder of division)

Assignment Operators:
= (assign)
+= (add and assign)
-= (subtract and assign)
*= (multiply and assign)
/= (divide and assign)
%= (modulo and assign)

Comparison Operators:
== (equal to)
!= (not equal to)
< (less than)
> (greater than)
<= (less than or equal to)
>= (greater than or equal to)

Logical Operators:
&& (logical AND)
|| (logical OR)
! (logical NOT)

Increment and Decrement Operators:
++ (increment by 1)
-- (decrement by 1)

Conditional (Ternary) Operator:
? : (conditional operator)

Bitwise Operators:
& (bitwise AND)
| (bitwise OR)
^ (bitwise XOR)
~ (bitwise complement)
<< (left shift)
>> (right shift)
>>> (unsigned right shift)

Java Classes and Objects
Classes:
A class is a blueprint or a template for creating objects.
It defines the properties (attributes) and behaviors (methods) that objects of the class will have.
Syntax: public class ClassName {

}
Objects:
Definition:An object is an instance of a class.
It represents a real-world entity and is created based on the blueprint provided by the class.
Creating Objects:
To create an object, you use the new keyword followed by the class constructor:
syntax: ClassName objectName = new ClassName();

Constructors:
Definition:
A constructor is a special method used to initialize the state of an object.
It has the same name as the class and is called when an object is created.
// Constructor
    public Car(String make, String model, int year) {
        this.make = make;
        this.model = model;
        this.year = year;
    }
Methods:
Definition:
Methods are functions defined within a class that define the behavior of the objects created from the class.
public class Car {
    // ... (other members)
    // Method
    public void startEngine() {
        System.out.println("Engine started!");
    }
}

What is OOP?
Object-Oriented Programming (OOP) is a programming paradigm centered around the idea of "objects," which encompass both data and associated methods. The primary goal of OOP is to enhance program flexibility and maintainability. By consolidating data and methods within individual objects, OOP facilitates a clearer understanding of program functionality. Java is considered a mature language in the realm of OOP.
A distinctive feature of objects is their ability to have procedures that access and often modify their own data fields, incorporating the concept of "this" or "self." In OOP, programs are constructed by assembling objects that interact with one another. While OOP languages exhibit diversity, class-based languages are the most prevalent and widely used.

Object-Oriented Programming (OOP) is popular for several reasons, and it has advantages over declarative and procedural programming paradigms in certain contexts. Modularity and Reusability, abstraction and Encapsulation, Flexibility and Maintainability, Code Organization, Collaborative Development, Security and Modeling Real-World Scenarios.

Features of OOP – Core features
Classes and Objects: A class is a blueprint for creating objects. Objects are instances of classes, and they encapsulate data (attributes) and behavior (methods).
Encapsulation: Encapsulation is the bundling of data and methods that operate on the data into a single unit, or class. It helps to hide the internal details of how an object works and expose only what is necessary.
Inheritance: Inheritance is a mechanism that allows a class (subclass or derived class) to inherit properties and behaviors from another class (superclass or base class). It promotes code reuse and establishes a relationship between classes.
Polymorphism: Polymorphism allows objects of different classes to be treated as objects of a common base class. This can take the form of method overloading (same method name, different parameters) or method overriding (same method name and parameters, but different implementation in the subclass).
Abstraction: Abstraction involves simplifying complex systems by modeling classes based on the essential properties and behaviors they share. It allows developers to focus on what an object does without needing to understand the details of how it achieves its functionality.
Overloading in simple words means more than one method having the same method name that behaves differently based on the arguments passed while calling the method. This called static because, which method to be invoked is decided at the time of compilation.
Overriding means a derived class is implementing a method of its super class. The call to overriden method is resolved at runtime, thus called runtime polymorphism.

Features of OOP – Other features
Coupling refers to the knowledge or information or dependency of another class. It arises when classes are aware of each other. If a class has the details information of another class, there is strong coupling.

Cohesion refers to the level of a component which performs a single well-defined task. A single well-defined task is done by a highly cohesive method. The weakly cohesive method will split the task into separate parts. The java.io package is a highly cohesive package because it has I/O related classes and interface.

Association represents the relationship between the objects. Here, one object can be associated with one object or many objects. There can be four types of association between the objects
One to One
One to Many
Many to One, and
Many to Many

Aggregation is a narrower kind of association. It occurs when there’s a one-way (HAS-A) relationship between the two classes you associate through their objects
One-directional association.
Represents a HAS-A relationship between two classes.
Only one class is dependent on the other.

Composition is a stricter form of aggregation. It occurs when the two classes you associate are mutually dependent on each other and can’t exist without each other.
A restricted form of aggregation
Represents a PART-OF relationship between two classes
Both classes are dependent on each other
If one class ceases to exist, the other can’t survive alone

Introduction to Decision control
Decision control structures allow you to control the flow of your program based on certain conditions. The primary decision-making constructs in Java are the if, else if, and else statements. These statements help you execute different blocks of code depending on whether a given condition is true or false.
if Statement:
The if statement is a fundamental decision-making statement in Java. It is used to execute a block of code only if a specified condition evaluates to true.
if-else Statement:
The if-else statement extends the functionality of the if statement. It allows you to execute one block of code if the condition is true and another block if the condition is false.
else if Statement:
The else if statement allows you to check multiple conditions in sequence. If the first if condition is false, it checks the next else if condition. If that is true, the corresponding block of code is executed.

If Statement, IF ELSE statement, Nested If Statement
if Statement:
The if statement is used to execute a block of code only if a specified condition evaluates to true.
int x = 10;
if (x > 5) {
    System.out.println("x is greater than 5");
}

if-else Statement:
The if-else statement allows you to execute one block of code if the condition is true and another block if the condition is false.
int y = 3;
if (y % 2 == 0) {
    System.out.println("y is even");
} else {
    System.out.println("y is odd");
}

 Nested if Statement:
You can nest if statements inside each other to create more complex decision-making structures. Each if statement is executed sequentially based on the condition.
int a = 10;
int b = 5;

if (a > 0) {
    System.out.println("a is positive");

    if (b > 0) {
        System.out.println("b is also positive");
    } else {
        System.out.println("b is not positive");
    }
} else {
    System.out.println("a is not positive");
}

Switch statement and the Tenary (?) operator
Switch Statement:
The switch statement is used when you have multiple possible execution paths based on the value of an expression. It's a cleaner alternative to a sequence of if-else if statements..

Ternary Operator (? :):
The ternary operator is a concise way to express a simple if-else statement. It takes three operands: a condition followed by a question mark (?), an expression to execute if the condition is true, a colon (:), and an expression to execute if the condition is false.

Java Identifiers
Rules for Java Identifiers:
Must Begin with a Letter, Dollar Sign ($), or Underscore (_):
The first character must be a letter, dollar sign, or underscore.
Subsequent characters can also be numbers.
No Spaces Allowed:
Identifiers cannot contain spaces.
No Keywords:
Identifiers cannot be a keyword or a reserved word in Java (e.g., if, class, int).
Case-Sensitive:
Java is case-sensitive, so myVar and myvar are different identifiers.
No Special Characters Except Dollar Sign ($) and Underscore (_):
Special characters like @, !, #, etc., are not allowed in identifiers.

Java Naming Conventions for Identifiers:
Class Names:
Should start with an uppercase letter.
Use CamelCase (e.g., MyClass).
Interface Names:
Should start with an uppercase letter.
Use CamelCase (e.g., MyInterface).
Method Names:
Should start with a lowercase letter.
Use camelCase (e.g., myMethod).
Variable Names:
Should start with a lowercase letter.
Use camelCase (e.g., myVariable).
Constants:
Should be in uppercase letters.
Use underscores to separate words (e.g., MAX_SIZE).

Access Modifiers:
Access modifiers determine the visibility and accessibility of classes, fields, methods, and constructors in different parts of your program. There are four main access modifiers in Java:
Non-access modifiers do not control access to classes, methods, or fields but instead provide additional information about their behavior.

Access modifiers
Public (public):
The class, method, or field with the public modifier is accessible from any other class or package.
Private (private):
The class, method, or field with the private modifier is only accessible within the same class.
Protected (protected):
The class, method, or field with the protected modifier is accessible within the same package and by subclasses, even if they are in a different package.
Default (Package-Private):
If no access modifier is specified (default), the class, method, or field is accessible within the same package but not outside of it.

Non  Access modifiers
Final (final):
When applied to a class, it indicates that the class cannot be extended (no subclasses allowed).
When applied to a method, it indicates that the method cannot be overridden in subclasses.
When applied to a variable, it indicates that the variable's value cannot be changed once assigned.
Abstract (abstract):
When applied to a class, it indicates that the class is abstract and cannot be instantiated on its own. It may contain abstract methods that must be implemented by its subclasses.
When applied to a method, it indicates that the method does not have a body and must be implemented by the subclass.
Static (static):
When applied to a method, it indicates that the method belongs to the class rather than an instance of the class. It can be called using the class name without creating an instance.
When applied to a variable, it indicates that the variable is a class variable (shared among all instances) rather than an instance variable.
