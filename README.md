<img src="https://media.discordapp.net/attachments/896783689176977508/906387936319275018/explosion-14066.png" align="right" width=200 height=200>

# Sodium Programming Language
Sodium is a general purpose programming language which is instruction-oriented (a new programming concept that we are developing and devising)

# Contact
<img src="https://cdn.icon-icons.com/icons2/2108/PNG/512/discord_icon_130958.png" width="200" height="200">
<br>
Valcan#1407 (The assistant developer)

# Running The Code
## In Python
1. Find the main program, [sodium.py](srcpy/sodium.py)
2. Open your terminal
3. `python sodium.py [sodium_program_name]`

## In C
We have not done the C version yet, sorry

# Introducing The Concept of Instruction Oriented Programming
Instruction-oriented programming is a new programming concept which is a little bit similar to the historical significant programming concept, functional programming. The basic concept of instruction oriented programming is simple:
Every keyword is an instruction

```python
print "Hello, World!"
```

```python
store "Hello, World!" msg
```

Defining a function is tantamount to appending a new keyword

`define myPrint msg`
<br>
```python
print "My print: " + msg
```
<br>
`end`
<br>
```python
myPrint "Hello World!"
```

Output:

`My print: Hello World!`

There are several advantages of an instruction-oriented programming language. Firstly, the syntax of the language would be eminently simple compared to some highly complicated programming languages such as Python, Java, and C. Secondly, theoretically these kinds of languages would be remarkably efficient due to the simplicity of their syntax. Last but not least, instruction oriented programming languages would be more nimble than procedural and functional programming languages. While the traditional programming languages are rapidly improving, the new concepts of programming are also developing in a very fast way. I truly believe that the concept of instruction-oriented programming will contribute to the contemporary programming area if we continuously contribute to the instruction-oriented programming language.
	As you can see, the syntax of an instruction oriented programming language is accessible and casual. The first token of a statement is always a keyword, and the tokens behind are the arguments of the keyword, yet we call them connectors because they serve as connectors or interfaces between programmers and the interpreter. The keywords in here are called instructions because they look like separate commands to a computer, that is the reason why this type of programming languages are named as instruction oriented programming languages. Compared to languages like C++ and Java, this type of language has advantages in readability.

# Basis
> Hello World

```python 
print "Hello World!"
```

> Variable

```python
store 3.1415926 pi
```
<br>
```python
store "GPA 4.0" gpa
```

> Defining Instruction

```python
define Person name age gender
    print name + "is a "
    print age
    print " year-old " + gender
end
```

Use an instruction:

```python
Person "Satin Wuker" 13 "male"
```
