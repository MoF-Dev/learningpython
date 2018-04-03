# Preparing the Editor
You'll need some sort of text editor for the upcoming sections and for the rest of this study guide. I recommend [Atom](https://atom.io/) but if there's a different editor you prefer, go ahead and use that.

# Hello World
We're going to start with the traditional Hello World program. That is, writing a program to print the words "Hello World" onto the screen.

Open up your text editor and create a file named *hello.py*

## Output
In programming terms, *printing* generally means to display text on some sort of screen or console. For us, this means displaying text in the terminal window.

In hello.py, type this line of code:

```python
#hello.py
print "Hello World"
```

Once you've done that, save the file. Open up terminal, navigate to where you saved the hello.py file and run

`$ python hello.py`

You should see something like

```
$ python hello.py
Hello World
```

Congratulations on writing your first program!

The print command does as it says and prints text to the screen. In hello.py, you wrote a line of code that executes the print command, specifying that you wanted to output "Hello World".

---

# Variables

Variables are pieces of code that store data. They're similar to variables used in math with the difference being that programming variables can store more than just numbers.

In programming, it's considered best practice to name your variables appropriately depending on their purpose.

In some languages, you have to declare that you are creating a variable.

For example in Javascript the keyword var is required.

```javascript
var variable1
```
To create a variable in python, you just have to name it and set it equal to something.

```python
variable1 = 1
```
### Basic Variable Types
As mentioned earlier, variables can store different kinds of data

|Data Type|Description|
|---|---|
|Integer|Integers are round numbers (positive or negative) with no decimal value|
|Float|Floats are numbers (positive or negative) with a decimal value|
|String|Strings are a set of numbers and/or characters arranged in a sequence|

Note: Keep in mind the difference between a string of numbers, and an actual number.
A string of numbers like '1234' is not the same as the number '1234'

Adding together integers

```
> a = 3
> b = 2
> a + b
5
```

Adding together Strings

```pyhon
> a = '800'
> b = '85'
> a + b
80085
```

When manipulating and combining multiple variables, keep in mind what data types each variable is currently storing.

```python
> var1 = 123
> var2 = abc
> var1 + var2
TypeError
```
In this example, the interpreter printed an error because you can't add an integer and a string together.

Try playing around with variables in the interpreter



---

# Input

Now that we've covered printing things to the screen, let's try getting some user input.
Create a new file called input.py in the editor.

In programming, a *function* is a piece of code that is given a name. This allows the programmer to use that piece of code to do things in multiple places of the program.

Some functions are built-in to the programming language itself so the programmer doesn't need to define it themselves. The `print` command was one such function. Functions are typically denoted by a pair of parentheses () after the name. The print command happens to be a special case.

We'll be using the `raw_input()` function to get user input from the terminal.

```python
name = raw_input("What is your name: ")
print("Hello " + name)
```

The `raw_input()` function does two things. First, it prints whatever is typed into the parentheses onto the console. Then, waits for the user to type something in and assigns it to the variable (`name`).

The `print()` function as we covered earlier prints whatever is in the parentheses to the console. In this case, we are adding together two strings together `"Hello " + name`, then printing that as one string.

Save this file and run it using `$ python hello.py`
When the program asks for your name, type it in and hit enter.
If all goes well you should see the program greet you.

This is just a very basic example of using a variable to store input and then outputting that information to the screen.

---

# Homework 😛
Task: Write a program `add.py` that takes in 2 inputs and outputs the sum.
Hint: `raw_input()` turns inputs into strings, to add the two inputs together, you'll first need to convert them both into integers.

---

## Next
We'll go over If and Else statements
[Lesson Three](https://github.com/MoF-Dev/learningpython/tree/master/Lessons/lesson3)
