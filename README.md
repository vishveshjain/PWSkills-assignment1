# PWSkills-assignment 1
PWSkills assignment1 of Data Science Masters all answers

-------------------------
1. Who developed Python programming Language?<br/>
Ans: Python programming language was developed by Guido van Rossum. He started working on Python in December 1989, and the first version of the language was released in February 1991. Python was named after Monty Python, a British comedy group, because Guido van Rossum was a fan of the group. Over the years, Python has become one of the most popular programming languages and is widely used for a variety of purposes, including web development, scientific computing, data analysis, and more.

2. Which type of programming does python support? <br/>
Ans: 
    <h3>Python supports multiple programming paradigms, including:</h3>
    <ul>
    <li>Object-Oriented Programming (OOP): This allows the creation of objects and classes that can be used to model real-world entities.</li>

    <li>Imperative Programming: This involves using statements to specify a sequence of actions that the computer should perform.</li>

    <li>Functional Programming: This involves treating computation as the evaluation of mathematical functions, and is supported by Python's built-in functional programming features like map, filter, and reduce.</li>

    <li>Procedural Programming: This involves breaking down a problem into a series of procedures or functions to solve the problem step by step.</li>

    <li>These paradigms can be used in different combinations, making Python a versatile language that can be used for a wide range of applications. Python's focus on readability and simplicity also makes it a great language for beginners to learn.</li>
    </ul>

3. Is Python case sensitive when dealing with identifiers?<br/>
Ans: Yes, Python is case sensitive when dealing with identifiers, such as variable names, function names, and class names. This means that the names foo, Foo, and FOO would each refer to a different identifier in the same scope.
It's a common practice in Python to use lowercase names with words separated by underscores for variable, function, and class names. For example:
    <code>
    first_name = "John"
    print_message = "Hello, World!"

    class Employee:
        pass
    </code>

4. What is the correct extenstion of Python file?<br/>
Ans: The correct extenstion of Python file is .py

5. Is python code compiled or interpreted?<br/>
Ans:Python is an interpreted language, not a compiled language. The source code is translated into an intermediate form called bytecode, which is executed by the Python interpreter. This allows for faster development and easier debugging, but can lead to slower runtime performance compared to compiled languages.

6. Name a few blocks of code used to define in python language?<br/>
Ans: Indentation is used to define a block of code in python.

7. State a character used to give single-line comments in Python?<br/>
Ans: #

8. Mention functions which can help us to find the version of python that we are currently working on?<br/>
Ans: sys. version

9. Python supports the creation of anonymous functions at runtime, using a construct called -------- <br/>
Ans: lambda

10. What does pip stand for  python? <br/>
Ans: Pip Installs Packages.

11. Mention a few built-in functions in python? <br/>
Ans: The few built-in functions in python are:
    <ul>
      <li>input()</li>
      <li>print()</li>
      <li>len()</li>
      <li>list()</li>
      <li>range()</li>
    </ul>
   
12. What is the maximum possible length of an identifier in python? <br/>
Ans: 79 characters.

13. What are the benefits of using Python? <br/>
Ans:
    <h3>Python has many benefits including:</h3>
    <ol>
    <li>Easy to learn and use: Python has a simple and straightforward syntax which makes it easy for beginners to pick up.</li>

    <li>Versatile: Python can be used for a wide range of applications, including web development, scientific computing, data analysis, artificial intelligence, and more.</li>

    <li>Large community: Python has a large and active community, which means there is a wealth of resources available, such as libraries and frameworks.</li>

    <li>Good for prototyping: Python's short development cycle and ease of use make it a great language for quickly prototyping ideas.</li>

    <li>Interoperability: Python can easily be integrated with other languages and tools, allowing it to be used as a "glue" language for connecting components.</li>

    <li>Good for data Science and analysis: Python has a number of powerful libraries, such as NumPy, Pandas, sklearn, opencv and Matplotlib, that make it a great choice for data Science and analysis.</li>
    </ol>
    
14. How is memory managed in Python? <br/>
Ans: Python uses automatic memory management, which means the Python memory manager automatically handles memory allocation and deallocation. The memory manager uses a reference counting system to track the number of references to objects in memory, and frees the memory occupied by an object when its reference count reaches zero. Additionally, Python has a garbage collector that periodically frees up memory occupied by objects that are no longer being used. This ensures that Python programs are able to efficiently use memory without the need for manual memory management.

15. How to install Python on windows and set path variables?<br/>
Ans: 
    <h3>Here's how you can install Python on Windows and set the path variables:</h3>
    <ol>
    <li>Download the latest version of Python from the official website (https://www.python.org/downloads/).</li>

    <li>Run the installer and follow the instructions to install Python on your system.</li>

    <li>Open the "Environment Variables" dialog by typing "Environment Variables" into the Windows search bar and clicking on "Edit the system environment variables."</li>

    <li>Under "System Variables," scroll down and find the "Path" variable, then click "Edit."</li>

    <li>Click "New" and add the path to your Python installation. For example, if you installed Python in the default location, the path would be "C:\PythonXX," where "XX" is the version number.</li>

    <li>Click "OK" to close all the dialog boxes.</li>

    <li>Open a new command prompt and type "python" to confirm that the installation was successful and that the path variables are set correctly.</li>
    </ol>
    Note: It may need to restart any open command prompts for the changes to take effect.
    
16. Is indentation required in python? <br/>
Ans: Yes, indentation is required in Python. Indentation is used to indicate the block of code associated with control structures such as loops and conditional statements. The indentation level determines the scope of the code block, and a consistent indentation style makes the code easier to read and understand. In Python, the indentation level is defined by one or more spaces at the beginning of a line. The recommended indentation level is 4 spaces, but some developers prefer 2 spaces or use tabs instead of spaces. It's important to be consistent within a single project, and most code editors can automatically handle indentation for you.
