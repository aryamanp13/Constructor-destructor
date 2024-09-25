# Constructor-destructor

# Aim: To study Constuctors and Destructors

## Theory: 
Constructors and destructors are special member functions of a class in C++ that are used to initialize and clean up objects. A constructor is invoked automatically when an object of the class is created, allowing for the initialization of member variables and the allocation of resources, ensuring that the object starts in a valid state. In contrast, a destructor is called when an object is destroyed, allowing for the proper release of resources and cleanup operations, such as deallocating memory or closing file handles, thereby preventing resource leaks and ensuring efficient memory management. Together, these functions facilitate robust and safe object lifecycle management, supporting encapsulation and resource management principles in OOP.


Constuctors
1. A constructor is a special member function of a class that is automatically called when an object of that class is created.
2. Its primary purpose is to initialize the object’s properties or allocate resources.

Constructors can be categorized into three main types:

1. Default Constructor:A constructor that either has no parameters or has all parameters set to default values.
   
2. Parameterized Constructor:A parameterized constructor takes one or more parameters. This allows the programmer to initialize an object with specific values at the time of creation.

3. Copy Constructor: A copy constructor is a special constructor that initializes a new object as a copy of an existing object. It takes a reference to an object of the same class as its parameter.


Destructors: Destructor is a special member function of a class that is automatically called when an object of that class is destroyed.
The primary purpose of a destructor is to release resources that the object may have acquired during its lifetime, such as memory or file handles.

Purpose: To release resources allocated to the object.


Characteristics:
There can only be one destructor in a class.
It cannot be overloaded.
It is called in the reverse order of the constructor calls.

## Algorithm : Default Constructor
1. Start
Class Definition

2.Define a class named construct.

3.Declare public member variables:
int a.
int b.
Default Constructor

4.Implement a default constructor:

Initialize a to 10.

Initialize b to 20.

5.Display Method

Define a method void display():
Print the values of a and b to the console in the format:
"a = [value of a]"
"b = [value of b]"

6.Main Function
Create an instance of the construct class named constructor.

Call the display() method on constructor to output the values of a and b.

7.End
