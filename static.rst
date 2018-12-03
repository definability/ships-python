Static method in Python language
================================

A static method in Python language
is a class method with ``@staticmethod`` decorator applied to it.
This allows to call the method without creating new instance of the class.

Advantage:
this allows you to implement some methods that are specific to the class
but don't really need an instance.
For example, converter from another type to current.

Disadvantage:
one may use static methods a lot instead of creating module functions.
