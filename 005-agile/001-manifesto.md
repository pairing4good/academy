# Agile Manifesto

1. watch [![YouTube](https://i.ytimg.com/vi/rf8Gi2RLKWQ/default.jpg)](https://www.youtube.com/watch?v=rf8Gi2RLKWQ)
1. read [Lesson: Interfaces and Inheritance](https://docs.oracle.com/javase/tutorial/java/IandI/index.html)
2. create your own 1 minute video 
	1. share one thing you learned
	1. share which of the agile values is most important and why
3. upload this video to YouTube
	1. set your video privacy to 'unlisted'
4. attach the video link to this assignment

## Resources
1. (https://youtu.be/OPda7mPdRsU)
1. (https://youtu.be/uI5EJ5PAxF4)

## Key Concepts

1. The Agile Manifesto was a recognition that the software industry needed a fundamental shift rather than just more best practices.  

1. Four Agile Manifesto Values

    1. Individuals and interactions over processes and tools 
    1. Working software over comprehensive documentation 
    1. Customer collaboration over contract negotiation 
    1. Responding to change over following a plan

1. While both sides have value, the Agile Manifesto favors the fist value over the second value.  
1. Interface: an abstract type that is used to specify a contract that classes must implement
1. An interface can extend other interfaces
1. Methods in an interface are implicitly public, so you can omit the public modifier.
1. A static method is a method that is associated with the class in which it is defined rather than with any object.
1. A class that is derived from another class is called a subclass (also a derived class, extended class, or child class). 
1. The class from which the subclass is derived is called a superclass (also a base class or a parent class)
1. One significant difference between classes and interfaces is that classes can have fields whereas interfaces cannot.
1. Polymorphism: the provision of a single interface to entities of different types or the use of a single symbol to represent multiple different types.
1. The access specifier for an overriding method can allow more, but not less, access than the overridden method.
1. Every class you use or write inherits the instance methods of Object.
1. The methods inherited from Object
	1. protected Object clone() throws CloneNotSupportedException
	1. public boolean equals(Object obj)
	1. protected void finalize() throws Throwable
	1. public final Class getClass()
	1. public int hashCode()
	1. public String toString()
1. You use the final keyword in a method declaration to indicate that the method cannot be overridden by subclasses.
1. An abstract method is a method that is declared without an implementation (without braces, and followed by a semicolon)
1. An abstract class is a class that is declared abstract—it may or may not include abstract methods.
1. Abstract classes are similar to interfaces. 
	1. You cannot instantiate them, and they may contain a mix of methods declared with or without an implementation.
	1. However, with abstract classes, you can declare fields that are not static and final, and define public, protected, and private concrete methods. 
	1. With interfaces, all fields are automatically public, static, and final, and all methods that you declare or define (as default methods) are public. 
	1. In addition, you can extend only one class, whether or not it is abstract, whereas you can implement any number of interfaces.
	
