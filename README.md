# numbersMatter

A static method should be called using the class name rather than an object reference vaeriable
example 
Math.random() vs. myFoo.go()

A static method can be invoked without any instances of the mthods class on the heap.

A static method is good for a utility method that does not (and will never) depend on a particular instance variable value.

A static methos is not associated with a particular instance- only the class- so it cannot access any instance variable of its class. it wouldnt know which instance value to use

A static method cannott access a non-static method, since non- static methods are usually associated wirth instance variable state.

if you have a class with only static methods, adn you do not want the class to be instatiated, you cna mark the constructor private

A static variable is a variable shared by all members of a given class. There is only one copy of a static variable in a class, rather than one copy per each individual instance for instance variables.

A statuc method can access a static variable

To make a constant in Java, mark a variable as both static and final

A final static variable must be assigned a value either at the time it is declared or in static initializer
static {
  DOG_CODE = 420;
  
}

Naming convention for constants (final static variables) is to make the name all uppercase.

A final variable value cannot be changed once it has been assigned

Assigning a value to a final instance variable must be either at the time it is declared or in the constructor

A final method cannot be overriden

A final class cannot be extended (subclassed)

Math methods 
Math.random()
Math.abs()
Math.round()
Math.min()
Math.max()

When you need to treat a primitive like an object, wrap it

Autoboxing: blurring the linbe between primitive and object

Wrappers have static utility methods

converting a string to a primitive value is easy
String s ="2"
int x = Integer.parseInt(s);
double d = Double.parseDouble("420.24")
boolean b = new Boolean("true).boolenValue();

the only required specifier is for TYPE 
you must include a type in your format instructions and if you specify tthings besides type, the type must come last.














