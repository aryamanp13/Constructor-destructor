# Constructor-destructor

# Aim: To study Constuctors and Destructors

## Theory: 

Constuctors
1. A constructor is a special member function of a class that is automatically called when an object of that class is created.
2. Its primary purpose is to initialize the object’s properties or allocate resources.

Constructors can be categorized into three main types:

1. Default Constructor:A constructor that either has no parameters or has all parameters set to default values.
   
2. Parameterized Constructor:A parameterized constructor takes one or more parameters. This allows the programmer to initialize an object with specific values at the time of creation.

3. Copy Constructor: A copy constructor is a special constructor that initializes a new object as a copy of an existing object. It takes a reference to an object of the same class as its parameter.


Destructors: Destructor is a special member function of a class that is automatically called when an object of that class is destroyed.
The primary purpose of a destructor is to release resources that the object may have acquired during its lifetime, such as memory or file handles.

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
