# Experiment No: 1A Python Basics- Printing Multiline String
# AIM
To create a Python program to print the string in multiple lines using triple quotes.

# ALGORITHM
Begin the program.
Use triple quotes (''' or """) to define a string that spans multiple lines.
Use the print() function to display the multi-line string.
Terminate the program.
# PROGRAM
```
# 212223060113
# Karnatam Bindu


print("""I am a string literal
... has more than one
... line
....placed inside triple single quotes
I am a string literal
... has more than one
... line
....placed inside triple double quotes""")
```
# OUTPUT
<img width="1189" height="462" alt="Screenshot 2025-09-02 092052" src="https://github.com/user-attachments/assets/d2199725-cb20-4910-9162-5451bbdf9bb9" />


# RESULT
The program prints a multiline string using both triple single (''') and triple double (""") quotes.


# Experiment No: 1B- Data Types – Printing Integer Literals
# AIM
To write a Python program to print the following integer and float literals: 10,3.14

# ALGORITHM
Begin the program.
Initialize the integer literals 10.
Initialize the float literals 3.14.
Use the print() function to display the numbers 10 and 3.14
Terminate the program.
# PROGRAM
```
# Reg.No-212223060113
# Name-Karnatam Bindu

a=int(input())
b=float(input())
print(a,b)

```

# OUTPUT
<img width="1170" height="310" alt="Screenshot 2025-09-02 093812" src="https://github.com/user-attachments/assets/977bab11-efcb-46cc-8ce0-a47cfa4fcd48" />

# RESULT
The program successfully prints the integer and float literals 10,3.14.

# Experiment No: 1C-Varibles and Expressions, Operators - using two values using all the relational operators
# AIM
To write a Python program for two values using all the relational operators (>,<,>=,<=,== ,!=).

# ALGORITHM
Start
Assign values a = 13 and b = 33
Compare a and b using > , < , >= , <= , == , !=
Print the results of each comparison
Stop
# PROGRAM
```
# Reg.No-212223060113
#Name-Karnatam Bindu

a = 13
b = 33
# a > b is False
print(a > b)
# a < b is True
print(a < b)
# a == b is False
print(a == b)
# a != b is True
print(a != b)
# a >= b is False
print(a >= b)
# a <= b is True
print(a <= b)
```
# OUTPUT
<img width="1196" height="353" alt="Screenshot 2025-09-02 174539" src="https://github.com/user-attachments/assets/3cf97198-7f4e-406c-86bb-b673a61af943" />

# RESULT
Thus, the Python program for comparing two numbers using all relational operators is successfully executed and the above results are obtained.

# Experiment No: 1D – Conditional Statements- Checking Vowel or not
# AIM
To Write a Python program to check whether the given character is a vowel or not using if..else statement

# ALGORITHM
Begin the program.
Take a character input from the user
Convert the character to lowercase
Check if the lowercase character is one of the vowels: 'a', 'e', 'i', 'o', 'u'
If it is a vowel, display "The given character is a vowel"
Otherwise, display "The given character is NOT a vowel"
Terminate the program.
# PROGRAM
```
# Reg.No-212223060113
# Name-Karnatam Bindu
num=int(input())
if num % 2==0:
    if num >=25:
        print(num,"is an Even number")
        print(num,"is greater than or equal to 25")
    else:
        print(num,"is an Even number")
        print(num,"is lesser than 25")
else:
   print(num,"is NOT an Even number")
```
# OUTPUT
<img width="1057" height="327" alt="Screenshot 2025-09-02 180605" src="https://github.com/user-attachments/assets/3879d3d0-21a1-4647-bf85-2a5f7ffcd952" />

# RESULT
A Python program to check whether the given character is a vowel or not using if..else statement has been implemented and executed successfully.

# Experiment No: 1E – SEB-Minimum of Three Numbers
# AIM
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

# ALGORITHM
Begin the program.
Read the three numbers: num1, num2, and num3 from the user.
Compare num1, num2, and num3 to find the smallest number:
If num1 is less than or equal to both num2 and num3, then num1 is the minimum.
Else, if num2 is less than or equal to both num1 and num3, then num2 is the minimum.
Otherwise, num3 is the minimum.
Print the minimum value along with the input numbers in the format:
"The minimum of num1, num2, num3 is min_num."
Terminate the program.
# PROGRAM
```
# Reg.No-212223060113
# Name-Karnatam Bindu
num1 = int(input())
num2 = int(input())
num3 = int(input())
min_num = num1 if (num1 <= num2 and num1 <= num3) else num2 if (num2 <= num1 and num2 <= num3) else num3
print(f"The minimum of {num1}, {num2}, {num3} is {min_num}")
```
# OUTPUT
<img width="1194" height="417" alt="Screenshot 2025-09-02 181914" src="https://github.com/user-attachments/assets/5cc59808-3a5b-458f-b5ae-5561b5e3ec46" />

# RESULT
Thus the python program for finding a minimum of three numbers has been implemented and executed successfully.
