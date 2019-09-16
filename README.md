# C_Sharp_Notes
___

* Stable Release (Sept 2019): v. 7.3

* The key organizational concepts in C# are programs, `namespaces`, `types`, `members`, and `assemblies`. 

  C# programs consist of one or more source files. 
  
  Programs declare types, which contain members and can be organized into namespaces. 
  
  Classes and interfaces are examples of types. 
  
  Fields, methods, properties, and events are examples of members. 
  
  When C# programs are compiled, they are physically packaged into assemblies. Assemblies typically have the file extension .exe or .dll, depending on whether they implement applications or libraries, respectively.
  
  * C# source code compiles to intermediate code. The CLR uses a JIT compiler to translate the intermediate code to code for the specific processor used. 

* C# offers garbage collection, exception handling, and is a type-safe language.

* A `declaration` defines a part of a program. `Statements` control the sequence of execution of the program. `Expressions` compute values and have other effects.

Accronynms:
* IL - Intermediate Language

* JIT - Just In Time

* CLR - Common Language Runtime

## Data Types

* classes
* interfaces
* enums
* delegates

* A class is a data structure that combines state (fields) and actions (methods and other function members) in a single unit.

* Classes support inheritance and polymorphism, mechanisms whereby derived classes can extend and specialize base classes.



Built-In Types:

* `bool`
* `byte`
* `char`
* `double`
* `decimal`
* `int`
* `float`
* `long`
* `object`
* `short`
* `string`

* Numbers
  * int
  * double
  * float
  * decimal (fixed point)
  
  
* The `decimal` type has a smaller range but greater precision than `double`.

* Integer division truncates the result.

* You can get the remainder by using the `modulo` operator, the `%` character.

* C#’s value types are further divided into simple types, enum types, struct types, and nullable value types. C#’s reference types are further divided into class types, interface types, array types, and delegate types.

* C#’s type system is unified such that a value of any type can be treated as an `object`. Every type in C# directly or indirectly derives from the `object` class type, and `object` is the ultimate base class of all types. 

*  Values of reference types are treated as objects simply by viewing the values as type `object`.

___

## Control Structures

___

## Data Structures

* Lists (Generic)
* Arrays
* Structs

___

## Object Oriented Programming

















___
Sources:

(1) Computing with C# Textbook

(2) https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/intro-to-csharp/

(3) https://docs.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/
