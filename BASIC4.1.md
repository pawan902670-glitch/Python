

1. Sum of First N Numbers

Add numbers from 1 to n

n = int(input("Enter number: "))
sum = 0

for i in range(1, n+1):
    sum = sum + i

print("Sum =", sum)

Example (n=5)
1 + 2 + 3 + 4 + 5 = 15


---

2. Even Numbers from 1 to N

n = int(input("Enter number: "))

for i in range(1, n+1):
    if i % 2 == 0:
        print(i)

Output for n=10
2 4 6 8 10


---

3. Odd Numbers from 1 to N

n = int(input("Enter number: "))

for i in range(1, n+1):
    if i % 2 != 0:
        print(i)


---

4. Sum of Digits of a Number

Example:
Input = 1234
Output = 1+2+3+4 = 10

n = int(input("Enter number: "))
sum = 0

while n > 0:
    digit = n % 10
    sum = sum + digit
    n = n // 10

print("Sum of digits:", sum)


---

5. Check Prime Number

n = int(input("Enter number: "))
count = 0

for i in range(1, n+1):
    if n % i == 0:
        count += 1

if count == 2:
    print("Prime Number")
else:
    print("Not Prime")

Example
7 → Prime


---

6. Multiplication Table (Full Tables)

for i in range(1,11):
    for j in range(1,11):
        print(i*j, end=" ")
    print()

This is an example of Nested Loop

Outer loop → rows
Inner loop → columns


---

7. Star Pattern (Basic)

*
**
***
****
*****

for i in range(1,6):
    print("*"*i)


---

8. Nested Loop Star Pattern

*
**
***
****
*****

for i in range(1,6):
    for j in range(i):
        print("*", end="")
    print()


---

9. Reverse Star Pattern

*****
****
***
**
*

for i in range(5,0,-1):
    print("*"*i)


---

10. Number Pattern

1
12
123
1234
12345

for i in range(1,6):
    for j in range(1,i+1):
        print(j,end="")
    print()


---

Important Concepts of Loops

1. for Loop

Used when number of iterations is known

Example

for i in range(5):
    print(i)


---

2. while Loop

Used when condition based loop

while condition:
    statement


---

3. range() Function

range(start, stop, step)

Example

range(1,10) → 1 to 9
range(1,10,2) → 1 3 5 7 9


---

4. Nested Loop

Loop inside another loop.

Example

for i in range(3):
    for j in range(3):
        print(i,j)

Output

0 0
0 1
0 2
1 0
1 1
1 2
2 0
2 1
2 2


---

Important Logic Questions (Very Common)

You should practice these:

1. Prime number


2. Fibonacci series


3. Factorial


4. Reverse number


5. Palindrome


6. Sum of digits


7. Armstrong number


8. Star patterns


9. Multiplication table


10. Number patterns

