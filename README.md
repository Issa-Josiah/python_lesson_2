# Variable and data types

- Variable --> container of storing this

 Data types
1. text types --> str

                                slicing
                                Helllo world
                                H --> 0
                                e --> 1
                                l --> 2 
                                l --> 3
                                o --> 4

slicing has this format  -->[starting : ending point]
 
 starting  0
ending point -1 

Example

            a = Government -->str
G --> 0
o --> 1

t --> -1

            print(Government[0:]);
            print(Government[-1:]);

2. Numeric types --> int, float, complex

            a = 10; --> integer (int)
            b = 10.01   --> float
            c = 2 + 3j; --> complex number


            f = 10;
            g = 13;

f > g   --> is this true or false
f = g   --> is this true or false
f < g   --> is this true or flase

next lesson

    If condition
    elif
    else
    for loop 
    while loop
    do while loop
    break
    continue


concluding
steps
1. GO your github and create a repository
2. I will send a link. go copy the link 
3. to your terminal write 
   
            git clone (link)

4. Check the read me for the practice work
5. create a new py file call it lesson2.py
6.  Practice todays work.
7. in the repository you created initialise you git repository

        git remote add origin https://github.com/Issa-Josiah/python_lesson_2.git

8. Save your work by doing what?

        --> git init
        --> git add .
        --> git commit -m "first lesson(any information you want")"
        --> git branch -M first
        --> git push -u origin first 


9. A dd me as collaborator
--> settings
--> press colaborators
--> add people
-->add my user name

        Issa-Josiah


I will review the work and teh corrections.




# PRACTICE WORK

*** 1. Personal Profile Generator  ***
Create variables:

name (string)

age (int)

height (float)

is_student (boolean)

Print a formatted introduction using an f-string.


output
Hello, my name is John.
I am 25 years old.
My height is 5.9 feet.
Student status: True

*** 2. Simple Calculator( this uses operators) if not possible i can touch on it later  ***
example
a = 1
b =2 
c = a+ b
print c

(you can set an input to do this in the output)
Create:

        num1
        num2
        Print:
        Addition
        Subtraction
        Multiplication
        Division
        Use f-strings for output.

*** 3. Name Formatter ***
format

            name = "john"
            reversed_name = name[::-1]

            print(reversed_name)

Tasks:
full_name = "Okal Gabriel"

Capitalize the first letter of first and last name
format

        name = "john"
        print(name.upper())

Print initials using slicing
Reverse the name using slicing

*** 4. casting practice  ***

Ask user for age using input()
format

             x = input("age of the use: ")

Convert to integer using casting.

NOTE: DONT USE F-STRINGS

*** 5. extra not shown .  ***
To ask to enter a value in the output you use input
example

        x = input("age of the use: ")

using this knowledge you can 
process
 a. prompt one to enter their name
 b. prompt someone to enter their age
 c. set a norminal age
 d. compare the ages 
 e. print out a fixed statement saying 

                (name) is (age) yrs old and their approval to learn is (booolean)