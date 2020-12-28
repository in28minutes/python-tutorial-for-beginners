# Python Programming For Beginners

Welcome to this book on **"Learning Python In 100 Steps"**. 

I am **Ranga Karanam**, and I have more than two decades of programming experience. 

At **In28Minutes**, we ask ourselves one question every day: "how do we create awesome learning experiences?" 

Whether we talk about big data, data analytics, or about doing simple things like scraping content from the web, Python is an awesome language for all that. Learning Python can be an awesome experience. 

In this book, you will learn to write **structural** and **object** **oriented** code with Python. You'll learn a lot of important Python concepts, including **types**, **modules**, **collections** (or **data** **structures**), **exceptions**, and a wide variety of other stuff. You will be exposed to a lot of examples, exercises and tips. We will take up a lot of examples, and try and see how to write code for those in Python. 

We would be using **Python 3**, with **PyCharm** as the IDE. 

## Table of Contents
* [Chapter 01 - Getting Ready with Python](#chapter-01---getting-ready-with-python)
* [Chapter 02 - Introduction To Python Programming](#chapter-02---introduction-to-python-programming)
* [Chapter 03 - Introducing Methods](#chapter-03---introducing-methods)
* [Chapter 04 - Introduction To Python Platform](#chapter-04---introduction-to-python-platform)
* [Chapter 05 - Introduction To PyCharm](#chapter-05---introduction-to-pycharm)
* [Chapter 06 - Introducing Data Types and Conditionals](#chapter-06---introducing-data-types-and-conditionals)
* [Chapter 07 - Introducing Loops](#chapter-07---introducing-loops)
* [Chapter 08 - Python Tips](#chapter-08---python-tips)
* [Chapter 09 - Introducing Object Oriented Programming](#chapter-09---introducing-object-oriented-programming)
* [Chapter 10 : Python Data Structures](#chapter-10---python-data-structures)
* [Chapter 11 - Object Oriented Programming Revisited](#chapter-11---object-oriented-programming-revisited)
* [Chapter 12 - Error Handling](#chapter-12---error-handling)
* [Chapter 13 - More Python Tips](#chapter-13---more-python-tips)



## Chapter 01 - Getting Ready with Python

### Installing Python 3, And Launching Python Shell

This video should help you get up and running with Python 3
- [Installing Python 3 and Launch Python Shell](https://www.youtube.com/watch?v=Ji1WW4Suaww)

Installing Python is really a cakewalk. Search for "Python download" on www.google.com. Download the installable and install it.

A quick word of caution on Windows
- Make sure that you have the check-box "Add Python 3.6 to PATH", checked. 

Once you have installed Python, you can launch the Python Shell. 
- Windows - Launch cmd prompt by typing in 'cmd' command. 
- Mac or Linux - Launch up terminal. 

Command to launch Python 3 is different in Mac.
- In Mac, type in `python3`
- In other operating systems, including windows, type `python`

You can type code in python shell and code as well! 

You can use ```print(5*4)```, and it shows ```20```. 

You can execute the code, and the shell would immediately give you output.

Using the the Python Shell is an awesome way to learn Python. 

## Chapter 02 - Introduction To Python Programming

Most programmers find programming a lot of fun, and besides, it also gets their work done. 

Programming mainly involves *problem solving*, where one makes use of a computer to solve a real world problem. 

During our journey here, we will approach programming in a very different way. We will not only introduce you to the Python language, but also help you pick up essential problem solving skills. 

As a programmer, you need to be able to look at a problem, and identify the important programming concepts relevant to solving it. Finally, you need to be able to use the language features and syntax, to express your solution on the computer. While all this looks complex, we want to make it easy for you. Together, we will tackle a variety of programming challenges, using these same steps. We will start with simple challenges (such as a Multiplication Table), and gradually increase the difficulty level over the duration of this book. 

Learning to program is a lot like learning to ride a bicycle. The first few steps are the most challenging ones. 

Once you get over these initial steps, your experience will become more and more enjoyable. 

Are you ready for your first programming challenge? Let's get going now! We wish you all the best.

#### Summary

In this step, we:

* Were introduced to the concept of problem solving
* Understood how good programmers approach problem solving 

### Step 01: Our First Programming Challenge

Our first *programming challenge* aims to do, what every kid does in math class: read out a multiplication table. We now want to give this task to the computer. Here is the  statement of our problem:

#### The **Print Multiplication Table Challenge (PMT-Challenge)**

1. Compute the multiplication table for ```5```, with entries from ```1``` to ```10```.
2. Display this table.

The display needs to be:

**_5 * 1  =  5_**

**_5 * 2  = 10_**

**_5 * 3  = 15_**

**_5 * 4  = 20_**

**_5 * 5  = 25_**

**_5 * 6  = 30_**

**_5 * 7  = 35_**

**_5 * 8  = 40_**

**_5 * 9  = 45_**

**_5 * 10 = 50_**

This is the challenge. For convenience, let's give it a label, say *PMT-Challenge*. What would be the important concepts we need to learn, to solve this challenge? The following list of concepts would be a good starting point:

* **Statements**
* **Expressions**
* **Variables**
* **Literals**
* **Conditionals**
* **Loops**
* **Methods**  

In the rest of this chapter, we will introduce these concepts to you, one-by-one. We will also show you how learning each concept, takes us closer to a solution to *PMT-Challenge*.

#### Summary

In this step, we:

* Stated our first programming challenge
* Identified what programming concepts we need to learn, to solve this challenge

### Step 02: Breaking Down *PMT-Challenge*

Typically when we do programming, we have problems. Solving the problem typically need a step-by -step approach. Common sense tells us that to solve a complex problem, we break it into smaller parts, and solve each part one by one. Here is how any good programmer worth her salt, would solve a problem:

* Simplify the problem,  by breaking it into sub-problems
* Solve the sub-problems in stages (in some order), using the language
* Combine these solutions to get a final solution 

The *PMT-Challenge* is no different! Now how do we break it down, and where do we really start? Once again, your common sense will reveal a solution. As a first step, we could get the computer to calculate say, ```5 * 3```. The second thing we can do, is to try and print the calculated value, in a manner similar to ```5 * 3 = 15```. Then, we could repeat what we just did, to print out all the entries of the ```5``` multiplication table. Let's put it down a little more formally:

Here is how our draft steps look like
* Calculate ```5 * 3``` and print result as ```15```
* Print ```5 * 3 = 15``` (```15``` is result of previous calculation)
* Do this ten times, once for each table entry (going from ```1``` to ```10```)

Let's start with that kind of a game plan, and see where it takes us.

#### Summary

In this step, we:

* Learned that breaking down a problem into sub-problems is a great help
* Found a way to break down the *PMT-Challenge* problem

### Step 03: Introducing Operators And Expressions 

Let's focus on solving the first sub-problem of *PMT-Challenge*, the numeric computation. We want the computer to calculate  ```5 * 5``` for example, and print ```25``` for us. How do we get it to do that? That's what we would be looking at in this step.

#### Snippet-01: Introducing Operators

Launch up Python shell. We want to calculate ```5 * 5```. How do we do that? 

Using our knowledge of school math, let's try ```5 X 5```. 

```py
	>>> 5 X 5
	File "< stdin >", line 1
	5 X 5
	  ^
	SyntaxError: invalid syntax
```

The Python Shell hits back at us, saying "*invalid syntax*". This is how Python complains, when it doesn't fully understand the code you type in. Here, it says our code has a "**SyntaxError**". 

The reason why it complains, is because '```X```' is not a valid **operator** in Python. 

The way you can do multiplication is by using the '```*```' *operator* .  

"*5 into 5*" is achieved by the code ```5 * 5```, and you can see the result ```25``` being printed. Similarly, ```5 * 6``` gives us ```30```.

```py
	>>> 5 * 6
	30
```


There are a wide range of other operators in Python: 
	
* ```5 + 6``` gives a result of ```11```. 
* ```5 - 6``` leads to ```-1```.  

```py
	>>> 5 + 6
	11
	>>> 5 - 6
	-1

```

```10 / 2```, gives an output of  ```5.0``` . There is one interesting operator, ```**```. Let's try ```10 ** 3```. We ran this code, and the result we get is ```1000```. Yes you guessed right, the operator performs "to the power of". "```10``` to the power of ```3```" is ```10 * 10 * 10```, or ```1000```. 

```py
	>>> 10 / 2
	5.0
	>>> 10 ** 3
	1000

```


Another interesting operator is ```%```,  called "*modulo*", which computes the remainder on integer division. If we do ```10 % 3```, what is the remainder when ```10``` is divided by ```3```? ```3 * 3``` is ```9```, and ```10 - 9``` is ```1```, which is what ```%``` returns in this case.


Let's look at some terminology:

- Whatever pieces of code we gave Python shell to run, are called **expressions**. So, ```5 * 5```, ```5 * 6``` and ```5 - 6``` are all *expressions*. An expression is composed of *operators* and **operands**. 
- In the expression ```5 * 6```, the two values ```5``` and ```6``` are called operands, and the ```*``` operator *operates* on them. 
- The values ```5``` and ```6``` are **literals**, because those are constants which cannot be changed. 


The cool thing about Python, is that you can even have expressions with multiple operators. Therefore, you can form an expression with ```5 + 5 + 5```, which evaluates to ```15```. This is an expression which has three operands, and two ```+``` operators. You can even have expressions with different types of operators, such as in ```5 + 5 * 5```. 

```py
	>>> 5 + 5 + 5
	15
	>>> 5 + 5 * 5
	30

```


Try and play around with the expressions, and understand the output which results. 

#### Summary

In this step, we:

* Learned how to give code input to the Python Shell
* Understood that Python has a predefined set of operators
* Used a few types of basic operators and their operands, to form expressions

### Step 04: Programming Exercise IN-PE-01

At this stage, your smile tells us that you enjoy evaluating Python expressions. What if we tickle your mind a bit, to make sure it hasn't fallen asleep? Here is your first programming exercise.

#### Exercises

1. Write an expression to calculate the number of minutes in a day.
2. Write an expression to calculate the number of seconds in a day.

##### Note

You need to solve these problems by yourself. If you are able to work them out, that's fantastic! But if not, that's part of the learning process.

#### Solutions

#### Solution 1

```py
	>>> 24 * 60

	1440


```

We wanted to calculate the number of minutes in a day. How do we do that? Think about this... 

* How many number of hours are there in a day? ```24```. 
* And how many minutes does each hour have? It's ```60```. 
* So if you want to find out the number of minutes in a day, it's ```24 * 60```, which is ```1440```. 

#### Solution 2

```py
	>>> 24 * 60 * 60

	86400


```

How many seconds are there in a day? 

* Let's start with the number of hours, ```24```. 
* The number of minutes in an hour is ```60```, and 
* The number of seconds in a minute is ```60``` as well. 
* So it's ```24 * 60 * 60```, or ```86400```.

#### Summary

In this step, we:

* Solved a Programming Exercise involving common scenarios, using Python code involving:
	* Expressions
	* Operators
	* Literals 

### Step 05: Puzzles On Expressions

Let's look at a few puzzles related to expressions, in this step. Before that, let's revise some of the terminology we had learned earlier.

```5 + 6 + 10``` is an example of an expression. In this expression, ```5```, ```6``` and ```10``` are operands. The ```+``` here is the operator. You can have multiple operators in an expression. We also did mention that the operands, namely ```10```, ```6``` and ```5```, are literals. Their values will not change.

Here are a few puzzles coming up, to explore aspects of expressions.

#### Snippet-01: Puzzles On Expressions

Think about what would happen when you do something of this kind: ```5 $ 2```. You're right, it would throw a ```SyntaxError```. When Python does not understand the code you type in, it reports an error. Here, the expression we're typing is ```5 $ 2```, which does not make sense to Python, hence the ```SyntaxError```.

```py
	>>> 5 $ 2
	File "< stdin >", line 1
	5 $ 2
	^
	SyntaxError: invalid syntax
	>>> 5$2
	File "< stdin >", line 1
	5 $ 2
	^
	SyntaxError: invalid syntax

```



Let's say we type in ```5+6+10```, without any spaces between the operands, and the operators. What do you think will happen? Surprisingly, the Python Shell does calculate the value!

```py
	>>> 5+6+10
	21

```

 In an expression, using spaces makes it easier for you to read it, but it's not mandatory. ```5 + 6 + 10``` is easier to read than ```5+6+10```,  but does not make any difference to the Python compiler.

The next puzzle tries to evaluate ```5 / 2```, which is "```5``` divided by ```2```". What would be the output? ```2.5```. 

```py
	>>> 5/2
	2.5

```

If you're coming from other programming languages like Java or C, this might be a surprising result. If you try this in Java for instance, you would get ```2``` as the output. Note that even though both operands are integers, the result of the ```/``` operation is a floating point value, ```2.5``` . Python does what is expected by a programmer!



The puzzle after that tries to play with ```5 + 5 * 6```. What would be the result of this expression? Will it be ```5 + 5``` or ```10```, then ```10 * 6```, which is ```60```? Or, will it be ```5``` plus ```5 * 6```, which is ```5``` + ```30```, that's ```35```? 

```py
	>>> 5 + 5 * 6
	35
```

The correct result is ```35```. 

Python decides this is based on the **precedence** of operators. 

Operators in Python are divided into two sets as follows:
*   ```**```, ```*```,  ```/``` and ```%``` have higher precedence, or priority.
*   ```+``` and ```-``` have a lower precedence. 

Sub-expressions involving operators from {```*```, ```/```, ```%```, ```**```} are evaluated before those involving operators from {```+```, ```-```}

Let's try another small puzzle on precedence, with ```5 - 2 * 2```. What would be the result of this? Will it be ```6```, or ```1```? It's ```1```, because ```*``` has a higher precedence than ```-```. Thus ```2 * 2``` is ```4```, and ```5 - 4``` gives us ```1```. 

```py
	>>> 5 - 2 * 2
	1

```

Let's say we want to execute ```5 - 2```, to give an output of ```2```. How do we change the operator precedence?

You cannot really change the precedence, but you can add parentheses to group sub-expressions differently. 

```py
	>>> (5 - 2) * 2
	6
	>>> 5 - ( 2 * 2 )
	1

```

 Parentheses have the highest precedence in Python, and can be used to override operator precedence.  ```(5 - 2)``` gets calculated first, and the final result of the expression is ```6```. 

A positive thing about using parentheses is, that it makes expressions more readable. So even in situations such as ```5 - 2 * 2```, where we know the result according to precedence, adding parentheses is good. 

#### Summary

In this step, we went about solving a few puzzles about expressions, touching concepts such as:
* ```SyntaxError``` for incorrect operators
* White-space in expressions
* Floating Point division by default
* Operator Precedence
* Using parentheses

### Step 06: Printing Text

In the previous step, we learned how to use expressions to compute values. In this step, let's see how we can actually print multiplication table entries, that are readable by the user.

#### Snippet-01: Printing Text

How do we go about printing a complete multiplication table entry? We want to print text such as  ```5 * 6 = 30``` . But trying to do so, as we know it, gives us a ```SyntaxError```. Clearly, there is a different way to print text, as compared to an expression.

```py
	>>> 5 * 6 = 30
	  File "<stdin>", line 1
	SyntaxError: can't assign to operator

```

Let's first try to print a simple piece of text, ```Hello```. Typing in this piece of code directly on Python Shell also gives us an error. 

```py
	>>> Hello
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'Hello' is not defined

```

Only expressions work that way, and ```Hello``` is not really an expression. 

```"Hello"``` is typically called a **string**, and represents the text of letters ```'H'```, ```'e'```, ```'l'```, ```'l'```, ```'o'```. ```"Hello"``` is hence different from the number ```5```. 

There are a number of in-built functions in Python to help print strings. One of these is the ```print()``` function. Can you just say ```print Hello```? 

```py
	>>> print Hello
	  File "<stdin>", line 1
	    print Hello
	              ^
	SyntaxError: Missing parentheses in call to 'print'. Did you mean print(Hello)?
```

The Python compiler gives you an error, that says "missing parentheses". 

Will ```print(Hello)``` work? 

```py
	>>> print (Hello)
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'Hello' is not defined

```

Nope! Again, this one failed because you need to indicate that ```"Hello"``` is a string. 

How do I indicate that ```"Hello"``` is a string? By putting it within double quotes.

Let's try `print ("Hello")`

```py
	>>> print ("Hello")
	Hello
	>>> print("Hello")
	Hello

```

```print("Hello")``` finally results in ```"Hello"``` being printed out. To be able to print ```"Hello"```, the things we need to do are:
		
*  Typing the method name print , 
*  open parentheses ( , 
*  Followed by a double quote " , 
*  The text Hello, 
*  and another double quote " , 
*  finished off with a closed parentheses ). 

What we have written here is called a **statement**, a simple piece of code to execute. As part of this statement, we are **calling** a **function**, named ```print()```. 

What exactly are we trying to print? 

The text ```"Hello"```, which is called a **parameter** or **argument**,  to ```print()```.

Now let's get back to what we wanted to do, which is to print ```5 * 6 = 30```. The most basic version would be something of this kind, ```print("5 * 6 = 30")```. Here, we are passing the entire value in the form of a string. 

```py
	>>> print("5 * 6 = 30")
	5 * 6 = 30

```

This prints the text on the console, as-is. The thing you need to understand here is, we aren't really calculating ```30``` using the formula ```5 * 6```, but directly putting text ```30``` in here. That's called **hard-coding**. 

In a later step, we will look at how to actually calculate the value and pass it in.

#### Summary

In this step, we:

* Understood that displaying text on the console is not the same as printing an expression value
* Learned about the ```print()``` function, that is used to print text in Python.
* Found a way to print the text ```"5 * 6 = 30"``` on the console, by hard-coding values in a string

### Step 07: Puzzles On Utility Methods, And Strings

In the previous step, we learned how to print ```5 * 6 = 30```. It was not a perfect solution, because we hard-coded everything.  we used an in-built function named ```print()```, passed a string to it, and invoked the method. 

In this step, let's look at a number of puzzles related to in-built methods, their parameters, and strings in general.

For example, let's do ```print("5 * 6")```, as in the previous step. What does this code result in?
```py
	>>> print("5*6")
	5*6
	>>> print('5*6')
	5*6

```

It just prints the string ```"5 * 6"```. 

Let's say we try the code ```print(5 * 6)```, 

```py
	>>> print(5*6)
	30

```

Without the double quotes, ```5 * 6``` is an expression. What will be the output? ```30```. 

If you call ```print()``` with an expression argument, it prints the value of the expression. However, when we pass something within double quotes, it becomes a piece of text, printed as-is. 

An interesting thing to note is, that in Python you can use either double-quotes (```"``` and ```"```), or single-quotes (```'``` and ```'```) with text values. 

Let's look at a few other in-built methods within Python.

Consider ```abs()``` (which stands for absolute value), a method that accepts a numeric value. You can use ```abs(10.5)```, passing ```10.5``` as a value to it, and it prints the absolute value of ```10```.
```py
	>>> abs 10.5
	  File "<stdin>", line 1
	    abs 10.5
	           ^
	SyntaxError: invalid syntax
	>>> abs(10.5)
	10.5
```

If you pass in a string value, will it work? It complains, "```abs()``` function will not work with a string, it only works with numeric values". 

```py
	>>> abs("10.5")
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: bad operand type for abs(): 'str'

``` 

Let's say you want to use a function that computes "to the power of", for instance "```2``` to the power of ```5```". In Python, there's an in-built function named ```pow()```, which does just what we need. To ```pow()```, you can pass two parameters and calculate the result. How do you do that?  


Will this work: ```pow 2 5```? No, not at all. This code does not work as well: ```pow(2 5)```. ```pow(2, 5)``` is the correct syntax.  
```py
	>>> pow 2 5
	  File "<stdin>", line 1
	    pow 2 5
	        ^
	SyntaxError: invalid syntax
	>>> pow(2 5)
	  File "<stdin>", line 1
	    pow(2 5)
	          ^
	SyntaxError: invalid syntax
	>>> pow(2, 5)
	32
```

	
You'll see that ```32``` is printed. 

Let's see another example, "```10``` to the power of ```3```". ```pow(10,3)``` is the alternative to saying ```10 ** 3```. This gives us ```1000```, similar to how ```pow()``` would.

```py
	>>> pow(10, 3)
	1000
	>>> 10 ** 3
	1000

```

```max()``` returns maximum in a set of numbers.```min()``` function returns the minimum value.
```py
	>>> max(34, 45, 67)
	67
	>>> min(34, 45, 67)
	34

```




These are some of the in-built functions in Python, and we saw how to call the in-built functions by passing in a varied number of parameters. 

Python is case sensitive. So let's say I want of calculate  ```pow(2,5)```. So this would give me ```32```. Now, what if I say capital ```'P'``` instead of small ```'p'``` here? ```Pow(2,5)``` would lead to an error. 

```py
	>>> pow(2,5)
	32
	>>> Pow(2,5)
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'Pow' is not defined

```
The only things not case-sensitive in Python, are string values. Earlier we saw that the code ```print("Hello")``` displays the text ```"Hello"```. Inside a string, the text can be in any case. Hence, ```print("hello")``` displays ```"hello"``` ,with a small ```'h'```.

```py
	>>> print("Hello")
	Hello
	>>> print("hello")
	hello
	>>> print("hellO")
	hellO
	>>> print ( "hellO" ) 
	hellO

```

However inside your code, you need to be very particular about the case of function names, class names, variable names, and the like. 

In your code, whitespace does not really matter. You can add space here and here, and you would still get the same output. However, in case of strings, whitespace does matter.

If we say ```print("hellO World")```, it would print ```"hellO World"```, with a space in between. And if you do ```print("hellO   World")``` with three spaces, it would print the same. In expressions, white-space does not affect the output.

```py
	>>> print ( "hellO World" ) 
	hellO World
	>>> print ( "hellO     World" ) 
	hellO     World

```


The last thing we want to look at, is an **escape sequence**. Let's say you want to print a double quote, ```"```, in the code.  If we were to do this: ```print("Hello"")```, what would happen? The compiler says error! 


```py
	>>> print("Hello"")
	  File "<stdin>", line 1
	    print("Hello"")
	                  ^
	SyntaxError: EOL while scanning string literal

```

If you want to print a ```"``` inside a string, use an escape sequence. In Python, the symbol ```'\'``` is used as an **escape character**. On using ```'\'``` adjacent to the ```"```, it prints  ```Hello"``` (notice the trailing ```"```). We have used the ```'\'``` to **escape** the ```"```, by forming an *escape sequence* ```\"```.

```py
>>> print("Hello\"")
Hello"
>>>

```

The other reason why you would want to use a ```'\'``` is to print a ```<NEWLINE>```. If you want to print ```"Hello World"```, but with ```"Hello"``` on one line and ```"World"``` on the next, ```'\n'``` is the escape sequence to use.
```py
	>>> print("Hello\nWorld")
	Hello
	World
```

The other important escape sequence is ```'\t'```, which prints a ```<TAB>``` in the output. When you do ```print("Hello\tWorld")```, you can see the tab-space between ```"Hello"``` and ```"World"```.

```py
	>>> print("Hello\tWorld")
	Hello	World

```

Another useful escape sequence is ```\\``` . If you want to print a ```\``` , then use the sequence ```\\``` . You would see that it prints ```Hello\World``` . Think about what would happen if we put six ```\``` . Yes you're right! It would print this string: ```"\\\"``` . 

```py
	>>> print("Hello\\World")
	Hello\World
	>>> print("Hello\\\\\\World")
	Hello\\\World

```
 
One of the things with Python is, it does not matter whether you use double quotes or single quotes to enclose strings. There are some interesting, and useful ways of using a combination of both, within the same string. Have a look at this call: ```print("Hello'World")```, and notice the output we get. In a similar way, the following code will be accepted and run by the Python system: ```print('Hello"World')```. 


```py
	>>> print('Hello"')
	Hello"
	>>> print("Hello'World")
	Hello'World
	>>> print("Hello\"World")
	Hello"World
	>>> print("Hello\"World")
	Hello"World

```

The above two examples can be used as a tip by newbie programmers when they form string literals, and want to use them in their code:	
* If the string literal contains one or more single quotes, then you can use double quotes to enclose it.
* However if the string contains one or more double quotes, then prefer to use single quotes to enclose it. 

#### Summary

In this step, we:

* Explored a number of puzzles related to code involving:
	* Built-in functions for numeric calculations
	* The ```print()``` function to display expressions and strings
* Covered the following aspects of the above utilities:
	* Case-sensitive aspects of names and strings
	* The role played by whitespace
	* The escape character, and common escape sequences

### Step 08: Formatted Output With print() 

In the previous step, we learned how to print a hard-coded string, such as ```"5 * 6 = 30"```. 

In this step, let's try to replace the hard-coded ```30``` with a computed value. 

Let's start with a simple scenario. Let's say we want to place that calculated value within a string, and display it. How do we do that? 



#### Snippet-01: print() Formatted Output

`format()` method can be used to print formatted text.

Let's see an example:

```py
	>>> print("VALUE".format(5*2))
	VALUE

```
We were expecting ```10``` to be printed, but it's actually printing ```VALUE```. 

How do we get ```10``` to be printed then? 

```py
	>>> print("VALUE {0}".format(5*2))
	VALUE 10

```

By having an open brace ```{```,  closed brace ```}```, and and by putting the index of the value between them. Here, the value is the first parameter, and it's index will be ```0```. 

```"VALUE {0}"``` is what we need. 


Let's take another example. Suppose to the ```format()``` function, we pass three values: ```10```, ```20``` and ```30```. 

Typically when we count positions or indexes, we start from ```0```. 

To print the first value, you need to pass in an index of ```0```. To print the second value, pass an index of ```1```.

```py
	>>> print("VALUE {0}".format(10,20,30))
	VALUE 10
	>>> print("VALUE {1}".format(10,20,30))
	VALUE 20
	>>> print("VALUE {2}".format(10,20,30))
	VALUE 30

```

Now going back to our problem, we wanted to display  ```"5 * 6 = 30"```, but without hard-coding. Instead of ```30```, we want the calculated value of ```5 * 6```.

```py
	>>> print("5 * 6 = 30".format(5,6,5*6))
	5 * 6 = 30
```

Let replace `"5 * 6 = 30"` with `"5 * 6 = {2}"`. `2` is the index of parameter value `5*6`. 

```py
	>>> print("5 * 6 = {2}".format(5,6,5*6))
	5 * 6 = 30

```

Cool! Progress made.

Let's replace `5 * 6` with the right indices - `{0} * {1}`. 
```py
	>>> print("{0} * {1} = {2}".format(5,6,5*6))
	5 * 6 = 30

```

The great thing about this, is now we can replace the values we passed to ```print()``` in the first place, without changing the indexes! So, we can display results for   ```5 * 7 = 35``` and ```5 * 8 = 40```. We are now able to print ```5 * 6 = 30```, ```5 * 7 = 35```, ```5 * 8 = 40```, and can do similar things for other table entries as well.

```py
	>>> print("{0} * {1} = {2}".format(5,7,5*7))
	5 * 7 = 35
	>>> print("{0} * {1} = {2}".format(5,8,5*8))
	5 * 8 = 40
	>>> print("{0} * {1} = {2}".format(5,8,5*8))
	5 * 8 = 40

```

#### Summary

In this step, we:

* Discovered that Python provides a way to do formatted printing of string values
* Looked at the ```format()``` function, and saw how to call it within ```print()```
* Observed how we could work only with the indexes of parameters to ```format()```, and change the parameters we pass without changing the code

### Step 09: Puzzles On format() and print()

In this step, let's look at a few puzzles related to the format, and the print methods.

#### Snippet-01: format() And print() Puzzles

Let's say we pass in additional values, such as: ```5 * 8```, ```5 * 9``` and ```5 * 10```. However, within the call to ```format()```, we are only referring to the values at index ```0```, index ```1``` and index ```2```. The values at indexes ```3``` and ```4``` are not used at all. What would happen when we run the code?

```py
	>>> print("{0} * {1} = {2}".format(5,8,5*8,5*9,5*10))
	5 * 8 = 40

```

Would this throw an error? No, it does not. You can see that the additional values which are passed in, are conveniently ignored. 

Let's say instead of passing in a value of ```2```, we pass ```4```. What would happen? 

```py
	>>> print("{0} * {1} = {4}".format(5,8,5*8,5*9,5*10))
	5 * 8 = 50

```

```5 * 10``` is the value at index ```4```


Now let's take a different scenario. We remove all the parameters passed to ```format()```. However, inside the call to ```print()```,  we continue to say ```{0} * {1} = {4}```. So we are trying to print the value at index ```4```, but are only passing two values to the function ```format()```. What do you think will happen?
```py
	>>> print("{0} * {1} = {4}".format(5,8))
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	IndexError: tuple index out of range

```

It says ```IndexError```, which means :"you are asking me to fetch the value at index ```4```, but only passing in two values. How can I do what you want?" 

Let's look at a few more things related to other data types. We try to format the following inside ```print()```: ```{0} * {1} = {2}```,  and would pass in ```2.5```, ```2```, and  ```2.5 * 2``` . Here, ```2``` is an integer value, but ```2.5``` is a floating point value. You can see that it prints ```2.5 * 2 = 5.0```.  So this approach of formatting values with ```print()```, works also with floating point data as well. 


```py
	>>> print("{0} * {1} = {2}".format(2.5,2,2.5*2))
	2.5 * 2 = 5.0

```

Now, are there are other types of data that ```format()``` works with? Yes, strings can join the party. 

Let's say over here, we do: ```print("My name is {0}".format("Ranga"))```. What would happen? 

```py
	>>> print("My name is {0}".format("Ranga"))
	My name is Ranga

```

Index ```0``` will be replaced with the first parameter to ```format()```.

#### Summary

In this step, we:

* Understood the behavior when the parameters passed to ```format()```:
	* Exceed the indexes accessed by ```print()```
	* Are less than the indexes accessed by ```print()```
	* Are of type integer, floating-point or string
  
### Step 10: Introducing Variables 

We are slowly making progress toward our main goal, which is to print the ```5``` multiplication table. 

In the first statement, we are printing ```5 * 1 = 5```, and then changing the literals. To make it print ```5 * 2 = 10```, we are changing ```1``` to ```2```. Next, we are changing ```2``` to ```3```. How do we make it a little simpler, so that our effort is reduced? 

```py
	>>> print("{0} * {1} = {2}".format(5,1,5*1))
	5 * 1 = 5
	>>> print("{0} * {1} = {2}".format(5,2,5*2))
	5 * 2 = 10
	>>> print("{0} * {1} = {2}".format(5,3,5*3))
	5 * 3 = 15

```

Let's try a different approach. 

What would happen if you replace ```1``` with ```index```, and ```5 * 1``` with ```5 * index```, and try to run it?  


It gives an error! It says: "index is not defined". 

Let's try and fix this, and execute ```index = 2```. What would happen? 

```py
	>>> index = 2

```

Aha! This compiles. 

```py
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 2 = 10
```

And this statement is printing ```5 * 2 = 10```. 

Let's try something else. Let's make ```index = 3```. What would happen? 

```py
	>>> index = 3
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 3 = 15

```

The same statement on being run, prints ```5 * 3 = 15```. 

How can you check the value that ```index``` has? Just type in ```index```. 

```py
	>>> index
	3
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 3 = 15
```


The ```index``` symbol we have used here, is what is called a **variable**. 

In Python, it's also called a **name**. 

You can see that the value ```index``` referring to, can change over the duration of a program. 

Initially, ```index``` was referring to a value of ```1```. later, ```index``` was referring to a value of ```3```. 
 

Now, think about how you would print the entire table. All that you need to do, is start from ```1```, execute the same statement with ```print()``` and ```format()```, to get output ```5 * 1 = 5```. Next, Change the value of index to ```2```, and then print the same statement. Next, ```index = 3```, and print the same statement again.

```py
	>>> index = 1
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 1 = 5
	>>> index = 2
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 2 = 10
	>>> index = 3
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 3 = 15

```

With the same statement `print("{0} * {1} = {2}".format(5,index,5*index))`, we are able to print different values. The value of ```index``` varies, but the code remains the same! 

Variables make the program much more easier to read, as well as more generic.

#### Snippet-02: Classroom Exercise On Variables

Let's do a simple exercise with variables. 

We want to create three variables ```a```, ```b``` and ```c```. Let's initially give them some values, say a value of ```5``` to ```a```, ```6``` to ```b``` and ```7``` to ```c```. 

We want to get output of this kind: ```5 + 6 + 7 = 18```, without using the literal values. 

You would want to use the values stored in the variables in ```a```, ```b``` and ```c```.

If you're hard-coding, the way to do it is with ```print("5 + 6 + 7 = 18")```.

```py
	>>> a = 5
	>>> b = 6
	>>> c = 7
	>>> print("5 + 6 + 7 = 18")
	5 + 6 + 7 = 18
	>>> print("5 + 6 + 7 = 18".format(a,b,c,a+b+c))
	5 + 6 + 7 = 18
```

The way you can do that is with code like this: ```print("{0} + {1} + {2} = {3}".format(a,b,c,a+b+c))```.
```py
	>>> print("{0} + {1} + {2} = {3}".format(a,b,c,a+b+c))
	5 + 6 + 7 = 18
```

How do you confirm we are accessing values stored in the variables? 

Let's change the values of ```a```, ```b``` and ```c```. Let's make ```a = 6``` , ```b = 7``` , and ```c = 8``` . Execute same statement.

```py
	>>> a = 6
	>>> b = 7
	>>> c = 8
	>>> print("{0} + {1} + {2} = {3}".format(a,b,c,a+b+c))
	6 + 7 + 8 = 21


```
You can see the magic of variables at play here! Based on what values these variables are referring to, you can see that the output of the print statement changes.

#### Summary

In this step, we:
* Were introduced to variables, or names, in Python
* Observed how we could pass in values of variables to the ```format()``` function

### Step 11: Puzzles On Variables

In the previous step, we were introduced to the concept of variables in Python.

We will start with looking at a few puzzles.

#### Snippet-01: Puzzles On Variables

What if I try to refer to a variable which is not yet created?

```py
	>>> count
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'count' is not defined
	>>> print(count)
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'count' is not defined
```

Before using a variable, you need to have it assigned a value. If you have not defined a variable before, then you cannot use it. Consider  ```print(count)```, it does not know what count is. So it would throw an error, saying: "```count``` is not defined, I have no idea what count is." 

Once you assign a value to a variable, you can use it.

```py
	>>> count = 4
	>>> print(count)
	4

```
The statement ```count = 4``` where we are creating a variable named ```count``` for the first time, is called a **variable definition**. 

This is the first time you're referring to a variable, and assigning a value to it. 

Python will create a variable in its memory.

Variable names are case sensitive. `count` and `Count` are not the same thing.

```py
	>>> Count
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'Count' is not defined
	>>> count
	4
```

There are rules to follow while naming variables. 

All variable names should either start with an alphabet , or an underscore ```_``` . 
`count`, `_count` are valid. `1count` is invalid.

```py
	>>> 1count = 5
	  File "<stdin>", line 1
	    1count = 5
	         ^
	SyntaxError: invalid syntax
	>>> count = 5
	>>> _count = 5
	>>> 1count
	  File "<stdin>", line 1
	    1count
	         ^
	SyntaxError: invalid syntax
	>>> 2count
	  File "<stdin>", line 1
	    2count
	         ^
	SyntaxError: invalid syntax

```

After the first symbol, you can also use a numeral in variable names.

```py
	>>> c12345 = 5

```

To summarize the rules for naming variables. 

* This should start with an alphabet (a capital or a small alphabet) or underscore. 
* Starting the second character, it can be alphabet, or underscore, or a numeric value. 


#### Summary

In this step, we:

* Understood that a variable needs to be defined before it is used
* Learned that there are certain rules to be followed while giving names to variables

### Step 12: Introducing Assignment

In this step, we will look at an important concept in Python, called **assignment**. In previous steps, we created variables, like ```i = 5```.

#### Snippet-01: Introducing Assignment 

You can create other variables using whatever value ```i``` is referring to. If we say ```j = i```, what would happen?

```py
	>>> i = 5
	>>> j = i
	>>> j
	5

```
```j``` would start referring to the same value that ```i``` is referring to. This statement is called an **assignment**. 

Let's try ```j = 2 * i```.

```py
	>>> j = 2 * i
	>>> j
	10

```

`j` refers to a value of `10`


```=``` has a different meaning in programming compared to mathematics. 

In mathematics, When we execute  ```j = i```, it means ```j``` and ```i``` are equal. 

In prgramming, the value of the expression on right hand side is assigned to the variable on the right hand side.
Can you use a constant on the left hand side of an assignment? The answer is "No"!

```py
	>>> 5 = j
	  File "<stdin>", line 1
	SyntaxError: can't assign to literal

```

The Python Shell throws an error, saying "Can't assign to literal", as ```5``` is a literal. 

Let's create a couple of variables. ```num1 = 5``` and ```num2 = 3```. We would want to add these and create a fresh variable. Let's say the name of the variable is ```sum```.

```py
	>>> num1 = 5
	>>> num2 = 3
	>>> sum = num1 + num2
	>>> sum
	8

```

Create 3 variables ```a```, ```b``` and ```c``` with different values and calculate their sum.

```py
	>>> a = 5
	>>> b = 6
	>>> c = 7
	>>> sum = a + b + c
	>>> sum
	18

```

We have just seen the mechanics of how assignment works in Python.

#### Summary

In this step, we:
* Learned what happens when you assign a value to a variable, which may or may not exist
* Discovered that literal constants cannot be placed on the left hand side of the assignment(`=`) operator

### Step 13: Introducing Formatted Printing 

Until now, we have been using the ```format()``` method to format and print values. Let's see a better approach to printing values.

This is the approach we used until now.

```py
	>>> a = 1
	>>> b = 2
	>>> c = 3
	>>> sum = a + b + c
	>>> print("{0} + {1} + {2} = {3}".format(a, b, c ,sum))
	1 + 2 + 3 = 6
```

Python has the concept of formatted strings. The syntax to use a formatted string is very simple - `f""`.

If we want to print the value of a variable ```a```, we can use ```{a}``` in the text.

```py
	>>> print(f"")	
	>>> print(f"value of a is {a}")
	value of a is 1
	>>> print(f"value of b is {b}")
	value of b is 2

```

 The variable within braces is replaced by its value.

 You can use expressions in a formatted string. Example below uses `{a+b}`.

```py
	>>> print(f"sum of a and b is {a + b}")
	sum of a and b is 3
```

This feature was introduced in a Python 3 release. 

Let's get back to the original problem we wanted to solve: printing ```5 + 6 + 7 = 18```, using formatted strings. 

```py
	>>> print(f"{a} + {b} + {c} = {sum}")
	1 + 2 + 3 = 6
```

You can see how easy it turns out to be! 


### Step 14: The PMT-Challenge Revisited

We want to print the ```5```-table from ```5 * 1 = 5``` onward, until we reach to ```5 * 10 = 50```. The best solution we have right now, is shown below:

#### Snippet-01:

```py
	>>> index = 1
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 1 = 5
	>>> index = 2
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 2 = 10
	>>> index = 3
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 3 = 15
	>>> index = 4
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 4 = 20

```
 
Can we do something, to make sure that the code remains the same all the time, but the ```index``` value gets updated? 

```py
	>>> index = index + 1
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 5 = 25
	>>> index = index + 1
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 6 = 30
	>>> index = index + 1
	>>> print("{0} * {1} = {2}".format(5,index,5*index))
	5 * 7 = 35

```

We used ```index = index + 1``` to increment `index` value. 

If we execute these same two statements again and again, we can print the entire table!
	
This is exactly what loops help us do: execute the same statements repeatedly. 

The simplest loop available in Python is the **for loop**. 

When we run a ```for``` loop, we need to specify the range of values - ```1``` to ```10``` or ```1``` to ```20```, and so on. `range()` function helps us to specify a range of values.

```py
	>>> range(1,10)
	range(1, 10)
```

The syntax of the ```for``` loop is: ```for i in range(1, 10): ...```. Here, ```i``` is the name of the **control variable**. In Python, you need to put a colon, '```:```', and in the next line give indentation.

```py
	>>> for i in range(1,10):
	...   print(i)
	... 
	1
	2
	3
	4
	5
	6
	7
	8
	9

```

You would see that it prints from ```1``` to ```9```.

When we run a loop in ```range(1, 10)```, ```1``` is *inclusive* and ```10``` is **exclusive**.The loop runs from ```1``` to the value before ```10```, which is ```9```. 

The leading whitespace before `print(i)` is called **indentation**. We'll talk about indentation later, when we talk about puzzles related to the ```for``` loop.

How can you extend this concept to solving our *PMT-Challenge* problem? 

```py
	>>> print(f"{5} * {index} = {5*index}")
	5 * 7 = 35

```

What we were doing earlier, was calling ```print()``` with a formatted string. Now we want to print this statement for different values of ```i```. 

How can you do that? 

Let's start with a simple example.

```py
	>>> for i in range(1,11):
	...   print(f"{i}")
	... 
	1
	2
	3
	4
	5
	6
	7
	8
	9
	10

```

```print(f"{i}")``` prints the value of i.

Now, how do we get it to print ```5 * 1 = 5``` to  ```5 * 10 = 50```? 

```py
	>>> for i in range(1,11):
	...   print(f"5 * {i} = {5 * i}")
	... 
	5 * 1 = 5
	5 * 2 = 10
	5 * 3 = 15
	5 * 4 = 20
	5 * 5 = 25
	5 * 6 = 30
	5 * 7 = 35
	5 * 8 = 40
	5 * 9 = 45
	5 * 10 = 50
	>>> 5 * 4 * 50
	1000

```

```print(f"5 * {i} = {5 * i}")``` prints a specific multiple of 5. 

### Step 15: Loops 

In a previous step, we took a major step in programming. We wrote our first for loop with Python. In this step, let's try a few puzzles to understand the for loop even further. 

The syntax of the for loop we looked at earlier was: 

```
  for i in range(1, 10):
	print(i)
```


#### Snippet-01:

Let's say we write a ```for``` loop, but don't give a ```:``` after the ```range()``` method, to close the first line. What would happen?

```py
	>>> for i in range(1,10)
	  File "<stdin>", line 1
	    for i in range(1,10)
	                       ^
		SyntaxError: invalid syntax

```

 Invalid syntax. A ```:``` is mandatory within the ```for``` loop syntax. 

 Let's provide a `:` and in the next line, use `print(i)` without space before it (without indentation).

```py
	>>> for i in range(1,10):
	... print(i)
	  File "<stdin>", line 2
	    print(i)
	        ^
	IndentationError: expected an indented block

```

Most other programming languages use open brace ```{``` and closed brace ```}```  as delimiters in a ```for``` loop. However, Python uses indentation to identify which code is part of a ```for``` loop, and which is not. So if we are writing  the body of a ```for``` loop, we must use indentation, and leave atleast a single ```<SPACE>```. 

```py
	>>> for i in range(1,10):
	...   print(i)
	... 
	1
	2
	3
	4
	5
	6
	7
	8
	9

```

How do we execute two lines of code as part of the ```for``` loop? 

```py
	>>> for i in range(1,10):
	...  print(i)
	...  print(2*i)
	... 
	1
	2
	2
	4
	3
	6
	4
	8
	5
	10
	6
	12
	7
	14
	8
	16
	9
	18

```

We are indenting both statements with a space - `print(i)` and `print(2*i)`.

When for loop has only one line of code, you can specify it right after the `:`

```py
	>>> for i in range(2,5): print(i)
	... 
	2
	3
	4

```

However, this is not considered to be a good programming practice. Even though you may want to execute just one statement in a ```for``` loop, indentation on a new line is recommended. 

Another best practice is to use four ```<SPACE>```s for indentation, instead of just two. This would give clear indentation of the code. 

```py
	>>> for i in range(2,5):
	...     print(i)
	... 
	2
	3
	4

```

Anybody who looks at the code immediately understands that this ```print()``` is part of the ```for``` loop.

Let's say you only want to print the odd numbers till ```10```, which are ```1```, ```3```, ```5```, ```7``` and ```9```. The ```range()``` function offers an interesting option. 

```py
	>>> for i in range (1,11,2):
	...   print(i)
	... 
	1
	3
	5
	7
	9

```

In ```for i in range(1, 11, 2)```, we pass in a third argument, called a *step*. After each iteration, the value of `i` is increment by `step`.

#### Summary

In this step, we:

* Looked at a few puzzles about the ```for``` loop, which lay emphasis on the following aspects of for:
	* The importance of syntax elements such as the colon
	* Indentation
	* Variations of the ```range()``` function

### Step 16: Programming Exercise PE-BA-02

In the previous step, after initially exploring the Python ```for``` loop, we looked at a number of puzzles. 

In this step, let's look at a few exercises. 

#### Exercises

1. Print the even numbers up to 10. We would want to print 2 4 6 8 10, using a for loop.
2. Print the first 10 numbers in reverse
3. Print the first 10 even numbers in reverse
4. Print the squares of the first 10 numbers
5. Print the squares of the first 10 numbers, in reverse
6. Print the squares of the even numbers

#### Solution 1

Instead of starting with ```1```, we need to start with ```2```. Each time, ```i``` it would be incremented by ```2```, and ```2 4 6 8 and 10``` would be printed.

```py
	>>> for i in range (2,11,2):
	...   print(i)
	... 
	2
	4
	6
	8
	10

```

#### Solution 2


We would want to print the numbers in reverse. Think about how you would do that using the ```range()``` function. We'd want go from ```10```, ```9```, ```8```, and so on up to ```1```. 

```py
	>>> for i in range (10,0,-1):
	...   print(i)
	... 
	10
	9
	8
	7
	6
	5
	4
	3
	2
	1

```

The value to start with is ```10```. As we discussed earlier, the end value is exclusive. So to print from ```10``` to ```1```, we want to end one value  which is ```0```. ```range(10, 0)``` seems to be what we need. 

Usually these step value is positive, but we need to go backwards from ```10```. Hence, we would give a step value of ```-1```. 


#### Solution 3

Now, let's print the first ```10``` even numbers in reverse. 

```py
	>>> for i in range (20,0,-2):
	...   print(i)
	... 
	20
	18
	16
	14
	12
	10
	8
	6
	4
	2

```

#### Solution 4

Next, we would want to print the squares of the first 10 numbers. 

```py
	>>> for i in range (1,11):
	...     print(i * i)
	... 
	1
	4
	9
	16
	25
	36
	49
	64
	81
	100

```

#### Solution 5

Let's print the squares in the reverse order. 

```py
	>>> for i in range (10,0,-1):
	...     print(i*i)
	... 
	100
	81
	64
	49
	36
	25
	16
	9
	4
	1

```


#### Solution 6

Print the squares of the even numbers. How to do that? 

```py
	>>> for i in range (10,0,-2):
	...     print(i*i)
	... 
	100
	64
	36
	16
	4

```

The key part is using a step of `-2`

We leave it as an exercise for you, to print squares of odd numbers. 

#### Summary

In this video, we:
	* Tried out a few exercises involving the for loop, by playing around with printing sequences of numbers.
* Used the for loop to simplify the solution to the *PMT-Challenge* problem.

### Step 17: Review: The Basics Of Python

It must have been a roller-coaster ride to solve the multiplication table challenge so far. If you're new to programming, there are a wide range of topics and concepts, that you would have learned during this small journey. 

Let's quickly revise the important concepts we have learned during this small journey.

* ```1```, ```11```, ```5```, ... are all called literals because these are constant values. Their values don't really change.
*Consider ```5 * 4 * 50```. This is an expression. ```*``` is an operator, and ```5```, ```4``` and ```50``` are operands.  
* The name ```i``` in ```i = 1```, is called a variable. It can refer to different values, at different points in time.
* ```range()``` and ```print()``` are in-built Python functions. 
* Every complete line of code is called statement. The specific statement ```print()```, is invoking a method. The other statement which we looked at earlier, was an assignment statement. ```index = index + 1``` would evaluate ```index + 1```, and have the ```index``` variable refer to that value.
* The syntax of the ```for``` loop was very simple. ```for var in range(1, 10) : ...```, followed by statements you would want to execute in a loop, with indentation. For the sake of indentation we left four ```<SPACE>```s in front of each statement inside the ```for``` loop. 

So that, in a nutshell, is what we have learned over the course of our first section. 

## Chapter 03 - Introducing Methods

In the last section, we introduced you to the basics of python. We learned those concepts by applying them to solve the *PMT-Challenge* problem. The code below is what we ended up with as we solved that chellenge.

#### Snippet-01: Current Solution To *PMT-Challenge*

```py
	>>> for i in range (1,11):
	...   print(f"8 * {i} = {8 * i}")

```

If we wanted to change the code to print the ```7``` table, we need to change the value ```7``` used in the for loop, to ```8```. It's simple, but still not as friendly as you would like. 

```py
	>>> for i in range (1,11):
	...   print(f"7 * {i} = {7 * i}")
```

To print a ```7``` table, it would be awesome if could say ```print_multiplication_table```, and give a value of 7 beside it, and it would do the rest:

```py
	>>> print_multiplication_table(7)
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'print_multiplication_table' is not defined
	>>> print_multiplication_table(8)
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'print_multiplication_table' is not defined

```

Similarly, ```print_multiplication_table(8)```, could print the multiplication table for ```8```! 

To be able to do this, we need to create a **method**, or a **function**. Creating a method makes the code *reusable*, and we can invoke that method very easily by passing *arguments*. 

In this section, we take an in-depth look at methods. 

### Step 01: Defining Your First Method

Methods are very important building blocks in Python programming. In this step, we will create a simple method that prints ```"Hello World"```, twice. 

#### Snippet-01:

When we talk about a method, we need to give it a name. We are already using an in-built Python method here, which is ```print()```.

```py
	>>> print("Hello World")
	Hello World
	>>> print("Hello World")
	Hello World

```

 Similar to that, we need to give a name to our body of code. Let's say the name is ```print_hello_world_twice```. 

The syntax to create a method in Python is straightforward: 
* At the start, use the keyword ```def``` followed by a space.
* Followed by name of the method - `print_hello_world_twice`.
* Add a pair of parenthesis: ```()```.  
* This is followed by a colon ```:``` (similar to what we used in a  ```for``` loop). 


```py
	>>> def print_hello_world_twice():
	...     print("Hello World")
	...     print("Hello World")
	... 
```
All statements in a method should be indented. The two `print("Hello World")` are indented. So, they are part of the method body.

```print_hello_world_twice()``` defines a method, and it has certain code inside its body. 

How do we call this method? Is it sufficient to say ```print_hello_world_twice```?

```py
	>>> print_hello_world_twice
	<function print_hello_world_twice at 0x10a71ef28>

```

Python Shell says, there's a function defined with that specific name.

How do we execute a method? Very simple! Add a pair of parentheses to the name, ```()```!

```py
	>>> print_hello_world_twice()
	Hello World
	Hello World
	>>> print_hello_world_twice()
	Hello World
	Hello World

```

 Now, we are able to run the method.

#### Summary

In this step, we:

* Learned we can define our own methods in the code we write
* Understood how to define a method, and all its syntax elements
* Saw how we can invoke a method we write

### Step 02: Programming Exercise PE-MD-01

We will now leave you with two exercises, based on what we have learned about methods so far.

#### Exercises

1. Write a method called ```print_hello_world_thrice()```. It should print ```"Hello World"``` thrice to the output. Define this method, and also invoke it. 

2. Write and execute a method, that prints four statements: 
	1. "I have created my first variable." 
	2. "I've created in my first loop." 
	3. "I've created my first method." 
	4. "I am excited to learn Python." 
	You need to print these four statements on four consecutive lines.

#### Solutions

#### Solution 1

```py
	>>> def print_hello_world_thrice():
	... 	print("Hello World")
	...     print("Hello World")
	...     print("Hello World")
	... 
	>>> print_hello_world_thrice()
	Hello World
	Hello World
	Hello World

```

#### Solution 2

```py
	>>> def print_your_progress():
	...     print("Statement 1")
	...     print("Statement 2")
	...     print("Statement 3")
	...     print("Statement 4")
	... 
	>>> print_your_progress()
	Statement 1
	Statement 2
	Statement 3
	Statement 4

```
		
```py
	def print_your_progress():
		print("Statement 1") 
		print("Statement 2") 
		print("Statement 3") 
		print("Statement 4") 

```

For convenience, we have changed the exact text we need to print. Call this method with the syntax ```print_your_progress()```, and you're able to execute its code. 

Now try another exercise. We want to print ```"Statement 1"```,  ```"Statement 2"```, ```"Statement 3"``` and ```"Statement 4"``` on different lines, using just one print statement. How can you do that? 

```py
	>>> def print_your_progress():
	...     print("Statement 1\nStatement 2\nStatement 3\nStatement 4")
	... 
	>>> print_your_progress()
	Statement 1
	Statement 2
	Statement 3
	Statement 4

```

We are using the newline character `\n`.

Let's look at the difference between defining and executing a method. 

When we are writing a method definition, we are writing the code as part of its body.  It has a specific syntax, and starts with the ```def``` keyword. 

A definition by itself cannot cause the code in its body to be executed. 

```print_your_progress()``` represents a method call. The code inside the method is executed.

#### Summary

In this step, we:

* Implemented solutions to a few exercises that test our understanding of Python methods. We touched concepts such as:
	* Defining a method body
	* The way to invoke a method, to run its code
	* The difference between the two

### Step 03: Passing Parameters To Methods

In the previous step,we created methods. We defined ```print_hello_world_twice()```, and this printed ```"Hello World"``` twice. In this step, let's talk about *method arguments*, or *parameters*.

#### Snippet-01:

```py
 
	>>> print_hello_world_twice()
	Hello World
	Hello World
	>>> print_hello_world_thrice()
	Hello World
	Hello World
	Hello World

```

Earlier, we wrote code for ```print_hello_world_thrice()```, which prints the message three times. 

Let's say you want to print it five times. You would need to write another method that does what you need. Doesn't that seem monotonous? 

Instead of that, Won't it be great if I can call the method by the same name, say ```print_hello_world(5)```, and it would print "Hello World" five times? 

The ```5``` which we are passing here is called an **argument**. 

How do we define our method to accept this argument? 

Let's call our argument ```no_of_times```. If you have any experience with other programming languages, they generally need you to specify the parameter type. Something like `This parameter is an integer/float/string, or other types`. But Python does not require parameter type. 

```py
	>>> def print_hello_world(no_of_times):
	...    print("Hello World")
	...    print(no_of_times)
	...

```

Although we are not doing exactly what we set out to, let's see what would happen. What would happen if we say ```print_hello_world()``` ? 

```py
 
	>>> print_hello_world()
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: print_hello_world() missing 1 required positional argument: 'no_of_times'

```

Error! Something like "Hey, you have created ```print_hello_world``` with a parameter, but not passing anything in here! Go ahead and pass a value". Let's pass in a value, such as ```5```. 

```py
	>>> print_hello_world(5)
	Hello World
	5
	>>> print_hello_world(10)
	Hello World
	10
	>>> print_hello_world(100)
	Hello World
	100

```

With ```print_hello_world(5)```, you can see ```"Hello World"``` and ```5``` being printed. We are now able to define this method to accept a value, and print that value by invoking it. You can pass in any value, such as```10```, ```100```, or others.

Now think of a different solution for this method, where you don't repeat the same piece of code to print ```"Hello World"```. Consider  ```print_hello_world(5)```, it should still print ```"Hello World"``` ```5``` times. How do you do that? 

Think about using something along the lines of a loop.

#### Snippet-02:

For now, what we are doing is we are printing ```"Hello World"``` ```10``` times.

```py
	>>> def print_hello_world(no_of_times):
	...    for i in range(1,10):
	...       print("Hello World")
	... 

	>>> print_hello_world(5)
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World

```
Our method call ```print_hello_world(5)``` now prints ```"Hello World"``` ```10``` times. 

However  just print the message ```5``` times. We need to make use of the parameter ```no_of_times``` inside the ```for``` loop as well. 

```py
	>>> def print_hello_world(no_of_times):
	...    for i in range(1,no_of_times):
	...       print("Hello World")
	... 

	>>> print_hello_world(5)
	Hello World
	Hello World
	Hello World
	Hello World

```

Now let's execute the method again. You can see that it's printing ```4``` times only. 

Why is it not printing ```5``` times? 

That's because ```no_of_times``` as a second parameter to ```range()``` is exclusive.  

```py
	>>> def print_hello_world(no_of_times):
	...    for i in range(1,no_of_times+1):
	...       print("Hello World")
	... 
	>>> print_hello_world(5)
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World

```

Great, it's now printing the message ```5``` times! 

```py
	>>> print_hello_world(7)
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World

```

If you pass a different argument like ```7```, the message is displayed ```7``` times. 

Something you need to always be cautious about in Python, is the indentation. Over here, the ```for``` loop is part of the method body. So we have extra  indentation for it. The print is part of the ```for``` loop body. So guess what, even more indentation for that code.

#### Summary

In this step, we:

* Learned how to pass arguments to a method
* Understood that the method definition needs to have parameters coded in
* Observed that arguments passed during a method call can be accessed inside a methods body 

### Step 04: Classroom Exercise CE-MD-01

In this step, Let's look at a few exercises related to the method parameter. 

#### Exercises 

1. Write a method called ```print_numbers()```, that would print all successive integers from ```1``` to ```n```. 

2. The second one is to write a method called ```print_squares_of_numbers()```, that prints squares of all successive integers from ```1``` to ```n```.

#### Solutions

#### Solution 1

```py
	>>> def print_numbers(n):
	...    for i in range(1, n+1):
	...       print(i)
	... 
	>>> print_numbers(5)
	1
	2
	3
	4
	5
	>>> 

```

If you are programming in other languages such as Java, you are used to naming methods in this way: ```printNumbers()```. This convention is popularly known as "Camel Case".

That's NOT how Python programmers name their methods. Pythonic way is to use underscore  ```_``` to separate words in the method name, as in ```print_numbers()```.

#### Solution 2

Let's define ```print_squares_of_numbers()```. This would be very similar to ```print_numbers()```, working with the same range. Only, we need to say ```print(i*i)``` . 

```py
	>>> def print_squares_of_numbers(n):
	...    for i in range(1, n+1):
	...       print(i*i)
	... 
	>>> print_squares_of_numbers(5)
	1
	4
	9
	16
	25

```


How is a parameter different from an argument? 

* Inside the definition of the method, the name within parentheses is referred to as a **parameter**. In our recent exercise, ```n``` is a parameter, because it's used in the definition of ```print_squares_of_numbers```.
* When you are passing a value to a method during a method call, say ```5```, that value is called an **argument**.  
* Don't worry too much about it. Just follow this convention for now:
	* In the method call, call it an *argument*. 
	* In a method definition, call it a *parameter*.

#### Summary

In this step, we looked at a few simple exercises related to passing method arguments

### Step 05: Methods With Multiple Parameters

In this step, let's look at creating a method with multiple parameters.

#### Snippet-01:

`print_hello_world` accepts one parameter and prints "Hello World" the specified number of times. 

```py
	>>> def print_hello_world(no_of_times):
	...    for i in range(1,no_of_times+1):
	...       print("Hello World")
	... 

```

 Let's say we want to print another piece of text ```Welcome To Python```, a specified number of times. How do you do that?

  You can always create another method similar to the first one, such as  ```print_welcome_to_python(no_of_times)``` and print the necessary text inside. 

  However, is that what a good programmer does? 

  A good programmer tries to create a more generic solution. 

```py
	>>> def print_string(str, no_of_times):
	...    for i in range(1,no_of_times+1):
	...       print(str)
	... 
	>>> print_string("Hello World", 3)
	Hello World
	Hello World
	Hello World

```

The good programmer that you are, you created a new method called ```print_string(str, no_of_times)``` accepting a text parameter, in addition to ```no_of_times```. 

Syntax rules for method parameters are quite strict. If we say ```print_string("Welcome to Python")``` and run it, we get an error! Python Shell says: "I need ```no_of_times``` to be present in here".

```py
	>>> print_string("Welcome to Python")
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: print_string() missing 1 required positional argument: 'no_of_times'

```

Let's say you want to assign default values for ```str``` and ```no_of_times``` in ```print_string()```. By default, we want to always print ```"Hello World"```, and that too ```5``` times.

The Python language makes this very easy. ```def print_string(str = "Hello World", no_of_times=5)```. The rest of the method remains the same. 

```py
	>>> def print_string(str="Hello World", no_of_times=5):
	...    for i in range(1,no_of_times+1):
	...       print(str)
	... 

``` 
Now you can call ```print_string()```, and ```"Hello World"``` is displayed ```5``` times.

```py
	>>> print_string()
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World

```

If it's ```print_string("Welcome To Python")```, what does it do? It prints ```"Welcome To Python"```, ```5``` times.

```py
	>>> print_string("Welcome to Python")
	Welcome to Python
	Welcome to Python
	Welcome to Python
	Welcome to Python
	Welcome to Python

```

Consider  ```print_string("Welcome to Python", 8)```, it would print that string ```8``` times.  

```py
	>>> print_string("Welcome to Python", 8)
	Welcome to Python
	Welcome to Python
	Welcome to Python
	Welcome to Python
	Welcome to Python
	Welcome to Python
	Welcome to Python
	Welcome to Python

```

Isn't that cool! 

#### Summary

In this step, we:	

* Looked at how to pass multiple parameters to a method, starting with two arguments
* Learned how you can define default values for those parameters
* Observed we could pass default arguments for none, some or all of those parameters

### Step 06: Back To Multiplication Table - Using Methods

Let's get back to our original goal, of why we needed methods. We wanted to create a multiplication table for a number, and observed that each time we needed to we needed change that number, we were forced to make a change in the code. This is not something we liked, and that's why we started investigating how methods can be used. 

In this step, Let's try our hand at creating a multiplication table method.

#### Snippet-01:

```py
	>>> for i in range (1,11):
	...    print(f"7 * {i} = {7 * i}")

```

Let's define a method called ```print_multiplication_table()```, and pass in a parameter to it.
```py
	>>> def print_multiplication_table(table):
	...    for i in range(1,11):
	...       print(f"{table} * {i} = {table * i}")
	... 
	>>> print_multiplication_table(7)
	7 * 1 = 7
	7 * 2 = 14
	7 * 3 = 21
	7 * 4 = 28
	7 * 5 = 35
	7 * 6 = 42
	7 * 7 = 49
	7 * 8 = 56
	7 * 9 = 63
	7 * 10 = 70

```

Now you have the entire multiplication table for ```7```. 

You can then call ```print_multiplication_table()``` with arguments ```8```, ```9```,and so on, by simply changing the ```table``` arguemnt value.

We now want to create even better ```print_multiplication_table()``` method. 

We want to control the start point, as well as the end point, in the call to ```range()```. We want to  say ```print_multiplication_table(7, 1, 6)```, to print the ```7``` table with entries from ```1``` to ```6```. How can you do that? 

```py
	>>> def print_multiplication_table(table, start, end):
	...    for i in range(start, end+1):
	...       print(f"{table} * {i} = {table * i}")
	... 
	>>> print_multiplication_table(7, 1 , 6)
	7 * 1 = 7
	7 * 2 = 14
	7 * 3 = 21
	7 * 4 = 28
	7 * 5 = 35
	7 * 6 = 42

```

Simple! Define those range limits as additional parameters! 

The other thing we can obviously do, is have default values for the ```start```, and the ```end```.

```py
	>>> def print_multiplication_table(table, start=1, end=10):
	...    for i in range(start, end+1):
	...       print(f"{table} * {i} = {table * i}")
	... 

	>>> print_multiplication_table(7)
	7 * 1 = 7
	7 * 2 = 14
	7 * 3 = 21
	7 * 4 = 28
	7 * 5 = 35
	7 * 6 = 42
	7 * 7 = 49
	7 * 8 = 56
	7 * 9 = 63
	7 * 10 = 70

```

Calling ```print_multiplication_table(7)``` would give us entries from ```7 * 1 = 7``` to ```7 * 10 = 70```.

Now you can actually send out this method, to your friends, who would find it easy to use, and cool! 

#### Summary

In this step, we:

* Learned how to define a method to print the multiplication table for a  number
* Looked at how to enhance this method to make table printing more flexible
* Further enhanced that method to accept default arguments while printing a table 

### Step 07: Indentation Is King

In Python, indentation denote blocks of code. So if you want to put something in a ```for``` loop, or outside it, proper indentation would be sufficient. In this step, let's explore indentation in depth. Let's start by creating a simple method.

#### Snippet-01:

```

	>>> def method_to_understand_indentation():
	...     for i in range(1,11) :
	...        print(i)
	... 
	>>> method_to_understand_indentation()
	1
	2
	3
	4
	5
	6
	7
	8
	9
	10

```

Consider the code below: `print(5)` is indented at the same level as `for loop`.

```py
	>>> def method_to_understand_indentation():
	...     for i in range(1,11) :
	...        print(i)
	...     print(5)
	... 
```

You can see that `print(5)` is called only once. It is not part of the `for loop`.

```
	>>> method_to_understand_indentation()
	1
	2
	3
	4
	5
	6
	7
	8
	9
	10
	5

```

Let's change the code in this method a bit. `print(5)` is indented the same way as `print(i)`

```py
	>>> def method_to_understand_indentation():
	...     for i in range(1,11) :
	...        print(i)
	...        print(5)
	... 
```

`print(5)` is part of the for loop. It is executed 10 times.

```py
	>>> method_to_understand_indentation()
	1
	5
	2
	5
	3
	5
	4
	5
	5
	5
	6
	5
	7
	5
	8
	5
	9
	5
	10
	5

```

Whether we're talking about loops, methods or conditionals, proper indentation is very important in Python. 

We indicate a block of code, by having all lines of that block at the same indentation level. There are no specific delimiters like for instance a pair of braces ```{...}```, as in other programming languages.

#### Summary

In this step, we:

* Ran through a few examples to see how indentation works in Python

### Step 08: Puzzles on Methods - Named Parameters

In this step, let's look at a variety of puzzles related to methods.

#### Snippet-01:

Consider the following method: I would want to print the default string 6 times. How do we do it?

```py
	>>> def print_string(str="Hello World", no_of_times=5):
	...     for i in range(1,no_of_times+1):
	...        print(str)
	... 
	>>> print_string()
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World

```

Will it work if we call the method as in: ```print_string(6)```? 

```py
	>>> print_string(6)
	6
	6
	6
	6
	6

```

```6``` is passed as the first parameter. ```6``` is matched to ```str```, and the method prints ```6``` the default number of times, which is ```5```. 

 to default to ```"Hello World"```, and print it ```6``` times.

You can do this in Python by using **named parameters**. During the method call, you can specify ```no_of_times = 6```. **```no_of_times```** is a named parameter. 

> There is no provision of doing something like this, in other languages like Java. 

Call it as ```print_string(no_of_times=6)```:

```py
	>>> print_string(no_of_times=6)
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World
	Hello World

```
```str``` gets a default value, and ```"Hello World"``` is printed ```6``` times. 

Named parameters are very useful, when a method has a number of parameters, and you would want to make it very clear which parameter you're passing a value for. 

Let's call ```print_string(7, 8)```. what happens? 

```py
	>>> print_string(7, 8)
	7
	7
	7
	7
	7
	7
	7
	7

```

You would see that ```7``` is printed ```8``` times.

Since ```print()``` method is quite flexible, you can pass a number as the first argument. You can even pass a ```float```. 


```py
	>>> print_string(7.5, 8)
	7.5
	7.5
	7.5
	7.5
	7.5
	7.5
	7.5
	7.5

```

What would be the result of this - ```print_string(7.5, "eight")```? 

```py
	>>> print_string(7.5, "eight")
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	  File "<stdin>", line 2, in print_string
	TypeError: must be str, not int
```

Note how ```no_of_times``` is used inside the method... as an argument to ```range()```. ```range()``` only accepts integers, nothing else. When you run the code with ```print_string(7.5, "eight")```, we get an error. 

It says: `TypeError: ```no_of_times``` must be ```int```, not string`. 


A simple rule of thumb is, if you have a parameter, you can pass any type of data to it. That could be an integer, a floating point value a string, or a boolean value. The Python language does not check for the type of a parameter. However, Python will throw an error if the function which is using that parameter, expects it to be of a specific type. The ```range()``` function expects that the ```no_of_times``` is an integer value. 
	
#### Snippet-02:

The last thing which we would be looking at, is method naming conventions. We named our methods in a consistent way: ```print_string```, ```print_multiplication_table```, and the like. 

This is exactly the format which most Python developers use, to name their methods. 

Convention is to use underscore to separate words in a name. 

However, there are a few rules for naming a method: 
	
One of the important rules is also related to variable names. We observed that a variable name cannot start with  a number. 

```py
	>>> def 1_print():
	  File "<stdin>", line 1
	    def 1_print():
	         ^
	SyntaxError: invalid token

```

Similarly, ```1_print``` will not be accepted as a method name.
 
* You can start a name with an alphabet, or with an underscore.
* From the second character onward, you are allowed to use numeric symbols.

Methods and variables cannot be named using Python keywords. 

Now, what is a keyword? For example, when we talked about ```for``` loop, as in: 

	```for i in range(1, 11): print(i)```... 

* **```for```** is a keyword
* **```in```** is a keyword 
* **```def```** is a keyword. 

Later we will look at a few other keywords, such as **```while```**, **```return```**, **```if```**, **```else```**, **```elif```**, and many more.

```py
	>>> def def():
	  File "<stdin>", line 1
	    def def():
	          ^
	SyntaxError: invalid syntax
	>>> def in():
	  File "<stdin>", line 1
	    def in():
	         ^
	SyntaxError: invalid syntax
	>>> def for():
	  File "<stdin>", line 1
	    def for():
	          ^
	SyntaxError: invalid syntax

```
	

#### Summary

In this step, we:

* Were introduced to the concept of named parameters
* Explored the typical naming rules and conventions for methods in Python
* Observed that reserved keywords cannot be used to name variables or methods

### Step 09: Methods - Return Values

Let's try and understand the importance of return values from a method. We will learn how to return a value from a method.

#### Snippet-01:

Let's name our method as ```product_of_two_numbers()```, and let's have parameters ```a``` and ```b``` that it accepts:

```py
	>>> def product_of_two_numbers(a,b):
	...     print(a * b)
	... 
	>>> product_of_two_numbers(1,2)
	2

```

Can we take the product of these two numbers into a variable, and use it in other code, in the same program? 

Suppose we say a ```product = product_of_two_numbers(1,2)```, is this allowed? 

Let's run this code, and see what's stored in ```product```.
```py
	>>> product = product_of_two_numbers(1,2)
	2
	>>> product

```

It's empty. 

The ```product_of_two_numbers()``` method is not really returning anything back, to be used elsewhere. 

Have a look at some of the built-in Python functions, such as ```max()``` for example.

```py
	>>> max(1,2,3)
	3
	>>> max(1,2,3,4)
	4
	>>> maximum = max(1,2,3,4)
	>>> maximum
	4
	>>> maximum * 5
	20

```

If I call ```max()``` with four parameters, as in ```maximum = max(1,2,3,4)```, the value ```4``` gets stored in maximum. 

Later on in the code that follows, we can say ```maximum * 5```,  or we can print the value of ```maximum```, or a similar calculation. This gives our programs a lot more flexibility.

So instead of just printing ```a*b```, if this function could return a value, that would be quite useful.

```py
	>>> def product_of_two_numbers(a,b):
	...      product = a * b;
	...      return product
	... 
	>>> product_of_two_numbers(2,3)
	6

```

We are creating a variable ```product``` and doing a ```return product```. 

Lets run ```product_result = product_of_two_numbers(2, 3)```

```py
	>>> product_result = product_of_two_numbers(2,3)
	>>> product_result
	6
	>>> product_result * 10
	60

```

You can see how simple it is to return values from a method!
	
#### Summary

In this step, we:

* Learned how to return values from inside a method
* Observed how we can store the values returned by a method call

### Step 10: Programming Exercise PE-MD-02

In this step let's look at a couple of exercises about returning values from methods. 

#### Exercises

1. Write a method to return the sum of three integers. 

2. Write a method which takes as input two integers, representing two angles of a triangle,  and computes the third angle. 

Hint: The sum of the angles in a triangle is ```180``` degrees. So if I am passing ```50``` and ```50```, ```50``` plus ```50``` is ```100```. So some of three angles should be ```180```, so the third angle will be ```180 - 100```, which is ```80```.

#### Solution 1 

```py
	>>>def sum_of_three_numbers(a, b, c):
	...     sum = a + b + c
	...     return sum
	... 

	>>> sum_of_three_numbers(1,2,3)
	6
	>>> something = sum_of_three_numbers(1,2,3)
	>>> something * 5
	30

```
The shorter way of doing that would have been to have a temporary variable called instead of ```sum```. We could directly ```return a + b + c```. 

```py
	>>> def sum_of_three_numbers(a, b, c):
	...     return a + b + c
	... 
	>>> something = sum_of_three_numbers(1,2,3)
	>>> something * 5
	30

```

In methods, you can use `return expression` as well. That `expression` gets evaluated, and the value gets returned back. You'd see that the result remains the same.

#### Solution 2

The second is to write a method to take two integers, representing two angles of a triangle, and compute the third one. 

```py
	>>> def calculate_third_angle(first, second) :
	...     return 180 - ( first + second )
	... 
	>>> calculate_third_angle(50, 20)
	110

```

In your programming career, you would be writing a number of methods. It's very important that you are comfortable  doing so. Most of the methods that you write would return values back. 

That's the reason why we're creating a lot of examples involving method calls. 

#### Summary

In this step, we:

* Looked at a couple of exercises related to returning values from methods
* Observed that returning expressions avoids creating unnecessary variables, and shortens method definitions


## Chapter 04 - Introduction To Python Platform

Until now we had been using Python Shell to execute all our code. 

In the real world, we'll be write Python code in a variety of scripts. Before we would go into an IDE and use the IDE to write the script, we thought it would be useful for us to understand how you can write Python code without the benefit of an IDE. 

This would also help us understand the Python environment, in-depth. 

In the next few steps, we'll be looking at how to create simple Python scripts, using any text editor of your choice. Use Notepad, Notepad++. Editpad, or whichever text editing software you are comfortable with. We'll see what involved in executing the program, and what's happening in the background. 


Here are a few videos you might want to look at.
- [Writing and Executing your First Python Script](https://www.youtube.com/watch?v=ORmDD1R7lNc)
- [Understanding Python Virtual Machine and bytecode](https://www.youtube.com/watch?v=HE-FC0csG68)

### Step 01 - Writing and Executing Python Shell Programs

Here's a recommended video to watch - [Writing and Executing your First Python Script](https://www.youtube.com/watch?v=ORmDD1R7lNc)

Let's get started with creating a simple script file. 

We want to type in a simple Python script, or a piece of Python code, such as ```print("Hello world")```. Does it get any simpler than this? 

We'll save this into any folder on our hard disk, with a name 'first.py' . 

***first.py***

```py
print("Hello world")
```

The '.py' is not really mandatory, but typically all python files end with a '.py' extension.

Here's how you can run it:
- Launch your terminal, or command prompt
- 'cd' to the folder where this python script file is saved
- execute the command `python first.py` 

You will see that `Hello World` will be printed.

If you are familiar with other programming languages, you would need a class, need to put the code in that class, and similar stuff. 

While Python supports Object Oriented Programming, is not mandatory to create a class. 

It's almost as if you're typing commands, starting from the line one! That's why we call it a python script. 


#### Summary

In this small step, we tried to create a simple python script, and we ran it from the command line. All we needed to do, was use the same command we use to launch up the python shell, and followed it up with a name of the file. We created a file called first.py, executed that, and were able to see the output on the console. 

As an exercise, try and add a few more methods and try to run those methods as well, as part of this script.

### Step 02 - Python virtual machine and bytecode

In this step, let's try and understand what's happening in the background. 

We wrote a simple piece of code using a text editor. We created a file named first.py, and all we did was: `python3 first.py`. If you look at other languages like Java for example, there is a separate compilation phase and then an execution phase. But with Python, just this command does both compilation and execution. 

We saw that, as soon as we make a change and we run `python3 first.py` , the change is compiled and executed as well! 

In Python, there is an intermediate format called **Python byte code**. Code is first compiled to bytecode, and then executed on the **Python virtual machine**. 

When we installed Python, we installed both the python compiler and interpreter, as well as the virtual machine. 

In Python, `bytecode` is not standardized. Different implementations of Python have different byte code. There are about 80 Python implementations, like CPython and Jython. 
- CPython is a Python implementation in C language. 
- Jython is a Python implementation in Java language. The bytecode which Jython uses is actually Java bytecode, and you can run it on the Java virtual machine. 

Python leaves a lot of flexibility to the implementations of Python. They have the flexibility to choose the bytecode, and to choose the virtual machine that is compatible. The bytecode is tied to the specific virtual machine you are using. Therefore, if you're using CPython to compile the bytecode, you'll not be able to use Jython to run it. 

You should make sure, that whatever implementation you are using to compile, is the same one you're using to run the code as well. 

#### Summary

A lot of this sounds like boring theory. Don't worry about it. As a beginner, this might not be very important for you right now. 

It's very important for you to understand the process. What's happening is you were writing Python code, and when you ran the command `python3 first.py`, it is both compiled and executed. An intermediate format called bytecode is created, which is not really standardized in Python. The bytecode is executed in a Python virtual machine.

The idea behind this quick section, is to give you a little bit of background on what's happening behind the scenes. I'll see you in the next section. Until then, bye-bye!

## Chapter 05 - Introduction To PyCharm

Let's start using the IDE PyCharm to write our Python Code

Here are recommended videos to watch
- [Installing PyCharm](https://www.youtube.com/watch?v=pI_cnCXpCTU)
- [Write and Execute a Python File with PyCharm](https://www.youtube.com/watch?v=Na05tSP21Jg)
- [Write Your First Python Program with PyCharm](https://www.youtube.com/watch?v=PvYSlWbXuCw)


### Step 01 - Installing and Introduction to PyCharm 

In this quick step, we'll help you install PyCharm. 

Here's the video guide for this step 
- [Installing PyCharm](https://www.youtube.com/watch?v=pI_cnCXpCTU)

Go to Google and type in "PyCharm Community Edition Download". Click the link which comes up first: https://www.jetbrains.com/pycharm/download. 

You'll go to a page where you can choose the operating system: whether you are on Windows, Mac, or Linux. 

Once you choose that, you can download the appropriate community version. 

On the right hand side, you'll see a community version, and you can click the download link, to start the download. 

If you are having a problem, you can also use the direct link to download. 

Once you download PyCharm, all you need to do is double-click the package which is downloaded. Follow the instructions, and you can continue with the defaults, until you completely install PyCharm. 

When you launch PyCharm for the first time, it should ask you for a theme, where you can choose the default.

You're all set to go ahead with the next step in the course. 

Pycharm is an awesome IDE, and I'm sure you learn a lot about it.


### Step 02 - Write and Execute a Python File with PyCharm

In this step, let's launch up the PyCharm IDE, and create our first Python project with a Python script. We want to be able to launch a Python script by the end of this step. 

Here's the video guide for this step 
- [Write and Execute a Python File with PyCharm](https://www.youtube.com/watch?v=Na05tSP21Jg)

Launch the Pycharm IDE. You'll see that it takes a little while to launch the first time, and then brings up a welcome screen. 

We would want to create a number of Python files. All these files will be in a project. You can think of our project as a collection of Python scripts, or modules. 

To get started, let's create a new project by clicking 'create new project'. Let's name it -  '01-first-python-project'.

Right now there are no files in the project. 

Let's create our first Python file, using the IDE. 

The way you can do that is by saying 'right-click' -> 'new' -> 'Python file', and then we'll give this a name of 'hello_world', and click OK. 

Now you can go ahead and write your first Python program. Let's write some simple code, like ```print("Hello World")```, and save it. 

You can do a right-click here, and say 'Run hello_world'. 

A small window comes up below, which shows the output. It says ```'Hello World'```. 


### Step 03 - Execise - Write Multiplication Table Method with PyCharm

Let's start with a simple exercise. We created the multiplication table method in the Python Shell. What we do now, is we'll create the same thing but in a Python file of its own.

Here's the video guide for this step:
- [Write Your First Python Program with PyCharm](https://www.youtube.com/watch?v=PvYSlWbXuCw)

## Chapter 06 - Introducing Data Types and Conditionals

Welcome to this section, where we will talk about numeric data types, and conditional program execution. After looking at the numeric and boolean data types, we will turn our attention to executing code, based on logical conditions.

### Step 01: Numeric Data Types

In previous sections, we created variables of this kind: ```number = 5``` , ```value = 2.5```, etc. The ```5``` here is an integer, and integers represent numbers, such as ```1```, ```2```, ```6```, ```-1``` and ```-2```. In Python, the ```class``` for this particular data type is ```int```. 

If you write code like ```type(5)```, you'd get ```'int'``` as the output.

In Python, there are no primitive types. What does that mean? Every value that you see in a Python program, is an object, an instance of some ```class```. 

In later sections, We'll understand what is a ```class```, and what is an object or an instance. For now, the most important thing for you to remember, is that behind every value, there is a ```class```.

#### Snippet-01: 

Let's look at ```2.5```, which is a floating point value. 

If you go ahead and do ```type(2.5)```, what would you see? You would see it's of type ```float``.

```py
	>>> type(2.5)
	<class 'float'>
	>>> type(2.55)
	<class 'float'>
```

When you perform a division operation between two integers, there is a chance that the result of the operation is a ```float```. If you do ```5/2```, the result is ```2.5```.  If we were to do ```4/2```, even then it's of type ```float```.

```py
	>>> type(5/2)
	<class 'float'>
	>>> type(4/2)
	<class 'float'>
	>>> 4/2
	2.0
	>>> 1 + 2
	3

```


 
All the operations we looked at until now, can also be performed on floating point values. 

```py
	>>> value1 = 4.5
	>>> value2 = 3.2
	>>> value1 + value2
	7.7
	>>> value1 - value2
	1.2999999999999998
	>>> value1 / value2
	1.40625
	>>> value1 % value2
	1.2999999999999998

```

```value1 - value2``` returns ```1.299999999999998```. Why? 

Floating point numbers don't really represent accurate values. That's one of the things you need to always keep in mind. 

Typically, if you're doing any highly sensitive financial calculations, don't use ```float```s to represent your values. Instead, use ```Decimal```. More about it later.

Operations can also be performed between ```int``` and ```float```.
```py
	>>> i + value1
	14.5
	>>> i - value1
	5.5
	>>> i / value1
	2.2222222222222223
	>>> 

```

 Result of an operation between a ```int``` and a ```float```, is always a ```float```. 

#### Summary

In this step, we:

* Looked at the two basic numeric types: ```int``` and ```float```.
* Saw the basic operations you can do among ```int```s, among ```float```s, and also between ```int```s and ```float```s.

### Step 02: Programming Exercise PE-DT-01 

In this step, let's do a simple exercise with numeric values. 

#### Exercises

1. You need to create a method called ```simple_interest```, and pass three parameters: ```principal```, ```interest``` and ```duration``` (in years). You also want to calculate the amount after the specific duration, and return it back. Call this method with a few example values. 

For example, if you want to call ```simple_interest``` with ```10000```, with an interest of ```5``` percent, for a duration of ```5``` years, the correct answer would be as follows: ```10000``` is the principal. In addition to ```10000```, you get the interest. The interest for one year is ```10000 * 0.05```, as the interest figure is in percentage.So that's ```500``` a year, into ```5``` which is ```2500```. The result would be ```12500```, and this value should be printed.

#### Solution 1

```py
	def calculate_simple_interest(principal, interest, duration) :
		    return principal * (1 + interest * 0.01 * duration)
	
	print(calculate_simple_interest(10000,5,5))

```

#### Summary

In this step, we:

* Wrote a very simple method to do a simple interest calculation

### Step 03: Puzzles On Numeric Types

In this section, we are looking at numeric types. In this specific step, we would be looking at a few puzzles related to values of these types.

#### Snippet-01: 

Let's create a simple variable ```i = 1```.  ```i = i + 1```. What would be the value of ```i``` after that?

```py
	>>> i = 1
	>>> i = i + 1
	>>> i
	2
```

 It would be ```2```. There is a shortcut way of doing the same thing, by using the ```+=``` operator.

```py
	>>> i += 1
	>>> i
	3

```

Typically in other programming languages, you can do something of this kind: ```i++```. There is no provision in Python to use increment operators like ```++```, in either prefix or suffix mode, like ```++i```, or ```i++```. 
```py
	>>> i++
	  File "<stdin>", line 1
	    i++
	      ^
	SyntaxError: invalid syntax
	>>> ++i
	3
```


Let's look at compound assignments.

```py
	>>> i += 1
	>>> i
	4
	>>> i -= 1
	>>> i
	3
	>>> i /= 1
	>>> i *= 2
	>>> i
	6.0

```

What you see here, is Dynamic Typing in Python. The type of a variable can change during the lifetime of the program. 
```py
>>> i = 2
>>> type(i)
<type 'int'>
>>> i = i/2.0
>>> type(i)
<type 'float'>
```

Let's create a couple more numbers. ```number1 = 5``` and ```number2 = 2```. What could be the result of ```number1 / number2```? You know it, it's ```2.5``` . 

```number1 // nummber2``` truncates the value of ```2.5```, to ```2```.

```py
	>>> number1//number2
	2
```

If you can do ```number1 // number2```, can you also do this: ```number1 //= number2```?

```py
	>>> number1 //= 2
	>>> number1
	2

```

```5 ** 3``` is ```5``` 'to the power of' ```3```, which is ```5 * 5 * 5```, or ```125```.

```py
	>>> 5 ** 3
	125
	>>> pow(5,3)
	125

```

This can also be achieved by invoking ```pow(5, 3)```. We have an operator, as well as a method at our disposal.

The last thing we will look at, are type conversion functions.

If you need to convert an ```int``` value to a ```float```, or a ```float``` to an ```int```.

```py
	>>> int(5.6)
	5
```

What if you want to round a value? ```5.6``` is nearer to ```6``` than ```5```. You can use a function called ```round()```, and here,```round(5.6)``` gives the correct result ```6```.

```py
	>>> round(5.6)
	6
	>>> round(5.4)
	5
	>>> round(5.5)
	6

```

```round()``` can also allows you to specify number of decimals in the result.

```py
	>>> round(5.67, 1)
	5.7
	>>> round(5.678, 2)
	5.68
```

You can also convert ```int``` to ```float```, by using the function ```float()```.
```py
	>>> float(5)
	5.0

```

#### Summary

In this step, we:

* Looked at a few corner cases related to your numeric types.
* Examined the different operators available for use with values of numeric types
* Learned about the usage of type conversion functions

### Step 04: Introducing Boolean Type

We will now shift our attention to the ```bool``` data type. 

A boolean value is something which can be either "true" or "false".


#### Snippet-01:

In Python, "true" is represented by ```True```, and "false" by ```False```. It's important to remember that it's ```True``` with a capital ```'T'```, and ```False``` with a capital ```'F'```. 

```py
	>>> True
	True
	>>> False
	False
	>>> true
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'true' is not defined
	>>> false
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'false' is not defined
```

The boolean variable ```is_even``` indicates whether a number is even or not. 
```py
	>>> is_even = True
	>>> is_odd = False

```
Let's create a variable ```i = 10```. We want to find out if ```i > 15```. What do you think is the result? ```False```.
```py
	>>> i = 10
	>>> i > 15
	False
	>>> i < 15
	True

```

 In general, boolean values can represent the result of logical conditions. 

Let's look at other operations that can result in ```bool``` values. We looked at ```>``` and ```<```. Another operation which you can perform, is ```>=```. 

```py
	>>> i >= 15
	False
	>>> i >= 10
	True
	>>> i > 10
	False
	>>> i <= 10
	True
	>>> i < 10
	False

```

`==` is the comparison operator. We are only comparing the value of ```i``` against ```10```, not changing its value. 

```py
	>>> i == 10
	True
	>>> i == 11
	False

```

#### Summary

In this step, we:

* Were introduced to the ```bool``` data type
* Learned that ```bool``` variables are useful handy while testing logical conditions

### Step 05: Introducing Conditionals

In this step, let's look at ```if``` statement.

Sometimes you need to execute code only when certain conditions are true. You can use a ```if``` condition, which is the simplest conditional in Python. Let's look at an example.

#### Snippet-01:

Let's say ```i``` has a value of ```5```. You want to print something, only if ```i``` has a value greater than ```3```. How do you do that?

```py
	>>> i = 5
	>>> if i>3:
	...     print(f"{i} is greater than 3")
	... 
	5 is greater than 3

```

The syntax of the ```if``` is very simple: ```if``` followed by a condition; with the condition you want to check. It looks like:  ```if i>3: ...``` You need to indent the body of the ```if``` with ```<SPACE>```s as usual.

Let's say ```i``` has a value of ```2```. What would happen if we execute the same code again?

```py
	>>> i = 2
	>>> if i>3:
	...     print(f"{i} is greater than 3")
	... 
```

You would see that nothing is printed to the console. Based on the value of ```i``` , either the statement is executed, or it's not. That's what an ```if``` helps us to do. 

The way you can think about an ```if```, is the body of code under the ```if``` is executed only when this condition is ```True```. If this condition is not ```True```, that code is not executed at all.

```py
	>>> if(False):
	...   print("False")
	... 
	>>> if(True):
	...   print("True")
	... 
	True

```

Let's take two different numbers, say ```a = 5```, and ```b = 7```. We want to compare them, and predict if ```a``` is greater that ```b``` .
```py
	>>> a = 5
	>>> b = 7
	>>> if(a>b):
	...   print("a is greater than b")
	...

	>>> a = 9
	>>> if(a>b):
	...   print("a is greater than b")
	... 
	a is greater than b

```
	
#### Summary

In this step, we:

* Were introduced to the ```if``` statement, the simplest Python conditional
* Understood how an ```if``` helps in implementing conditional program logic

### Step 06: Classroom Exercise CE-DT-01

In this step, let's look at a couple of exercises with the if statement.

#### Snippet-01:

Let's say we define four variables: ```a = 1```, ```b = 2``` , ```c = 3``` and ```d = 5```. we want to find out, if ```a + b``` is greater than ```c + d```.

```py
	>>> a = 1
	>>> b = 2
	>>> c = 3
	>>> d = 5
	>>> if a+b > c+d :
	...    print("a+b > c +d")
	... 
	>>> a = 9
	>>> if a+b > c+d :
	...    print("a+b > c +d")
	... 
	a+b > c +d

```

Let's say we are given three values meant to be the angles of a triangle.  Their values are ```angle1 = 30```,  ```angle2 = 20``` and ```angle3 = 60```. You want to find out if these three angles actually form a  valid triangle. You know that the sum of the angles of a triangle is always ```180``` degrees. 

```py
	>>> angle1 = 30
	>>> angle2 = 20
	>>> angle3 = 60
	>>> if(angle1 + angle2 + angle3 == 180):
	...      print("Valid Triangle")
	... 
	>>> angle2 = 90
	>>> if(angle1 + angle2 + angle3 == 180):
	...      print("Valid Triangle")
	... 
	Valid Triangle

```

The last exercise is to check if a number is even or not. 

Hint L you need to use one of the operators we talked about earlier. That's right, use the modulo operator ```%```.

```py
	>>> i = 2
	>>> if(i%2==0): 
	...   print("i is even")
	... 
	i is even

	>>> i = 3
	>>> if(i%2==0): 
	...   print("i is even")
	... 

```

#### Summary

In this step, we:

* Looked at a few exercises related to the if statement, for writing and testing conditions.

### Step 07 - Logical Operators - and or not

In this step, let's look at the different operators that can be used on ```bool``` values. These operators are called logical operators -  ```and```, ```or``` , ```not``` and ```^``` (xor). 

Let's say we have a value ```True```, and the other ```False```, and we want to play around with them. 

Logical operator ```and``` returns true only when both operands are `True`. 

```py
	>>> True and False
	False
	>>> True and True
	True
	>>> True and False
	False
	>>> False and True
	False
	>>> False and False

```

Logical operator ```or``` returns true when atleast one of the operands is `True`. 

```py
	False
	>>> True or False
	True
	>>> False or True
	True
	>>> True or True
	True
	>>> False or False

```

Logical operator ```not``` returns negation. 

```py
	False
	>>> not True
	False
	>>> not(True)
	False
	>>> not False
	True
	>>> not(False)
	True

```

The XOR operation, denoted by the ```^``` operator, is ```True``` when operands have different boolean values.

```py
	>>> True ^ True
	False
	>>> True ^ False
	True
	>>> False ^ True
	True
	>>> False ^ False
	False

```

#### Summary

In this step, we:

* Looked at the logical operators that act on boolean values, such as ```and```, ```or```, ```not``` and ```^```
* Explored each of these operators, finding out when they return ```True```, and when ```False```.
	
### Step 08: Puzzles On Logical Operators

In this step, Let's look at a few simple puzzles to look at the logical operators.

#### Snippet-01:

Let's say ```i``` has a value of ```10```, and ```j``` has a value of ```15```. You want to find out if both ```i``` and ```j``` are even. How do you do that?

```py
	>>> i = 10
	>>> j = 15
	>>> if i%2==0 and j%2==0:
	...   print("i and j are even")
	... 
	>>> j = 14
	>>> if i%2==0 and j%2==0:
	...   print("i and j are even")
	... 
	i and j are even

```

```py
	>>> if i%2==0 or j%2==0:
	... 
	  File "<stdin>", line 2    
	    ^
	IndentationError: expected an indented block
	>>> if i%2==0 or j%2==0:
	...   print("atleast one of i and j are even")
	... 
	atleast one of i and j are even

```

If we want to find out if at least one of ```i``` and ```j``` is even, we can use the ```or``` operator.

```py
	>>> i = 15
	>>> j
	14
	>>> if i%2==0 or j%2==0:
	...   print("atleast one of i and j are even")
	... 
	atleast one of i and j are even
	>>> j = 23
	>>> if i%2==0 or j%2==0:
	...   print("atleast one of i and j are even")
	... 
	>>> i
	15

```

Now try and guess the value of this. ```if(True ^ False): print("Message")``` 


```py
	>>> if(True ^ False):
	...     print("This will Print")
	... 
	This will Print
	>>> if(False ^ True):
	...     print("This will Print")
	... 
	This will Print
	>>> if(True ^ True):
	...     print("This will Print")
	... 

```

Xor operation using ```^``` - message will get printed if the operands are different. 

What would happen if both of them are ```True```? No message is printed. 

So you would use ```^``` in situations, where you'd want one of the operands to be ```True```, and the other to be ```False```. 

Let's say, ```x = 5```, and you want to check ```if not x == 6: print("This")```. What will be the result of running this code?

```py
	>>> x = 5
	>>> if not x == 6:
	...   print("This")
	... 
	This
	>>> x = 6
	>>> if not x == 6:
	...   print("This")
	... 

```

Actually, there is a shortcut for such a condition: ```if x != 6 : print("This")```.

```py
	>>> if x!=6:
	...   print("This")
	... 
	>>> x=5
	>>> if x!=6:
	...   print("This")
	... 
	This

```

```int()``` is a conversion function, which when given say a ```float``` value, returns an ```int``` value. Consider ```int(True)```, what would happen?

```py
	>>> int(True)
	1
	>>> int(False)
	0

```
	
```int(True)``` returns 1. ```int(False)``` returns 0.

```py
	>>> x = -6
	>>> if x:
	...   print("something")
	... 
	something

```

One of the most interesting facts about boolean stuff, is anything which is non-zero, is considered to be ```True```. 

```0``` is the only integer value which is considered to be ```False```.

```py
	>>> bool(6)
	True
	>>> bool(-6)
	True
	>>> bool(0)
	False
	>>> 

```
So, if I have a value of ```x = -6```, and execute ```if x: print("something")``` what do you think will happen? 

```"something"``` will be printed.

You can use the function ```bool()```, to convert ```int``` to a ```bool``` value. 
- ```bool(6)``` returns ```True```
- ```bool(-6)``` returns ```True``` 
- ```bool(0)``` returns ```False```. 

Except for ```bool(0)```, all the other results would be ```True```.

#### Summary

In this step, we:

* Looked at a few puzzles related to the logical operators
* Looked at conversion functions such as ```bool()``` and ```int()``` to convert between boolean and integer data

### Step 09:

In this step, let's look at two other important components of an ```if``` statement: ```else``` and ```elif```. Let's start with ```else```.

#### Snippet-01:

Consider a scenario where ```i``` has a value of ```2```. Let's try to print a message ```"i is even"``` if ```i``` is an even number. Otherwise, print ```"i is odd"```.

Earlier we wrote code along these lines: ```if i % 2 == 0 : print("i is even")```.  However if this condition is not ```True```, we would want to ```print("i is odd")```. How do we accomplish that?

```py
	>>> i = 2
	>>> if i%2 == 0:
	...   print("i is even");
	... else:
	...   print("i is odd");
	... 
	i is even

```

An ```else``` clause provides an alternative code body to execute, if the ```if``` condition is ```False```.

```py
	>>> i = 3
	>>> if i%2 == 0:
	...   print("i is even");
	... else:
	...   print("i is odd");
	... 
	i is odd

```

Let's look at `elif`.

We want to do something if  ```i``` has value of ```3```, and something totally different if ```i``` has a value of ```4```. 

In short, we want to specify 2 alternatives to the ```if``` condition. How can that be done? 

```py
	>>> if i==1:
	...   print("i is 1")
	... elif i==2:
	...   print("i is 2")
	... else:
	...   print("i is not 1 or 2")
	... 
	i is not 1 or 2
	>>> 

```
That's where the **```elif```** clause comes into the picture. The code in ```elif``` is executed if the previous conditions are false and the current `elif` condition is true.


#### Summary

In this step, we:

* Looked at two important components of the ```if``` statement: ```else``` and ```elif```.
* Understood that the ```elif``` clauses and the final ```else``` clause provide alternative conditions to check, when earlier if conditions are true.

### Step 10: Classroom Exercise CE-DT-02

In this step, let's do a simple exercise with ```if```, ```else``` and ```elif```. 

Before getting to the exercise, let's try and learn how to get console input from the user. 

Until now, we had been hard-coding all the data we were to use. Let's make that part more dynamic now.

#### Snippet-01:

How do we get input from the user? We want to get input from the console, and assign it to a variable. The way we can do that, is by statement ```value = input()``` 

```py
	value = input("Enter a Value: ")
	print("you entered ", value)
```

We can call the ```input()``` method with a text 'prompt', such as ```"Enter A Value: "```.  What we can initially do here, is print the value which was entered, back to the console, by ```print("you entered ", integer_value)```.

An interesting point to explore here, is the type of data input at the console. 

Let's do a ```print(type(value))```. 

```py
	value = input("Enter a Value: ")
	print("you entered ", value)
	print(type(value))
```

Input a value of ```Test```. It has a class of ```str```.

Let's run it again to see other possibilities. This time, let's enter a numeric value, say ```12```. what would happen? 

We again get ```str```. 

We want to get an integer value from the input. How can we do it?

```int()``` function converts string to int. Let's use it.

```py
value = input("Enter a Value: ")
integer_value = int(value)
print("you entered ", integer_value)
print(type(integer_value))
```

Let's run our code once again. 

```"Enter A Value: "``` is prompted, and we enter ```15```. And now, of it says ```"You entered 15"```, and the type it indicates to us,  is ```int```. 

#### Design a menu

* Ask the User for input:
	* Enter two numbers
	* Choose the Option:
		* 1 - Add
		* 2 - Subtract
		* 3 - Multiply
		* 4 - Divide
* Perform the Operation
* Publish the Result

Let's design a menu, and then ask the user for input. 

We have codes for each of the operations : add is ```1```, subtract is ```2```, divide is ```3```, and multiply is ```4```. 

In the first version of the program let's get all the inputs and print them out.

##### Solution

The first version of the program is simple to write

```py
number1 = int(input("Enter Number1: "))
number2 = int(input("Enter Number2: "))
print(f"You entered {number1}")
print(f"You entered {number2}")
print(number1 + number2)
print("\n\n1 - Add")
print("2 - Subtract")
print("3 - Divide")
print("4 - Multiply")
print("5 - Exit")
choice = int(input("Choose Operation: "))
print(choice)

```

We will continue this exercise to complete it, in the next step.

#### Summary

In this step, we:

* Looked at the in-built ```input()``` function that can read console input
* Learned that ```input()``` always returns what the user enters, as a string
* We can convert the string from ```input()```, to the data type we expect by invoking conversion functions

### Step 11: Continued - Classroom Exercise CE-DT-02

#### Exercises

In the previous step, we got the input from the user. Let's continue the exercise in this step. We want to write an if condition.

#### Solution (Continued)

Extending the solution is easy. Write appropriate `if`, `elif` and `else` conditions.

```py
number1 = int(input("Enter Number1: "))
number2 = int(input("Enter Number2: "))

print("\n\n1 - Add")
print("2 - Subtract")
print("3 - Divide")
print("4 - Multiply")

choice = int(input("Choose Operation: "))

# print(number1 + number2)
# print(choice)
if choice==1:
    result = number1 + number2
elif choice==2:
    result = number1 - number2
elif choice==3:
    result = number1 / number2
elif choice==4:
    result = number1 * number2
else:
    result = "Invalid Choice"

print(result)
```

We added the following code to account for invalid input.

```py
else:
    result = "Invalid Choice"
```

#### Summary

In this step, we:

* Augmented the Menu Exercise to get all the input from the console, and compute a value from them 
* Corrected the logic to handle incorrect input

### Step 12: Puzzles On Conditionals

In this step, let's look at a few puzzles related to these `if`, `elif` and `else` clauses. 

#### Puzzle-01

Let's start with the first puzzle. Guess the output.

```py
k = 15
if (k > 20):
  print(1)
elif (k > 10):
  print(2)
elif (k < 20):
  print(3)
else:
  print(4)

```

When we run it, you can see that the output is ```2```. 

```k``` has a value of ```15```, is it greater than ```20```? No! Execution goes to the ```elif```,  is ```k``` greater then ```10```? Yes. It prints ```2``` and goes out of the complete `if`-`else` block. 

Inside the ```if``` conditional, the ```if```, ```elif``` and ```else``` clauses are all independent ones. Only one matching block is ever executed.

#### Puzzle-02

What do you think would be the output of this particular piece of code?

```py
l = 15
    if (l < 20):
        print("l<20")
if (l > 20):
    print("l>20")
else:
    print("Who am I?")

``` 
Note that there are two totally different ```if``` conditions in here : ```if l < 20: ...``` immediately followed by```if l > 20: ... else: ... ```. 

The first `if` is true. `l<20` is printed.

The second `if` is a separate statement. The condition is false. So. ```else``` gets executed. Therefore, ```"who am I"``` gets printed. 

#### Puzzle-03

Let's run this code. 

```py
m = 15
if m>20:
    if m<20:
        print("m>20")
    else:
        print("Who am I?")

```

You can see that nothing is printed. 

The most important thing to focus on here, is indentation. 

The second `if` block is executed only if the first `if` is true. 

#### Puzzle-04

What would be the output?

```py
number = 5
if number < 0:
  number = number + 10
number = number + 5
print(number) 

```

`10` is printed.

The most important thing to focus on here, is indentation. 

Only `number = number + 10` is part of `if` block. It is not executed because the condition is false.

`number = number + 5` is not part of `if`. So, it gets executed.

Let's add a couple of spaces before `number = number + 5`.

What would be the output?

```py
number = 5
if number < 0:
  number = number + 10
  number = number + 5
print(number) 

```

`5` is printed.

Both the statements `number = number + 10` and `number = number + 5` are part of `if` block. They are not executed because the condition is false.

#### Summary

In this step, we:

* Looked at a few puzzles related to ```if```, ```elif``` and ```else```
* Explored the importance of indentation and the different condition clauses inside an ```if``` statement

### Step 01: The Python Type To Denote Text

Let's start looking at another important data type in Python, that's used to represent strings. Not surprisingly, it is in fact named ```str```! 

Let's look at valid string representations.
```py
	>>> message = "Hello World"
	>>> message = 'Hello World'
	>>> message = 'Hello World"
	  File "<stdin>", line 1
	    message = 'Hello World"                          ^
	 SyntaxError: EOL while scanning string literal

```

In Python, you can use either ```` or `""` to delimit string values.


```type()``` method can be used to find type of a variable.  

```py
	>>> message = "Hello World"
	>>> type(message)
	<class 'str'>

```

The ```str``` ```class``` provides a lot of utility methods.

```py
	>>> message.upper()
	'HELLO WORLD'
	>>> message.lower()
	'hello world'
	>>> message = "hello"
```

```message.capitalize()``` does init caps. Only first character is changed to uppercase. 

```py
	>>> "hello".capitalize()
	'Hello'
	>>> 'hello'.capitalize()
	'Hello'

```

You can also run this directly - ```'hello'.capitalize()```. Isn't that cool! 

That's because each piece of text in python is an object of the ```str``` ```class```, and we can directly call methods of that ```class``` on `str` objects. 

Now let's shift our attention to methods, which gives us more information about the specific contents of a string.
* We want to find out if this string contains numeric values? 
* Does it contain alphabets only? 
* Does it contain alpha-numeric values? 
* Is it lowercase? 
* Is it uppercase? 


To find if a piece of text contains only lower case alphabets.

```py
	>>> 'hello'.islower()
	True
	>>> 'Hello'.islower()
	False

```

If the first letter is in uppercase, then ```istitle()``` will return a ```True``` value.

```py
	>>> 'Hello'.istitle()
	True
	>>> 'hello'.istitle()
	False

```

To find if a piece of text contains only upper case alphabets.

```py
	>>> 'hello'.isupper()
	False
	>>> 'Hello'.isupper()
	False
	>>> 'HELLO'.isupper()
	True
	
```

```isdigit()``` checks if a string is a numeric value.
```py
	>>> '123'.isdigit()
	True
	>>> 'A23'.isdigit()
	False
	>>> '2 3'.isdigit()
	False
	>>> '23'.isdigit()
	True

```

```isalpha()``` checks if a string only contains alphabets. 
```py
	>>> '23'.isalpha()
	False
	>>> '2A'.isalpha()
	False
	>>> 'ABC'.isalpha()
	True

```

```isalnum()``` checks if a string only contains alphabets and/or numerals. 
 
```py
	>>> 'ABC123'.isalnum()
	True
	>>> 'ABC 123'.isalnum()
	False

```
Lastly, we look at things which you can use, to check characters of a string. 

`endswith` is self explanatory.

```py
	>>> 'Hello World'.endswith('World')
	True
	>>> 'Hello World'.endswith('ld')
	True
	>>> 'Hello World'.endswith('old')
	False
	>>> 'Hello World'.endswith('Wo')
	False

```

`startswith` is self explanatory as well.
```py
	>>> 'Hello World'.startswith('Wo')
	False
	>>> 'Hello World'.startswith('He')
	True
	>>> 'Hello World'.startswith('Hell0')
	False
	>>> 'Hello World'.startswith('Hello')
	True

```

`find` method returns if a piece of text is present in another string. Returns the first match index.

```py
	>>> 'Hello World'.find('Hello')
	0
	>>> 'Hello World'.find('ello')
	1
```

A value of ```-1``` is returned, if you're searching for something which is not present in the string.

If you are searching for ```'Ello'``` with a capital ```'E'``` ,you'll not be able to find it. Search is case sensitive.

```py
	>>> 'Hello World'.find('Ello')
	-1
	>>> 'Hello World'.find('bello')
	-1
	>>> 'Hello World'.find('Ello')
	-1

```

### Step 02: Type Conversion Puzzles

We'll now try and convert values from one type to another, and try and play around with them. 

`str` converts boolean value to a text value.

```py
	>>> str(True)
	'True'
```

All text value except for empty string represent True. So, `bool` returns True for everything except empty string.

```py
	>>> bool('True')
	True
	>>> bool('true')
	True
	>>> bool('tru')
	True
	>>> bool('false')
	True
	>>> bool('False')
	True
	>>> bool('')
	False

```

Let's try and convert a few integer values to strings.
```py
	>>>str(123)
	'123'
	>>> str(12345)
	'12345'
	>>> str(12345.45678)
	'12345.45678'

```

Let's do the reverse.

```py
	>>> int('45')
	45
	>>> int('45.56')
	ValueError: invalid literal for int()

```

if we do ```int('45.56')```, you can see that it throws an error. It says "I cannot convert this to an ```int```, as ```45.56``` is an invalid integer". 

You can also pass an additional parameter to `int` indicating the numeric system - 16 for Hexa decimal, 8 for Octal etc. Default is 10 - Decimal.

```py
	>>> int('45abc',16)
	285372
	>>> int('a',16)
	10
	>>> int('b',16)
	11
	>>> int('c',16)
	12
	>>> int('f',16)
	15
	>>> int('g',16)
	ValueError: invalid literal for int() with base 16: 'g'

```

You can also convert string to float.

```py
	>>> float("34.43")
	34.43
	>>> float("34.43rer")
	ValueError: could not convert string to float: '34.43rer'

```


#### Summary

In this quick step,  we looked at converting different types to strings, and converting strings to different types. So we looked at ```int```, ```bool``` and ```float``` values, and we looked at how to convert them to string, and how to convert strings back to these specific types.

### Step 02: Strings Are Immutable

In this step, let's learn an important fact about strings in Python. 

String values are immutable. 

What does immutability mean, and why do we say strings are immutable? 

Let's create a very simple string: ```message = 'Hello'```,  and we're saying ```message.upper()```. But what does it do? It prints ```'HELLO'```, with all characters in uppercase. Well, what would happen if you do ```print(message)```? It says ```'Hello'```. 

```py
	>>> message = "Hello"
	>>> message.upper()
	'HELLO'
	>>> message
	'Hello'

```
You would see we tried change the content of message, but it has not changed. 

When we execute ```message.upper()```, a new string is created, and it is returned back. Original string remained unchanged. This is called immutability. 

Once you define a string in Python, you'll not be able to change the value of it. 

You can use - "OK. I can do something of this kind: ```message = message.upper()```". 

What would happen now? 

Will the value of ```message``` get changed? It prints ```'HELLO'```, with all caps. 

Did the value of ```message``` change? Does this prove that strings are mutable?

The important thing you need to understand about all this stuff, is how objects are stored inside Python. 

There are things called variables, and there are things called objects. 

When we run ```message = 'Hello'```
- We are creating one object of `str` class with a values ```'Hello'```. 
- We are creating one variable called ```message```
- The location of ```'Hello'``` is stored into ```message```

In Python, your variables are nothing but a name. 

If location of ```'Hello'``` in memory is `A`, then the value stored in `message` is `A`. `message` is called a reference.

What happens with ```message = message.upper()```?

A new object is created with value ```'HELLO'``` at a different location ```B```. 

A reference ot location `B` is stored into `message` variable.

Summary : The original value at location `A` has not changed and cannot be changed for `str` variables. Hence 'str' objects are immutable.

Variables are just names referring to a location. They don't really contain the value. Variables contain a reference to the location that contains the object.

### Step 03: Python Has No Separate Character Type 

One of the things that surprises people new to Python, is that there is no character data type in Python. 

Typically we have text data types in all the languages, don't we? ```'Hello World'``` for example, is text data, and we stored it in ```message```. This is called a string. 

In other languages, you would have something to represent a single character symbol. For example in Java, you can have a `char` data type, to store a single character  `ch`, in which ```'h'``` is one character. But in Python, there is no separate data type to store single characters. 

For example, let's see how Python treats the first character of the following string ```message```. The way you can access the first character of a string is by saying ```message[0]```. 

```py
	>>> message = "Hello World"
	>>> message[0]
	'H'
	>>> type(message[0])
	<class 'str'>
	>>> type(message)
	<class 'str'>

```

```type(message[0])``` and `type(message)` print the same type ```str```. No difference.

In Python, whether you're talking about a string, or you're talking about a single character symbol, they are all represented by the same ```class```, ```str```. 

```message[100]``` throws an ```IndexError```.

```py
	>>> message[0]
	'H'
	>>> message[1]
	'e'
	>>> message[2]
	'l'
	>>> message[3]
	'l'
	>>> message[100]
	IndexError: string index out of range

```

It says: "The given index is out of the range of the value of that specific string". 

Let's say we would want to print all the characters in this string. 

The way you could do that, is by saying: ```for ch in message: print(ch)```.

#### Summary

In this short step, we looked at the fact that there is no separate character class, or data type in Python. We also looked at how do we loop over a given string, and print all the characters present inside this string.

### Step 04: The ```string``` ```module```

In this step, we will introduce you to the ```string``` ```module```. 


If we would want to use anything from a module in Python, you need to import that specific ```module``` into your program.
```py
	>>> import string
```

If you do a ```string.```  and press <TAB>, it would show the different things which are part of the ```string``` ```module```.


```py
	>>> string.
	string.Formatter(       string.ascii_uppercase  string.octdigits
	string.Template(        string.capwords(        string.printable
	string.ascii_letters    string.digits           string.punctuation
	string.ascii_lowercase  string.hexdigits        string.whitespace

```

Let's explore some of these.

```py
	>>> string.ascii_letters
	'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'
	>>> string.ascii_lowercase
	'abcdefghijklmnopqrstuvwxyz'
	>>> string.ascii_uppercase
	'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
	>>> string.digits
	'0123456789'
	>>> string.hexdigits
	'0123456789abcdefABCDEF'
	>>> string.punctuation
	'!"#$%&\'()*+,-./:;<=>?@[\\]^_`{|}~'
	>>> string.ascii_letters
	'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'

```

You have a set of printable characters, punctuation characters and a lot more. 

You can check a text value against any of these

```py
	>>> 'a' in string.ascii_letters
	True
	>>> 'ab' in string.ascii_letters
	True
	>>> 'abc' in string.ascii_letters
	True

```

```in```  operation on a string, checks if a given string. 

```py
	>>> '1' in '13579'
	True
	>>> '2' in '13579'
	False
	>>> '4' in '13579'
	False

```

#### Summary

In this step, we explored more exercises involving the ```str``` module of Python.

### Step 05: More Exercises With The ```str``` Module 

Let's start with an Exercise - find if a specific character is a vowel or not.

```py
	>>> char = 'a'
	>>> vowel_string = 'aeiouAEIOU'
	>>> char in vowel_string
	True
	>>> char = 'b'
	>>> char in vowel_string
	False

```

he other thing you can do, is just have the capital vowels, or just the lowercase versions. 

```py
	>>> vowel_string = 'AEIOU'
	>>> char.upper() in vowel_string
	False
	>>> char = 'a'
	>>> char.upper() in vowel_string
	True

```

Now let's move on to the next one. 

We want to find out and print all the capital alphabets, from ```A``` to ```Z```. 

There was a small clue at the start of the previous step, regarding importing the ```string``` ```module```. We did the ```string``` ```module```, and we saw that ```string``` ```module``` contained a number of things. 

```py
	>>> string.ascii_uppercase
	'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
	>>> for char in string.ascii_uppercase:
	...   print(char)
	... 
	A
	B
	C
	D
	E
	F
	G
	H
	I
	J
	K
	L
	M
	N
	O
	P
	Q
	R
	S
	T
	U
	V
	W
	X
	Y
	Z

```

Try another easy exercise: print all the lower characters. Instead of ```string.ascii_uppercase```, you have ```string.ascii_lowercase```. 

```py
	>>> for char in string.ascii_lowercase:
	...   print(char)
	... 
	a
	b
	c
	d
	e
	f
	g
	h
	i
	j
	k
	l
	m
	n
	o
	p
	q
	r
	s
	t
	u
	v
	w
	x
	y
	z

```

An even easier exercise, would be to print all the digits. 

```py
	>>> for char in string.
	string.Formatter(       string.ascii_uppercase  string.octdigits
	string.Template(        string.capwords(        string.printable
	string.ascii_letters    string.digits           string.punctuation
	string.ascii_lowercase  string.hexdigits        string.whitespace
	>>> for char in string.digits:
	...   print(char)
	... 
	0
	1
	2
	3
	4
	5
	6
	7
	8
	9
	>>> 

```

The last exercise which we want to leave you with, is to check if something is a consonant.

A consonant is an alphabet which is not a vowel, so any alphabet which is not in ```'aeiou'``` is a consonant. The simplest way of doing this is to say ```consonant_string = 'bcdfghj...'``` and so on. Looks like a very long solution? There is an easier way out. 

```py
	>>> vowel_string = 'aeiou'
	>>> char = 'b'
	>>> char.isalpha() and char.lower() not in vowel_string
	True

``` 

### Step 06: More Exercises On Strings

In the step, let's look at a few more puzzles and exercises related to strings. Let's say we have a simple string, ```string_example```, and this is contains an English sentence. ```'This is a  great thing.'``` 

Let's try to to print each of the words present in this string, on a separate line. 

So we would want to print ```'This'```, ```'is'```, ```'a'```, ```'great'``` and ```'thing'``` on individual lines.


One of the clues we'll give you is, try and do ```string_example. <TAB>```. There are a huge list of methods, which would come up if you do that. 

```py
	>>> string_example = "This is a great thing"
	>>> string_example.
	string_example.capitalize(    string_example.join(
	string_example.casefold(      string_example.ljust(
	string_example.center(        string_example.lower(
	string_example.count(         string_example.lstrip(
	string_example.encode(        string_example.maketrans(
	string_example.endswith(      string_example.partition(
	string_example.expandtabs(    string_example.replace(
	string_example.find(          string_example.rfind(
	string_example.format(        string_example.rindex(
	string_example.format_map(    string_example.rjust(
	string_example.index(         string_example.rpartition(
	string_example.isalnum(       string_example.rsplit(
	string_example.isalpha(       string_example.rstrip(
	string_example.isdecimal(     string_example.split(
	string_example.isdigit(       string_example.splitlines(
	string_example.isidentifier(  string_example.startswith(
	string_example.islower(       string_example.strip(
	string_example.isnumeric(     string_example.swapcase(
	string_example.isprintable(   string_example.title(
	string_example.isspace(       string_example.translate(
	string_example.istitle(       string_example.upper(
	string_example.isupper(       string_example.zfill(

``` 

One of the methods in the list is the ```split()``` method.

```py
	>>> string_example.split()
	['This', 'is', 'a', 'great', 'thing']
	>>> for word in string_example.split():
	...    print(word)
	... 
	This
	is
	a
	great
	thing

```

```split_lines()``` method  looks for a ```'\n'```, and it divides the string based on it. If you have a string which contains newlines, and you would want to divide it into a number of strings with each line as a new element, the method you can use is ```split_lines()```. 

```py
	>>> string_example = "This\nis\n\ngreat\nthing"
	>>> print(string_example)
	This
	is
	
	great
	thing
	>>> string_example = "This\nis\na\ngreat\nthing"
	>>> print(string_example)
	This
	is
	a
	great
	thing
	>>> string_example.splitlines()
	['This', 'is', 'a', 'great', 'thing']
	>>> 

```


The last thing which we look at, is **concatenation operator**. 

```py
	>>> 1 + 2
	3
	>>> "1" + "2"
	'12'
	>>> "1" + 1
	TypeError: must be str, not int
	>>> "ABC" + "DEF"
	'ABCDEF'

```

In Python, you cannot do ```+``` operator between two different types. ```+``` with two strings is concatenation. ```+``` with two numbers is addition.


One other interesting operator on strings is multiplication. If you do a ```'1' * 20```, What do you think will be the output?

```py
	>>> 1 * 20
	20
	>>> '1' * 20
	'11111111111111111111'
	>>> 'A' * 10
	'AAAAAAAAAA'

```

If you multiply a string with `number`,  the string value is concatenated `number` times.

The last thing which we look at in this step, is comparing strings. 

Let's say we have a string with a value ```str = 'test'```, and you have another string to with a value ```str1 = 'test1'```. 

We want to check whether both these strings are the same.

```py
	>>> str = "test"
	>>> str2 = "test1"
	>>> str == str2
	False
	>>> str2 = "test"
	>>> str == str2
	True

```

You can compare strings using the ```==``` operator.

#### Summary

In this step, we explored a few exercises on strings, covering areas such as:

* Splitting a given sentence into individual words
* The concatenation operator, ```+```
* The string multiplication pattern, ```*```
* The use of the ```==``` operator to compare strings


## Chapter 07 - Introducing Loops

Welcome to the section on Loops. In this section, we will look at a variety of loops that are available in Python. We will look mainly at the **```for```** loop, and the  **```while```** loop. 

### Step 01: Revisited: The for Loop

Let's start with revising the basics of the for loop, we have learned in the previous steps. 

We saw that a ```for``` loop helps us to loop around the same set of code statements, many times over. 

Let's look at a few simple examples, once again.

#### Snippet-01

The syntax of a ```for``` loop is very simple. 

For example, this code snippet will tell you all about it: ```for i in range(1, 11): print(i)```. 

What does this do? Very simple, it prints from ```1``` to ```10```. 

In the call to the ```range()``` function, the second parameter is exclusive. We are actually looping from ```1``` to ```10```, and this piece of code, ```print(i)```,  is being executed for different values of ```i```. 

```py
	>>> for i in range(1,11):
	...   print(i)
	... 
	1
	2
	3
	4
	5
	6
	7
	8
	9
	10

```

```for``` loop can also be used to loop round the characters in a string.

```py
	>>> for ch in "Hello World":
	...   print(ch)
	... 
	H
	e
	l
	l
	o 
	W
	o
	r
	l
	d

```

```for``` loop can be used to loop around all the words in  a given sentence.

```py
	>>> for word in "Hello World".split():
	...   print(word)
	... 
	Hello
	World

```

`for` loop can be used to loop around a specific list of values.

```py
	>>> for item in (3, 6, 9):
	...   print(item)
	... 
	3
	6
	9

```

#### Summary

In this step, we started with discussing and revising basic concepts about the ```for``` loop

### Step 02: Programming Exercise PE-LO-01

Welcome back to this step, where we would do a lot of exercises with the ```for``` loop. 

#### Exercises

1. The first exercise is to find out if a number is prime. We want to write a method, ```is_prime()```, which accepts an integer value as parameter, and returns whether it's a prime. (**Hint**: A prime number is something which is only divisible by ```1``` and itself).
	1. ```5``` is only divisible by ```1``` and ```5```. It is not divisible by any other number. Same is the case with ```7``` and ```11```. 
	2. However, ```6``` is divisible by ```1```, ```2```, ```3``` and ```6```. So it's not a prime number. 

2. The second exercise is to write a method to calculate the sum up to a given integer,  starting from ```1```. **Hint**: If I would want to find that the sum up to ```6```. what's needed is ```1 + 2 + 3 + 4 + 5 + 6```. 

3. The third exercise is to find that the sum of divisors of a given integer. **Hint**: Let's say we want to find out the sum of the divisors of ```15```. The divisors of ```15``` are ```1```, ```3```, ```5``` and ```15```. So I would want to calculate ```1 + 3 + 5 + 15```, and return that value. 

4. Fourth exercise is to print a numbered triangle, when given a specific integer. 

Hint: Given an input ```5```, we would want to print the number triangle of these kind:
 
	1  
	1 2  
	1 2 3  
	1 2 3 4
	1 2 3 4 5. 

These are the exercises for the ```for``` loop. We also test our skills, with creating method and executing them, in our IDE.

#### Solution 1

Let's start with creating the ```is_prime()``` method, in a file named ```for_exercises```. 

We would want to accept an ```int``` parameter, and find out if it is prime, or not. 

We need to check whether it's divisible by any other number, other than ```1``` and itself. If we are passed in a value of ```5```, you want to see if it's divisible by any of ```2```, ```3``` or ```4```. 

```py
def is_prime(number):

```

We can use a ```for``` loop. We can structure it like this: ```for divisor in range(1, number): ...```. We would not want to divide it with ```1```, but start with ```2``` instead, and go up to ```number-1```, which is ```4```.  

```py
for divisor in range(2,number):

```

How can we check if the `number` is divisible by `divisor`? 

By using the ```%``` operator. If `number` is divisible by `divisor` we return `False`.

```py
for divisor in range(2,number):
	if number % divisor == 0:
		return False

```


What happens if the code comes up to the end? It would mean we tried with ```2```, ```3``` and ```4```, but ```number``` was not divisible by all of them. In that case, ```number``` would be prime, and we can safely return ```True```.

```py
for divisor in range(2,number):
	if number % divisor == 0:
		return False

return True

```

For ```1```, the rules are a little different, as it is neither a prime or composite.  We will add an ```if``` condition to check if the number is ```1```. 
	
```if(number < 2):``` 

This ```if``` condition is called a guard check or a boundary check, to make sure that you are processing only the right input. If ```number``` has a value less than ```2```, do nothing. OK, it's not a prime. 

Here is the entire code at one place, for your reference:

```py
def is_prime(number):
    if(number < 2):
        return False
    for divisor in range(2,number):
        if number % divisor == 0:
            return False
    return True
print(is_prime(5));

```

### Step 03: Continued - Programming Exercise PE-LO-01

In the previous step, we looked at solving the ```is_prime()``` exercise. In this step, let's look at an implementation of ```sum_up_to_n()```. 
Here is the entire code for this exercise:

```py
def sum_upto_n(number):
    sum = 0
    for i in range(1, number+1):
        sum = sum + i
    return sum
print(sum_upto_n(6))
print(sum_upto_n(10))

```

#### Summary

In this step, we:

* Wrote a Python function to compute the sum of all integers, from ```1```, up to the input integer ```n```.

### Step 04: Continued - Programming Exercise PE-LO-01

Let's focus on the third exercise, ```sum_of_divisors```. 

One of the clues we can give you, is that ```sum_of_divisors()``` is very similar to ```is_prime()```. 

You want to find out if a number is dividing ```15```, and if it's dividing ```15```, with the remainder of ```0```, then you need to add that up.

```py
def calculate_sum_of_divisors(number):
    sum = 0
    if(number < 2):
        return sum
    for divisor in range(1,number+1):
        if number % divisor == 0:
            sum = sum + divisor
    return sum
print(calculate_sum_of_divisors(6))
print(calculate_sum_of_divisors(15))

```

### Step 05: Continued - Programming Exercise PE-LO-01

In this step, Let's look at the last exercise - ```print_a_number_triangle```. 

For example, if we call such a function with input ```5```, the output needs to be:

```
1  
	
1 2  
	
1 2 3  
	
1 2 3 4  
	
1 2 3 4 5 
```

Let start with a simple thing. Let's try and print ```1 2 3 4 5``` first, and then we would look at how to print the rest of the output. Lets proceed with defining this method.

We can say ```def print_a_number_triangle(number): ...``` that takes a number as an input. You want to print a sequence of integers starting from ```1```, up to that specific ```number```. How can you do that? Let's try this: ```for i in range(1,number+1): print(i)``` What would happen? Let's call ```print_a_number_triangle(5)``` now. It prints: 

		1 
		2 
		3 
		4 
		5 

on individual lines. 

To print this sequence on a single line, let's delimit them with ```<SPACE>``` instead. Call ```print()``` like this instead: ```for i in range(1,number+1): print(i, end=" ")```. 

Let's see what would happen now.
	
```1 2 3 4 5```

To solve our exercise, we want to repeat this again and again.

Yes, we need another for loop around it! 
	
```py
for j in range(1, number+1):
	for i in range(1, number + 1): 
		print(i, end=" ")

```

Make sure that you have the indentation right. This is called `loop within a loop`. 

The output of above program is 

```1 2 3 4 5 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5```

Let's add ```print("\n")```, so we have a new line at the end of each outer loop iteration. 

```py
for j in range(1, number+1):
	for i in range(1, number + 1): 
		print(i, end=" ")
	print("\n")

```
Output

```
1 2 3 4 5 
1 2 3 4 5 
1 2 3 4 5 
1 2 3 4 5 
1 2 3 4 5 
```

We are printing  a square, not a triangle.  

What we want to do is to print up to ```1``` in first line, upto `2` in second line and so on.

How can we do that? Think about it. 

When you are inside this loop, you can see the variable ```j```. 

Instead of ```number+1```, let's say ```j + 1```. 

When ```j``` has a value of ```1```, ```for``` will print from ```1``` to ```1```. When ```j``` has a value of ```2```, print from ```1``` to ```2```, literally printing ```1 2```. When j has a value of ```3```, I'll print from ```1``` to ```3```. Let's try this and see what would happen. 


```py
for j in range(1, number+1):
	for i in range(1, j + 1): 
		print(i, end=" ")
	print("\n")

```

You can see that our number triangle is ready! 

```
1  
	
1 2  
	
1 2 3  
	
1 2 3 4  
	
1 2 3 4 5 
```

Here is the entire code for you:

```py
def print_a_number_triangle(number):
    for j in range(1, number + 1):
        for i in range(1, j + 1):
            print(i, end=' ')
        print()
print_a_number_triangle(6)

``` 

An important point to note is, a couple of these things can be done in a much simpler way. We will look at these options when we talk about functional programming.

#### Summary

In this step, we:

* Presented a solution to the exercise for printing a number triangle.

### Step 06: Introducing The while Loop

Let's look at one of the other loops which is present in Python, called the  **```while```** loop. 

In the ```for``` loop, we can specify the range of our iteration, by using the ```range()``` function. 

In a ```while``` loop, we specify a logical condition. While the condition is true, loop continues running.

Do you remember one place where we use the condition until now? It was in an ```if``` statement. 

Let's see how to use a simple ```while``` loop.

#### Snippet-01:

```py
	>>> i = 5
	>>> if i == 5:
	...   print("i is 5")
	... 
	i is 5

```

Let's say ```i``` has a value of ```0```,  and we then do: ```while i < 5: print(i)```.


```py
	>>> i = 0
	>>> while i < 5:
	...   print(i)
	... 
	0
	0
	0
	0
	0
	0
	0
	0
	^CTraceback (most recent call last):
	  File "<stdin>", line 2, in <module>
	KeyboardInterrupt
	>>> 
	KeyboardInterrupt

```


If we leave it to run, you'd see that it continuously prints ```0``` again, and again. Let's do a ```<CTRL-C>``` or ```<COMMAND-C>``` to interrupt this. 

What is happening here? 

Initially ```i``` is ```0```, and the condition ```i < 5``` is ```True```, and ```print(i)``` is executed.  Next iteration, it checks the condition, it is ```True```, and ```0``` is printed. This continues to happen. What's happening is an **infinite loop**.

One of the important things to make sure in a ```while``` loop, is to increment the value of ```i```. We need to say something like  ```i = i + 1```.

```py
	>>> while i < 5:
	...   print(i)
	...   i = i + 1
	... 
	0
	1
	2
	3
	4

```

So how does it work? 
*```i``` initially had a value of ```0```. First the condition is checked. It's ```True```, so ```0``` is printed and then the value of ```i``` is incremented to ```1```. 
* ```i``` is still less than ```5```, so the loop continues to execute, and this happens until ```4``` is printed. ```i``` again  gets incremented to  ```4 + 1```, or ```5```. 
* Then we check the condition ```i < 5```. This is now ```False```. Control goes out of the ```
while``` loop, and terminates it. 

When executing a ```while```, control flow is just based on a condition. As long as the condition is ```True```, we keep executing the code. An important thing to remember, is to make sure the control variable is updated. 

```py
 
	>>> for i in range(0,5): print(i)
	... 
	0
	1
	2
	3
	4

```

A ```for``` loop is much simpler to code than a ```while```. With ```while```, we have to write an expression statement, to increment the value. 

The question you might have is - What are the situations when you should use a while? 

We will look at that very soon.

#### Summary

In this video, we:

* Were introduced to the concept of a ```while``` loop in Python
* Understood the importance of a control variable being incremented inside the loop
* Observed differences between the working of a ```while```, and a ```for``` loop

### Step 07: Programming Exercise PE-LO-02

In the previous step, we were introduced to ```while``` loop. In this step, let's look at a couple of exercises using the ```while``` loop. 

#### Exercises 

1. ```print_squares_upto_limit(30)```: We need to print all the squares of numbers, up to a limit of ```30```. The output needs to be ```1 4 9 16 25```.

2. ```print_cubes_upto_limit(30)```: We need to print all the cubes of numbers, up to a limit of ```30```.The output needs to be 1 8 27.

#### Exercise 1: Solution

Here is the entire code for your reference:

```py
def print_squares_upto_limit(limit):
	i = 1
	while i * i < limit:
	    print(i*i, end = " ")
	    i = i + 1

```

Now the next exercise, was to print cubes up to a limit.  

The expression in the ```while``` condition should now be ```i*i*i < 30```.

```py
def print_cubes_upto_limit(limit):
    i = 1
    while i * i * i < limit:
        print(i*i*i, end = " ")
        i = i + 1
print_cubes_upto_limit(80)

```

Could we have implemented above two examples with `for` loop? It would've been a little more difficult.

Typically, we use a `for` loop when we know how many times the loop will be executed is clear at the start.

If we do not know, how many times a loop will run, `while` is a better option.

### Step 08: While Example


Earlier we used `if` statement to implement a solution for this:
* Ask the User for input:
	* Enter two numbers
	* Choose the Option:
		* 1 - Add
		* 2 - Subtract
		* 3 - Multiply
		* 4 - Divide
* Perform the Operation
* Publish the Result

We would want to enhance it to execute in a loop multiple times, until the user chooses to exit. We will add an option 5 - Exit.

* Ask the User for input:
	* Enter two numbers
	* Choose the Option:
		* 1 - Add
		* 2 - Subtract
		* 3 - Multiply
		* 4 - Divide
		* 5 - Exit
* Perform the Operation
* Publish the Result
* Repeat until Option 5 is chosen.


#### Snippet-01 Explained

Here's the earlier code we wrote with if:

```py
number1 = int(input("Enter Number1: "))
number2 = int(input("Enter Number2: "))

print("\n\n1 - Add")
print("2 - Subtract")
print("3 - Divide")
print("4 - Multiply")

choice = int(input("Choose Operation: "))

# print(number1 + number2)
# print(choice)
if choice==1:
    result = number1 + number2
elif choice==2:
    result = number1 - number2
elif choice==3:
    result = number1 / number2
elif choice==4:
    result = number1 * number2
else:
    result = "Invalid Choice"

print(result)
```

Let's use `while` around the `if`. We cannot predict what choice the user enters. We'll say: ```while choice != 5:...``` and at the end, we would want to ask the user for a choice. If your choice is anything other than ```5```, we will give the output, and print the whole menu again. 

```py
number1 = int(input("Enter Number1: "))
number2 = int(input("Enter Number2: "))

print("\n\n1 - Add")
print("2 - Subtract")
print("3 - Divide")
print("4 - Multiply")
print("5 - Exit")

choice = int(input("Choose Operation: "))

while(choice != 5):

    # print(number1 + number2)
    # print(choice)
    if choice==1:
        result = number1 + number2
    elif choice==2:
        result = number1 - number2
    elif choice==3:
        result = number1 / number2
    elif choice==4:
        result = number1 * number2
    else:
        result = "Invalid Choice"

    print(result)

    choice = int(input("Choose Operation: "))

print("Thank You")
```

These are the kind of situations where ```while``` loop is good. W

#### Summary

In this step, we:

* Enhanced the menu exercise done earlier, to allow the user to give operation choices repeatedly
* Found that a ```while``` loop was ideal to solve this exercise

### Step 09 - Loops - Puzzles - break and continue

We would be discussing about a wide variety of puzzles related to ```for``` loop, and ```while loop```. 

#### Snippet-01:

What would be the output of this script?

```py
	for i in range(1,11,2):
	    print(i, end=' ')

```

Output : ```1 3 5 7 9```

``range()``` function accept a ```step``` parameter. It starts with ```1```, and at each step it increments by ```2```.```11``` is exclusive. So ```11``` is not printed. 


Let's look at the next one.  

```py
for i in range(11,0,-1):
    print(i,  end=' ')

```

Output : `1 10 9 8 7 6 5 4 3 2 1`

On to the next puzzle. 

```py
i = 5
while i*i < 10:
    print(i)
print("done")
	
```

Output : `done`

On to the next puzzle. 

```py
i = 2 
while i * i < 10: 
  print(i, end=" ") 
print('done')

``` 

Output : `222222222222....`

It's printing ```2``` continuously. We forgot the increment. Let's try and fix this. 

```py
 i = 2
 while i*i < 10:
     print(i,  end=' ')
     i = i + 1
 print("done")

```

Output : ```2 3 'done'```.

Now, let's look at a new puzzle, with a new key word, **break**.

```py
for i in range(1,11):
    if i==5:
       break
    print(i,  end=' ')
print("done")

```

Output : ```1 2 3 4 'done'```

```break``` breaks out of the loop when executed.  With ```5```, the condition matches `if i==5`. ```break``` is executed, and we get outside the ```for``` loop. 

Let's look at the next puzzle:

```py
for i in range(1,11):
	if i%2:
	   break
	print(i ,  end=' ')
print("done")

```

Output : `'done'`

You don't really see anything being printed from the for loop. 

When you evaluate ```1 % 2```, it returns ```1``` as the remainder. Any non-zero number is considered to be ```True```. We break out of the loop. 

Next Puzzle:

```py
for i in range(2,11):
    if i%2:
       break
    print(i ,  end=' ')
print("done")

```

It prints ```2```, because ```2 % 2``` is ```0```, and ```0``` is ```False```, so the print is executed as the ```break``` is not called. However when it becomes ```3```, ```3 % 2``` is 1, which is considered to be ```True```. The ```break``` is executed, and we exit out of the loop. 

Let's look at a new keyword, called **continue**. Look at the following code: 

```py
for i in range(1,11):
   if i%2==0:
     continue
   print(i ,  end=' ')
print("done")

```

It's printing ```1 3 5 7 9 'done'```

What do you think will be the output?

```continue``` skips the code inside the ```for``` loop for the current iteration, and then resumes the next one. 

Lines after ```continue``` in loop are skipped and you'd start the next iteration of the loop.

What would happen, if we remove the ```i%2 == 0```, and only have condition as ```i%2```? 

```py
for i in range(1,11):
   if i%2:
     continue
   print(i ,  end=' ')
print("done")

```
It prints even numbers only. For odd numbers,  ```i%2``` is ```True```. They are skipped.

The last puzzle we'll be looking at is exactly a modification of the earlier one. Instead of. ```i%2```, we give the condition as ```i % 2 != 0```. 

```py
for i in range(1,11):
   if i%2!=0:
     continue
   print(i ,  end=' ')
print("done")

```

What do you think will be the output? Yes you're right. No change in output, because ```if i % 2 !=0``` is the same as a ```if i % 2```. That's because if ```i % 2``` is ```0```, then ```i % 2``` will be ```False```. If ```i % 2``` is ```0```, then  ```i % 2 != 0``` also will be ```False```.

## Chapter 08 - Python Tips

### Tip 1 - Using Predefined Python Modules

There are a number of predefined modules in Python, providing a wide variety of features for use. In this step, let's learn how to import a module, and how to use methods from specific modules.

Let's talk about the ```math``` ```module``` to start off with. Import it by saying ```import math```. If you do ```math.``` and press ```<TAB>```,  it shows all the functions that are defined in the ```math``` ```module```. 

```py
	>>> import math
	>>> math.
	math.acos(       math.erf(        math.inf         math.pi
	math.acosh(      math.erfc(       math.isclose(    math.pow(
	math.asin(       math.exp(        math.isfinite(   math.radians(
	math.asinh(      math.expm1(      math.isinf(      math.sin(
	math.atan(       math.fabs(       math.isnan(      math.sinh(
	math.atan2(      math.factorial(  math.ldexp(      math.sqrt(
	math.atanh(      math.floor(      math.lgamma(     math.tan(
	math.ceil(       math.fmod(       math.log(        math.tanh(
	math.copysign(   math.frexp(      math.log10(      math.tau
	math.cos(        math.fsum(       math.log1p(      math.trunc(
	math.cosh(       math.gamma(      math.log2(       
	math.degrees(    math.gcd(        math.modf(       
	math.e           math.hypot(      math.nan

```


```math.floor(4.5)``` gives you back ```4```. 

If you want to find out a little bit more about the ```math.floor()```, say ```help(math.floor)```. 

This command would show you the documentation for this ```floor()``` function. It says "floor(x) returns the floor of x as an integer. This is the largest integer, which is less than or equal to x".

```py         
	>>> math.floor(4.5)
	4
	>>> help(math.floor)
	>>> help(math)	

```

You can import all the members from the entire module by using ```from math import *```. 

What would happen now, is all the functions which are present in ```math```, are visible in your namespace. 

You can directly call ```floor(5)```, without the need for ```math.floor()```. 

You can do ```gcd(2, 4)```, where ```gcd()``` finds the greatest common divisor of these two numbers. 

For help, You can use ```help(gcd)```, and it responds with the documentation. 

An important things to remember, is when you do ```import * from math```, you are importing everything from there. This means if you have any local variable with the names as these functions, they might get shadowed. 

```py
 
	>>> from math import *
	>>> floor(5)
	5
	>>> gcd(34,56)
	2

```

Typically it's not really considered to be a good practice to import everything into the namespace. 

If there are specific things that you would want to import and use them directly, Then you can import just that, by doing this: ```from math import floor```. Also ```from math import gcd```.

```py
	>>> from math import gcd
	>>> gcd(56,68)
	4

```


### Step 74: Tip 2 - Getting Index Element

Let's next look at a tip regarding loops. In certain scenarios with loops, you might want to access the index of the element. That's what we would be looking at, in this specific tip. 

Let's say we have a list ```numbers = [1, 4, 6, 3, 4]```. Looping through this will be like this: ```for number in numbers: print(number)```, which will simply print the numbers. However, if you want to find the index of a specific element from within the loop, how would you do that? 

```py
	>>> numbers = [1,4,6,3,4]
	>>> for number in numbers:
	...   print(number)
	... 
	1
	4
	6
	3
	4

```

You can achieve that by saying ```for index, number in enumerate(numbers): print(number)```. 

```enumerate()``` is a built-in Python method, which makes available both the index, and the number.

 We can now print a formatted string, by accessing ```{index}``` and ```{number}```. 

```py
	>>> for index,number in enumerate(numbers):
	...    print(f'{index} - {number}')
	... 
	0 - 1
	1 - 4
	2 - 6
	3 - 3
	4 - 4

```


This would also work for strings, consider ```'aeiou'```. This contain all the vowel characters. Now if we loop around it: ```for index, vowel in enumerate (values): print(f'{index}{vowel}')```. Nothing fancy in here. You can print the index, as well as the particular vowel character. 

```py
	>>> values = list('aeiou')
	>>> values
	['a', 'e', 'i', 'o', 'u']

	>>> for index, vowel in enumerate(values):
	...     print(f'{index} - {vowel}')
	... 
	0 - a
	1 - e
	2 - i
	3 - o
	4 - u

```


### Short Hand If Statement

In this step, let's look at a way in which you can make your ```if``` statements, even simpler. 

Let's say you have a number, ```number = 5```. You want to find out, if it's even or not, and store it in a name call ```isEven```. Typically, the way you can write that is really simple, isn't it! You can use ```if number % 2 == 0: isEven = True else: isEven = False```.However, there is even simpler way of doing this! 

```py
	>>> number = 5
	>>> if(number%2==0):
	...   isEven = True
	... else:
	...   isEven = False
	...

```

You can use ```isEven = True if number % 2 == 0 else isEven = False``` . You can see what it contains.

```py
 
	>>> isEven = True if number%2==0 else False
	>>> isEven
	False

```

Now let's have ```number = 6```, and do it again. 

```py
	>>> number = 6
	>>> isEven = True if number%2==0 else False
	>>> isEven
	True

```

his is a shortcut ```if``` statement, which is very useful when you have simple condition, based on which you want to set the values.

Actually the even easier way of doing this, would have been to do this - ```isEven = number%2 == 0``` . 

If the return value is something like a string, what would you do? 

Let's say you want, instead of ```True``` or ```False```, a ```'yes'``` or ```'no'``` result. You can use ```isEven = 'yes' if number%2 == 0 else 'no'```. 

```py
	>>> isEven = number%2==0
	>>> isEven = "Yes" if number%2==0 else "No"
	>>> isEven
	'Yes'

```


In this step, we quickly took a look at shortcuts for ```if``` statement.

### Tip 4 - Beginners Mistakes - Shadowing

In this step, we'll talk about a mistake which a lot of beginners make. 

Let's talk about the built-in ```sum()``` function. You can pass it lists of values, and it would add them up. 

```py
	>>> sum
	<built-in function sum>
	>>> sum([12,34,56])
	102

```

Now let's say you are trying to solve a problem, where you want to have two numbers: ```number = 10```, and ```number2 = 20```. During the validating logic,we have to add these up, so what we do is ```sum = number1 + number2```. 

```py
	>>> number1 = 10
	>>> number2 = 20
	>>> sum = number1 + number2
	>>> sum
	30

```

What would happen now if you call this ```sum([12,34,56])```?  

```py
	>>> sum([12,34,56])
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: 'int' object is not callable

```

The compiler says "```TypeError``` in object". It's not callable. Why is it coming up , is we are shadowing the global built-in ```sum()``` function, with a local variable of our own. 

The bad practice we're doing in here is shadowing a global function with a local variable. And that's not good. 

The way we could have avoided that is by using a different name, maybe calling it ```sum_of_two_numbers```, or even `	``sum_```. This would prevent us from shadowing some built-in function. 

```py
	>>> sum_ = number1 + number2
	>>> del sum
	>>> sum
	<built-in function sum>
	>>> sum([12,34,56])
	102

```


#### Summary

The best practice is to avoid having variables named with the same names as a building function.

### Tip 3 - Python is Strongly Typed and Dynamic Language

In this step, we look at important concept about Python, that it is **strongly typed**, but is also a **dynamically typed** language. 

What is the strongly typed property of Python? Let's say a variable ```a``` has a value, so ```a = 1``` .  Can I do a ```len(1)``` ? Nope, it's not allowed, because the type of ```a``` does not allow it. What is the ```type(1)```? It is the type of ```a``` here, which is ```int```. On an ```int```, an operation called ```len()``` is not really defined.

```py
	>>> a = 1
	>>> len(1)
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: object of type 'int' has no len()
	>>> type(a)
	<class 'int'>

```

Now consider the variable ```str```, that has the text ```'Value'``` stored inside it. On this variable , we would be able to say ```str.upper()```, and this would print ```'VALUE'```.

```py
	>>> str = "Value"
	>>> str.upper()
	'VALUE'
```

 Will I be able to do ```a.upper()```, in a similar fashion? In ```a```, a method called ```upper()``` is not really defined. In Python, as we have already seen, everything is an object. 
```py
	>>> a.upper()
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	AttributeError: 'int' object has no attribute 'upper'

```

Even Consider  ```type(1)```, it's always ```int```. ```1.5``` is always  a ```float```, ```'value'``` was, ans is, a ```str```. 

```py
	>>> type(1)
	<class 'int'>
	>>> type(1.5)
	<class 'float'>
	>>> type("1.5")
	<class 'str'>

```

What about ```boolean``` values?  It's ```bool```. So everything that you see in a Python program, including methods and the data values, are instances of some ```class```. 

```py
	>>> type(True)
	<class 'bool'>
	>>> type(str)
	<class 'str'>

```


The two important things we have learned over here are:

* Python is strongly typed. You cannot do anything that is not allowed by a specific type on an instance of that specific type. And if you do, so you would get an error. 
* The second thing which we looked at, was the fact that everything in Python is an object. 

The other important concept over here is, we have ```str``` binding to ```'value'```. What is the value of ```type(str)``` right now? It's a ```str```, a string.

However one can always say in Python, ```str = 1```, that is reassign ```str``` with ```1``` . 

What would be the ```type(str)``` now? it's of a type ```int```. 

Type of the ```str``` can change during the run-time of the program.

```py
	>>> str = 1
	>>> type(str)
	<class 'int'>

```

It can be now a ```boolean```, or and you can assign a ```list``` to it as well. 
```py
	>>> str = True
	>>> type(str)
	<class 'bool'>

```

What is ```type(str)``` right now? The type is ```list```. 

```py
	>>> str = [1,2]
	>>> type(str)
	<class 'list'>

```

### Step 79: Tip-6 - PEP8 Python Style Guide

In this quick step, we'll talk about **PEP 8**. PEP stands for Python Enhancement Proposal, and PEP 8 Is the style guide for Python programs. If you search on Google for PEP 8, you'll land up on with this document, and you can see it's quite old. This was actually created in 2001, and the awesome thing is, it lays down all the guidelines on how you can write good Python code. 

An important thing we love about Python, is the fact that it is very practical, and has a variety of resources surrounding it. While defining this style guide, one of the PEP 8 statements says: "Do not follow the PEP blindly. Think about it, and then follow the guidelines". Guidelines may not be applicable to 100% of the code scenarios. Make sure that you're using your judgment in the best way. 

What are the different things that are discussed in this style guide? 

You can find it out here - https://www.python.org/dev/peps/pep-0008/

#### Summary

As you get better with Python, spend more time with PEP8, so that you get a better understanding of good coding practices.

### Step 80: Tip-7 - PEP20 Zen Of Python

In this quick tip, we look at **PEP 20**. 

It's also popularly called the "**Zen of Python**". This document was created way back in 2004.

The Zen Of Python says: "Beautiful is better than ugly", "Explicit is better than implicit" and "Simple is better than complex".

This is how you should think, when you are writing your Python code. The Zen of Python tries to explain what are the code design decisions you should take while programming.

One of the things which it focuses a lot on, is expressing clarity. Your code should be simple to read, and easy to understand. As soon as you look at a piece of code, you should be able to understand what it is doing. You can see a phrase saying "Readability counts", and "Flat is better than nested". 

If you have a lot of nested structure, the code is inherently difficult to understand. Rather than that approach, having a flat structure is considered to be better. 

Making sure that what you are writing is explicit or clear to look at, is much more important than being implicit, because it makes code obscure. 

"Never hide errors". If there's an error,and it can be handled, don't try to suppress it. Make sure that you are trying to handle it, and that there is enough information for someone to look at, to handle at a later point in time. 

PEP 20 also says "Keep the implementation easy to explain". 

If you are lazy like us, and you don't want to go to Internet to read the Zen Of Python, all that you need to do is import this document, and this would print The Zen Of Python on your computer. 


```py
>>> import this
The Zen of Python, by Tim Peters
Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
>>> 
	
```

As a beginning programmer, a lot of these might not really make sense. 

This is a document we would recommend you to visit, every once in a while to gain some insights. As you work and write more code, you will see that most of these start making sense. 

An important thing to realize, is that the basic idea behind all these 19 principles is very simple. Whatever code you write, should be understandable for other programmers.

## Chapter 09 - Introducing Object Oriented Programming

Welcome to section on object oriented programming. The way you think in structured or procedural programming, is completely different from how you would think in **object oriented programming**, or **OOP**. In this chapter, you'll be introduced to thinking in terms of objects. We will discuss about: what is a class, what is an object, what is state, what is behavior, and also discuss about a few basic and important OOP concepts, such as encapsulation and abstraction. Of course, we will use a lot of examples to discuss these aspects of OOP, and the different terminology which is used with respect to the same. We are excited to bring this section to you.

### Step 01: OOP - The Basics

Object oriented programming is all about thinking in terms of objects. Before we get into depth with this, we'll talk a little bit about structured programming. 

If you have written programs in a language such as C or Pascal, you'd be doing *procedural* or *structured* programming. Such programming involves thinking in terms of procedures. These are also popularly known as methods or functions. 

Let's say you have a problem to solve. The first thing you would try and do, is to split the problem into multiple functions, or multiple procedures. You would start thinking in terms of: OK, what are the functions I would need to write? What are the different steps involved in doing this? 

Humans think in a step by step process.

Let's say I've to take a flight from London to New York. This is how I would think:

- Take a cab to London Airport
- Check in
- Pass Security
- Board the flight
- Wish the Hostess
- Take Off
- Cruise
- Land
- Get off the plane
- Take a cab to ..

Procedural programming is just a reflection of this thought process. A procedural program for above process would look something like this:

```java
takeACabToLondonAirport();
checkIn();
passSecurity();
boardPlane();
wishHostess();
takeOff();
cruiseMode();
land();
getOffPlane();
//...
```

Object Oriented Programming (OOP) brings in a new thought process around this. 

How about thinking in terms of the different Actors? How about storing data related to each actor right beside itself? How about giving them some responsiblity and let them do their own actions?

Here's how our program would look like when we think in terms of different actors and give them data and responsibilities

```java

    Person
    	name
    	boardFlight(Plane flight), wishHostess (Hostess hostess), getOffFlight(Plane flight)

    AirPlane
    	altitude, pilot, speed, flightMode
		takeOff(), cruiseMode(), land()

    Hostess
    	welcome()
```

Do not worry about the implementation details. Focus on the difference in approaches.

We have **encapsulated** data and methods into these entities, which are now called **objects**. We have defined object boundaries, and what it can (and cannot) do. 

An object has
* **State** : Its data
* **Behavior** : Its operations

The ```position``` of an ```Airplane``` can change over time. The operations that can be performed on an ```Airplane``` include ```takeOff()```, ```land()``` and ```cruiseMode()```. Each of these actions can change its ```position```. Therefore, an object's behavior can affects its own state.

It's now time to introduce you to some core **OOP** terms, which will make our future discussions easier.

### Step 02 - OOP Terminology 

Let's visit and enhance  the ```Planet``` example we had written a few sections ago. This time, let's also explore the conceptual angle.

**_Planet_**

```java

	class Planet
		name, location, distanceFromSun // data / state / fields
		rotate(), revolve() // actions / behavior / methods

	earth : new Planet
	venus : new Planet

```

Let's look at some **OOP** terminology.

A **class** is a template. An **object** is an instance of a class. In above example, `Planet` is a class. `earth` and `venus` are objects.
* ```name```, ```location``` and ```distanceFromSun``` compose object state.
* ```rotate()``` and ```revolve()``` define object's behavior.

**Fields** are the elements that make up the object state. Object behavior is implemented through **Methods**.

Each Planet has its own state:
* ```name```: "Earth", "Venus"
* ```location``` : Each has its own orbit
* ```distanceFromSun``` : They are at unique, different distances from the sun

Each has its own unique behavior:
* ```rotate()``` : They rotate at different rates (and in fact, different directions!)
* ```revolve()``` : They revolve round the sun in different orbits, at different speeds

#### Summary

In this step, we:

* Understood how OOP is different from Prodedural Programming
* Learned about a few basic OOP terms

### Step 03: Programming Exercise PE-01

#### Exercises

In each of the following systems, identify the basic entities involved, and organize them using object oriented terminology:

1. Online Shopping System
2. Person

#### Solution-1: Online Shopping System
	
```java

	Customer
		name, address
		login(), logout(), selectProduct(Product)

```

```java

	ShoppingCart
		items
		addItem(), removeItem()

```

```java

	Product
		name, price, quantityAvailable
		order(), changePrice()

```

#### Solution-2: Person

```java

	Person
		name, address, hobbies, work
		walk(), run(), sleep(), eat(), drink()

```

### Step 04: Classes And Objects

 After hearing a lot of theory about OOP, it's time to get our hands dirty.

Let's get started, with trying to create a ```class``` in Python. 

The syntax is very simple. Let's say you want to create a ```Country``` ```class```, ```class Country```. For now, you don't want to do anything in this class, so we'll say **```pass```**. 

```pass``` helps us to create an empty ```class```. ```pass``` can also be used to create an empty method. ```class``` is the key word and colon is part of the syntax. ```Country``` is the name of the ```class```. 

```py
	>>> class Country: 
	...     pass
	... 

```

```class``` acts as a template. It's a blueprint, and based on this blueprint, we can create instances of the ```class```. 

How can we create instances of class in Python? 

```india``` is the name of the instance, and ```Country``` is the name of the class.

```py
	>>> india = Country()
	>>> usa = Country()
	>>> netherlands = Country()

```
These instances are also called objects. We have created three objects of the ```Country``` ```class```. 

Each of these objects have their own state. Right now, the class does not provide any data elements, the state of these objects is empty. 

Let's add a little bit of state to these objects. How can you add state? By creating attributes. 

Let's use : ```india.name``` = '```India```'. We can also say ```india.capital``` =  '```New Delhi```'. 

```py
	>>> india.name = 'India'
	>>> india.capital = 'New Delhi'

```

What is the state of the ```india``` object? 

It has the name of '```India```', the capital of '```New Delhi```'. 

However the state of ```usa```, and ```netherlands``` are still empty. 

Let's create some state for them as well. 

```py
	>>> usa.name = 'USA'
	>>> usa.capital = 'Washington'
	>>> netherlands.name = 'Netherlands'
	>>> netherlands.capital = 'Amsterdam'

```

Now we have state in each of these objects. 

Each of these objects have their own individual state. When we are changing the state of ```netherlands```, or the state of ```usa```, the state of ```india``` does not change.

```py
	>>> india.name
	'India'

```

### Step 05: The ```MotorBike``` Class Example

In this step, Let's create a `class` in the IDE. We want to call the class as ```Motorbike```. We create a few instances of the specific ```class```. 

How can we define a class? 

How do we create instances of the class? 
You just need to say ```honda``` = ```MotorBike()``` ,  ```ducati``` = ```MotorBike()```.

We'll go ahead, and print these objects, ```print(honda)``` and ```print(ducati)```. 

Let's see what would happen when we run this code. 
```py
class MotorBike:pass

honda = MotorBike()
ducati = MotorBike()	

print(honda)
print(ducati)

```  

Output
```
<__main__.MotorBike object at 0x7fbceddd41d0>
<__main__.MotorBike object at 0x7fbceddd4278>
```

You can see that two objects are being printed. 

We can also add a little bit of state to these motor bikes. 

```py
class MotorBike:pass

honda = MotorBike()
ducati = MotorBike()	
honda.speed = 50
ducati.speed = 250

print(honda)
print(ducati)

print(honda.speed)
print(ducati.speed)

```

Output
```
<__main__.MotorBike object at 0x7fbceddd41d0>
<__main__.MotorBike object at 0x7fbceddd4278>
50
250
```

The state of an object can change during the lifetime of the object. 


#### Time for an Exercise : Book class

Create a new class called ```Book```. Create three instances of ```Book```. Have you favorite books as the name of the object instances, let each of these instances have an attribute ```name```, and set the name of the book into that object. At the end, print the name of all three instances of the books.

Here's the solution:

```py
class Book: pass

the_art_of_computer_programming = Book()
learning_python = Book()
learning_restful_services = Book()

the_art_of_computer_programming.name = 'The Art of Computer Programming'
learning_python.name = 'Learning Python'
learning_restful_services.name =  'Learning Restful Services In 50 Steps'

print(the_art_of_computer_programming.name)
print(learning_python.name)
print(learning_restful_services.name)

```


The initial versions of the ```MotorBike``` and the ```Book``` class we are creating here, are quite basic. 

During the course of this section, will enhance these two classes to be having more functionality.


### Step 06: Class And Objects: Puzzles

In this quick step, we will look at a few puzzles related to what we have learned about: classes and objects. 

Let's create a new class, and call it ```class Planet```, and we'll have it as an empty class. 
```py
	>>> class Planet: pass
	... 	

```

How do you create instances of the ```Planet``` class? 

```py
	>>> earth = Planet()
```

You cannot do a `new Planet()` - like in Java, for example.

```py
	>>> earth = new Planet()
	  File "<stdin>", line 1
	    earth = new Planet()
	                     ^
	SyntaxError: invalid syntax

```

We have just created an instance called earth. So what would happen now if we say ```earth.name```?  The compiler says: '```Planet``` object has no attribute ```name```'. 

```py
	>>> earth.name
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	AttributeError: 'Planet' object has no attribute 'name'
```

Let's set ```earth.name = 'The Earth'```. now if we ```print(earth.name)``` what would happen? 

```py
	>>> earth.name = 'The Earth'
	>>> earth.name
	'The Earth'

```

It prints ```'The Earth'```. 

Now let's create a new instance of the ```Planet```. Let's call this ```venus```. What happens if we do ```venus.name```? It does not have an attribute ```name```. 
```py
	>>> venus = Planet()
	>>> venus.name
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	AttributeError: 'Planet' object has no attribute 'name'
```

An important thing to note is, each object has its own data, its own attributes. The fact we have set attributes on ```earth```, does not mean the same attributes would exist on ```venus```. 

What we need to do, is set the name for ```venus``` as well. Now, You'd be able to use ```venus.name```. 
```py
	>>> venus.name = 'Venus'
	>>> venus.name
	'Venus'

```


The last thing we will be looking at, is the behavior. What would happen if we call a non-existent method? 

```py
	>>> venus.do_something()
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	AttributeError: 'Planet' object has no attribute 'do_something'

```

An interesting thing to note is that Python considers **methods**, as well as **data**, as **attributes**. In Python, you can add attributes dynamically. During the run-time of the program, you can add new data and methods, as attributes as well.


### Step 07: A Constructor For The ```MotorBike``` Class

How to set an initial state for an object when it is being created?

That's where a **constructor** comes into picture. 

In this step, we will define a constructor for the ```MotorBike``` ```class```. 

How do you define a constructor for a ```MotorBike``` class? Once we decide to have a constructor, this cannot be an empty ```class``` anymore. We'll remove ```pass``` and define a method. 

```
class MotorBike:
    def __init__(self):
        print("MotorBike instance created")

honda = MotorBike()
ducati = MotorBike()	

```

A constructor is a special method. Syntax is ```def __init__(self)``` . 

For all the instance methods in a class,  you need to pass in an attribute called ```self```. We'll talk about a few puzzles related to ```self``` a little later. For now, it's important that you follow this exact syntax. 

When a ```MotorBike``` object is created, we might want to print a message. We can say ```print("MotorBike instance created")```. 

```
MotorBike instance created
MotorBike instance created
```

```'MotorBike instance created'``` is printed twice - once for each instance created, ```honda``` and ```ducati```. 

Typically we do not use constructors to print statements. We use them to initialize data. 

We want to set initial speed for `honda` and `ducati`.

```
honda = MotorBike(50)
ducati = MotorBike(250)
```

We can add `speed` as a parameter to the constructor. 

Here's the syntax - ```def __init__(self, speed)```

```
class MotorBike:
    def __init__(self, speed):
        print(speed)

honda = MotorBike(50)
ducati = MotorBike(250)	

```

Output
```
50
250
```

How can we set the value into an instance of the object?  

```self.speed = speed``` where ```self.speed``` represents a ```speed``` attribute of the ```MotorBike``` instance. On the current object we would want to set an attribute called ```speed```, with the value that is passed to this parameter.

```py
class MotorBike:
    def __init__(self, speed):
        self.speed = speed 

honda = MotorBike(50)
ducati = MotorBike(250)

print(honda.speed)
print(ducati.speed)

```

If we print the ```speed``` values of ```honda``` and ```ducati```, we get the following: ```honda.speed``` is ```50```, and ```ducati.speed``` is ```250```. 


### Step 08: A Constructor For ```Book``` Class

Let's start with an exercise. Enhance the book class to have a constructor to enable create Book with a name - ```Book('Learning Python In 100 Steps')``` 

```py
class Book:
	def __init__(self, name):
	    self.name = name

	learning_python = Book('Learning Python In 100 Steps')
	print(learning_python.name);

```


### Step 09: Constructors - Puzzles

In this step, let's look at a few puzzles related to constructors. 

Let's create the ```Planet``` ```class``` again, this time with a constructor.  We're not passing anything in here, and also saying ```pass```, so it's an empty constructor. 

```py
	>>> class Planet:
	...    def __init__(): pass
	...

```
What would happen When we execute  ```Planet()```? 

```py
 
	>>> Planet()
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: __init__() takes 0 positional arguments but 1 was given

```


It says error! "__init__ takes 0 positional arguments, but 1 was given" 

What's happening here? 

All instance methods in a class need to have ```self``` as a parameter. 

Whenever you're creating an object, we are calling the constructor and by default, Python would pass the current instance as an argument. Even though we are not passing any arguments in here, Python would pass one secretly. If we really want to actually create the right constructor, then we would need to have ```self``` as the first parameter of the constructor method. 

```py
	>>> class Planet:
	...    def __init__(self): pass
	... 
	>>> Planet()
	<__main__.Planet object at 0x10426bc88>

```

Now, in addition to the existing constructor, we want to create another constructor, ```def __init__(self, name)```, and let's make it an empty method for now.

We're creating two constructors, one with one parameter, and the other one with two parameters. 

```py
	>>> class Planet:
	...    def __init__(self, name): pass
	...    def __init__(self): pass
	...
```

Let's create `Planet()` and `Planet("Jupiter")`.

```py
	>>> Planet()
	<__main__.Planet object at 0x10426bdd8>
	>>> Planet("Jupiter")
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: __init__() takes 1 positional argument but 2 were given

```

For `Planet("Jupiter")`, we got "TypeError: __init__() takes 1 positional argument but 2 were given". 

There are two constructors definitions but only the second one is available. 

In Python, you can only have one constructor per ```class```. 

When you define the class - whichever constructor comes last, is the one which is available.

> Exercise : Try reversing the order of constructors and creating instances

What if I would want to be able to create `Planet` instances using  `Planet()` and `Planet("Jupiter")`? Solution - default parameter values. 

You can use, ```def __init__(self, name = 'Earth')```. By default,  ```Planet```  instance has a name of ```'Earth'```.

```py
	>>> class Planet:
	...    def __init__(self, name="Earth"): pass
	... 
	>>> Planet()
	<__main__.Planet object at 0x10426beb8>
	>>> Planet("Jupiter")
	<__main__.Planet object at 0x10426bef0>

```


Let's consider the code below: a real constructor

```py
	>>> class Planet:
	...    def __init__(self, name="Earth"):
	...        self.speed = 10
	...        self.name = name
	...        self.distance_from_sun = 10000
	...

```

If we now create a new object ```earth = Planet()```, and execute ```earth.name```, what would be the value? 

```py
 
	>>> earth = Planet()
	>>> earth.name
	'Earth'
	>>> earth.speed
	10
	>>> earth.distance_from_sun
	10000

```

Typically in Python, you will have your constructor define all the properties and set initial values to them. 

Earlier we looked at naming variables. ```distance_from_sun``` is a variable. We used small case, and we use underscores to separate the words. We use the same convention, when we name methods as well. 

However, when we name classes, typically CamelCase is used. That's the reason why, when we named the class  "```MotorBike```". 

The program would work even if the class is named `motor_bike`. But, what we are talking about are conventions followed across the world of Python programming.

### Step 10: Class And Objects : Methods And Behavior

The state of an object changes with time. 

Let's say we want to increase the ```speed``` of ```honda```: ```honda.speed = honda.speed + 150```. We can also do: ```ducati.speed += 25```. We are modifying the state of the object, from outside the class.

In this step, we will talk about encapsulation, and how we can encapsulate this kind of behavior directly inside the ```class```. 

Encapsulation is one of the most important object oriented principles, that says: all the data changes should be through methods, the behavior of a ```class```. 

In the previous example, we are directly changing the value of an attribute. That is not considered to be a good practice, when it comes to object oriented programming. Ideally, the increase in ```speed``` should happen through a method call, which is defined inside the ```MotorBike``` ```class```. 

Let's look at how we could define a method, inside ```MotorBike``` ```class```. 

Note that this is at the same indentation level as the constructor. 

Let's name the method as ```increase_speed()```. For instance methods, we need to pass ```self``` as one of the parameters. 

```py
def increase_speed(self, how_much):
    self.speed += how_much

```

You can call this method on the instances, like ```honda.increase_speed(150)```. 
```py
honda.increase_speed(150)
ducati.increase_speed(25)

```

 What if you want to decrease the speed? Let's write a method called ```decrease_speed()```.

```py
def decrease_speed(self, how_much):
   self.speed -= how_much

```


Here is the full code for your reference:

```py
class MotorBike:
    def __init__(self, speed):
        self.speed = speed #State

    def increase_speed(self, how_much):
        self.speed += how_much

    def decrease_speed(self, how_much):
        self.speed -= how_much

honda = MotorBike(50)
ducati = MotorBike(250)
print(honda)
print(ducati)

honda.increase_speed(150)
ducati.increase_speed(25)
honda.decrease_speed(50)

ducati.decrease_speed(25)
honda.decrease_speed(350)
print(honda.speed)
print(ducati.speed)

honda.speed = 150
print(honda.speed)
print(ducati.speed)

```  

### Step 11: Exercise - ```EnhancedBook``` Class With Copies

Let's start with an exercise.

Enhance the ```Book``` class we created, to have a new property called ```copies```, which says how many copies of the book are available. Have a method to **increase** the copies, and one to **decrease** the copies as well. The other thing is to have ```copies``` has a constructor argument.

In the constructor, we'll set the default values of ```copies``` to ```0```. 
```py
def __init__(self, name, copies=0):
	    self.name = name
	    self.copies = copies

```

We want to have a method called ```increase_copies()```, which we define and call it as ```learning_python.increase_copies()```. 

```py
def increase_copies(self, how_much):
	    self.copies += how_much
	
```

We also want a method to decrease the ```copies```, to be used as ```learning_python.decrease_copies()```.

```py
def decrease_copies(self, how_much):
	    self.copies -= how_much

```


This is how you can use all the methods we created earlier

```py
learning_python = Book('Learning Python in 100 Steps', 100)

learning_python.increase_copies(25)
learning_python.decrease_copies(10)

```

Here is the code in full, for your perusal:

```py
class Book:
	def __init__(self, name, copies=0):
	    self.name = name
	    self.copies = copies

	def increase_copies(self, how_much):
	    self.copies += how_much

	def decrease_copies(self, how_much):
	    self.copies -= how_much

the_art_of_computer_programming = Book('The Art of Computer Programming')
learning_python = Book('Learning Python in 100 Steps', 100)
learning_restful_services = Book('Learning RestFul Service in 50 Steps')

print(the_art_of_computer_programming.name)
print(learning_python.name)
print(learning_restful_services.name)

learning_python.increase_copies(25)
learning_python.decrease_copies(10)
learning_python.copies = 50

print(learning_python.copies)

```

### Step 12: Methods And Behavior - Puzzles On ```self```

In this step, let's look at a few puzzles related to behavior, or the methods we create on a ```class```. Let's get back to our favorite ```Planet``` ```class```, and this time, let's create a method. 

Consider the steps below. What would be the result of `earth.revolve()`?

```py
	>>> class Planet:
	...    def revolve(): pass
	... 
	>>> earth = Planet()
	>>> earth.revolve()
```

Here's the result

```py

	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: revolve() takes 0 positional arguments but 1 was given'

```

Remember ```self```. When we call a method on an instance of a ```class```, one parameter automatically gets passed, that's ```self```. We saw that when we were invoking the constructor. The same is the case with all the methods inside a class. So on all of the instance methods, you'd need to create a parameter called ```self```.

Let's look at this code:

```py
class Planet(object):
    def rotate(self):
        print("rotate")

    def revolve(self):
        print("revolve")

```

We want to create a method inside `Planet` to call both `rotate` and `revolve` methods.

```py
    def rotate_and_revolve(self):
        rotate()
        revolve()
```

Will this work? No.

You need to use `self`.

```py
    def rotate_and_revolve(self):
        self.rotate()
        self.revolve()
```

You need to have ```self``` to call a method on the same object - ```self.<specific-method>()```.

```py
earth = Planet()
earth.rotate_and_revolve()
```

### Step 13: Advantages Of Encapsulation

An important question that a number of people ask about encapsulation, is do we really need it? 

In this small step, We'll give you an example of why we need encapsulation. 

What we have with the ```MotorBike``` ```class```, are methods to increase speed and decrease speed.

```py
class MotorBike:
    def __init__(self, speed):
        self.speed = speed #State

    def increase_speed(self, how_much):
        self.speed += how_much

    def decrease_speed(self, how_much):
        self.speed -= how_much

honda = MotorBike(50)
honda.decrease_speed(350)

print(honda.speed)

```  

Consider above snippet. Should ```honda.decrease_speed(350)``` be allowed? The initial speed of ```honda``` is ```50```, and by saying decrease speed by ```350```, it becomes ```-300```. Negative Speed. 

How do we prevent it?

To prevent it from happening, you can enhance `decrease_speed` method.

```py
    def decrease_speed(self, how_much):
        if(self.speed-how_much>0):
            self.speed -= how_much
        else:
            print("Get a life")

```

If you use behavior to change the state of the object, then you can add additional logic, such as validation, at a later point in time. 

That's one of the reasons why encapsulation is good.

### Step 14: Everything Is ```object``` In Python

In Python, everything is an object. What do we mean by 'everything is an object'? 

Let's check type of some values. They all are instances of some `class`.

```py
	>>> 5
	5
	>>> type(5)
	<class 'int'>
	>>> type(True)
	<class 'bool'>
	>>> type('Hello')
	<class 'str'>
	>>> type(5.5)
	<class 'float'>

```

You can call methods on these values as well.

```py
	>>> 'Hello'.upper()
	'HELLO'

```

This is possible because everything in Python is an object of some class!


The interesting part comes when we talk about methods. We have created methods earlier. Let's say ```def do_something()```, an empty method.If you type in ```do_something()``` on the prompt, it says: 'function ```do_something``` at <specific-address>'.  a method is also an object. 

```py
	>>> def do_something(): pass
	... 
	>>> do_something
	<function do_something at 0x104275488>

```


You can actually define a method ```do_something()```, let's say ```print('something')``` . ```do_something``` points to a new address. 

```py
	>>> def do_something():
	...    print("something")
	... 
	>>> do_something
	<function do_something at 0x104275510>
	>>> do_something()
	something

```

Let's try ```test =  do_something```. 


```py
	>>> test = do_something
	>>> test
	<function do_something at 0x104275510>
	>>> test()
	something
	>>> 

```

`test` refers to the same function and you can run it using `test()`.


This is possible, because even a function is an object in Python. 

#### Summary

The most important thing to understand from this step, is in Python, everything is an object. The constant values that you create are objects of specific classes, and methods are objects as well.

## Chapter 10 : Python Data Structures

Welcome to this section on data structures in Python. Here, we'll discuss why we need data structures, and what are the important in-built data structures that Python provides.

### Step 01: Why We Need Data Structures

In this step, let's focus on the first question: "why do we need data structures?" 

Suppose we have multiple values to store, like marks of different students in a course. 
Let's say these are as follows: 
* first student: ```mark1``` is ```45``` 
* second student: ```mark2``` is ```54```.(These are quite average students, maybe like me!) 
* and third student: ```mark3``` is say, ```80```. This guy is a very good student. 


Let's assume the professor asked: "What's the sum, and what is the average?".

```py
	>>> mark1 = 45
	>>> mark2 = 54
	>>> mark3 = 80
	>>> mark1 + mark2 + mark3
	179
	>>> (mark1 + mark2 + mark3)/3
	59.666666666666664

```

The professor says: "There's a new student".  What?

We would need to add a new student with this mark. Not just that, the formulas for calculating sum and average will also need to be changed.

```py
	>>> mark4 = 43
	>>> (mark1 + mark2 + mark3 + mark4)/3
	74.0
	>>> (mark1 + mark2 + mark3 + mark4)/4
	55.5

```

When you have a list of marks, you'd rather store them in a specific data structure, that would allow easy manipulation. And that's where the data structures in Python are useful. 

Let's look at a specific data structure in Python, called list, and how it helps us to solve the problem. 

Creating data structures in Python is very simple. You don't need to be even aware of which ```class``` our data structure belongs to. Let's say we want to store the marks. 
```py
	>>> marks = [45, 54, 80]
```
We initialized ```marks``` with these three values.

We want to find the sum and average.

```py
	>>> sum(marks)
	179
	>>> sum(marks)/len(marks)
	59.666666666666664

```

We get a new student.

```py
	>>> marks.append(43)
	>>> sum(marks)/len(marks)
	55.5
	>>> type(marks)
	<class 'list'>

```

The code to find sum and average does not change.


### Summary

In this step, we discussed the need for data structures in Python programs.

### Step 02: Operations On List Data Structures

In this step, let's look at the ```list``` data structure. 

How do you create a list structure? 

All that do you need to do, is use the square brackets ```[]``` syntax, and put the elements you'd want to have in the list. So ```[23, 56, 67]``` is a list. 

```py
	>>> marks = [23,56,67]

```

Let's look at the basic things you can do with a list. 

We saw ```sum(marks)```. You can do ```max(marks)```, ```min(marks)```, and ```len(marks)```. All these functions are very obvious, aren't they! ```len()``` gives you how many elements are present, ```min()``` is the minimum, ```max()``` the maximum, and ```sum()``` returns the sum of the elements.

```py
	>>> sum(marks)
	146
	>>> max(marks)
	67
	>>> min(marks)
	23
	>>> len(marks)
	3

```

If you want to add more elements, you can do ```max.append(76)```.
```py
	>>> marks.append(76)
	>>> marks
	[23, 56, 67, 76]

```

If you want to add element at a specific index, you can do that as well; ```marks.insert(...)```.

Let's say you would want to insert ```60``` in between ```56``` and ```67```. You would want to insert it at index ```2```. 

Indexes in a python list start at ```0```, going through ```1```, ```2```, etc. Now if we do ```marks```, you would see that ```60``` is inserted in here. 

```py
	>>> marks.insert(2, 60)
	>>> marks
	[23, 56, 60, 67, 76]

```

You can remove a value from ```marks``` as well. All you need to do is say ```marks.remove(60)```. 
```py
	>>> marks.remove(60)

```

You can also check if a specific element is in the list or not. All that you need to do is, ```55 in marks```, which returns ```False```. ```56 in marks``` returns ```True``` . 
```py
	>>> 55 in marks
	False
	>>> 56 in marks
	True

```

Also, you can search for a specific element; you do ```marks.index(...)```.  


```py
	>>> marks.index(67)
	2
	>>> marks
	[23, 56, 67, 76]
```

Let's try ```marks.index(69)```, on a non-existing element ```69```. What does it return? It returns an error, that says: "69 is not in list". 

```py
	>>> marks.index(69)
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	ValueError: 69 is not in list

```

The next thing you can do, is loop around the elements in the list. You can use ```for mark in marks: print(mark)```.

```py
	>>> for mark in marks:
	...   print(mark)
	... 
	23
	56
	67
	76

```


#### Summary

In this step, we looked some of the basic operations that you can perform on lists. We saw operations like ```sum()```, ```max()```, ```min()```, ```len()```, appending a new element, inserting a new element, removing a specific element, checking whether the element is in the list or not. We understood how to find a specific elements in the list, and how to loop around a list. 

### Step 03: An Exercise With ```list``` Of ```Student```

In this step, let's look at an exercise using the ```list``` we created earlier. 

Create a ```Student``` ```class``` accepting a name, and a list of marks. We want to be able to perform all of these operations which are listed in here, on the ```Student``` ```class```:
* Find out how many number of marks are there, 
* Find out what the total sum of marks, 
* Determine the maximum mark, 
* Determine the minimum mark, 
* Calculate the average, 
* Add a new mark, as well as remove a mark, at a specific index.


Suppose the list is ```[23, 45, 56, 75]```, which are his marks in different subjects. 

Let's define a constructor: 

```py
def __init__(self, name, marks):
        self.name = name
        self.marks = marks

```

We need to define the ```get_number_of_marks()``` method, next up. 

```py
def get_number_of_marks(self):
        return len(self.marks)

```


We can easily create the other methods as well.
```py
def determine_maximum_mark(self):
        return max(self.marks)

```

```py
def determine_minimum_mark(self):
        return min(self.marks)

```

There is a statistic module in Python, which helps us with the average, but let's keep things simple and directly use the methods we already have in here. 

```py
def determine_average(self):
        return self.get_total_sum_of_marks()/self.get_number_of_marks()

```

The next one we would want to define is ```add_number_of_marks()```. How would you add a mark? We need a parameter, say ```new_mark```. 

```py
    def add_new_mark(self, new_mark):
        self.marks.append(new_mark)

```

The last function we have, is ```remove_mark_at_index(5)```. The method which we looked at earlier, ```remove()```, will only remove a specific value, and cannot be used to specify the element index. 

```py
    def remove_mark_at_index(self, index):
        del self.marks[index]

```

The code to do what we need, would be: ```del self.marks[index]``` .

We'll print out these values one by one to complete the program functionality. 

One of the features you can make use of to print strings that have content split over distinct lines, is to use the triple quote ```"""```. 

```py
print(f"""Student[
    number_of_marks-{number} 
    sum_of_marks-{sum_of_marks}
    max-{maximum_mark} 
    min-{minimum_mark} 
    avg-{average} ] """)

```

What it allows us to do, is split the console output of the string into multiple lines. 

Here is the code for your reference:

```py
class Student:

    def __init__(self, name, marks):
        self.name = name
        self.marks = marks

    def get_number_of_marks(self):
        return len(self.marks)

    def get_total_sum_of_marks(self):
        return sum(self.marks)

    def determine_maximum_mark(self):
        return max(self.marks)

    def determine_minimum_mark(self):
        return min(self.marks)

    def determine_average(self):
        return self.get_total_sum_of_marks()/self.get_number_of_marks()

    def add_new_mark(self, new_mark):
        self.marks.append(new_mark)

    def remove_mark_at_index(self, index):
        del self.marks[index]

student = Student ("Ranga", [23, 45, 56, 75])
number = student.get_number_of_marks()

sum_of_marks = student.get_total_sum_of_marks()
maximum_mark = student.determine_maximum_mark()
minimum_mark = student.determine_minimum_mark()
average = student.determine_average()

student.add_new_mark(35)
student.remove_mark_at_index(2)

print(student.marks)

print(f"""Student[
    number_of_marks-{number} 
    sum_of_marks-{sum_of_marks}
    max-{maximum_mark} 
    min-{minimum_mark} 
    avg-{average} ] """)
	
```

Output
```
[23, 45, 75, 35]
Student[
    number_of_marks-4 
    sum_of_marks-199
    max-75 
    min-23 
    avg-49.75 ] 
```

#### Summary

In this step, we explored an exercise on how to call methods on a list, to do basic arithmetic on its elements. We computed values such as number fo elements, sum, minimum, maximum, average. We also showed you how to add a new element to, or delete an existing element from, the list.

### Step 04: Puzzles With ```list``` Of Strings

In this step, we will look at a few puzzles to help us understand lists even better. 


Let's create a simple list.


```py
	>>> animals = ['Cat', 'Dog','Elephant']
	>>> len(animals)
	3
```
	
What would ```sum(animals)``` give? 
```py
	>>> sum(animals)
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: unsupported operand type(s) for +: 'int' and 'str'

```
Error, obviously! Because ```sum()``` is not defined on a `str`. 

Here are other basic list operations on `str`.

```py
	>>> animals.append('Fish')
	>>> animals
	['Cat', 'Dog', 'Elephant', 'Fish']
	>>> animals.remove('Dog')
	>>> animals
	['Cat', 'Elephant', 'Fish']

```


You can use index to access elements from list. 

```animals[2]``` will print  ```'Fish'``` , much to your surprise!

This is exactly the kind of the array-indexing, we use in C or Java programming. ```animals[1]``` returns ```'Elephant'```, and ```animals[0]``` gives you ```'Cat'``` . But make sure you actually use an accurate index, because if you do things like ```animals[4]```, the compiler would throw an ```IndexError```. 

```py
	>>> animals
	['Cat', 'Elephant', 'Fish']
	>>> animals[2]
	'Fish'
	>>> animals[1]
	'Elephant'
	>>> animals[0]
	'Cat'
	>>> animals[4]
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	IndexError: list index out of range

```


Let's look at difference between ```animals.remove()``` and ```del```. 

```animals.remove()``` would remove the specified value from the list.  When we do ```del animals[2]```, we are specifying the ```index```. 

If you do ```del animals[2]```, the list contents goes down to ```['Cat', 'Elephant']```. The last element which was at index 2, ```'Fish'```, got deleted. 

```py
	>>> del animals[2]
	>>> animals
	['Cat', 'Elephant']

```

Let's look at the difference between ```append()``` and ```extend()```. 

If you invoke the ```extend()``` method with ```'Fish'```, what would happen? 
```py
	>>> animals.extend('Fish')
	>>> animals
	['Cat', 'Elephant', 'F', 'i', 's', 'h']
```
You can see that individual character symbols are being added in. So, ```'F', 'i', 's', 'h'``` are added in. 

If you do ```animals.append('Fish')```, it would add an element called ```'Fish'``` to the list. 

```py
	>>> animals.append('Fish')
	>>> animals
	['Cat', 'Elephant', 'F', 'i', 's', 'h', 'Fish']
```

```animals.extend()``` is actually used to add a list of values. You can use ```['Giraffe', 'Horse']``` (if we got the spelling right!) , You can see that the elements are added in.
```py
	>>> animals.extend(['Giraffe', 'Horse'])
	>>> animals
	['Cat', 'Elephant', 'F', 'i', 's', 'h', 'Fish', 'Giraffe', 'Horse']

```

There is another way you can actually do the ```extend()```.  ```animals = animals + ['Jackal', 'Kangaroo']```. 
```py
	>>> animals = animals + ['Jackal','Kangaroo']
	>>> animals
	['Cat', 'Elephant', 'F', 'i', 's', 'h', 'Fish', 'Giraffe', 'Horse', 'Jackal', 
	'Kangaroo']

```
With a list, you can also use ```+=``` !  ```animals += ['Lion', 'Monkey']``` !

```py
	>>> animals += ['Lion','Monkey']
	>>> animals
	['Cat', 'Elephant', 'F', 'i', 's', 'h', 'Fish', 'Giraffe', 'Horse', 'Jackal', 
	'Kangaroo', 'Lion', 'Monkey']

```


In Python, is there is no restriction on what you can have in a list. 

You can easily say ```animals.append(10)```, and ```animals``` would have now include a value of ```10``` . So there is no type restrictions on the ```list```.

```py
	>>> animals.append(10)
	>>> animals
	['Cat', 'Elephant', 'F', 'i', 's', 'h', 'Fish', 'Giraffe', 'Horse', 'Jackal', 
		'Kangaroo', 'Lion', 'Monkey', 10]

```

### Step 05: List Slicing

In this step, we look at one of my favorite features in Python. It's called **List slicing**. 

It's a really powerful feature, which can help you to break lists into different kinds of values, without a lot of code. 

Let's look at what it is, with a simple example, of creating a list called ```numbers```. It has strings from ```'Zero'``` to ```'Nine'```. 

```py
	>>> numbers = ['Zero','One','Two','Three','Four','Five','Six','Seven','Eight','Nine']
```

How many elements does it have? ```len(numbers)```, or ```10```, right? You want to find out what is the second element, or what is the element at ```index``` ```2```. ```numbers[2]``` gives you ```'Two'```. The same index you used, ```2```, can be used to get a subset of elements from this list. 
```py
	>>> len(numbers)
	10
	>>> numbers[2]
	'Two'

```

How do we get elements from index ```2```, to ```6```? 

Welcome List Slicing?

Syntax is very simple. Let's try `numbers[2:6]`

```py
	>>> numbers[2:6]
	['Two', 'Three', 'Four', 'Five']

```

index `6` is exclusive. We should do `numbers[2:7]`

There are multiple ways in which you can use lists slicing. 

`numbers[:6]` doesn't have a start index. `0` is default.
```py
	>>> numbers[:6]
	['Zero', 'One', 'Two', 'Three', 'Four', 'Five']

```

`numbers[3:]` doesn't have end index. default is up to the end of the list.

```py
	>>> numbers[3:]
	['Three', 'Four', 'Five', 'Six', 'Seven', 'Eight', 'Nine']

```

Let's make it even more powerful. What we can even do, is specify we want to start from index ```1```, going up to index ```8```, but only want to get every second element. 

```py
	>>> numbers[1:8:2]
	['One', 'Three', 'Five', 'Seven']

```

How to get every third element?

```py
	>>> numbers[1:8:3]
	['One', 'Four', 'Seven']

```

```numbers[::3]```. You get ```'Zero'```. ```'Three'```, ```'Six'```, ```'Nine'```. Isn't this awesome! 

```py
	>>> numbers[::3]
	['Zero', 'Three', 'Six', 'Nine']

```

You can also use slicing to access the list in reverse order. 

So ```numbers[::-1]``` will return the list elements, but this time in the reverse order. 

```py
	>>> numbers[::-1]
	['Nine', 'Eight', 'Seven', 'Six', 'Five', 'Four', 'Three', 'Two', 'One', 'Zero']
```

When you say ```numbers[::-3]```, it starts from the end of the list, and fetches every third element from the end, backwards. 
```py
	>>> numbers[::-3]
	['Nine', 'Six', 'Three', 'Zero']

```


A lot of programmers from other languages struggle with slicing, because when they first see this syntax  ```::```, they go mad! 

What is it doing?  What's the ```:```? What is it doing all over the place? ```[1:8:2]```... Oh My God! 

Python seems like a  weird language to them. 

Once you understand slicing well, then it makes your code much simpler. 

You can use slicing to delete elements from a list. 

Let's say you want to delete all the elements starting from index ```3```. You could do ```del numbers[3:]```. 

```py
	>>> del numbers[3:]
	>>> numbers
	['Zero', 'One', 'Two']
```

Let's re-initialize the list, and try to delete numbers in the middle of the list, starting from index ```5``` to ```7```. The thing to remember, is ```7``` here is exclusive.  

```py
	>>> numbers = ['Zero','One','Two','Three','Four','Five','Six','Seven','Eight','Nine']
	>>> del numbers[5:7]

```

Another important thing that you can do with slicing, is replace the values in the list.

```py
	>>> numbers = ['Zero','One','Two','Three','Four','Five','Six','Seven','Eight','Nine']
	>>> numbers[3:7] = [3,4,5,6]
	>>> numbers
	['Zero', 'One', 'Two', 3, 4, 5, 6, 'Seven', 'Eight', 'Nine']

```

We've replaced values `'Three','Four','Five','Six'` with `3, 4, 5, 6`.

#### Summary

In this step, we looked at how you can use slicing to retrieve values from a list, delete values from a list, and update values in a list. When you're coming from other languages to Python, slicing is one of the important things that you need to understand very well.

### Step 06: ```list``` - Sorting, Looping And Reversing

We have been talking about different features of lists, in the last few steps. And there are still a few more steps to come. 

In this step, let's focus on a few simple pieces of code to **sort**, to **reverse**, and also a few other tips related to **looping** around a list, using an *index*. 

Let's get started with initializing ```numbers``` again. We allow ```numbers``` to have values from ```'Zero'``` to ```'Nine'```, so we have something to play with.
 
```py
	>>> numbers = ['Zero','One','Two','Three','Four','Five','Six','Seven','Eight','Nine']
	>>> numbers.reverse()
```

The first thing we look at, is reversing the list, by doing ```numbers.reverse()```. It reverses the existing list. ```numbers.reverse()``` is an **in-place reverse**. That means, it is modifying the existing list directly.
```py
	>>> numbers
	['Nine', 'Eight', 'Seven', 'Six', 'Five', 'Four', 'Three', 'Two', 'One', 'Zero']
	>>> numbers = ['Zero','One','Two','Three','Four','Five','Six','Seven','Eight','Nine']

```

However, if you'd want to loop through the list in a reverse direction, this is not necessary.

Let's re-initialize ```numbers``` again, so we have the original ```list``` back. If you don't want to do an in-place reverse, but only access the elements in reverse order, then you can use  ```reversed()```. ```reversed(numbers)``` would actually give you an **iterator**, that helps you access the elements in a reverse direction. 

```py
	>>> numbers
	['Zero', 'One', 'Two', 'Three', 'Four', 'Five', 'Six', 'Seven', 'Eight', 'Nine']
	>>> reversed(numbers)
	<list_reverseiterator object at 0x109560ba8>
	>>> for number in reversed(numbers):
	...    print(number)
	... 
	Nine
	Eight
	Seven
	Six
	Five
	Four
	Three
	Two
	One
	Zero

```

What is the difference between ```reverse()``` and ```reversed()```? ```reverse()``` does an in-place reverse. So, the original list gets reversed. However, when want to access the elements in reverse without changing them, we can use ```reversed()```.

Let's say we want to sort the list. ```numbers.sort()``` sorts strings in alphabetical order.

```sort()``` does an in-place sort. 
```py
	>>> numbers
	['Zero', 'One', 'Two', 'Three', 'Four', 'Five', 'Six', 'Seven', 'Eight', 'Nine']
	>>> numbers.sort()
	>>> numbers
	['Eight', 'Five', 'Four', 'Nine', 'One', 'Seven', 'Six', 'Three', 'Two', 'Zero']

```

Let's initialize ```numbers``` again. If you don't want to do an in place sort, rather just access elements in a sorted order, there is something else for it. What you can do, is use ```sorted()```. 

Iterating is simple: ```for number in sorted(numbers): print number```.

```py
	>>> numbers = ['Zero','One','Two','Three','Four','Five','Six','Seven','Eight','Nine']
	>>> for number in sorted(numbers):
	...   print(number)
	... 
	Eight
	Five
	Four
	Nine
	One
	Seven
	Six
	Three
	Two
	Zero

```

Another interesting feature in ```sorted()```, is you can pass in a key to use. 

We are passing in ```len``` , length of the string, or the number of characters present in it. We will get the elements in the increasing order of their length.
```py
	>>> numbers
	['Zero', 'One', 'Two', 'Three', 'Four', 'Five', 'Six', 'Seven', 'Eight', 'Nine']
	>>> for number in sorted(numbers, key=len):
	...   print(number)
	... 
	One
	Two
	Six
	Zero
	Four
	Five
	Nine
	Three
	Seven
	Eight

```

Another interesting feature of the ```sorted()``` method is ```reverse=True```. 

What would happen?

```py
	>>> for number in sorted(numbers, key=len, reverse=True):
	...   print(number)
	... 
	Three
	Seven
	Eight
	Zero
	Four
	Five
	Nine
	One
	Two
	Six

```

You are right, **it starts printing elements in the reverse order of the length**.

These are really powerful things that you can do with a key in here. You can also use a `Lambda Expression`. We will look at it, when we talk about functional programming.  

Instead of  ```sorted()```, we can use ```numbers.sort()``` function.

```py
	>>> numbers.sort(key=len)
	>>> numbers
	['One', 'Two', 'Six', 'Zero', 'Four', 'Five', 'Nine', 'Three', 'Seven', 'Eight']
	>>> numbers.sort(key=len, reverse=True)
	>>> numbers
	['Three', 'Seven', 'Eight', 'Zero', 'Four', 'Five', 'Nine', 'One', 'Two', 'Six']

```

#### Summary

In this step, we focused on two important features. ```sort()``` versus ```sorted()```, and ```reverse()``` versus ```reversed()```. We saw that the basic methods on the list directly does an in-place change. If you call ```numbers.sort()``` or ```numbers.reverse()```, then the original list get affected. However, ```sorted()``` and ```reversed()``` are returning iterators, which do not change the original list. We also looked at the fact we can pass in a **key** to the sorted(), indicating how we would want to sort it, what is the criteria based on how we would want to sort. And we can also pass in a parameter called **reverse**, to indicate we would want to sort in reverse order. There's a lot of stuff we learned in this specific step.

### Step 07: Using ```list``` As Stack And Queue

In this step, we look at the features which a list provides, where it can act as a **stack**, and a **queue**. 

First of all, what is a stack, and what is a  queue? 

A **stack** is typically called a **Last In, First Out** data structure. If you insert elements in the order ```1``` ```2``` ```3``` and ```4```, then to take out the elements from the stack, the first one which come out is ```4```, the next one is ```3```, Next one is ```2```, and next to one is ```1```. So it's called Last In, First Out. 

A **Queue**, as we all know, is **first in, first out**. If you insert elements in this order, to take out an element of the queue, you would get ```1``` out first. 

How can we use a list as stack, or a queue? 

Let's start with the stack. 

Let's create a simple list.

```py
	>>> numbers = []
	>>> numbers.append(1)
	>>> numbers.append(2)
	>>> numbers.append(3)
	>>> numbers.append(4)
```

 The way you can use a list as a stack is by saying ```numbers.pop()```. 
```py
	>>> numbers.pop()
	4

```
```pop()``` method retrieves the last inserted element as well as deletes it. If you look at numbers right now, ```4``` is removed from the list. 

You can look at the result of multiple `pop` operations below.
```py
	>>> numbers
	[1, 2, 3]
	>>> numbers.pop()
	3
	>>> numbers
	[1, 2]
	>>> numbers.append(10)
	>>> numbers.pop()
	10
	>>> numbers
	[1, 2]

```

How do we use it as a queue?

Let's create the list again.

```py
	>>> numbers = []
	>>> numbers.append(1)
	>>> numbers.append(2)
	>>> numbers.append(3)
	>>> numbers.append(4)

```

`numbers.pop(0)` would take the first inserted element out of the list. If you look at ```numbers```, it would only have ```[2, 3, 4]```.

```py
	>>> numbers.pop(0)
	1
	>>> numbers
	[2, 3, 4]

```

Look at few more operations below:

```py
	>>> numbers.pop(0)
	2
	>>> numbers
	[3, 4]
	>>> numbers.append(10)
	>>> numbers.pop(0)
	3
	>>> numbers.pop(0)
	4
	>>> numbers.pop(0)
	10
	>>> numbers
	[]

```


### Step 09: ```list``` With a custom ```class```

In this step, let's look at using instances of custom classes inside a list. Let's create a ```class Country```. 

```py
from operator import attrgetter

class Country:
    def __init__(self, name, population, area):
        self.name = name
        self.population = population
        self.area = area
    def __repr__(self):
        return repr((self.name,self.population,self.area))

countries = [Country('India',1200,100),
             Country('China', 1400, 200),
             Country('USA', 120, 300)]
	
```

Most of the class is self explanatory. 

```__repr__(self)``` method provides the string representation of a class. When you print an object of this class, the return value from this method is printed. 

Some of the operations you can perform are shown below:

```py
countries.append(Country('Russia',80,900))


print(countries[0]) 
print(countries[0:2])
print(countries[2:])
```

Output
```
('India', 1200, 100)
[('India', 1200, 100), ('China', 1400, 200)]
[('USA', 120, 300), ('Russia', 80, 900)]
```

#### Summary

In this step, we looked at how to create lists using custom classes in Python. In the next step, we would look at how to sort, and manipulate this list.

### Step 10: ```list``` With a custom ```class``` - Part 2

In the previous step, we created a ```Country``` ```class```, and we created a list of countries. In this step, Let's focus on trying to find the:

*  country with the maximum population 
*  country with the maximum area 
*  country with the minimum area 
*  sorted list of countries, in a specific order 

```py
from operator import attrgetter

class Country:
    def __init__(self, name, population, area):
        self.name = name
        self.population = population
        self.area = area
    def __repr__(self):
        return repr((self.name,self.population,self.area))

countries = [Country('India',1200,100),
             Country('China', 1400, 200),
             Country('USA', 120, 300)]

countries.append(Country('Russia',80,900))

```

Now what we want to do is sort countries. Can we do this, ```countries.sort()```? You get an error
```
Traceback (most recent call last):
  File "main.py", line 15, in <module>
    countries.sort()
TypeError: '<' not supported between instances of 'Country' and 'Country'
```

If the values were numbers, or strings, then Python knows how to compare them. The values in this list belong to a user-defined ```class```. How do we help Python compare one ```Country``` with another? 

Let's say we want to sort by ```population```. 

You can do it by `countries.sort(key=attrgetter('population'))`. `attrgetter` method needs to be imported in - ```from operator import attrgetter()``` . 

Output
```
[('Russia', 80, 900), ('USA', 120, 300), ('India', 1200, 100), ('China', 1400, 200)]
```
Countries are sorted in the increasing order of population. 

How can you sort them in the reverse order, in the decreasing order? 

```py
countries.sort(key=attrgetter('population'), reverse=True)

```

Output
```
[('China', 1400, 200), ('India', 1200, 100), ('USA', 120, 300), ('Russia', 80, 900)]
```

We can use ```max()```, ```min()``` and all the other stuff using the same approach. 

```py
>>> print(max(countries, key=attrgetter('population')))
('China', 1400, 200)
>>> print(min(countries, key=attrgetter('population')))
('Russia', 80, 900)
>>> print(min(countries, key=attrgetter('area')))
('India', 1200, 100)
>>> print(max(countries, key=attrgetter('area')))
('Russia', 80, 900)
```

Here's the complete program we wrote during this step.

```py
from operator import attrgetter

class Country:

    def __init__(self, name, population, area):
        self.name = name
        self.population = population
        self.area = area

    def __repr__(self):
        return repr((self.name,self.population,self.area))
countries = [Country('India',1200,100),
             Country('China', 1400, 200),
             Country('USA', 120, 300)]

countries.append(Country('Russia',80,900))

countries.sort(key=attrgetter('population'), reverse=True)
print(max(countries, key=attrgetter('population')))
print(min(countries, key=attrgetter('population')))
print(min(countries, key=attrgetter('area')))
print(max(countries, key=attrgetter('area')))

print(countries)
```

### Step 11: ```list``` Comprehension

We know we have been playing with lists a lot, and the final thing we talk about is list comprehension. 

Why do we need list comprehension? Great question. 

Let's get back to the ```numbers``` example.

We want filter elements that have length ```4```. 

Let's look at the traditional approach:

```py
	
	>>> numbers = ['Zero', 'One','Two','Three','Four','Five','Six','Seven', 'Eight','Nine']
	>>> numbers_length_four=[]
	>>> for number in numbers:
	...    if len(number)== 4:
	...      numbers_length_four.append(number)
	... 

```

Lot of code. Isn't it?

List comprehension allows you to do this in a much simpler way.

The basic syntax is ```numbers_length_four = [number for number in numbers]```. 

```py
	>>> numbers_length_four = [ number for number in numbers  ]
	>>> numbers_length_four
	['Zero', 'One', 'Two', 'Three', 'Four', 'Five', 'Six', 'Seven', 'Eight', 'Nine']

```

We are printing complete list again.

Let's try something else, say ```[len(number) for number in numbers]```. 

```py
	>>> numbers_length_four = [ len(number) for number in numbers  ]
	>>> numbers_length_four
	[4, 3, 3, 5, 4, 4, 3, 5, 5, 4]

```

Interesting. We created a list with lengths of each element.

Let's get back to the problem we wanted to solve, where we only wanted to get the ones of length 4. 

We can add an ```if``` condition between the ```[...]```: ```[number for numbers in numbers if len(number) == 4]```. 


```py
	>>> numbers_length_four = [ number for number in numbers if len(number)==4 ]
	>>> numbers_length_four
	['Zero', 'Four', 'Five', 'Nine']

```

Isn't that cool? You can see that ```numbers_length_four``` contains ```'Zero'```, ```'Four'```, ```'Five'```, ```'Nine'```.

Now let's create another list, ```values = [3, 6, 9, 1, 4, 15, ...] ```, which can have duplicates as well. so it might have ```6``` twice, even thrice. You want to create another list named ```values_even``` filtering only the even numbers.

```values_even = [value for value in values if value %2 == 0]``` will do the job for us.
```py
	>>> values = [3, 6, 9, 1, 4, 15, 6, 3]
	>>> values_even = [ value for value in values if value%2==0]
	>>> values_even
	[6, 4, 6]

```

To extract only the odd numbers instead, use the condition ```value % 2 == 1```. 
```py
	>>> values_odd = [ value for value in values if value%2==1]
	>>> values_odd
	[3, 9, 1, 15, 3]
	
```


### Step 12: Introduction To ```set```

A ```list``` can contain duplicates. So if we create a **list** ```numbers = [1, 2, 3, 2, 1]```, it is a valid ```list```. A list is more based on the index, or position of elements. So in ```numbers```, at **index** ```[0]``` is element 1, the element at **index** ```[1]``` is ```2```,and so on. A ```list``` is a *positional* data structure. You can add things at the end, or anywhere in-between.

A set, on the other hand, does not contain duplicates. 

You can create a set from a list `numbers`, by ```set(numbers)```.

```py
	>>> numbers = [1,2,3,2,1]
	>>> numbers
	[1, 2, 3, 2, 1]
	>>> numbers_set = set(numbers)
	>>> numbers_set
	{1, 2, 3}

```

You can see that the `numbers_set` is printed using `{`, `}` as delimiters. It does not have duplicates.

You can add a number to a set. Let's add an element already present in the set. No change. No duplicates.

```py
	>>> numbers_set.add(3)
	>>> numbers_set
	{1, 2, 3}

```

If we add a fresh element , it would be added to the set.
```py
	>>> numbers_set.add(4)
	>>> numbers_set
	{1, 2, 3, 4}
	>>> numbers_set.add(0)
	>>> numbers_set
	{0, 1, 2, 3, 4}

```

When you do ```numbers_set.remove(0)```,  ```0``` is deleted. 
```py
	>>> numbers_set.remove(0)
	>>> numbers_set
	{1, 2, 3, 4}

```


Set does not support access using index. So you cannot say  ```numbers_set[0]``` and try to access the first element in the set. 

```py
	>>> numbers_set[0]
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: 'set' object does not support indexing
```

You can check if an element is in a set, or not. You can use ```1 in numbers_set```, to get a boolean result.
```py
	>>> 1 in numbers_set
	True
	>>> 5 in numbers_set	
	False

```

You can do aggregate operations - `min`, `max`, `sum` and `len`.

```py
	>>> min(numbers_set)
	1
	>>> max(numbers_set)
	4
	>>> sum(numbers_set)
	10
	>>> len(numbers_set)
	4

```


In a set, you can perform operations like **intersection, union and disjoint**. 

Let's create a new set ```numbers_1_to_5_set```, to hold the set `{1, 2, 3, 4, 5}`. We want to have a set ```numbers_4_to_10_set``` to have the set ```{4, 5, 6, 7, 8, 9, 10}```.

```py
	>>> numbers_1_to_5_set = set(range(1,6))
	>>> numbers_1_to_5_set
	{1, 2, 3, 4, 5}
	>>> numbers_4_to_10_set = set(range(4,11))
	>>> numbers_4_to_10_set
	{4, 5, 6, 7, 8, 9, 10}

```

Now, if you do ```numbers_1_to_5_set + numbers_4_to_10_set```, what would happen? 
```py
	>>> numbers_1_to_5_set + numbers_4_to_10_set
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: unsupported operand type(s) for +: 'set' and 'set'
```
It says 'unsupported operation'. 

Union can be done using `|`. The union of two sets combines the set elements, and finds the unique ones among them. So it returns ```{1, 2, 3, 4, 5, 6, 9, 10}```. 

```py
	>>> numbers_1_to_5_set | numbers_4_to_10_set
	{1, 2, 3, 4, 5, 6, 7, 8, 9, 10}

```


Intersection is doing using the '```&```' operator. It returns elements which are present in both these sets, ```{4, 5}```.
```py
	>>> numbers_1_to_5_set & numbers_4_to_10_set
	{4, 5}

```

The other operation you can do is subtraction represented by ```-```. This would return the elements in first set, but not present in the second set.

```py
	>>> numbers_1_to_5_set - numbers_4_to_10_set
	{1, 2, 3}

	>>> numbers_4_to_10_set - numbers_1_to_5_set
	{6, 7, 8, 9, 10}

```

### Step 13: Introduction To ```dict```

In this step, let's look at dictionary - represented by the ```class``` ```dict```. Dictionary represent key-value pairs.

Let's say we have a sentence, and we would want to find out how many times each character occurred in that sentence. In those kind of situations, you can use a dictionary. Suppose ```'a'``` occurred ```10``` times, ```'b'``` occurred ```15``` times, ```'c'``` occurred' ```25``` times. If you are familiar with Java, then this is like a ```HashMap```, where it stores a key and its value. The key can be any object, and the value can be any object as well. 

Let's create a dictionary. Syntax is ```occurrances = dict(a=5, b=6, c=8)```.

```py
	>>> occurances = dict(a=5,b=6,c=8)
	>>> occurances
	{'a': 5, 'b': 6, 'c': 8}
	>>> type(occurances)
	<class 'dict'>

```

A dictionary allows us to access values, using a key, something like ```occurrences['d'] = 15```.  

```py
	>>> occurances['d'] = 15
	>>> occurances
	{'a': 5, 'b': 6, 'c': 8, 'd': 15}
	>>> occurances['d'] = 10
	>>> occurances
	{'a': 5, 'b': 6, 'c': 8, 'd': 10}

```

In a list, the index used was a number. However, in a dictionary, the index can be anything. It can be any object, and over here, we are using a string. 

You can also print the value of ```occurrences['d']```. 
```py
	>>> occurances['d']
	10
```

You should be cautious when using the approach. If the key does not exist, you get a ```KeyError```.
	
```py
	>>> occurances['e']
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	KeyError: 'e'

```

A better way, without throwing an exception, would be ```get()```. 
```py
	>>> occurances.get('d')
	10
	>>> occurances.get('e')

```

You can use ```occurrances.get('e', 10)``` to provide a default value. If key `e` is not present, it returns `10` back.

```py
	>>> occurances.get('e', 10)
	10
```

There are a number of useful methods which are present in a dictionary. Let's look at some of them. 

```py
	>>> occurances
	{'a': 5, 'b': 6, 'c': 8, 'd': 10}
	>>> occurances.keys()
	dict_keys(['a', 'b', 'c', 'd'])
	>>> occurances.values()
	dict_values([5, 6, 8, 10])

```

```occurrances.items()``` returns the key-value pairs,  in the format of a **tuple**. Each tuple has key as the first element, and value as the second element. You can loop around all the items, by using this way. 
```py
	>>> occurances.items()
	dict_items([('a', 5), ('b', 6), ('c', 8), ('d', 10)])
	>>> for (key,value) in occurances.items():
	...    print(f"{key} {value}")
	... 
	a 5
	b 6
	c 8
	d 10

```

You can also delete a specific key - `del occurances['a']`. 

```py
	>>> occurances
	{'a': 0, 'b': 6, 'c': 8, 'd': 10}
	>>> del occurances['a']
	>>> occurances
	{'b': 6, 'c': 8, 'd': 10}

```

### Step 14: An Exercise With ```dict```

In this step, let's do a simple exercise with a dictionary. We have a simple string for  you here:

```"This is an awesome question. This has never happened before This is your first time learning Python. Hopefully this has never happened before."``` 

With this string, we want to do two things:

* Compute how many times has each word is present in the string. 
* Find out how many times each character is present in this string. 

#### Solution 1

```py
str = "This is an awesome occasion. This has never happened before."
# key:value
char_occurances = {} #[]
for char in str:
    char_occurances[char] = char_occurances.get(char, 0) + 1
print(char_occurances)

``` 

Output
```py
{'T': 2, 'h': 4, 'i': 4, 's': 6, ' ': 9, 'a': 5, 'n': 4, 'w': 1, 'e': 8, 'o': 4, 'm': 1, 'c': 2, '.': 2, 'v': 1, 'r': 2, 'p': 2, 'd': 1, 'b': 1, 'f': 1}
```

What this does is
*  It checks the ```char_occurrances``` to see how many times ```char``` is present.
*  If it's not present, then return ```0```. 
*  The first time you find ```char```, the value which would be set to ```0 + 1```, or ```1```. 
*  The second time you'll find the character, you'll have ```1``` in the dictionary, add ```1``` to it, and store and return a ```2```. 

#### Solution 2

```py
str = "This is an awesome occasion. This has never happened before."

word_occurances = {} #[]

for word in str.split():
    word_occurances[word] = word_occurances.get(word, 0) + 1
print(word_occurances)

```
Output
```py
{'This': 2, 'is': 1, 'an': 1, 'awesome': 1, 'occasion.': 1, 'has': 1, 'never': 1, 'happened': 1, 'before.': 1}
```
### Step 15: Puzzles With Data Structures


In this step on data structures, we look at a number of puzzles related to set, lists and dictionary. 

We want to create a simple list which has the squares of the first ```10``` numbers. How do you do that? The simplest way to do that in Python, would be to use list comprehension.
```py
	>>> squares_first_ten_numbers = [  i*i for i in range(1,11) ]
	>>> type(squares_first_ten_numbers)
	<class 'list'>

```

We would want to create a set, with the same values. We can use set comprehension. Use braces `{}` instead of square brackets `[]` - ```squares_first_ten_numbers_set = { i*i for i in range(1,11) }```. If you do a ```type(squares_first_ten_numbers_set)```, you get a  ```'set'```.
```py
	>>> squares_first_ten_numbers_set = set(squares_of_first_10_numbers)
	>>> squares_first_ten_numbers_set = { i*i for i in range(1,11)}
	>>> type(squares_first_ten_numbers_set)
	<class 'set'>

```

Square brackets ```[]``` denote `list`. Braces ```{}```, denotes `set` or a `dict`.

To create a dictionary, you need a key and a value pair - `{ i : i*i for i in range(1,11)}`. `i : i*i` is `key : value` pair.

```py
	>>> squares_first_ten_numbers_dict = { i:i*i for i in range(1,11)}
	>>> type(squares_first_ten_numbers_dict)
	<class 'dict'>
	>>> squares_first_ten_numbers_dict
	{1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64, 9: 81, 10: 100}

```


```type([])``` is `list` and ```type({})``` is `dict`. If you want to create an empty set, you can use the ```set()``` function. 

```py
	>>> type([])
	<class 'list'>
	>>> type({})
	<class 'dict'>
	>>> type(set())
	<class 'set'>
```

The other way you can create a set, by actually having an element - `type({1})`.


```py
	>>> type({1})
	<class 'set'>
```

However if you actually make it a key-value pair... ? It would be of type 'dict'.
```py
	>>> type({'A':5})
	<class 'dict'>
```

You can create `tuple` by using `()`, We will look at `tuple` in the next step.

```py
	>>> type(())
	<class 'tuple'>
	>>> type((1,2,3))
	<class 'tuple'>
	>>> 

```


#### Summary

These are all pretty nuanced but these are powerful things you would need to understand to make complete use of the power of Python. I think understanding all the things we are discussing in this specific step, are key to making great use of all Python data structures. 

```()``` represents tuples, ```[]``` represents a list, and ```{}``` might be a set or a dictionary. If ```{}``` does not contain anything it's a dictionary. If the ```{]``` contain a set of elements, it's a set. If the ```{}``` contains key-value pairs, then it's a dictionary. _Make sure that you understand every word of this_.

### Step 16: Introducing ```tuple```

In this quick tip, we would be looking at interesting data type in Python, called the **tuple**. Now what does that mean, how do you use it, and how is it different from a list? 

Let's look at it right now. Let's define a method called ```create_ranga()```, and let's return ```'Ranga'```, followed by the date of birth ```1981```, as well as the country, ```'India'```.

Is this really allowed? Of course! 
```py
	>>> def create_ranga():
	...    return 'Ranga',1981,'India'
```

We are returning multiple values from above method. 

Let's call this method: ```ranga = create_ranga()```. 	
	
```py
	>>> ranga = create_ranga()
```

What's the return type? It's of type ```tuple```.
```py
	>>> type(ranga)
	<class 'tuple'>
	>>> ranga
	('Ranga', 1981, 'India')

```
	

A ```tuple``` is nothing but a sequence of values, separated by a comma. 

Let's say you want to take ```ranga```, and assign values to three different variables. `name, year, country = ranga`.
```py
	>>> name, year, country = ranga
	>>> name
	'Ranga'
	>>> year
	1981
	>>> country
	'India'

```

`name, year, country = ranga` is called **destructing**. We are assigning the values from the tuple, to three different variables.   

On the tuple, you can do a number of operations. For example, you can do a ```len(ranga)```, which returns ```3```. You can use an index to retrieve the values of a tuple, as in ```ranga[1]```, and ```ranga[2]```. 

```py
	>>> len(ranga)
	3
	>>> ranga[0]
	'Ranga'
	>>> ranga[1]
	1981
	>>> ranga[2]
	'India'
```


Now let's try and change a value. Suppose ```ranga``` was not born in ```1981```. We would want to reduce his age.

```py
	>>> ranga[1] = 1991
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: 'tuple' object does not support item assignment

```
It does not allow you to do that, because a tuple is by definition, immutable. The values in a tuple cannot change. For that reason, in certain situations, tuples might be more efficient to use than a list. 

Typically, a list is a collection of different values or objects of same type - a list of persons, a list of numbers etc. Typically, a tuple is a set of related attributes - details of a person. 

A tuple typically stores details about a specific thing and the list stores a number of things. 

Let's look at a few simple tips regarding usage of tuples. 

You an create a tuple by using ```person = ('Ranga', 1981, 'India')``` or `person = 'Ranga', 5, 'India'`.  And once you have it, you can destruct it.
```py
	>>> person = ('Ranga', 5, 'India')
	>>> person = 'Ranga', 5, 'India'
	>>> type(person)
	<class 'tuple'>
	>>> name, age, country = person
```

What would happen, if we have only two variables on the left hand side? Obviously, it would throw an error!

```py
	>>> name, age = person
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	ValueError: too many values to unpack (expected 2)

```


Tuples make swapping very easy.

Let's have two values ```x = 0```,  ```y = 1```. You want to swap values.
```py
	>>> x = 0
	>>> y = 1
```

Swap is easy.

```py
	>>> x, y = 0, 1
	>>> x, y = y, x
	>>> x
	1
	>>> y
	0

```
R.H.S of `x, y = y, x` is a tuple `(y, x)` and it is destructed to the L.H.S variables.

We could've done both assignments together.
```py
	>>> x, y = 0, 1
```

An interesting thing is related to how do you create a tuple with one element. Consider  ```x = (0)```, what would happen? What would be the type of ```x```? It's of ```class``` ```int```. 
```py
	>>> x = (0)
	>>> type(x)
	<class 'int'>
```

How do you create a tuple with just one value? The way you can do that, is by putting a comma. So you can do ```x = 1,```, and it is actually a tuple . 

```py
	>>> x = (0,)
	>>> x = 1,
	>>> type(x)
	<class 'tuple'>

```

It's typically an interesting piece of code, for people who come from other languages. They would be worrying: `Oh!! what does it really mean?` Time for Python programmers to have some fun! 

## Chapter 11 - Object Oriented Programming Revisited

Welcome to this section, a continuation on Object-Oriented Programming. In an earlier section, we understood the basics of object oriented programming. 

In this section, we will focus on more advanced stuff related to object oriented programming, such as: 
* Object composition 
* Inheritance
* Abstract classes, and class design 

Recommended Video
- Java Advanced Object Oriented Programming Tutorial - https://www.youtube.com/watch?v=0flBHkyET_E

### Step 01: OOP Basics Revised

In this first step, we will revise the concepts we learned earlier: **class**, **object**, **state** and **behavior**. As We understood earlier, a class is a template. The ```MotorBike``` class hence is a **template**, for all the objects of its kind. ```honda``` is an object or instance, and so is ```ducati```. ```honda``` has a specific state at this point: it has a value of ```50``` for its speed. The state of an object is represented by the values of its  properties, or member members. ```speed``` is a property and a member variable. We change the state of an object through the behavior of an object. Here we have ```increase_speed()``` and ```decrease_speed()``` as the methods to change the ```speed``` of the object. We saw that the state of the object can change during the lifetime of the program.

### Step 02: Designing A ```Fan``` Class

In the previous step, we talked about a few important questions that you need to ask when you are talking about your classes: 

* What is the state? That means, what are the member variables you need to have. 
* How do you want to allow creation of a specific object? That is, what is the kind of constructor that you want to allow? 
* What is what is the behavior you want? That would be the member method definitions. 

Let's consider the example of a ceiling fan. For this ```Fan``` ```class```, you can think about the different elements that represent the state of a specific ```Fan``` object. You can think about how you want to allow construction of a ```Fan``` object, and how to define its behavior. In other words, what kind of changes you want to allow in the state of a ```Fan``` class.

The state we're looking at is ```make``` (manufacturer), ```radius``` (wing radius), ```color```, ```isOn``` (a ```bool```, representing whether it's on), and ```speed```. It's  now time to represent the ```Fan``` class in our code. Above  are the different things that make up the state of a ```Fan```.

An important thing you need to take care of, when you're designing the behavior of a class, is to think about the consumers. Think about who's going to use your class, and how they would like to see it. When we talk about a fan, the typical behavior is: 
* Switch it on 
* Switch it off
* Increase the speed 
* Decrease the speed 

This is the typical behavior that might be expected by consumers, who would use our class. Even when you're not really designing classes to be consumed by others, we would recommend you to think about what kind of behavior you would want, and get an outside in perspective. 

All that theory aside, Python is all about getting things done, as fast as possible. Let's try and keep this analysis to a bare minimum. Let's get down to business.

Let's create the constructor first. 

When we're creating a fan all we will need to decide is the make, radius and the color. Therefore, we want to pass in ```make```, ```radius```, ```color``` to this constructor.

```py
class Fan:
    def __init__(self, make, radius, color):
        self.make = make
        self.radius = radius
        self.color = color
        self.speed = 0
        self.is_on = False
```

Let's define the representation method so that we can see the content of the object.

```py
    def __repr__(self):
        return repr((self.make,self.radius,self.color,self.speed,self.is_on))

```

When we run this code:

```py
fan = Fan('Manufacturer 1', 5, 'Green')
print(fan)
```

We get ```('Manufacturer 1', 5, 'Green', 0, False)```

Now let's go ahead and represent the behavior we wanted to have, for this specific class. 

`switch_on` starts the fan and gives a initial `speed` value.

```py
    def switch_on(self):
        self.is_on = True
        self.speed = 3

```	

`switch_off` stops the fan and makes `speed` `0`.

```py
    def switch_off(self):
        self.is_on = False
        self.speed = 0

```


Here is the full code so far, for your reference:

```py
	
class Fan:
    def __init__(self, make, radius, color):
        self.make = make
        self.radius = radius
        self.color = color
        self.speed = 0
        self.is_on = False

    def __repr__(self):
        return repr((self.make,self.radius,self.color,self.speed,self.is_on))

    def switch_on(self):
        self.is_on = True
        self.speed = 3

    def switch_off(self):
        self.is_on = False
        self.speed = 0

fan = Fan('Manufacturer 1', 5, 'Green')
fan.switch_on()
print(fan)
fan.switch_off()
print(fan)

``` 

We leave it as an exercise, to implement the ```increased_speed()``` and the ```decrease_speed()```. It should be very easy. All that you need to do, is and given the speed, increment and decrement the speed variables. 

### Step 03: Object Composition -  ```Book``` And ```Review```s

In this step, we want to do a simple exercise on object composition. 

First of all, what is object composition? 

Up until now, we stored simple elements inside our object, so **id** is a number, **name** is a string,  **author** is a string. In a class, you can use instances of other classes as well. Earlier we used instances of the predefined classes in Python. 

In this step,  we'll create a custom class called ```Review```. In the ```Book``` class, we will have a ```list``` of ```Reviews```. This is called **object composition**. 

Let's look at the solution. 

Let's have a constructor, as in: ```def __init__(self, id, name, author)```. Let's define a `repr` method as well.

```py
class Book(object):
    def __init__(self, id, name, author):
        self.id = id
        self.name = name
        self.author = author
        self.reviews = []

    def __repr__(self):
        return repr((self.id,self.name,self.author,self.reviews))
```

Let's create an **instance** of the ```Book```, read the book as well. You're able to see the content of the book, but the reviews are still empty. 

```py
book = Book(123, 'Object Oriented Programming with Python', 'Ranga')

print(book)
```

Output
```py
(123, 'Object Oriented Programming with Python', 'Ranga', [])
```

How do we add reviews? 

Before we are able to add reviews, we need to have a ```class``` called ```Review```. 

In Python, You can have multiple classes in the same file. 

Let's start with this

```py
class Review:
    def __init__(self, id, description, rating):
        self.id = id
        self.description = description
        self.rating = rating

    def __repr__(self):
        return repr((self.id,self.description,self.rating))
```

Let's create a Review and print it as well. 
```py
review = Review(10, "Great Book", 5)
print(review)
```

Output
```py
(10, 'Great Book', 5)
```

There is no relationship between the ```Book``` and ```Review```. Let's fix it by creating an ```add_review()``` method. Let's add this to `Book` class.

```py
    def add_review(self, review):
        self.reviews.append(review)
```

Let's use this to add a couple of reviews:

```py
book.add_review(Review(10, "Great Book", 5))
book.add_review(Review(101, "Awesome", 5))

print(book)
```

Output
```
(123, 'Object Oriented Programming with Python', 'Ranga', [(10, 'Great Book', 5), (101, 'Awesome', 5)])
```



Here's the complete code we have until now.

```py
class Book(object):
    def __init__(self, id, name, author):
        self.id = id
        self.name = name
        self.author = author
        self.reviews = []

    def __repr__(self):
        return repr((self.id,self.name,self.author,self.reviews))

    def add_review(self, review):
        self.reviews.append(review)

class Review:
    def __init__(self, id, description, rating):
        self.id = id
        self.description = description
        self.rating = rating

    def __repr__(self):
        return repr((self.id,self.description,self.rating))
book = Book(123, 'Object Oriented Programming with Python', 'Ranga')

# book.add_review()
book.add_review(Review(10, "Great Book", 5))
book.add_review(Review(101, "Awesome", 5))

print(book)

```

Output
```
(123, 'Object Oriented Programming with Python', 'Ranga', [(10, 'Great Book', 5), (101, 'Awesome', 5)])
```


#### Summary

We created a ```Book``` ```class```, a ```Review``` ```class```, and added behavior to the ```Book``` so we can add Reviews to it. The relationship between ```Book``` and ```Review``` is called composition. A ```Book``` instance consists of instances of Review. 

In the next step, we would look at on the relationship called inheritance.

### Step 04: Why Do We Need Inheritance

In this step, let's look at why we need **inheritance**. We consider a simple example involving an ```Animal``` and a ```Pet```, and understand its importance. 

Let's create a simple class called  ```Animal``` with a method `bark` and create an instance of it.

```py
	>>> class Animal:
	...   def bark(self):
	...     print("bark") 
	>>> animal = Animal()
	>>> animal.bark()
	bark

```

We want to create another class `Pet` with ability to `bark` and `groom`.
```py
	>>> class Pet:
	...   def bark(self):
	...     print("bark")
	...   def groom(self):
	...     print("groom")
	>>> pet = Pet()
	>>> pet.bark()
	bark
	>>> pet.groom()
	groom

```


In above classes, there is an unnecessary repetition of ```bark()```. Why can't `Pet` inherit the behavior from ```Animal```? That's where **inheritance** comes in. 

Let's see how can how we can do that.

Look at this class definition: `class Pet(Animal)` indicates that `Pet` extends `Animal` class.

```py
	>>> class Pet(Animal):
	...   def groom(self):
	...     print("groom")
	... 
	>>> dog = Pet()
```

You can obviously do ```pet.groom()``` on the ```Pet```. 

But the interesting thing is you would be able to even do ```pet.bark()```, even though pet does not contain ```bark()```. It inherits the behavior from the ```Animal``` ```class```. 

```py
	>>> dog.bark()
	>>> bark

```


```Animal``` class is called a super-class, and ```Pet``` is called a **subclass**. The subclass inherits the behavior and properties of the super-class.

Inheritance is a powerful concept. One of the most important things to understand, is to use inheritance only when there is an **is-a relationship**. Over here, **Pet is-a Animal**. 

Sometimes, inheritance is misused in situations where there is no is-a relationship, and that can lead to problems.

### Step 05: All Classes In Python 3 Inherit From ```object```

object is a base for all classes in Python.

It has the methods that are common to all instances of Python classes

Let's define Book class, create an instance and print it

```py
class Book(): pass

book = Book()

print(book)
```

Output is `<__main__.Book object at 0x7f78e7fe1588>`.

Where is the output coming from?

`Book` class inherits from `object` class.

The default implementation of `repr` method return the value shown in the output.

Let's override the `repr` method.

```py
class Book():
  def __repr__(self):
     return repr('new book')

book = Book()

print(book)
```

Output is `'new book'`. 

We are now overriding the default `repr` implementation from `object` class.

### Step 06: Multiple Inheritance

In this step, let's look at an interesting feature which is supported by Python. It's called multiple inheritance. It means a single ```class``` can inherit from multiple classes. 


We will create two classes - ```LandAnimal``` and ```WaterAnimal```. 



```py
class LandAnimal: pass

class WaterAnimal: pass

```

We want to create ```Amphibian``` class extending both ```WaterAnimal``` and ```LandAnimal```. 
```py
class Amphibian(WaterAnimal, LandAnimal): pass

amphibian = Amphibian()

```

What we are doing in here is called **multiple** **inheritance**. 

The ```Amphibian``` ```class``` is inheriting from  ```WaterAnimal``` and the ```LandAnimal```. If these classes have any methods, then the ```Amphibian``` class will also inherit those. 

Let's add constructors to these classes.

First thing we do is we'll delegate to the superclass constructor - ```super().__init__()```.

We will add a `walking_speed` to `LandAnimal` and `swimming_speed` to `WaterAnimal`.

```py
class LandAnimal:
    def __init__(self):
        super().__init__()
        self.walking_speed = 5

class WaterAnimal:
    def __init__(self):
        super().__init__()
        self.swimming_speed = 10

class Amphibian(WaterAnimal, LandAnimal):
    def __init__(self):
        super().__init__()

amphibian = Amphibian()
print(amphibian.swimming_speed)
print(amphibian.walking_speed)
```

Output
```
10
5
```

You can see that `amphibian` object inherits properties from both super classes.

Let's add behavior as well : method `increase_walking_speed` in `LandAnimal` and method `increase_swimming_speed` in `WaterAnimal`.

```py
class LandAnimal:
    def __init__(self):
        super().__init__()
        self.walking_speed = 5

    def increase_walking_speed(self, how_much):
        self.walking_speed += how_much

class WaterAnimal:
    def __init__(self):
        super().__init__()
        self.swimming_speed = 10

    def increase_swimming_speed(self, how_much):
        self.swimming_speed += how_much

class Amphibian(WaterAnimal, LandAnimal):
    def __init__(self):
        super().__init__()

amphibian = Amphibian()
amphibian.increase_swimming_speed(25)
amphibian.increase_walking_speed(50)
print(amphibian.swimming_speed)
print(amphibian.walking_speed)
```

Output
```
35
55
```

You can see that we are successfully able to call super class methods on the `amphibian` object.

#### Summary

In Python, you can have multiple inheritance. We saw how you can inherit from two classes. ```Amphibian``` ```class``` inherit data and behavior from the two super-classes.

### Step 07: Creating And Using An Abstract Class

In this step let's look at an important feature in related to object oriented programming called **abstract** **class**. We'll understand how you can create abstract classes, and also see where you can use abstract classes.

What do we mean by an abstract class? 

Let's say we have a class called ```Animal```. It's an empty ```class```. Typically, you'll be able to create instances of this class.

There might be certain situations where we don't know what the code inside a method should be. However, you want the sub-classes to define how this method should behave. 

When we created ```Animal```, it might not know how to ```bark```. We would want to leave the definition of the method to sub-classes. In such situations, we go for an abstract class. 

An abstract class might have several **abstract methods**. 

Let's define `AbstractAnimal` class with abstract method `bark`.

We would need to extend a class called `ABC` - Abstract Base Class. We need add a decorator on abstract method - `@abstractmethod`. 

```py
from abc import ABC, abstractmethod

class AbstractAnimal(ABC):
    @abstractmethod
    def bark(self): pass

```

We cannot create an instance of abstract class.

```
animal = AbstractAnimal()
```

Error from above code - `TypeError: Can't instantiate abstract class AbstractAnimal with abstract methods bark`


You can create a sub class implementing the abstract methods in the abstract class. 

```py
	
class Dog(AbstractAnimal):
    def bark(self):
        print("Bow Bow")

print(Dog().bark())

```

This prints ```'Bow Bow'```

Let's look at more related to abstract classes in the next step.

### Step 08: Template Method Pattern With ```Recipe``` Class

In the previous step, we looked at the basics of abstract class. 

In this step. Let's look at a real world example of how you can use an abstract class. 

Let's create a class called ```Recipe```. Typically when we cook something, there are typically three steps involved. 
* The first one is to prepare. You'd want to make sure, that you have all the raw materials ready, you have clean vessels, and the dishes are done and ready for use. 
* The second one, is to execute the recipe, so you need to follow the instructions.
* The last step is to do a clean up. Make sure that you clean and things like that.

Let's say now, you're creating a ```class``` to represent a ```Recipe```, and you want to make sure that each of the sub-classes follow these three steps. 

How do we do that? 

One of the solutions we can use, is to use abstract class. 

Let's create the class ```AbstractRecipe```. 

It has three abstract methods - `prepare` and `recipe` and `cleanup`. Sub classes can implement these methods.

The `execute` method calls these three steps.

```py
from abc import ABC, abstractmethod
class AbstractRecipe(ABC):

    def execute(self):
        self.prepare()
        self.recipe()
        self.cleanup()

    @abstractmethod
    def prepare(self): pass

    @abstractmethod
    def recipe(self): pass

    @abstractmethod
    def cleanup(self): pass
```

What we are saying is, we don't know what are the steps which are involved in the preparation, recipe or cleanup. However, we want to ensure that these three steps are defined by all the sub-classes. And when we execute something, we would want to follow these steps in that order. 

We are defining an algorithm, and leaving the implementation of individual steps to the sub-classes. This design pattern is also called a **Template Method design pattern**. 

Let's create `Recipe1` .

```py
	
class Recipe1(AbstractRecipe):

    def prepare(self):
        print('do the dishes')
        print('get raw materials')

    def recipe(self):
        print('execute the steps')

    def cleanup(self): pass
	
```

When you run this:
```py
Recipe1().execute()
```

You get 
```
do the dishes
get raw materials
execute the steps
```

Let's create another recipe - `MicrowaveRecipe`. 
```py
class MicrowaveRecipe(AbstractRecipe):

    def prepare(self):
        print('do the dishes')
        print('get raw materials')
        print('switch on microwave')

    def recipe(self):
        print('execute the steps')

    def cleanup(self):
        print('switch off microwave')

```

When you run this:
```py
MicrowaveRecipe().execute()
```

You get 
```
do the dishes
get raw materials
switch on microwave
execute the steps
switch off microwave
```

### Step 09: A Quick Revision

In this section, we looked at a wide variety of object oriented concepts. 

* We started with revising the basic concepts - classes, objects - state and behavior. We created a couple of simple object oriented programming examples. We designed a Fan and Book classes with state and behavior. 
* We looked at object composition. We created a Book class having a number of Reviews. 
* We looked at inheritance. We created multiple examples of inheritance, and we looked at an example of multiple inheritance as well. Inheritance helps us to design a class hierarchy, and to use properties from the super-class. 
* We looked at a specific type of a class called abstract class, for which you'll not be able to create instances. We looked at examples where abstract classes are really useful. 
* We looked at the Template Method design pattern, where you define a template, and leave specific implementation details to the subclass. We saw how abstract classes help us to implement Template Method design pattern.

## Chapter 12 - Error Handling

### Step 01: Introduction To Error Handling - Your Thought Process

Welcome to this section, where we'll focus on all the important things concerned with **exception handling**. We'll discuss how to handle exceptions, and how a programmer's thought process needs to be when implementing exception handling. 

An important things to note is, it's not just the bad programmers who cause exceptions. Even code written by good programmers can have exceptions. Exceptions can occur because of bad code. Exceptions can also occur when your expectations about the environment did not match. Maybe you were expecting a directory to be there on the system, or a folder structure was not present on your deployment environment. You could be expecting some configuration to be done on a database, which was not done. 

What are the keys to exception handling? 

The most important thing is, if something that goes wrong is in your system, you should give a good message to the end user. You should tell him what are the next steps he can take. If let's say, your system expects a file to be there, and the file was not, you should tell the user: "Hey! The file  was not there, That's the reason why the program terminated". 

If the exception happened due to a programming error, you should not just gobble up the exception. You should give enough information to the debugging team to debug the problem. Try and make sure that that information is logged, to help the person who is going to debug the problem. 

#### Summary

In this step, we looked at the fact that both good and bad programmers cause exceptions. But the great programmers are the ones who implement exception handling properly, so that there's a friendly message to the end user, as well as there is enough information logged for someone to debug the problem.

### Step 02: Basics Of Exception Hierarchy

Let's look at a variety of exceptions.

Let's do ```1/0```. What do you think will happen? 

```py
	>>> 1/0
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	ZeroDivisionError: division by zero

```

```py
	>>> i = 0
	>>> j = 10/i
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	ZeroDivisionError: division by zero

```

The result of this is undefined, and that's why an error is **thrown**:   ```ZeroDivisionError```. 

Earlier we looked at this one as well: ```'2' + 2```. 

We are trying to add a string ```'2'```, to a number ```2```. What would happen?

```py
	>>> 2 + '2'
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: unsupported operand type(s) for +: 'int' and 'str'

```
It says "```TypeError```: I don't know how to add ```'int'``` to a ```'str'```". 

Let's create a simple ```list``` of numbers: ```values = [1, '2']```, 

and we do ```sum(values)```, what would happen? Again, the same error: ```TypeError```. 
```py
	>>> values = [1,'2']
	>>> sum(values)
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: unsupported operand type(s) for +: 'int' and 'str''

```

Let's try to access a variable, which is not defined. What would happen? 
```py
	>>> value
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'value' is not defined

```
It says "```NameError```! The name '```value```' is not defined yet". 

Earlier we created a list called ```values```, so on that, let's call an attribute which is does not exist. 

```py
	>>> values.non_existing
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	AttributeError: 'list' object has no attribute 'non_existing'

```
If we try to say ```values.<non-existing>``` ,what would happen? It throws ```AttributeError```, that says: "```list``` does not have an attribute ```non_existing```'. 


The same thing happens, If you try to call a non-existing method.
```py
	>>> values.non_existing()
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	AttributeError: 'list' object has no attribute 'non_existing'

```


```ZeroDivisionError```, ```TypeError```, ```NameError``` and ```AttributeError```: all are different kinds of exceptions that are defined in Python. 

If you want to see the complete list of exceptions, you can import the ```builtins``` ```module```, and do ```help(builtins)```. 

You would see at the top are classes, and you'd see later a class called ```BaseException```, from which ```Exception``` inherits. And after that is a set of errors. The one which we looked at earlier, is ```ZeroDivisionError```:
```py
	>>> import builtins
	>>> help(builtins)
	Help on built-in module builtins:
	NAME
	    builtins - Built-in functions, exceptions, and other objects.
	DESCRIPTION
	    Noteworthy: None is the `nil' object; Ellipsis represents `...' in slices.
	CLASSES
	    object
	        BaseException
	            Exception
	                ArithmeticError
	                    FloatingPointError
	                    OverflowError
	                    ZeroDivisionError
	                AssertionError
	                AttributeError
	                BufferError
	                EOFError
	                ImportError
	                    ModuleNotFoundError
	                LookupError
	                    IndexError
```

You can see that ```ZeroDivisionError``` inherits from ```ArithmeticError```, which inherits from ```Exception```, which inherits from ```BaseExeption```, which inherit from ```Object```. 

You also have ```IndentationError```:
```py
	>>>     values = [1,'1']
	  File "<stdin>", line 1
	    values = [1,'1']
	    ^
	IndentationError: unexpected indent
	>>>     sum(values)
	  File "<stdin>", line 1
	    sum(values)
	    ^
	IndentationError: unexpected indent

```

In this step, we looked at a high level hierarchy of exceptions. We'll talk about this a little more in the subsequent step.

### Step 03: Basics Of Error- Handling - ```try```-```except```

In this step, let's get started with understanding how to **handle** **exceptions**. 

We know that ```1/0``` throws an error.

```py
1/0
``` 

Output
```
Traceback (most recent call last):
  File "main.py", line 1, in <module>
    1/0
ZeroDivisionError: division by zero
```

You can see that the line which throws the error is also printed.

Consider this piece of code. Will j be printed?

```py
i = 0
j = 10/i
print(j)

``` 

Nope it will not be.

When an exception occurs, program execution terminates, then and there. Unless, you handle the exception. 

Even if we had a hundred lines of code right below it, not one of those would get executed. And that's why you would want to handle exceptions. 

We would want to make sure that if an exception happens here, we can give a default value to ```j```. 

How can you do that? That's where the ```try``` **block** comes in. 

`try except` has a simple syntax. You put the code you want to look out for exceptions in `try`. You would write the code to handle the exception in `except` block.

```py
try:
    i = 0
    j = 10/i
except:
    print("Exception")
    j = 0
print(j)

``` 

Output
```
Exception
0
```

You can see that `j` is assigned a value 0 and the `print` method is also called.

#### Summary

In this step, we looked at the basics of exception handling. We learned that if an exception is not handled, then the subsequent lines of code are not executed. We used a ```try``` block to protect our code and we created an ```except``` block to say what should happen, if an exception is thrown. 

At the end, we saw we were able to handle the exception, and continue with the rest of the code.

### Step 04: Handling Multiple Errors With Multiple ```except```- Blocks

In this we do let's dig deeper and try to learn more about the ```try- except``` **block**.

When we run the code, what would happen? 

```py
try:
    i = 0
    j = 10/i
except:
    print("Exception")
    j = 0
print(j)
print("End")

``` 

It would print 

```
Exception
0
End
```


What would result, if the exception did not occur? Let's say ```i``` had a value of ```1``` or ```2```. 

```py
try:
    i = 1
    j = 10/i
except:
    print("Exception")
    j = 0
print(j)
print("End")

``` 

It would print 

```
10.0
End
```

You can see that ```'Exception'``` is not printed. 

The code in ```except``` block is executed, only when there is an exception. If there is no exception, all `except` blocks are skipped.

Let's look at code below: We are doing a `sum` on list with different types of values.

```py
try:
    i = 1
    j = 10/i
    values = [1, '1']
    print(sum(values))
except:
    print("Exception")
    j = 0
print(j)
print("End")
```

Output
```
Exception
0
End
```

It prints an exception, ```Exception```. But it does not give us a clue as to what went wrong?

You might be thinking, "What if I want to handle these two exceptions differently?" You might want to be able to say: "For this one, I want to handle and assign a different value to the name. However, if a divide by zero exception happened, then I would want to do something different." How do you do that? 

You can specify what kind of exceptions you would want to handle, is by saying something like ```except: TypeError```.

If you only want the handle ```TypeError```s, and have code specific to that, as in ```print('Type Error')```. What would this do? If a ```TypeError``` happens, it prints ```'Type Error'```, assigns a value of ```0``` to ```j```, and the code continues execution as expected. 

```py
try:
    i = 1
    j = 10/i
    values = [1, '1']
    print(sum(values))
except TypeError:
    print("TypeError")
    j = 0
print(j)
print("End")

```

Output
```
TypeError
0
End
```

If a divide by zero exception happens, it is not handled, and will get thrown out. 

The block says _OK! I only know how to handle a ```TypeError```. I don't know how to handle the `ZeroDivisionError`_.  

How can you handle this? 

We can define **another** ```except``` block. 

```py
try:
    i = 0
    j = 10/i
    values = [1, '1']
    print(sum(values))
except TypeError:
    print("TypeError")
    j = 0
except ZeroDivisionError:
    print("ZeroDivisionError")
    j = 0
print(j)
print("End")
```

Output
```
ZeroDivisionError
0
End
```
In this step, we looked at two basic things. 

We saw that if no exception happens, then the code in `except` is not executed.  

The second thing we learnt, is You can have specific exception blocks, tailored to handle specific exceptions. So if we say ```except TypeError```, then I would only handle ```TypeError```.  ```except ZeroDivisionError```  would only match  ```ZeroDivisionError```. 

### Step 05: Error Handling Puzzles And Exception Details

In this step, we will be talking about a number of puzzles related to exception handling. 

Now let's start with a very basic example. 

What will be the output for this? Think about it. 
```py
try:
    10/0
except TypeError:
    print("TypeError")
except ZeroDivisionError:
    print("ZeroDivisionError")

print("End")

```

You run the code, and the output is ```ZeroDivisionError```, and ```'End'```.

Now let's look at the next one. We want to do ```10/0```. Also, you know that ```object``` is the super-class of all the classes in Python. 
```py	

try:
    10/0
except object:
    print("ZeroDivisionError")
# catching classes that do not inherit from BaseException is not allowed
print("End")

```

You'll see that it throws an error: "catching classes that do not inherit from ```BaseException``` is not allowed". Even though ```object``` is a valid Python ```class```, you cannot catch it. You can only catch those classes which inherit from ```BaseException```.

What will be the output?

Code is throwing a divide by zero error, handling ```Exception```.

```py
try:
    10/0
except Exception:
    print("Exception")

```
Output - `Exception` 

`Exception` will match all its sub classes as well. One of which is `ZeroDivisionError`.

Here's the hierarchy
```py
BaseException
    Exception
        ArithmeticError
            FloatingPointError
            OverflowError
            ZeroDivisionError

```
To handle `ZeroDivisionError`, you can handle `ZeroDivisionError` or any of its super classes - `ArithmeticError`, `Exception` or `BaseException`

Now let's look at the next puzzle. 

You can also handle multiple errors in the same ```except``` block. 

```py
try:
    sum([1, '1'])
except (ZeroDivisionError, TypeError):
    print("Exception")

print("End")

```

Output is ```'Exception'```

The last puzzle shows how you can print the exception details. You would want to get the details of the error, and print them out.

```py
	
try:
    sum([1,'1'])
except TypeError as error:
    print(error)
print("End")

```

Output
```
unsupported operand type(s) for +: 'int' and 'str'
End
```

You can see the error details. So, you can handle it better.

#### Summary

These were a few interesting puzzles related to exception handling. There are two new things we learned in this step. One is, you can handle multiple exceptions in a single except block. The second thing we learned was you can get the error details as well.

### Step 06: Error Handling - ```finally``` And ```else```

We looked at ```try``` and ```except```. The other two things which are typically part of a ```try```-```except``` block are ```else``` and ```finally```. 

We keep this example very simple for now. Let's see what would happen, if we run the code as it is:

```py
try:
    # Business Logic to read
    i = 1 # Not hardcoded, getting a input from user
    j = 10/i
except Exception as error:
    print(error)
    j = 0
else:
    print("Else")
finally:
    # Close
    print("Finally")

print(j)
print("End")

``` 

Output
```
Else
Finally
10.0
End
```

Exception is not thrown. So, `else` and `finally` are executed. `except` is not executed.

What if an error is thrown?

Let's change `i` to 0.

```py
    i = 0 # Not hardcoded, getting a input from user
```

Output
```
division by zero
Finally
0
End
```
Exception is thrown. So, `except` and `finally` are executed. `else` is not executed.


Here's the summary:
- ```except``` is called when exception is thrown and exception matches.
- ```else``` is executed only when an exception is not thrown. 
- ```finally``` is always executed

### Step 07: Error Handling Again

In this step, let's look at a few more things related to exception handling blocks. We have a ```try``` block, ```except``` block, ```else``` block and ```finally``` block. What are the allowed combinations?
- With a `try`, you can have multiple ```except``` blocks.
- You cannot have an `else` without `except` blocks.
- You can have a ```try``` with just ```finally``` - If there is an exception, code in finally is executed.

### Step 08: Raising Exceptions

In the previous steps, we looked at how to handle exceptions. But you might be writing code which might throw exceptions as well. So how do you throw exceptions? 

Let's get started with creating a simple example, about currencies. Let's say we have ```20 USD```, and you would want to be able to add ```30 USD``` to it. What would be the result? ```50 USD```. 

We want to develop a simple program, which allows us to add currencies. 

Think of a scenario where you have to add ```INR 500``` to ```USD 50```. 

Let's say the first version of the program we write, we don't support the exchange feature. When different kinds of currencies are passed, we want to throw an exception. 

Let's see how to do that. 

Let's create a  ```Currency``` ```class``` with a constructor and `repr`.

```py
class Currency:
    def __init__(self, currency, amount):
        self.currency = currency
        self.amount = amount

    def __repr__(self):
        return repr((self.currency,self.amount))
```

All simple stuff. 

Let's create a couple of instances and try to add them.

```py
value1 = Currency("USD", 20)
value2 = Currency("INR", 30)
print(value1 + value2)
```

Output
```
Traceback (most recent call last):
  File "main.py", line 11, in <module>
    print(value1 + value2)
TypeError: unsupported operand type(s) for +: 'Currency' and 'Currency'
```

You cannot add two currencies. How can we support adding currencies? 

We can do **operator overloading**, so you can give a new meaning for `+` operator for the ```Currency``` class. 

We will implement the ```__add__()``` method.

```py
    def __add__(self, other):
        total_amount = self.amount + other.amount
        return Currency(self.currency, total_amount)
```

If we are doing ```value1 + value2```, ```self``` would be ```value1```, and ```other``` would be ```value2```. Let's assume for the time being that the both of them have the same currency. 

Let's run this program. 

Output - `('USD', 50)`

We are assuming that both currencies have the same type. We need to have a check if the currencies are the same. If not, throw an exception. 

How do we do that? 

You can do that in Python, by saying ```raise```, and mention ```Exception``` class, by passing in a text message such as ```'currencies do not match'```. 

```py
    def __add__(self, other):
        if self.currency != other.currency:
            raise Exception("Currencies Do Not Match")
        total_amount = self.amount + other.amount
        return Currency(self.currency, total_amount)

```

Let's create currencies that have different currencies and add them.

```py
value1 = Currency("USD", 20)
value2 = Currency("INR", 30)
print(value1 + value2)

```
You can see that `"Currencies Do Not Match"` is thrown.

Output
```py
Traceback (most recent call last):
  File "main.py", line 17, in <module>
    print(value1 + value2)
  File "main.py", line 11, in __add__
    raise Exception("Currencies Do Not Match")
Exception: Currencies Do Not Match
```

Here is the entire code of the program, for your reference:

```py
	
class Currency:
    def __init__(self, currency, amount):
        self.currency = currency
        self.amount = amount

    def __repr__(self):
        return repr((self.currency,self.amount))

    def __add__(self, other):
        if self.currency != other.currency:
            raise Exception("Currencies Do Not Match")
        total_amount = self.amount + other.amount
        return Currency(self.currency, total_amount)

value1 = Currency("USD", 20)
value2 = Currency("INR", 30)
print(value1 + value2)

```

### Step 09: Creating a Custom Exception class

In the previous step, we looked at how to raise an exception. In this step, create a new exceptio type and raise it. 

Just like the ```Exception``` ```class```, we would want to create our own ```CurrenciesDoNotMatchError```. 

Let's get started with ```CurrenciesDoNotMatchError```

```py
class CurrenciesDoNotMatchError: pass

```

Can you ```raise``` this? 

What do you think will happen if we say ```raise CurrenciesDoNotMatchError("currencies do not match")```? 

Error - "exceptions should drive from ```BaseException```" 

Whenever you create a custom exception, you need to extend ```BaseException```, or a subclass of ```BaseException```. Let us choose to extend ```Exception```. 

Let's add a constructor accepting a message.

```py
class CurrenciesDoNotMatchError(Exception):
    def __init__(self,message):
        super().__init__(message)

```

You can also pass in the values of  ```self.currency``` and ```other.currency```, so that it's clear why the exception happened. 
```py
raise CurrenciesDoNotMatchError(self.currency + " " + other.currency)

```


Here is the entire code for your reference:

```py
	
class CurrenciesDoNotMatchError(Exception):
    def __init__(self,message):
        super().__init__(message)
class Currency:
    def __init__(self, currency, amount):
        self.currency = currency
        self.amount = amount

    def __repr__(self):
        return repr((self.currency,self.amount))

    def __add__(self, other):
        if self.currency != other.currency:
            raise CurrenciesDoNotMatchError(self.currency + " " + other.currency)
        total_amount = self.amount + other.amount
        return Currency(self.currency, total_amount)

value1 = Currency("USD", 20)
value2 = Currency("INR", 30)
print(value1 + value2)

```

Output
```
Traceback (most recent call last):
  File "main.py", line 20, in <module>
    print(value1 + value2)
  File "main.py", line 14, in __add__
    raise CurrenciesDoNotMatchError(self.currency + " " + other.currency)
__main__.CurrenciesDoNotMatchError: USD INR
```


### Step 10: Exception Handling Best Practices

Let's review some of the important exception handling best practices, from our experience.

So what's the first best practice? 

Never hide exceptions. If an exception happens, put the entire stack trace into your logs. In the example which we saw, We understood 'currencies do not match'. And we also listed what currencies did not match. So that kind of context really helps somebody from outside your team, who's trying to handle the exception. The moment you start hiding the exceptions, the guy who's trying to solve it, does not know where to start. He knows something is going wrong, but he does not know which line of code threw the exception.

The second thing is - do not use exception handling for flow control. You cannot have exception handling to redirect the way logic flows in a program, like an ```if```-```else```. Exception handling is very expensive.

The most important thing about exception handling, is think about your user. If an exception happens, what does your end user want to see, and what can he do about it?  As long as you are thinking about it, then you are doing very well. 

The other thing is, plan on supporting the guy who's going to handle the call from your end user. What kind of information does he need to solve the error? The support team might also include the developer, who might want to have a lot of information in the log. 

Also, think about the calling method. If you're designing an API, think about what the calling method can do about this exception.

Last one is have global exception handling. Make sure that you have something sitting on top of everything which is like the global exception handling, so that no exceptions actually go to the end user. It should always be a proper exception message that end user sees, which should tell him what he can do about it. Remember that na end user will not be able to do anything with the stack trace. 

We know some of these are not easy to implement, but the most important thing is for you to keep thinking about this. 

Once you have the attitude of to think about the end user, your support team, and the calling method, that's all you would need to make sure that you have some exception handling.

## Chapter 13 - More Python Tips

### Tip-1: ```math``` Module And ```Decimal``` Class

In this quick step, we look at how you can do mathematical calculations accurately, and also at a few important contents of the ```math``` module.  

```float``` ```class``` is not really that accurate. If you do ```4.5 - 3.2``` , the value that get is something like ```1.29999.....999998```. 

```py
	>>> print(4.5 - 3.2)
	1.2999999999999998
```

That's where the Decimal class steps in.
```py
	>>> value1 = Decimal('4.5')
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	NameError: name 'Decimal' is not defined

```

`decimal` module needs to be imported. Make sure that you create `Decimal` instances using string constructors. ```value1 - value2``` is printed as ```1.3``` - which is accurate. 
```py
	>>> import decimal
	>>> from decimal import Decimal
	>>> value1 = Decimal('4.5')
	>>> value2 = Decimal('3.2')
	>>> value1 - value2
	Decimal('1.3')

```

Let's look more closely at the ```math``` module, and other components present within it. 

```py
	>>> import math
	>>> math.
	math.acos(       math.erf(        math.inf         math.pi
	math.acosh(      math.erfc(       math.isclose(    math.pow(
	math.asin(       math.exp(        math.isfinite(   math.radians(
	math.asinh(      math.expm1(      math.isinf(      math.sin(
	math.atan(       math.fabs(       math.isnan(      math.sinh(
	math.atan2(      math.factorial(  math.ldexp(      math.sqrt(
	math.atanh(      math.floor(      math.lgamma(     math.tan(
	math.ceil(       math.fmod(       math.log(        math.tanh(
	math.copysign(   math.frexp(      math.log10(      math.tau
	math.cos(        math.fsum(       math.log1p(      math.trunc(
	math.cosh(       math.gamma(      math.log2(       
	math.degrees(    math.gcd(        math.modf(       
	math.e           math.hypot(      math.nan

```


You can also find out the value of ```math.pi```, which a constant, and ```math.e```. 

```py
         
	>>> math.pi
	3.141592653589793
	>>> math.e
	2.718281828459045

```

If you want to do any mathematical operation, like those involving trigonometry, logarithms, mathematical conversions (degrees to radians, for example), this is your go to module.

### Tip-02: ```None```

In this quick tip, we will be talking about ```None```. What is ```None```? Where do you use it? What are the best practices with it? 

The way you think about ```None``` is very similar to how you think about ```NULL``` in ```SQL```. In ```SQL```, if we say something is ```NULL```, it means that it does not have a value. Java programmers would be familiar with that concept as well. When a variable object is ```null```, that means it's not referring to anything. 

In Python, ```None``` is very similar, except for the fact that ```None``` actually is an instance of a class. If you look at ```type(None)```, it is ```NoneType```. ```None``` is the only instance of this class. 

```py
	>>> None
	>>> type(None)
	<class 'NoneType'>

```

Let's look at a simple example using ```None```. 

Let's create a simple method, and call it ```email()```. We would put the ```subject```, ```content```, ```to```, ```cc```, ```bcc``` as parameters to this method. Let's say this is the definition of ```email```, and it's just simply print everything in the body, using a formatted string. We are printing upto ```{cc}``` among the parameters. 

```py
	>>> def email(subject, content, to , cc , bcc): 
	...    print(f" {subject}, {content}, {to}, {cc}, "
	... )
	...
```
Let's call the method as shown below:

```py
	>>> email("subject", "great work", "in28minutes@gmail.com")
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	TypeError: email() missing 2 required positional arguments: 'cc' and 'bcc'

```

You can to see that ```email``` is missing required positional arguments, which are ```cc``` and ```bcc```. But if ```cc``` and ```bcc``` are not relevant to my particular email, what to do? Is there a way we can assign default values to them? The default should be something that means "nothing is to be used". 

The solution is: set ```cc = None``` and ```bcc = None```. Also, print the ```cc``` and ```bcc``` inside the method for display. 

```py
	>>> def email(subject, content, to , cc=None , bcc=None): 
	...    print(f" {subject}, {content}, {to}, {cc}, {bcc}");
	... 
```

We can now call the method again. This time we see the right result.

```py
	>>> email("subject", "great work", "in28minutes@gmail.com")
	 subject, great work, in28minutes@gmail.com, None, None

```


If you want to indicate that you don't want to have a ```subject```, specify the ```subject``` as ```None```.

```py
	>>> email(None, "great work", "in28minutes@gmail.com", None, None)
	 None, great work, in28minutes@gmail.com, None, None

```


Using ```None``` is considered to be good programming practice, because you can compare variables against it. 

Here's an example:

```py
	>>> var = "123"
	>>> if var is None : print ("do something");
	... 
	>>> var = None
	>>> if var is None : print ("do something");
	... 
	do something
	>>> 

``` 

### Tip-2: ```statistics``` Module - Find Mean And Median

In this step, let's try and understand the ```statistics``` module within Python.

Let's create a simple list, and play around with a few of the functions which are present in the ```Statistics``` ```class```. 
```py
	>>> import statistics
	>>> statistics.
	statistics.Decimal(          statistics.mean(
	statistics.Fraction(         statistics.median(
	statistics.StatisticsError(  statistics.median_grouped(
	statistics.bisect_left(      statistics.median_high(
	statistics.bisect_right(     statistics.median_low(
	statistics.chain(            statistics.mode(
	statistics.collections       statistics.numbers
	statistics.decimal           statistics.pstdev(
	statistics.groupby(          statistics.pvariance(
	statistics.harmonic_mean(    statistics.stdev(
	statistics.math              statistics.variance(


```
Let's say we have ```marks```, having entries ```[1, 6, 9, 23, 2]```. Let's say you want to find the average mark in the list. What is the average called in statistics? It's called mean.

```py
	>>> marks = [1, 6, 9, 23, 2]
	>>> statistics.mean(marks)
	8.2

```

There are other statistical functions which are present in here. Let's say you want to find the median of ```marks```. The median of a list is the entry that is placed in the middle, when you arrange the numbers in sorted order. Over here, the median seems to be ```6```. If there are even number of numbers (suppose there was a ```7``` also in ```marks```) ```median(marks)``` returns the average of the two values in the center, ```6``` and ```7```. The result is ```6.5```. 
```py
	>>> statistics.median(marks)
	6
	>>> marks = [1, 6, 9, 23, 2, 7]
	>>> statistics.median(marks)
	6.5

```

If you want to get the higher of those, you can use ```median_high()```, which will return 7. For the lower one, use ```median_low()```, which gives back ```6```. 

```py
	>>> statistics.median_high(marks)
	7
	>>> statistics.median_low(marks)
	6

```

The other interesting function is ```variance()```, which gives an estimate of how much these values vary.
```py
	>>> statistics.variance(marks)
	63.2

```


### Tip-3: ```collections``` Module - ```deque``` For Queue And Stack

In one of the previous tips, we understood the fact that a list can be used both as a queue and a stack. List is not the most efficient representation of a stack. 

The best data structure to represent them is a ```deque```. It' a double-ended queue. That means you can remove values from the start, or at the end.

You can create a simple queue, by using a ```deque``` and passing it a ```list```. 

```py
	>>> from collections import deque
	>>> queue = deque(['Zero','One','Two'])
	>>> queue.pop()
	'Two'

```


If you wanted to start using values from the right, do ```queue.pop()```. You could also append a new value, by doing ```queue.append('Three')```. If you look at the queue right now, it would have entries ```['Zero', 'One', 'Three']```.
```py
	>>> queue.append('Three')
	>>> queue
	deque(['Zero', 'One', 'Three'])
	>>> queue.append('Four')
	>>> queue.append('Five')

``` 

You can even append at the start of the queue. The way you can do it is to call ```appendleft()```. Now if you print the contents of ```queue```, ```"Minus One"``` would be the one at the start of the queue. 

```py
	>>> queue.appendLeft('Minus One')
	Traceback (most recent call last):
	  File "<stdin>", line 1, in <module>
	AttributeError: 'collections.deque' object has no attribute 'appendLeft'
	>>> queue.append
	queue.append(      queue.appendleft(  
	>>> queue.appendleft('Minus One')
	>>> queue

```

The other operation is to ```popleft()```, which returns the first value inside the queue, starting from the left. 
```py
	deque(['Minus One', 'Zero', 'One', 'Three', 'Four', 'Five'])
	>>> queue.pop()
	'Five'
	>>> queue.popleft()
	'Minus One'

```

### Tip-4: ```date``` Module

In this quick tip, we look at how to handle dates in Python. 

Let's get started with importing the ```datetime``` module, which has most of the date and time features. 

Let's say we would want to get the value of today's date. 

How do you do that? ```datetime.datetime.today()```

```py
	>>> import datetime
	>>> datetime.datetime.today()
	datetime.datetime(2018, 5, 21, 9, 59, 57, 450683)

```

Let's take this into a variable: ```today_date = datetime.datetime.today()```. The structure is very simple, it's year, month, day of the month, followed by hour, minute, second, and micro-seconds. 

```py
	>>> today_date = datetime.datetime.today()
	>>> today_date
	datetime.datetime(2018, 5, 21, 10, 0, 39, 732463)

```

How do you get information from this structure? 

To get year - ```today_date.year```. 

Few more examples:

```py
	>>> today_date.year
	2018
	>>> today_date.month
	5
	>>> today_date.day
	21
	>>> today_date.hour
	10
	>>> today_date.minute
	0
	>>> today_date.second
	39

```

How do you create a specific date? 

```py
	>>> some_date = datetime.datetime(2019, 5, 27)
	>>> some_date
	datetime.datetime(2019, 5, 27, 0, 0)

```

You can also create a date with time by adding additional time attributes. 
```py
	>>> some_date = datetime.datetime(2019, 5, 27, 9, 5,25)
	>>> some_date
	datetime.datetime(2019, 5, 27, 9, 5, 25)
	>>> some_date = datetime.datetime(2019, 5, 27, 9, 5,25, 234567)
	>>> some_date
	datetime.datetime(2019, 5, 27, 9, 5, 25, 234567)
	>>> some_date.time()
	datetime.time(9, 5, 25, 234567)

```

Now we looked at some of the basic things you can do with ```datetime```, we'll look at a few operations to manipulate the date.


We have a date, that is currently ```2019, 5, 27```.
```py
	>>> day = some_date
	>>> day
	datetime.datetime(2019, 5, 27, 9, 5, 25, 234567)

```
We want to add to this, a specific number of days, or weeks, or things like that. How to do that? 

That's where a concept called `timedelta` is used. 

We have a day variable which contains the value of the date. To this date, you can add a time delta, or remove a time delta.

```py
	>>> day + datetime.timedelta(days=90)
	datetime.datetime(2019, 8, 25, 9, 5, 25, 234567)

``` 
An important thing to note, is that the original value of ```day``` is not modified. 
```py
	>>> day
	datetime.datetime(2019, 5, 27, 9, 5, 25, 234567)
```

You can add weeks and number of hours. 
```py
	>>> day + datetime.timedelta(days=90)
	datetime.datetime(2019, 8, 25, 9, 5, 25, 234567)
	>>> day + datetime.timedelta(weeks=3)
	datetime.datetime(2019, 6, 17, 9, 5, 25, 234567)
	>>> day + datetime.timedelta(hours=48)
	datetime.datetime(2019, 5, 29, 9, 5, 25, 234567)

```


### Tip-5: Methods And Arguments - The Basics

Methods in Python are very very powerful. There are a variety of things that you can pass to them. In this specific step, let's focus on understanding all the different things that you can pass to a method: **normal arguments, default argument, variable arguments, and keyword arguments**. 

Let's create a very very simple method, and call this ```example_method()```. 


```py
def example_method(mandatory_parameter, default_parameter="Default"
                   , *args, **kwargs):
    print(f"""
        mandatory_parameter = {mandatory_parameter} {type(mandatory_parameter)}
        default_parameter = {default_parameter} {type(default_parameter)}
        args = {args} {type(args)}
        kwargs = {kwargs} {type(kwargs)}
        """)
``` 

`*args` represents variable arguments. ```**kwargs``` is called ```keyword argument```. All we do in this method, is print all the values out. 

Let's look at how we can call this method. The idea behind what we do, is to understand all these parameters being passed in, how can you call this method with certain order of values, and what get passed to this method, in different ways. 

What would happen if we just say ```example_method()```? 

```py
example_method() #example_method() missing 1 required positional argument

```

It says "it's missing one required positional argument". You should definitely pass a value to `mandatory_parameter`. 

Let's say you call this with a value, say ```15```.  What does it do? 

```py
example_method(15)
```

Output
```
	mandatory_parameter = 15 <class 'int'>
	default_parameter = Default <class 'str'>
	args = () <class 'tuple'>
	kwargs = {} <class 'dict'>

```

You can also use the named parameter to get the same result.

```py
example_method(mandatory_parameter=15)
```

Let's pass two parameters.

```py
example_method(25,"Some String")

```

Output
```

        mandatory_parameter = 25 <class 'int'>
        default_parameter = Some String <class 'str'>
        args = () <class 'tuple'>
        kwargs = {} <class 'dict'>
```

Instead of the default values, 	`default_parameter` gets the `Some String` value.

Let's say you want to pass more values. 

```py
example_method(25,"String 1","String 2","String 3")

```

Output
```
  mandatory_parameter = 25 <class 'int'>
        default_parameter = String 1 <class 'str'>
        args = ('String 2', 'String 3') <class 'tuple'>
        kwargs = {} <class 'dict'>
```

Additional arguments are passed as variable arguments into `args`.

What if we have even more arguments?

```py
example_method(25,"String 1","String 2","String 3","String 4","String 5")

```

Output
```

        mandatory_parameter = 25 <class 'int'>
        default_parameter = String 1 <class 'str'>
        args = ('String 2', 'String 3', 'String 4', 'String 5') <class 'tuple'>
        kwargs = {} <class 'dict'>

```

Same result : All additional arguments are passed as variable arguments into `args`.


### Tip-6: Methods And Arguments - Keyword Arguments

In this step, let's focus on the last argument: ```kwargs``` or keyword arguments. 

```py
def example_method(mandatory_parameter, default_parameter="Default"
                   , *args, **kwargs):
	    
``` 

Let's pass a few key-value pairs to the method.

```py
example_method(25,"String 1","String 2","String 3",key1='a', key2='b')

```

Output
```

        mandatory_parameter = 25 <class 'int'>
        default_parameter = String 1 <class 'str'>
        args = ('String 2', 'String 3') <class 'tuple'>
        kwargs = {'key1': 'a', 'key2': 'b'} <class 'dict'>
```

You can see the key value pairs are now part of keyword arguments - `kwargs`.

Let's see what would happen if we don't pass in any of the variable arguments.
```py
example_method(25,"String 1",key1='a', key2='b')

```

Output
```

        mandatory_parameter = 25 <class 'int'>
        default_parameter = String 1 <class 'str'>
        args = () <class 'tuple'>
        kwargs = {'key1': 'a', 'key2': 'b'} <class 'dict'>
```

As expected, the variable arguments param `args` is empty.

You can also use named parameters: Result does not change.

```py
example_method(key1='a', key2='b',mandatory_parameter=25,default_parameter="String 1")

```


One of the things we would recommend you to do, is now that you have this method, play around with it. Try to understand the different ways of calling it. Make sure that you are trying different combinations, and understand what is happening in the background. 

I think having a good understanding of what are the possibilities, that you can do with your method signatures, is one of the most important things to be a good Python programmer.


### Tip-7: Methods And Arguments - Unpacking Lists And Dictionaries

Welcome to another very useful tip about how to pass values to a method in Python. 

Let's say we have a simple list of values, ```example_list = [1,2,3]```. We want to use the values from this list, as parameters to call a method. How can I do that? 

```py
example_list = [1,2,3]
example_method(example_list[0],example_list[1],example_list[2])
```
Output
```
        mandatory_parameter = 1 <class 'int'>
        default_parameter = 2 <class 'int'>
        args = (3,) <class 'tuple'>
        kwargs = {} <class 'dict'>
```

Is there a simpler way? Code below give you same result.

```
example_method(*example_list)
```

This cool concept is called **unpacking**. When you say ```*example_list```, all the elements in the list are passed as individual arguments.

Let's say you have keyword arguments to pass in, but they are all defined in a dictionary.  You can use `**example_dict`.

```py
example_list = [1,2,3]
example_dict = {'a':'1', 'b':'2'}
example_method(*example_list, **example_dict)

```

Output
```

        mandatory_parameter = 1 <class 'int'>
        default_parameter = 2 <class 'int'>
        args = (3,) <class 'tuple'>
        kwargs = {'a': '1', 'b': '2'} <class 'dict'>
```

You can see that values in `example_dict` are picked by argument `kwargs`.

#### Summary

In this step, we learned that unpacking of data structures is a very useful feature in Python. When you have the parameter values that you would want to pass, in a list or a dictionary, you can use unpacking.

### Tip-8: Creating Custom Modules

In this specific step, we will try and understand the concept of a ```module```. 

Let's create a new Python file ```module_1```. 

A python file can contain methods and classes.

```py
#module_1.py
def method_1():
    print("method 1")

class ClassA:
    def class_method_1(self):
        print("class_method_1 method 1")

method_1()
ClassA().class_method_1()

```

If you're coming from an object oriented programming language like Java, where each ```class``` is defined in its own source file, you need to change how you think about it. When it comes to Python, a single source file can contain multiple classes. 

The way you organize a module in Python, would be to have all of the things which are related to it in a single file. So if you have a group of classes which are related, you take them and put them in a single file.

Whatever code you have directly outside the boundary of a ```class``` or a method would automatically get executed. Here, ```method1()``` will be executed. ```ClassA().class_method_1()``` will be executed next. 

You can **reuse one module in another**. We're going to create a new file ```module_2```. 

And over here, you would want to start using the code from ```module_1```. 

The first thing to do is to **import** it, by saying ```import module_1``` . Now, you can use all the features available in ```module_1```, by doing things such as ```module_1.method_one()```, or ```module_1.ClassA()``` . And on that ```ClassA()``` instance, you can call ```class_method_1()```.
```py
#module_2.py
import module_1

module_1.method_1()
module_1.ClassA().class_method_1()

```

When this code is run, you would see that the messages are shown twice. 
- Once from module_1 import
- Once from module_2 execution

**If you have any code that's not within a class or a method, then that code is executed automatically.** 

How can we prevent code outside a class or a method from executing when it is imported?

You can update module_1 with an if condition

```
if __name__ == '__main__':
    method_1()
    ClassA().class_method_1()
```

### Tip-9: Defining Equality For Classes

In this tip, we will be looking at how to compare objects in Python. 

Let's create a simple class, ```Student```, and and let's say it's an empty class. Let's create a couple of instances of it, ```student1``` and ```student2```. Are these two ```Student```s equal? 

```py
	>>> class Student: pass
	... 
	>>> student1 = Student()
	>>> student2 = Student()

```

```id(student1)``` gives you an indication of where it is stored in memory.

```py
	>>> id(student1)
	4554811768
	>>> id(student2)
	4554811992

```

These two are different objects with different values returned by `id`. 

You can use `is` to compare objects. With ```student1 is student2``` , what we're really comparing is where they are stored. Is it the same location? Is ```student1``` the same object as ```student2```? 
```py
	>>> student1 is student2
	False
```
The answer is No.

Let's create a new variable `student3` as shown below. You can see that `student3` and `student1` are referring to the same location. `student1 is student3` returns `True`.

```py
	>>> student3 = student1
	>>> id(student3)
	4554811768
	>>> id(student1)
	4554811768
	>>> student1 is student3
	True

```

In Python, you can use ```==``` to check equality. The default implementation of ```==``` uses ```'is'```. 
```py
	>>> student1 == student2
	False
	>>> student1 == student3
	True

```

Let's create the ```Student``` ```class``` again, but this time with a constructor. We are creating a simple class, which can have in it, a constructor accepting an ```id```.  We have also added in an implementation of `def __eq__(self, other)` comparing the id's.

```py
	>>> class Student:
	...    def __init__(self, id):
	...       self.id = id
	...    def __eq__(self, other):
	...       return self.id == other.id
	...
```

Let's update the definitions of our students. If you look at these objects, ```student4``` and ```student1``` are referring to the same object, aren't they! 
```py
 
	>>> student1 = Student(1)
	>>> student2 = Student(2)
	>>> student3 = Student(1)
	>>> student4 = student1

```

All statements except for ```student1 is student4``` return `False`. 

```py
	>>> student1 is student4
	True
	>>> student1 is student2
	False
	>>> student1 is student3
	False
	>>> student1 == student3
	False

```

Are ```student4``` and ```student1``` equal? They are pointing to the same object. They are definitely equal. 
```py
	>>> student4 == student1
	True

```

Is ```student2``` == ```student1```? ```False```, because they have different ```id```s. 
```py
	>>> student2 == student1
	False

```

Let's see if ```student3 == student1``` Interesting to note, because we have now provided our own implementation of ```==```. 
```py
	>>> student3 == student1
	True

```


If you are defining a class, and you would want equality for that class to be looking at the content of the class, then we would need to override the ```__eq__``` method. When you compare objects using ```==``` , the ```__eq__``` method would be called. 
