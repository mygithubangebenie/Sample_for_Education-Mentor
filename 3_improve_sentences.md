self points to the instance object itself. Use self when calling an instance object in a class or when calling that instance object.


Revised

In many object-oriented programming languages, this (also called self or Me ) is a variable that is used in instance methods to refer to the object on which they are working. ... Some languages require it explicitly; others use lexical scoping to use it implicitly to make symbols within their class visible.


The reason you need to use self. is because Python does not use the @ syntax to refer to instance attributes. Python decided to do methods in a way that makes the instance to which the method belongs be passed automatically, but not received automatically: the first parameter of methods is the instance the method is called on. That makes methods entirely the same as functions, and leaves the actual name to use up to you (although self is the convention, and people will generally frown at you when you use something else.) self is not special to the code, it's just another object.