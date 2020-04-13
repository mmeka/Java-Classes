# Constructors

Default constructor. Compliler generates only when no other constrcutor is defined. Access modifier for default constructor is same as that of the class it is contained inside. It contains call to super constructor?? What if the super class doesn't have a no-arg constructor defined??
A constructor will not have any return type, exception throws.
A constrcutor allows only access modifiers - public, protected, default, private. Synchronized is not allowed. 
A method can share the same name as a constructor. However, not recommended.
First line of code inside a constrcutor must be super(); or this();. What if not??

How to validate the data inside a constructor and prevent the object creation??
Difference between "return this;" and "return this();"??
What's the behavior during object creation when the access modifier of the class is different from the constructor within?
