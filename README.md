# What is OBJECT-ORIENTED PROGRAMMING?

Object-oriented programming is a programming paradigm built on the concept of objects.
In Other Words, it is an approach to problem-solving where all computations are carried out using objects.

1. Program is divided into small parts called objects.
2. Object-oriented programming follows a bottom-up approach.
3. Have access specifiers like private, public, protected, etc.
4. Adding new data and functions is easy.
5. Provides data hiding so it is more secure than procedural programming.
6. Overloading is possible in object-oriented programming.
7. Data is more important than function.
8. Provides the ability to simulate real-world
9. Examples: C++, Java, Python, C#, JavaScript, Ruby, PHP, VB.NE

<h2>TERMINOLOGIES</h2>
  <br>
<h4><li>Class</li></h4>  A class is a group of objects that share common properties and behavior.It is a blueprint or template from which objects are created.

<h4><li>Object</li></h4>  Object is any real-world entity that can have some characteristics or which can perform some tasks. It is also called the instance of a class
For example, we can consider a car as a class that has characteristics like steering wheels, seats, brakes, etc.
Class - color. Red - an object of color

<h4><li>Constructor</li></h4> Constructors are special methods whose name is the same as the class name. The constructors serve the special purpose of initializing the objects.

<h4><li>Interface </li></h4> Like a class, an interface can have methods and variables, but the methods declared in an interface are by default abstract.

<h4><li>Default constructor</li></h4>  The default constructor is the constructor which doesn’t take any argument. It has no parameters.

<h4><li>Parameterized constructor</li></h4>  The constructors that take some arguments are known as parameterized constructors.

<h4><li>Copy constructor</li></h4>  A copy constructor is a member function that initializes an object using another object of the same class.

<h4><li>Friend Function</li></h4>  It is basically a function that is used to access all private and protected members of classes.

<h4><li>Member Function</li></h4>  It is basically a function that can be declared as members of a class. It is usually declared inside the class definition and works on data members of the same class.

<h4><li>Destructor</li></h4>  It frees up the resources and memory occupied by an object. Destructors are automatically called when an object is being destroyed.

<h4><li>Subclass</li></h4>  The subclass is a part of Inheritance. The subclass is an entity, which inherits from another class. It is also known as the child class.

<h4><li>Superclass</li></h4>  Superclass is also a part of Inheritance. The superclass is an entity, which allows subclasses or child classes to inherit from itself.

<h4><li>Abstract Class</li></h4>  An abstract class is a special class containing abstract methods. The significance of abstract class is that the abstract methods inside it are not implemented and only declared. So as a result, when a subclass inherits the abstract class and needs to use its abstract methods, they need to define and implement them.

<h4><li>Abstract Method</li> </h4> An abstract method is a method that doesn’t have anybody.

<h4><li>Methods</li></h4>  A method is a procedure or function in OOPs Concepts. It is a set of instructions that are associated with an object.

<h4><li>Static Method</li></h4>  A static method is a method that belongs to a class, but it does not belong to an instance of that class and this method can be called without the instance or object of that class. Non-static methods can access any static method and static variable, without creating an instance of the object.

<h4><li>Overloading</li></h4>  Overloading is a compile-time polymorphism feature in which an entity has multiple implementations with the same name.

<h4><li>Overriding</li></h4>  Whereas Overriding is a runtime polymorphism feature in which an entity has the same name, but its implementation changes during execution.

<h4><li>Exception</li></h4>  An exception can be considered as a special event, which is raised during the execution of a program at runtime, that brings the execution to a halt.

<h4><li>Exception handling</li></h4>  It is the mechanism for identifying the undesirable states that the program can reach and specifying the desirable outcomes of such states.
Try-catch is the most common method used for handling exceptions in the program.

<h4><li>Garbage Collection:</li></h4> It refers to the mechanism of handling the memory in the program. Through garbage collection, the unwanted memory is freed up by removing the objects that are no longer needed.

<h4><li>Interface v/s Abstract class difference</li></h4>  Interface and abstract classes both are special types of classes that contain only the method declaration and not their implementation. But the interface is entirely different from an abstract class. The main difference between the two is that, when an interface is implemented, the subclass must define all its methods and provide its implementation. Whereas when an abstract class is inherited, the subclass does not need to provide the definition of its abstract method, until and unless the subclass is using it.
Also, an abstract class can contain abstract methods as well as non-abstract methods

