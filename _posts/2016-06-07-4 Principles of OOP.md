### 4 Principles of OOP
### Object Oriented Programming
Object Oriented Programming (OOP) refers to using self-contained pieces of code to develop applications. We call these self-contained pieces of code objects, better known as Classes in most OOP programming languages and Functions in JavaScript. We use objects as building blocks for our applications. Building applications with objects allows us to adopt some valuable techniques, namely, Inheritance (objects can inherit features from other objects), Polymorphism (objects can share the same interface—how they are accessed and used—while their underlying implementation of the interface may differ), and Encapsulation (each object is responsible for specific tasks).

### The four OOP Principles

#### 1.Encapsulation
Encapsulation is the mechanism that binds together code and the data it manipulates, and keeps both safe from outside interference and misuse. One way to think about encapsulation is as a protective wrapper that prevents the code and data from being arbitrarily accessed by other code defined outside the wrapper. Access to the code and data inside the wrapper is tightly controlled through a well-defined interface.


In java the basis of encapsulation is the class. The following brief discussion will be helpful now. A class defines the structure and behavior (data and code) that will be shared by a set of objects. Each object of given class contains the structure and behavior defined by the class, as if it were stamped out by a mold in the shape of the class. For this reason, objects are some times referred to as instances of a class. Thus, a class is logical construct; an object has physical reality.


The idea of encapsulation is to keep classes separated and prevent them from having tightly coupled with each other.A live example of encapsulation is the class of java.util.Hashtable. User only knows that he can store data in the form of key/value pair in a Hashtable and that he can retrieve that data in the various ways. But the actual implementation like, how and where this data is actually stored, is hidden from the user. User can simply use Hashtable wherever he wants to store Key/Value pairs without bothering about its implementation.

#### 2.Abstraction:
Humans manage complexity through abstraction. Hiding inner details of system how its been working internally. Only explore the essentials details to end user. Ex car-breaks-engine etc.

Data abstraction is the simplest of principles to understand. Data abstraction and encapuslation are closely tied together, because a simple definition of data abstraction is the development of classes,objects, types in terms of their interfaces and functionality, insteadof their implementation details. Abstraction denotes a model, a view,
or some other focused representation for an actual item. Its the development of a software object to represent an object we can find inthe real world. Encapsulation hides the details of that implementation.

Abstractionis used to manage complexity. Software developers use abstraction to decompose complex systems into smaller components. As development progresss, programmers know the functionality they can expect from as
yet undeveloped subsystems. Thus, programmers are not burdened by considering the waysin which the implementation of later subsystesm will affect the design of earlier development.

#### 3.Inheritance: 
Inheritance is the process by which one object acquires the some/all properties of another object.It supports the concept of hierarchical classification.Different kinds of objects often have a certain amount in common with each other.Object-oriented programming allows classes to inherit commonly used state and behavior from other classes.
For example: Car is a classification of Four Wheeler. Here Car acquires the properties of a four-wheeler. Other classifications could be a jeep, tempo, van etc. Four Wheeler defines a class of vehicles that have four wheels, and specific range of engine power, load carrying capacity etc. Car (termed as a sub-class) acquires these properties from Four Wheeler (termed as a super-class), and has some specific properties, which are different from other classifications of Four Wheeler, such as luxury, comfort, shape, size, usage etc.

A car can have further classification such as an open car, small car, big car etc, which will acquire the properties from both Four Wheeler and Car, but will still have some specific properties. This way the level of hierarchy can be extended to any level.Java Swing and Awt classes represent best examples for inheritance.

#### 4.Polymorphism
Polymorphism (from the Greek, meaning "many forms") same name with different forms.Polymorphism means to process objects differently based on their data type.
In other words it means, one method with multiple implementation, for a certain class of action. And which implementation to be used is decided at runtime depending upon the situation (i.e., data type of the object)
This can be implemented by designing a generic interface, which provides generic methods for a certain class of action and there can be multiple classes, which provides the implementation of these generic methods.
Lets us look at same example of a car. A car have a gear transmission system. It has four front gears and one backward gear. When the engine is accelerated then depending upon which gear is engaged different amount power and movement is delivered to the car.

Polymorphism could be static and dynamic both. Overloading is static polymorphism while, overriding is dynamic polymorphism.
Overloading in simple words means two methods having same method name but takes different input parameters. This called static because, which method to be invoked will be decided at the time of compilation
Overriding means a derived class is implementing a method of its super class.


#### References

[what-are-four-principles-of-oop.html](http://crackingjavainterviews.blogspot.co.ke/2013/04/what-are-four-principles-of-oop.html)
[major-principles-of-object-oriented-programming](http://codebetter.com/raymondlewallen/2005/07/19/4-major-principles-of-object-oriented-programming/)
[object-oriented-programming-principles](https://sites.google.com/site/java4interviews/home/object-oriented-programming-principles)
[oops-in-java-encapsulation-inheritance-polymorphism-abstraction](http://beginnersbook.com/2013/03/oops-in-java-encapsulation-inheritance-polymorphism-abstraction/)



 


