## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Python is a programming language that is both general-purpose and high-level.

Q2. Why is Python called a dynamically typed language?

In python we don't need to declear variable type while a creating variable 

Q3. List some pros and cons of Python programming language?

- pros
    - Easy learn
    - Free and Open Source
    - object-oriented languange  
    - A vast collection of libraries
- cons
    - Consumes a lot of memory space
    - Not easy to test
    - Python is not so strong in mobile computing

Q4. In what all domains can we use Python?

- Machine learning / Artificial intelligence
- Desktop GUI
- Data analytics and data visualization 
- Web development
- Embedded systems


Q5. What are variable and how can we declare them?

Variable is a basic unit of data storage point,In python is a dynamically typed language we don't declare type while creating a variable 

Syntax
    
    data_type variable_name = value

Q6. How can we take an input from the user in Python?

By using 'input' keyword we take input from the user

syntax

    variable_name = input(String)

Q7. What is the default datatype of the value that has been taken as an input using input() function?

    String

Q8. What is type casting?

Converting one data type to another type
- int()
- float()
- str()

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Yes, By using Split() we can take multiple inputs with a single input() function

Q10. What are keywords?

Keywords are pre-defined reserved words that have a specific purpose and usage to them. we can not use any keyword as a variable name.



Q11. Can we use keywords as a variable? Support your answer with reason.

No, keyword can't use ad variable beacuse keyword are predefined keywords in python

Q12. What is indentation? What's the use of indentaion in Python?

Indentation is spaces begin of the code, In python, they are used to indent the code blocks

Q13. How can we throw some output in Python?
 
 we can use the keyword 'print' to show the output in the console

Q14. What are operators in Python?

operators are to perform Arithmetic, Assignment, Comparison, Logical and Bitwise operations on variables

Q15. What is difference between / and // operators?

/ : Divide left operand by the right one (always results into float)

// : Floor division - division that results into whole number adjusted to the left in the number line

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
    print("iNeuroniNeuroniNeuroniNeuron")

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

    x=int(input("enter a number:"))
        if(x%2==0):
            print(x,"is even number")
        else:
            print(x,"is a odd number")


Q18. What are boolean operator?

boolean is True or False 

boolean operator are:
- not
- and
- or


Q19. What will the output of the following?
```
1 or 0
Ans 1

0 and 0
Ans 0

True and False and True
Ans False

1 or 0 or 0
Ans 1

```

Q20. What are conditional statements in Python?

Condtitonal statement are use decision based flows
 - if statement
 - if-elif-else statement
 - if-else statment

Q21. What is use of 'if', 'elif' and 'else' keywords?

if is the start of flow checks the expression and passes through the if the expression is true to execute the statement and comes out of condition else passes to elif condition there again interpreter checks the expression and its true execute the statement else goes to else part its a default statement if a condition fails then default flow goes to the else part.

syntax

    if(expression):
        Statement...
    elif(expression):
        Statement...
    else:
        default Statement...

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

    age= int(input("enter a your age:"))
    if(age >= 18):
        print("I can vote")
    elif(age <18):
        print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
sum=0
for i in numbers:
    if(i%2==0):
        sum=sum+i
print(sum)
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

    
    x=int(input("enter a number:"))
    y=int(input("enter a number:"))
    z=int(input("enter a number:"))
    result=[x,y,z]
    print(sorted(result, reverse=True)[0])

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if(i<500):
        if(i!=150 and i%5==0):
            print(i)
    else:
        break

```