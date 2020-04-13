# Constructors

Default constructor. Compliler generates only when no other constrcutor is defined. Access modifier for default constructor is same as that of the class it is contained inside. It contains call to super constructor?? What if the super class doesn't have a no-arg constructor defined??
A constructor will not have any return type, exception throws.
A constrcutor allows only access modifiers - public, protected, default, private. Synchronized is not allowed. 
A method can share the same name as a constructor. However, not recommended.
First line of code inside a constrcutor must be super(); or this();. If not, a compile error results in. Why is that so??
Usage of this(); and super(); must be within the constructor. Elsewhere usage results in compile time error.
super and this keywords can be used anywhere except static areas.
When a this(); is called from another constrcutor, controller will call that no-arg constrcutor and then executes the remaining lines inside the calling constructor.

How to validate the data inside a constructor and prevent the object creation??
Difference between "return this;" and "return this();"??
What's the behavior during object creation when the access modifier of the class is different from the constructor within?
How varargs constrcutor is executed when defined alongside other parameterized constrcutors?
