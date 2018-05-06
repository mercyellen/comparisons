# comparisons

### Instance reference name in data type (class)

  * Java | Swift
    ---- | -----
    This | self

### Properties

* Getters and setters

  * Java | Swift
    ---- | -----
    You have to create your own getters and setters | Getters and setters for constants, variables, and subscripts automatically receive the same access level as the constant, variable, property, or subscript they belong to. You can give a setter a lower access level than its corresponding getter, to restrict the read-write scope of that variable, property or subscript.
* Backing variables

  * Java | Swift
    ---- | -----
    Java does not have backing fields. | Swift unifies Objective-C's ways to store variables into a single property declaration. Swift doesn't have a corresponding instance variable, and the backing variable for a property is not accessed directly. All the information about a property is stored in a single location. 
    
* Computed properties

  * Java | Swift
    ---- | -----
     As soon as you use a custom getter and/or setter method with a variable, it is a computed property | Calculate a value rather than storing the value by providing a getter and an optional setter to retrieve and set other properties and values indirectly
    
### Interfaces / protocols
* What does the language support

  * Java | Swift
    ---- | -----
    Interfaces|Protocols
    
* What abilities does it have?

  * Java | Swift
    ---- | -----
    You are able to implement as many interfaces as needed. The interface will also force you to include all methods defined within it in every class that implements it. | The protocol can be adopted by a class, structure, or enumeration to provide an actual implementation of those requirements. Any type that satisfies the requirements of a protocol is said to conform to that protocol. In addition to specifying requirements that conforming types must implement, you can extend a protocol to implement some of these requirements or to implement additional functionality that conforming types can take advantage of.

* How is it used?

  * Java | Swift
    ---- | -----
    Unless the class that implements the interface is abstract, all the methods of the interface need to be defined in the class. The interface keyword is used to declare an interface. A class uses the implements keyword to implement an interface. The implements keyword appears in the class declaration following the extends portion of the declaration. |  The protocol specifies whether each property must be gettable or gettable and settable. They can also require specific instance methods and type methods to be implemented by conforming types, which are written as part of the protocol's definition without curly braces or a method body.
    
### Inheritance / extension

* Inheritance

  * Java | Swift
    ---- | -----
    Multiple inheritance is not allowed (A class extending multiple classes). You can have superclass = new subclass(), but you cannot have subclass = new superclass(). It's used to gain access to another class' members, including methods and fields. | Only classes can inherit from another class. In other words, structures and enumerations don't support inheritance. Multiple inheritance is also not allowed. It's used to gain access to another class' members, including methods and fields.
  
* Extension

  * Java | Swift
    ---- | -----
    Does not support extension | Extensions add new functionality to an existing class, structure, enumeration, or protocol type. This includes the ability to extend types for which you do not have access to the original source code (known as retroactive modeling). Four uses include protocol conformance, preserving initializers, code separation, and nested types.


### Reflection

* What reflection abilities are supported?

  * Java | Swift
    ---- | -----
    Makes it possible to inspect classes, interfaces, fields and methods at runtime, without knowing the names of the classes, methods etc. at compile time. It is also possible to instantiate new objects, invoke methods and get/set field values using reflection. | Swift's reflection capabilities are based around a struct called Mirror. You create a mirror for a particular subject and the mirror will then let you query it.

* How is reflection used?

  * Java | Swift
    ---- | -----
    Java Reflection can be used to map properties in JSON files to getter / setter methods in Java objects, like Jackson, GSON, Boon etc. does. Or, Reflection can be used to map the column names of a JDBC ResultSet to getter / setter methods in a Java object. | Its current functionality allows us to look at the objects’ properties without modifying them, which is represented by Mirror structure
    

