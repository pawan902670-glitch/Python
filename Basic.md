
---

Python Conditional Statements (if–else)

Conditional statements allow a program to make decisions based on conditions.

In Python, the main conditional statements are:

if

if-else

if-elif-else


They execute different code depending on whether a condition is True or False.


---

1. Program to Check Positive or Negative Number

Code

n = int(input("Enter the number"))

if (n > 0):
    print("Number is positive +")
else:
    print("Number is negative -")

Step-by-Step Explanation

1. Taking input

n = int(input("Enter the number"))

input() takes value from the user.

Input is normally stored as string.

int() converts the input into an integer number.

The value is stored in variable n.


Example:

Enter the number: -1


---

2. Checking condition

if (n > 0):

if checks whether a condition is True or False.

n > 0 means the number is greater than zero.

If the condition is True, the code inside if runs.



---

3. Printing result

print("Number is positive +")

This prints the message if the number is positive.


---

4. Else statement

else:
    print("Number is negative -")

else runs when the if condition is False.

If the number is not greater than 0, it prints negative.



---

Example Output

Enter the number: -1
Number is negative


---

2. Program to Check Even or Odd Number

Code

n = int(input("Enter the number"))

if (n % 2 == 0):
    print("Number is even")
else:
    print("Number is odd")


---

Step-by-Step Explanation

1. Input from user

n = int(input("Enter the number"))

User enters a number which is stored in n.


---

2. Modulus Operator

n % 2

% is called the modulus operator.

It returns the remainder after division.

Examples:

Expression	Result

4 % 2	0
5 % 2	1



---

3. Condition

if (n % 2 == 0):

If the remainder after dividing by 2 is 0, the number is even.


---

4. Output

print("Number is even")

If condition is true.

Otherwise:

print("Number is odd")


---

Example Output

Enter the number: 5
Number is odd


---

3. Program to Print Number in Words (1–5)

Code

n = int(input("Enter the number"))

if (n == 1):
    print("One")

if (n == 2):
    print("Two")

if (n == 3):
    print("Three")

if (n == 4):
    print("Four")

if (n == 5):
    print("Five")

if (n < 0 or n > 5):
    print("Invalid Number")


---

Step-by-Step Explanation

1. Input

n = int(input("Enter the number"))

The user enters a number.


---

2. Equality Operator

n == 1

== checks if two values are equal.

Example:

Expression	Meaning

n == 1	n is equal to 1
n == 2	n is equal to 2



---

3. Printing word

If user enters:

1 → One
2 → Two
3 → Three
4 → Four
5 → Five

Example:

Enter the number: 3
Three


---

4. Logical Operator

if (n < 0 or n > 5):

or is a logical operator.

Condition becomes True if either side is true.

Meaning:

number less than 0
OR

number greater than 5


Then the program prints:

Invalid Number

Example:

Enter the number: 6
Invalid Number


---

Important Operators Used

Operator	Name	Example

>	Greater than	n > 0
%	Modulus	n % 2
==	Equal to	n == 1
or	Logical OR	n < 0 or n > 5



---

Important Concept: Indentation

Python uses indentation (spaces) to define code blocks.

Example:

if n > 0:
    print("Positive")

The space before print shows it belongs to the if block.

Without indentation, Python gives an error.


---

Better Version of the Third Program (Using elif)

n = int(input("Enter the number"))

if n == 1:
    print("One")
elif n == 2:
    print("Two")
elif n == 3:
    print("Three")
elif n == 4:
    print("Four")
elif n == 5:
    print("Five")
else:
    print("Invalid Number")

elif means else if and makes the program cleaner.


---

✅ Summary

if checks a condition.

else runs when condition is false.

% operator helps check even/odd.

== compares two values.

or checks multiple conditions.

Python requires indentation.
