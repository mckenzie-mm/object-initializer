# object-initializer


### How to initialize objects by using an object initializer (C# Programming Guide)


You can use object initializers to initialize type objects in a declarative manner without explicitly invoking a constructor for the type.

The following examples show how to use object initializers with named objects. The compiler processes object initializers by first accessing the parameterless instance 
constructor and then processing the member initializations. 

Therefore, if the parameterless constructor is declared as private in the class, object initializers that require public access will fail.
