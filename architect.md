## SOLID principles
#### S: Single Responsibility
A class should have one and only one reason to change, meaning that a class should have only one job.
This principle aims to separate behaviours so that if bugs arise as a result of your change, it won’t affect other unrelated behaviours.
#### O: Open-Closed
Classes should be open for extension, but closed for modification.
If you want the Class to perform more functions, the ideal approach is to add to the functions that already exist NOT change them.
This principle aims to extend a Class’s behaviour without changing the existing behaviour of that Class. This is to avoid causing bugs wherever the Class is being used.
#### L: Liskov Substitution
If S is a subtype of T, then objects of type T in a program may be replaced with objects of type S without altering any of the desirable properties of that program.
This principle aims to enforce consistency so that the parent Class or its child Class can be used in the same way without any errors.
#### I: Interface Segregation
This principle aims at splitting a set of actions into smaller sets so that a Class executes ONLY the set of actions it requires.
That's mean better way to split interfaces to not force client to implement contracts of methods that they don't use.  
*EX: Shape -> FlatShape + 3DShape (for square and cube)*
#### L: Dependency Inversion
High-level module must not depend on the low-level module, but they should depend on abstractions.  
In other words, high level module should use abstract interfaces which low-level modules can implement, and they could be replaceable.
