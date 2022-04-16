# Why You Shouldn't Use Java

* Java copied all syntax from C++. Although this does not make it bad, it shows
  how the developers are not willing to add new features.
* Java is slow. In my tests, it runs 2-3x slower than C++. This is a big difference,
  and can mean running for a whole workday rather than a few hours.
* Java lacks useful features. There is no control of pointers, references, and there
  are no low level operations in Java. It is even missing unsigned integer types!
* Everything must be a class. A class defines the memory layout of an abstract concept,
  optionally with functions that are tied to the class (methods). If you need to group
  members together, a namespace is more intuitive, rather than a class.
* Java is not flexible. Some people use Java to make non speed critical programs.
  In those cases, one thing most programmers are looking for is development speed,
  or ease of usage. Java is not suitable for this because it requires static typing,
  object oriented programming, and one class per file. If a programmer just wants to
  write a simple script to do something, they must first make a whole directory for it,
  do some detailed planning of the class structure, and spend a lot of time managing
  the types. An alternative of this is Python, which is moderately fast, very flexible,
  and very easy to use to write a quick application.
* Java does not have a lot of libraries or an installer. Python has pip, and anyone
  can create libraries and publish them for the world. There are libraries like numpy,
  which provides fast C implementations of matrices, and pytorch, which have GPU
  implementations. Because Python is easier to use, more developers choose to develop
  libraries for Python, increasing its ease of usage (a positive feedback loop).

If you are in a course which teaches Java, I highly recommend you learn C++ and/or Python
on the side so you finish the class with useful skills.
