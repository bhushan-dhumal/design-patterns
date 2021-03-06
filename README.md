# design-patterns


Design pattern classified by purpose in below three category

1. **Creationl** - concern the process of object creation.
2. **Structural** - composition of classes or objects.
3. **Behavioural** - characterize the ways in which classes or objects interact and distribute responsibility.

Design pattern can also be classifed by scope in below two category

- Class (c)
- Object (o)

## Creational
### Factory Method (c)
Define an interface for creating the object, but let subclasses decide which class to instantiate.

Factory Method lets a class defer instantiation to subclasses.

### Abstract Factory (o)
Provide an interface for creating families of related or dependent objects without specifying their concrete classes.

### Builder (o)
Separate the construction of a complex object from its representation so that the same construction process can create different representations.

### Prototype (o)
Specify the kinds of objects to create using a prototypical instance, and create new objects by copying this prototype.

### Singleton (o)
Ensure a class only has one instance, and provide a global point of access to it.

## Structural
### Adapter (c) (o)
Convert the interface of a class into another interface clients expect.

The adapter lets classes work together that could not otherwise because of incompatible interfaces.

### Bridge (o)
Decouple an abstraction from its implementation so that the two can vary independently.

### Composite (o)
Compose objects into tree structures to represent part-whole hierarchies.

Composite lets clients treat individual objects and compositions of objects uniformly.

### Decorator (o)
Attach additional responsibilities to an object dynamically.

Decorators provide a flexible alternative to subclassing for extending functionality.

### Facade (o)
Provide a unified interface to a set of interfaces in a subsystem.

A facade defines a higher-level interface that makes the subsystem easier to use.

### Flyweight (o)
Use sharing to support large numbers of fine-grained objects efficiently.

### Proxy (o)
Provide a surrogate or placeholder for another object to control access to it.

## Behavioural
### Interpreter (c)
Given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences

### Template Method (c)
Define the skeleton of an algorithm in an operation, deferring some steps to subclasses.

Template Method lets subclasses redefine certain steps of an algorithm without changing the algorithm's structure.

### Chain of Responsibility (o)
Avoid coupling the sender of a request to its receiver by giving more than one object a chance to handle the request.

Chain the receiving objects and pass the request along the chain until an object handles it.

### Command (o)
Encapsulate a request as an object, thereby letting you parameterize clients with different requests, queue or log requests, and support undoable operations.

### Iterator (o)
Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.

### Mediator (o)
Define an object that encapsulates how a set of objects interact.

Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and it lets you vary their interaction independently.

### Momento (o)
Without violating enacapsulation, capture and externalize an object's internal state so that the object can be restored to this state later.

### Observer (o)
Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.

### State (o)
Allow an object to alter its behaviour when its internal state changes.

The object will appear to change its class.

### Strategy (o)
Define a family of algorithms, encapsulate each one, and make them interchangeable.

Strategy lets the algorithm vary independently from clients that use it.


### Visitor (o)
Represent an operation to be performed on the elements of an object structure.

Visitor lets you define a new operation without changing the classes of the elements on which it operates.
