# Interfaces

is a blueprint of a class. It has static constants and abstract methods.
The interface in Java is a mechanism to achieve abstraction. There can be only abstract methods in the Java interface, not method body.

## Why use Java interface?
![](https://static.javatpoint.com/interview/images/why-use-java-interface.jpg)

# How to declare an interface?

     interface <interface_name>{  
     declare constant fields  
     declare methods that abstract   
     by default.  
    }  

## Multiple inheritance in Java by interface

![](https://static.javatpoint.com/images/core/multipleinheritance.jpg)

## deffirant between inheritance and interface

An interface is always an agreement or a promise. When a class says "I implement interface Y", it is saying "I promise to have the same public methods that any object with interface Y has".

An abstract class is the foundation for another object. When a class says "I extend abstract class Y", it is saying "I use some methods or properties already defined in this other class named Y".