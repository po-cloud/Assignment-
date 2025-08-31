# Assignment-
assign

#1.Write a program that takes two numbers as variables and prints their sum, difference, product, and quotient.

#two numbers:sum, difference, product, quotient

#variables
a = 10
b = 5

#operations
print("sum:", a + b)
print("Difference:", a - b)
print("Product:", a * b)
print("Quotient:", a / b)
sum: 15
Difference: 5
Product: 50
Quotient: 2.0
#2.Write a program that takes the radius of a circle as a variable and prints its area. Use π = 3.1416.

#area of a circle

#variable
radius = 7
pi = 3.1416

#area
area = pi * radius * radius
print("Area of circle:", area)
Area of circle: 153.9384
#3.Write a program that takes a string and prints it in reverse.

#reverse a string

s = "Hello World"
print("Reversed string:", s[::-1])
Reversed string: dlroW olleH
#4.Write a program that counts the number of words in a sentence. 

#count number o words in a sentence

sentence = "Python is fun to learn"
words = sentence.split() #splits by spaces
print("Number of words:", len(words))
Number of words: 5
#5.Write a program that converts a string to uppercase and then to lowercase.

#convert string to uppercase and lowercase

s = "Python Programming"
print("Uppercase:", s.upper())
print("Lowercase:", s.lower())
Uppercase: PYTHON PROGRAMMING
Lowercase: python programming
#6.Write a program to find the length of String in Python.

#find length of a string

s = "python"
print("Length of string:", len(s))
Length of string: 6
#7.Write a program to remove user defined letters From a String in Python.Note: Use only functions and operations discussed in class. Do not use conditional statements and control loops.

#remove user-defined letters from a string

s = "Hello World"
letters_to_remove = "lo" #remove 'l' and 'o'

for letter in letters_to_remove:
    s = s.replace(letter, "") #replace with empty string

print("String after removal:", s)
String after removal: He Wrd
#8.Difference between implicit and explicit typecasting Use of .strip Use of .find

#difference between implicit and explicit typecasting

#implicit typecasting
x = 5 #int
y = 2.5 #float
z = x + y # x is automatically converted to float
print(z) #7.5

#explicit typecasting
a = "10"
b = int(a) + 5
print(b) #15
7.5
15
#9.Use of .strip

s = "    Hellow World    "
print("Before strip:", repr(s))
print("After strip:", repr(s.strip()))
Before strip: '    Hellow World    '
After strip: 'Hellow World'
#10.Use of .find

s = "Python Programming"
print("Index of 'p':", s.find("p"))
print("Index of 'g':", s.find("g"))
Index of 'p': -1
Index of 'g': 10