<h4><li>Private</li></h4>  The access level of a private modifier is only within the class. It cannot be accessed from outside the class.

<h4><li>Default</li></h4>  The access level of a default modifier is only within the package. It cannot be accessed from outside the package. If you do not specify any access level, it will be the default.

<h4><li>Protected</li></h4>  The access level of a protected modifier is within the package and outside the package through child class. If you do not make the child class, it cannot be accessed from outside the package.

<h4><li>Public </li></h4> The access level of a public modifier is everywhere. It can be accessed from within the class, outside the class, within the package and outside the package.

<h3>Why we use object-oriented programming?</h3>
Object-oriented programming is the programming paradigm that is defined using objects. Objects can be considered as real-world instances of entities like class, that have some characteristics and behaviors.

<li></li>OOPs helps users to understand the software easily, although they don’t know the actual implementation.
<li></li>With OOPs, the readability, understandability, and maintainability of the code increases multifold.
<li></li>Even very big software can be easily written and managed easily using OOPs.

<h4>What are the main features of OOPs?</h4>
<li>Data Abstraction</li>
Data abstraction refers to providing only essential information about the data to the outside world, hiding the background details or implementation.
Hiding the implementation and displaying only the functionality to the users.
<li>Advantages</li>
It reduces the complexity of viewing things.
Reduces the duplication of the code
Real Life Example
Consider a real-life example of a man driving a car. The man only knows that pressing the accelerators will increase the speed of the car or applying brakes will stop the car but he does not know about how on pressing the accelerator the speed is actually increasing, he does not know about the inner mechanism of the car or the implementation of the accelerator, brakes, etc in the car.

<li>Encapsulation</li> 
It describes the idea of bundling data and methods that work on that data within one unit.

<li>Advantages</li> 
Encapsulation protects an object from unwanted access by clients.
Simplifies the maintenance of the application
Real Life Example
A Real-Life Example of Encapsulation is a School Bag.

<li>Polymorphism</li> 
The word polymorphism means having many forms. It describes the concept that different classes can be used with the same interface.
Polymorphism is the ability of any data to be processed in more than one form.

Polymorphism is divided into two types:

<li>Compile Time Polymorphism</li>  - Compile time polymorphism, also known as Static Polymorphism, refers to the type of Polymorphism that happens at compile time. What it means is that the compiler decides what shape or value has to be taken by the entity in the picture.
<li>Runtime Polymorphism </li> - Runtime polymorphism, also known as Dynamic Polymorphism, refers to the type of Polymorphism that happens at the run time. What it means is it can't be decided by the compiler. Therefore what shape or value has to be taken depends upon the execution. Hence the name Runtime Polymorphism.
Advantages
It helps the programmer to reuse the codes, i.e. classes once written, tested and implemented can be reused as required. Saves a lot of time.
A single variable can be used to store multiple data types.
Real Life Example
Like a man at the same time is a father, a husband, an employee. So the same person possesses different behavior in different situations. This is called polymorphism.

<li>Inheritance</li> 
Inheritance is a feature of OOPs which allows subclasses classes to inherit properties from the parent class.

Types of Inheritance

<li>Single inheritance</li>  - When a class inherits from a single class, it is known as a single inheritance

<li>Multiple inheritances</li>  - Multiple inheritances come into the picture when a class inherits from more than one base class.

Parent 1 && Parent2 → child

<li>Multilevel inheritance</li>  - When there is a chain of inheritance, it is known as multilevel inheritance.

Example: Animal → Dog → Puppy
Puppy Inherits from the Dog Class, Dog class inherits from the Class Animal.

<li>Hierarchical inheritance</li>  - When two or more classes inherit a single class, it is known as hierarchical inheritance.

Example: Animal → Dog = Cats

<li>Hybrid inheritance</li> - Hybrid inheritance is a combination of multiple and multi-level inheritances.

<li>Advantages</li>
The main advantages of inheritance are code reusability and readability. When a child class inherits the properties and functionality of the parent class, we need not to write the same code again in the child class. This makes it easier to reuse the code, makes us write less code and the code becomes much more readable.

Real Life Example
If there is a class such as ‘vehicle’, other classes like ‘car’, ‘bike’, etc can inherit common properties from the vehicle class.

<h3>What is Overloading and Overriding?</h3>
<li>When two or more methods in the same class have the same name but different parameters, it's called Overloading.</li>

<li>When the method name and parameters are the same in the superclass and the child class, it's called Overriding.</li>
