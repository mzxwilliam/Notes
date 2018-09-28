# Notes
Intro
Reasons for OOP
	- Programmer friendly
	Easy to design and visualize
	- Simple program
	Easy to understand
	- Code reuse
	Inheritance
	Modularity
	- Maintainability 
	- Errors are isolated in a small part of code
	Due to encapsulation and modularization
	
Class: abstract idea
Object: real thing, created in memory
Inheritance: super class --- subclass
Instance = object

Override / overwrite: same function under different class
A subclass uses the same method declaration as its superclass (static / dynamic)

Overload: two functions have same names but different argument
A subclass uses two or more declarations of the same name, one could also be from super class

1 class has 1 super class

UML diagram

Minus (-) means private 
Plus (+) means public --- access modifier

Data type
Primitive data type:
	- Float: 4 bytes
	- Double: 8 bytes
	
	- Int: 4 bytes
	- Long: 8 bytes

	- Boolean: 1 byte

	- String --- object

Dependency (UML diagram)
	- Dotted line: object with not arrow need object / interface with arrow
	- Add complexity 
		○ Decrease maintainability 
			§ Change one object, how does it affect others
			§ Modularity: self-confined part of the program, change it, no effect on others
		○ Inconvenient implementation
			§ Less dependency & more modularity decrease error 
			
Inheritance 
Encapsulation (hidden info)

Polymorphism: one object can be treated as two or more types of object

