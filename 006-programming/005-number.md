# Number Data Types

## Discover
- watch [![YouTube](https://i.ytimg.com/vi/G5c_Pc8P2EI/default.jpg)](https://www.youtube.com/watch?v=G5c_Pc8P2EI)

## Try
- Site: SoloLearn.com
- Topic: Java
- Modules: More on Classes

## Apply
- Site: https://github.com/pairing4good/java-koans
- Complete `AboutMocks`

## Key Concepts
1. There are 4 core concepts in OOP: 
   1. encapsulation, 
   2. inheritance, 
   3. polymorphism, 
   4. and abstraction.
1. The idea behind encapsulation is to ensure that implementation details are not visible to users. 
1. The variables of one class will be hidden from the other classes, accessible only through the methods of the current class. This is called data hiding.
1. Encapsulation provides the following benefits:
   1. Control of the way data is accessed or modified
   1. More flexible and easily changed code
   1. Ability to change one part of the code without affecting other parts
1. Inheritance is the process that enables one class to acquire the properties (methods and variables) of another. 
1. The protected access modifier, which makes the members visible only to the subclasses.
1. Constructors are not member methods, and so are not inherited by subclasses.
1. You can access the superclass from the subclass using the super keyword. 
1. Polymorphism is one method, with different implmentations.
1. Rules for Method Overriding:
   1. Should have the same return type and arguments
   1. The access level cannot be more restrictive than the overridden method's access level (Example: If the superclass method is declared public, the overriding method in the sub class can be neither private nor protected)
   1. A method declared final or static cannot be overridden
   1. If a method cannot be inherited, it cannot be overridden
   1. Constructors cannot be overridden
1. When methods have the same name, but different parameters, it is known as method overloading.
1. Data abstraction provides the outside world with only essential information, in a process of representing essential features without including implementation details.
1. An abstract class is defined using the abstract keyword.
   1. If a class is declared abstract it cannot be instantiated (you cannot create objects of that type).
   1. To use an abstract class, you have to inherit it from another class.
   1. Any class that contains an abstract method should be defined as abstract.
1. An interface is a completely abstract class that contains only abstract methods.
1. Some specifications for interfaces:
   1. Defined using the interface keyword.
   1. May contain only static final variables.
   1. Cannot contain a constructor because interfaces cannot be instantiated.
   1. Interfaces can extend other interfaces.
   1. A class can implement any number of interfaces.
1. A class can inherit from just one superclass, but can implement multiple interfaces!
1. When you compare objects using the equality testing operator (==), it actually compares the references and not the object values.
1. When you override the equals method you must also override the hashCode method.
