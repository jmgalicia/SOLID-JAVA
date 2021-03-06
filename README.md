# SOLID-DESIGN-PRINCIPLES

![image](https://user-images.githubusercontent.com/32823174/35490855-9105ce1e-0470-11e8-988e-72b3ecd0ff0e.png)

- - - -
### Issues that we encountered during development
* Rigidity - is the tendency for software to be difficult to change, even in simple ways. Every change causes a cascade of subsequent changes in dependent modules
* Fragility - When you make a change, unexpected parts of the system break.
* Immobility - hard to reuse
* Viscosity - easier to hack than fix properly
* Opacity - Hard to read/understand 

- - - -
### How do you define “Good Code”?

* Code should be self documenting
* Code should be transparent - easy to understand
* Good code is like a good joke, It needs no explanations

- - - -
### Design Principles

* Keep it (D.R.Y.) – Don’t repeat yourself!
* K.I.S.S – Keep it simple, St**id!
* Y.A.G.N.I – You aren’t gonna need it!
* S.O.L.I.D

- - - -
### S.O.L.I.D. Design Principles - Robert Martin 

Books:
* Agile Principles, Patterns and Practices by Robert and Micah Martin.
* Clean Code - A Handbook of Agile Software Craftsmanship

S.O.L.I.D.
* S – Single Responsibility Principle
* O – Open/Close Principle
* L – Liskov Substitution Principle
* I – Interface Segregation Principle
* D – Dependency Inversion Principle

- - - -
### Single Responsibility Principle (SRP)
![image](https://user-images.githubusercontent.com/32823174/35490986-a854f562-0471-11e8-9ee9-45c31e342cd5.png)

![image](https://user-images.githubusercontent.com/32823174/35491001-c09dee3a-0471-11e8-9c25-43d53fdde2b2.png)

##### Definition:
A class should have only one reason to change

Benefits:
* easier to understand
* easier to maintain
* more reusable

Disadvantages of Long Methods:
* hard to read
* hard to reuse/ leads to duplication
* hard to test
* many reasons to change

- - - -
### Open Close Principle (OCP)
![image](https://user-images.githubusercontent.com/32823174/35491066-3f4e987e-0472-11e8-9531-2d243bac165e.png)
#### “open for extension, but closed for modification.”

- - - -
### Liskov Substitution Principle (LSP)
![image](https://user-images.githubusercontent.com/32823174/35491121-8754a122-0472-11e8-98af-3ddac98cbbc6.png)

- - - -
### Interface Segregation Principle (ISP)
![image](https://user-images.githubusercontent.com/32823174/35491152-afee5bc8-0472-11e8-8d3e-f1f66c0bb1a5.png)

* Don't force clients to depend on methods they do not use
* avoid fat interfaces
* Single Responsibility in a interface level

- - - -
### Dependency Inversion Principle (DIP)
![image](https://user-images.githubusercontent.com/32823174/35491203-f21ac536-0472-11e8-9085-2ddddc0756a7.png)

“High-lever modules should not depend on low-level modules. Both should depend on abstractions”

High-level modules <----> ABSTRACTION <----> Low-level modules



