
# Go Language - Design Patterns

##  Go Language Features That Affect Design Patterns
No support for traditional OOP classes like in C# or Java
* No static members or constructors - affects patterns like Singleton
No support for class-based inheritance or method overloading
* Affects patterns like Visitor
No support for exceptions error handling is via return values
* Affects patterns like Builder
No support for abstract classes 
* Affects patterns like Abstract Factory and Bridge


##  Creational Pattern: Builder Pattern
Purpose:

* Encapsulates an object's construction process along with specifying the various parts of a complex API.
* Enables flexible creation of an object that can have many different representations.
* Increases code readability for complex type.

Scenarios: 

* Objects that have complex APIs, multiple constructor options, and several different possible representations.
