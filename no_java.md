## Why Java is a mediocre programming language

* Java lacks useful features. The OOP system is very powerful, but because of the lack
  of extra features, programming something is very difficult. On the other hand, Python
  is slow, but has many features, such as C integration, list comprehension, and running
  code dynamically, that makes the language superior. Java copied style and syntax from
  C++, but designed the language to be high level. If the purpose and features don't
  match, the language will not succeed.
* Everything must be a class. A class defines the memory layout of an abstract concept,
  optionally with functions that are tied to the class (methods). If you need to group
  members together, use a namespace instead of a class to be clear about your purpose.
  Depending on the implementation, this may even reduce overhead.
* Java is not flexible. Some people use Java to make non speed critical programs.
  In those cases, one thing most programmers are looking for is development speed,
  or ease of usage. Java is not suitable for this because it requires static typing,
  object oriented programming, and one class per file. If a programmer just wants to
  write a simple script to do something, they must first make a whole directory for it,
  do some detailed planning of the class structure, and spend a lot of time managing
  the types. An alternative of this is Python, which is moderately fast, very flexible,
  and very easy to use to write a quick application.
* Java does not have a lot of libraries. Python has pip, and anyone can create libraries
  and publish them for the world. There are libraries like numpy, which provides fast C
  implementations of matrices, and pytorch, which have GPU implementations. Because
  Python is easier to use, more developers choose to develop libraries for Python,
  increasing its ease of usage (a positive feedback loop).
* Python has a good documentation tool, Sphinx, which allows users to
  easily understand and use libraries. As stated in [this StackOverflow post][so], good
  documentation needs examples. Luckily, many Python packages have good examples. However,
  JavaDoc, the Java documentation tool, simply generates docs of the methods of each
  class. This makes it difficult to provide good examples in a way that is easy to follow
  for someone new to a library.
* Some people believe that Python is inferior because it depends on C and C++. Yes, it
  is inferior if you don't use the language at all. The power of Python is in it's
  flexibility, as described above. Compare two APIs in Java and Python, and see which
  one is easier to use.

If you are in a course which teaches Java, I highly recommend you learn C++ and/or Python
on the side so you finish the class with useful skills.

## Why do schools use Java as an introductory language?

I don't know, but here are my guesses.

* Java is an extremely organized language. As stated previously, this is so extreme that
  it makes the language very limited. However, it is useful for teaching concepts like
  OOP and good development habits.
* Java is easy to set up. Modern code editors like VSCode have features that make Java code
  easy to manage, and is good for beginner programmers.
* Some historical reason. Maybe Java seemed like a good choice when schools first decided
  what programming language they were going to use.

## Advanced Placement (AP) computer science

I believe that the curriculum for APCS can be improved. APCS A focuses on the Java language
and being able to read basic code. APCS B focuses on data structures.

"Computer science" is a very broad term, just like "math". There are different math courses,
such as calculus, stats, linear algebra, etc. Each one focuses on a specific branch of
study in math. However, we see CS A, CS B, etc. An ideal set of AP CS courses should test
advanced concepts and assume that the individuals already know the basic concepts. Just like
how math AP courses start at calculus and assume knowledge of algebra and arithmetic, AP CS
tests should assume knowledge of programming languages, and should test algorithms, like
USACO.

However, this is unlikely to change in the future, similar to how an API cannot be changed
once many people start using it. The only solution is to self study beyond the AP CS curriculum.

[so]: https://meta.stackoverflow.com/a/303885/16570071
