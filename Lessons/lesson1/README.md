# Running the Interpreter
Assuming you followed the instructions and downloaded python, you can open terminal and type run the command

`$ python`

This should change the symbol in your terminal window.
You are now in the python interpreter.

From here, the simplest thing to start with is to try out various math operations.

---

# Mathematical Operations
You should already be familiar with the basic operations but I'll go over them again briefly.

|Operation| Symbol | Usage|
|---|:---:|---|
|Addition|+|1+2|
|Subtraction|-|1-2|
|Multiplication|*|1*2|
|Division|/|1/2|
|Modulo|%|1%2|

If you are unfamiliar with modulo, it gives back the remainder when dividing.

```python
> 5 / 2
2
> 5 % 2
1
```
Normally, dividing 5 by 2 gives 2.5 which the interpreter then rounds to 2
Using modulo however, the interpreter returns 1. This is because 2 fits into 5 two times with one remaining.

### Order of operations

Parentheses can be used to indicate precedence just like in normal math.
```python
> 5+(3*2)
11
> (5+3)*2
16
```
At this point we're really only using the interpreter as a calculator, let's try doing something more fancy.

---
## Next
We'll be tackling Input and Output as well as writing our first program!
[Lesson Two](https://github.com/MoF-Dev/learningpython/tree/master/Lessons/lesson2)
