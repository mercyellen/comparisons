# comparisons

### Instance reference name in data type (class)

  * Java | Swift
    ---- | -----
    This | self

### Properties

* Getters and setters

  * Java | Swift
    ---- | -----
    You have to create your own getters and setters | 
* Backing variables

  * Java | Swift
    ---- | -----
    
* Computed properties

  * Java | Swift
    ---- | -----
    
### Interfaces / protocols
* What does the language support

  * Java | Swift
    ---- | -----
    Interfaces|Protocols
    
* What abilities does it have?

  * Java | Swift
    ---- | -----
    Unsure | The protocol can then be adopted by a class, structure, or enumeration to provide an actual implementation of those requirements. Any type that satisfies the requirements of a protocol is said to conform to that protocol. In addition to specifying requirements that conforming types must implement, you can extend a protocol to implement some of these requirements or to implement additional functionality that conforming types can take advantage of.

* How is it used?

  * Java | Swift
    ---- | -----
    IDK | 
    
### Inheritance / extension

*Inheritance

 * Java | Swift
   ---- | -----
     Multiple inheritance is not allowed (A class extending multiple classes). You can have superclass = new subclass(), but you cannot have subclass = new superclass(). It's used to gain access to another class' members, including methods and fields. | Only classes can inherit from another class. In other words, structures and enumerations don't support inheritance. Multiple inheritance is also not allowed. It's used to gain access to another class' members, including methods and fields.
       
*Extension

  * Java | Swift
    ---- | -----
    Does not support extension | Extensions add new functionality to an existing class, structure, enumeration, or protocol type. This includes the ability to extend types for which you do not have access to the original source code (known as retroactive modeling). Four uses include protocol conformance, preserving initializers, code separation, and nested types.


### Reflection

* What reflection abilities are supported?

  * Java | Swift
    ---- | -----
    Makes it possible to inspect classes, interfaces, fields and methods at runtime, without knowing the names of the classes, methods etc. at compile time. It is also possible to instantiate new objects, invoke methods and get/set field values using reflection. | its current functionality allows us to look at the objects’ properties without modifying them, which is representeted by Mirror structure

* How is reflection used?

  * Java | Swift
    ---- | -----
    Java Reflection can be used to map properties in JSON files to getter / setter methods in Java objects, like Jackson, GSON, Boon etc. does. Or, Reflection can be used to map the column names of a JDBC ResultSet to getter / setter methods in a Java object. | 
    

