## Why Java is a mediocre programming language

* Java lacks useful features. The OOP system is very powerful, but because of the lack
  of extra features, programming something is very difficult because only a limited set
  of tools are provided. On the other hand, Python is slow but has many features, such
  as C integration, list comprehension, and running code dynamically, which makes the
  language superior due to the tools it provides. Java copied style and syntax from C++,
  but designed the language to be high level. If the purpose and features don't match,
  the language will not succeed. Strict static typing is a hindrance rather than an
  optimization in high level languages.
* Java forces object oriented programming. A class defines the memory layout of an abstract
  concept, optionally with functions that are tied to the class (methods). If you need to
  group members together, use a namespace instead of a class to be clear about your purpose.
  Depending on the implementation, this may even reduce overhead.
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
  one is easier to use. Having water faucets in your house is worse than not if you don't
  use them because it involves drilling holes into walls. However, we still prefer
  having them. Why? This is left as an exercise to the reader.
* The compiler does not allow some coding techniques, in the hope of reducing accidental
  errors. One example is unreachable code, which is an error, not a warning! What if we
  want to stop the last part of a function as a test debug by putting an early return
  statement? We cannot do that, and we must comment the whole block, which takes a few
  extra seconds, but more importantly, reduces the programmer's morale as they see the
  flaws of the Java compiler.

If you are in a course which teaches Java, I highly recommend you learn C++ and/or Python
on the side so you finish the class with useful skills.

## Why do schools use Java as an introductory language?

I don't know, but here are my guesses.

* Java is an extremely organized language. As stated previously, this is so extreme that
  it makes the language very limited. However, it is useful for teaching concepts like
  OOP and good development habits.
* Java is easy to set up and beginner friendly. Modern code editors like VSCode have
  features that make Java code easy to manage, and is good for beginner programmers.
* Java is simple. This allows students to start writing programs quickly instead of trying
  to wrap their heads around pointers.
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
