# OO Design

## SOLID

Solid stands for:

* S - Single-responsiblity Principle
* O - Open-closed Principle
* L - Liskov Substitution Principle
* I - Interface Segregation Principle
* D - Dependency Inversion Principle

### Single-responsiblity Principle

This means that the class will handle one operation or one job, suppose that we want to calculate the area of shapes then our class will only claculate the areas only and will not do any other operation.

### Open-Closed Principle

This means that we can extend a class and use its parameteres or values but we can't modify from another class, we can'e add a new shape for the shapes class from another class but instead we can build an interface for the shapes and then add as many shapes as we want and then implement the interface.

### Liskov Substitution Principle

This means that we can replace our child class with the parent class and use it but it should serve the same purpose/operation of the class.

### Interface Segregation Principle

This means that we don't need to/can't put methods to an iterface that don't work or aplly to our class, like we can't put a volume methode in our interface if we want to implement it in a square class instead we build a new interface that serves the shapes that can have volumes.

### Dependency Inversion Principle

High-level modules should not depend on low-level modules. Both should depend on interfaces.
Abstractions should not depend on details. Details (concrete implementations) should depend on interfaces. (Source wikipedia)

