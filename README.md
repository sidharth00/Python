# Python
# Q1. Explain the key features of Python that make it a popular choice for programming. • There are many key features of python that make it popular, as shown below a. Simple and Readable Syntax b. Interpreted Language c. Dynamically Typed d. Extensive Standard Library e. Large Ecosystem of Libraries and Frameworks f. Cross-platform Compatibility g. Community Support h. Object-Oriented and Functional Programming Support i. suitable for Rapid Prototyping j. Integration Capabilities

Q2.Describe the role of predefined keywords in Python and provide examples of how they are used in a program. -Predefined keywords (also known as reserved words) in Python are words that are built into the language and have special meaning. we cannot use them as variable names, function names, or identifiers because Python uses them to define its syntax and structure. -Examples of Python Keywords in Use


[6]
0s
# 1. if, else, elif – Used for decision-making

marks = 63
if marks>33:
  print("you pass this exam")
else:
  print("you fail this exam")
  

you pass this exam

[10]
0s
# 2. for, in, range – Used for looping
a = "Sidharth"
for i in a:
  print(i, end=" ")

S i d h a r t h 
. Compare and contrast mutable and immutable objects in Python with examples. -mutable objects--->are those variables or objects which can be change anytime after they created in the code. EXAMPLE: 1.list

-immutable onjects--->are those keywords or abjects which Cannot be changed after creation and we do any change in it i will becomes a new object. EXAMPLE: Examples:1.Tuple


[34]
#mutable
my_data = [1, 2, 3]
print("Original data:", my_data)
Original data: [1, 2, 3]

[36]
0s
#immutable
my_string = "Sidharth"
print("Original String:", my_string)
Original String: Sidharth
Discuss the different types of operators in Python and provide examples of how they are used. ● In Python, operators are special symbols or keywords used to perform operations on variables and values. There are several types of operators, each serving a different purpose.
a.) Arithmetic Operators: Perform basic math operations.


[40]
0s
#Example for arithmetic operators

a = 10
b = 3
print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)
print("Floor Division:", a // b)
print("Modulus:", a % b)
print("Exponentiation:", a ** b)




Addition: 13
Subtraction: 7
Multiplication: 30
Division: 3.3333333333333335
Floor Division: 3
Modulus: 1
Exponentiation: 1000

[42]
0s
#Example for assingnment operator
x = 5
x += 3
print("x after += 3:", x)
x -= 2
print("x after -= 2:", x)
x *= 4  # x = x * 4
print("x after *= 4:", x)
x /= 6  # x = x / 6
print("x after /= 6:", x)

x after += 3: 8
x after -= 2: 6
x after *= 4: 24
x after /= 6: 4.0

[43]
0s
#Example of Rlearional Operator
a=3
b = 10
print("a == b:", a == b)
print("a != b:", a != b)
print("a > b:", a > b)
print("a < b:", a < b)
print("a >= 5:", a >= 5)
print("b <= 9:", b <= 9)

a == b: False
a != b: True
a > b: False
a < b: True
a >= 5: False
b <= 9: False

[44]
0s
#Example for Logical Operators
x = 7
print("x > 5 and x < 10:", x > 5 and x < 10)
print("x < 5 or x > 10:", x < 5 or x > 10)
print("not(x == 7):", not(x == 7))

x > 5 and x < 10: True
x < 5 or x > 10: False
not(x == 7): False

[45]
0s
#Example for Bitwise Operators
a = 5
b = 3
print("a & b:", a & b)
print("a | b:", a | b)
print("a << 1:", a << 1)
print("a >> 1:", a >> 1)

a & b: 1
a | b: 7
a << 1: 10
a >> 1: 2
Q5. Explain the concept of type casting in Python with examples Type casting means converting one data type into another. Python provides built-in functions to convert between different data types like int, float, str, etc. -There are two type of type casting

Implicit Type Casting (Python does it automatically).
Explicit Type Casting (we do it manually using functions).

[47]
0s
# Implicit type casting
a = 5
b = 2.0
result = a + b
print(result)

7.0

[49]
0s
a=5
b=2.0
print (type(a))
print (type(b)) 
print (type(result))

<class 'int'>
<class 'float'>
<class 'float'>

[51]
0s
# Explicit type casting
num_str = "42"
num_int = int(num_str)
num_float = float(num_str)
print(num_int + 10)
print(num_float + 0.5)

52
42.5
Q6. How do conditional statements work in Python? Illustrate with examples ? -Conditional statements lets our program choose different paths based on whether a condition is True or False. In Python, the main conditional keywords are: if elif (else if)


[53]
0s
#Example for conditional statement
marks = 75
if marks >= 90: print("Grade: A")
elif marks >= 70: print("Grade: B")
elif marks >= 50: print("Grade: C")
else:
  print("Grade: F")


Grade: B
Q7.Describe the different types of loops in Python and their use cases with examples.

1.Forloop 2.While loop 3.Nested Loop 4.Loop Control Statement 5.continue

Else in Loop

[54]
0s
#for loop
for i in range(1, 6):
  print("I love India", i)
  
I love India 1
I love India 2
I love India 3
I love India 4
I love India 5

[69]
0s
# While Loop
count=0
while count<5:
  print("count",count)
  count+=1
  

count 0
count 1
count 2
count 3
count 4

[74]
#Nested Loops
for i in range(3):
  for j in range(2):
    print(f"i={i}, j={j}")

i=0, j=0
i=0, j=1
i=1, j=0
i=1, j=1
i=2, j=0
i=2, j=1

[88]
0s
#Loop control statement
for num in range(1, 11):
    if num == 5:
        break
    else:
        print(num)


1
2
3
4

[94]
#continue
num = 0
while num < 10:
    num += 1
    if num == 6:
        continue
    print(num)



1
2
3
4
5
7
8
9
10

[105]
0s
for i in range(3):
  print(i)
else:
  print("loop breaks")


0
1
2
loop breaks
