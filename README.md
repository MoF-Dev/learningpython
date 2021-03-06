# How to read instructions
Sometimes I'll ask you to input to type a command in the terminal (command line / cmd) or in the python interpreter (more on this later).

To distinguish between the two, take a look below:

#### Terminal command:
```bash
$ cd desktop
```
The `$` indicates a terminal command.
#### Interpreter command:
`> a + b`
The `>` indicates an Interpreter command.

Sometimes I'll give an example input and output:
```bash
$ pwd
/Users/atan/Desktop/images/dogpictures
```
```python
> a = 1
> a + 2
3
```
The lines with the symbols `$` and `>` are the commands, lines without the symbols are the output.

If you see multiple lines, execute them one at a time.
```bash
$ mkdir dogphotos
$ cd dogphotos
```
When there is a comment and a filename at the top of the example code, I'm just indicating what file the code should be written in.
```python
#example.py
print "This is an example"
```


Finally, one last rule:
**DO NOT COPY AND PASTE**
Copy and pasting skips developing the muscle memory that lets you memorize code syntax. So don't do it.

---

# The Command Line
While not a hard requirement for learning how to code, knowing your way around the command line will be helpful later on.

### Commands to keep in mind
|Command Name|Usage|Example|
|---|---|----|
|`cd`|Changes directory| `$ cd ./dogpictures/`|
|`pwd`|Prints the current working directory|`$ pwd`|
|`ls`|Prints contents of the current working directory|`$ ls`|
|`rm`|Removes specified directory or file|`$ rm /dogpictures/sora.png`|
|`mkdir`|Creates a directory with specified name|`$ mkdir catpictures`|
|`mv`|Moves file or directory to specified location with specified name|`$ mv /dogpictures/nyan.png ../catpictures/nyan.png`|

[Further explanation and examples of each command](link) //todo

---
# Installing Python
There are 2 version of python: 2.7, and 3. The difference between the two aren't important for us now but we'll be using 2.7

[Download python 2.7](https://www.python.org/downloads/)

Once you've downloaded the installer, run it to install python (just keep clicking next)

---

## Next
First topic we'll cover is basic mathematical operations
[Lesson One](https://github.com/MoF-Dev/learningpython/tree/master/Lessons/lesson1)
