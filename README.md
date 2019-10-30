# SolidHomework
S - Single-responsiblity principle
O - Open-closed principle
L - Liskov substitution principle
I - Interface segregation principle
D - Dependency Inversion Principle

S- it makes your software easier to implement and prevents unexpected side-effects of future changes.
You need to change your class as soon as one of its responsibilities changes. That is obviously more often than you would need to change it if it had only one responsibility.

O-Software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification.
It tells you to write your code so that you will be able to add new functionality without changing the existing code. That prevents situations in which a change to one of your classes also requires you to adapt all depending classes. 

L-Let Φ(x) be a property provable about objects x of type T. Then Φ(y) should be true for objects y of type S where S is a subtype of T.
The principle defines that objects of a superclass shall be replaceable with objects of its subclasses without breaking the application. That requires the objects of your subclasses to behave in the same way as the objects of your superclass.

I-Clients should not be forced to depend upon interfaces that they do not use.
the goal of the Interface Segregation Principle is to reduce the side effects and frequency of required changes by splitting the software into multiple, independent parts.

D-What Dependency Inversion Principle says is that instead of a high-level module depending on a low-level module, both should depend on an abstraction.

1.High-level modules should not depend on low-level modules. Both should depend on abstractions.
2.Abstractions should not depend on details. Details should depend on abstractions.
The important detail about this principle is, that high-level and low-level modules depend on the abstraction
It splits the dependency between the high-level and low-level modules by introducing an abstraction between them. So in the end, you get two dependencies.
