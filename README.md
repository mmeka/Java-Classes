# Constructors

Default constructor. Compliler generates only when no other constrcutor is defined. Access modifier for default constructor is same as that of the class it is contained inside. It contains call to super constructor?? What if the super class doesn't have a no-arg constructor defined??
A constructor will not have any return type, exception throws.
A constrcutor allows only access modifiers - public, protected, default, private. Synchronized is not allowed. 
A method can share the same name as a constructor. However, not recommended.
First line of code inside a constrcutor must be super(); or this();. If not, a compile error results in. Why is that so??
Usage of this(); and super(); must be within the constructor. Elsewhere usage results in compile time error.
super and this keywords can be used anywhere except static areas.
When a this(); is called from another constrcutor, controller will call that no-arg constrcutor and then executes the remaining lines inside the calling constructor.
Purpose of having a constructor inside an abrstract class is to have it called from instantiation of child classed so that any instance variables inside that abstract class gets initialized.
"Recursive constructor invocation" - is a compile time error when two constructors are recusively calling each other.
When a class is defined with no no-arg constuctor, a child class is required to have a constructor defined with an explicit call to the parameterized constrcutor.
If the parent class constrcutor throws a checked exception, it's required to have the child class constrcutor with super(); statement to have declared with a throws declaration of to have same exception or it's parent exception.

How to validate the data inside a constructor and prevent the object creation??
Difference between "return this;" and "return this();"??
What's the behavior during object creation when the access modifier of the class is different from the constructor within?
How varargs constrcutor is executed when defined alongside other parameterized constrcutors?

"Could not find or load main class <class_name>": is the error occurred when corresponding ".class" file is not available during Run command.


# Packages and Imports

A Java file may contain atmost one public class only. And, if the file has a public class defined, the name of the class and the Java file it's contained within must share the same name.
A Java file may contain any number of classes, given not more than one is defined as public. After compilation, each class get it's individual ".class" file generated.
While declaraing explicit imports as "import java.util.* ", only the classes within that package are available to the declared class. Sub-packages have to imported explicitly.


# Classes
Allowed access modifiers are - public, (default), abstract, final and strictfp.

# Adapter classes

# Inner Classes
Allowed access modifiers are - public, (default), abstract, final, strictfp, private, protected and static.
