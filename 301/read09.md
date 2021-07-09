What is functional programming?
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia

What is a pure function and how do we know if something is a pure function?
So how do we know if a function is pure or not? Here is a very strict definition of purity:
It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects
It returns the same result if given the same arguments
Imagine we want to implement a function that calculates the area of a circle. An impure function would receive radius as the parameter, and then calculate radius * radius * PI:

What are the benefits of a pure function?
Pure functions are much easier to read and reason about. All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs. This means that we can quickly understand a function and its dependencies, just by reading the function's declaration.١٢‏/٠٨‏/٢٠١٩

What is immutability?
In object-oriented and functional programming, an immutable object (unchangeable[1] object) is an object whose state cannot be modified after it is created.[2] This is in contrast to a mutable object (changeable object), which can be modified after it is created. [3] In some cases, an object is considered immutable even if some internally used attributes change, but the object's state appears unchanging from an external point of view. For example, an object that uses memoization to cache the results of expensive computations could still be considered an immutable object.


What is Referential transparency?
Referential transparency and referential opacity are properties of parts of computer programs. An expression is called referentially transparent if it can be replaced with its corresponding value (and vice-versa) without changing the program's behavior.[1] This requires that the expression be pure, that is to say the expression value must be the same for the same inputs and its evaluation must have no side effects. An expression that is not referentially transparent is called referentially opaque.



What is a module?
A module is a software component or part of a program that contains one or more routines. One or more independently developed modules make up a program. An enterprise-level software application may contain several different modules, and each module serves unique and separate business operations.

What does the word ‘require’ do?
How do we bring another module into the file the we are working in?
What do we have to do to make a module available?