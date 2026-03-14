

1. Print "Hello" N times

n = int(input("Enter the number: "))

for i in range(n):
    print("Hello")


---

2. Print "Hello" with count (while loop)

n = int(input("Enter the number: "))
count = 1

while count <= n:
    print(count, "Hello")
    count += 1


---

3. Table of a Number

n = int(input("Enter the number: "))

for i in range(1, 11):
    print(n * i)


---

4. Factorial using for loop

n = int(input("Enter the number: "))
fact = 1

for i in range(1, n + 1):
    fact = fact * i

print(fact)


---

5. Factorial using while loop

n = int(input("Enter the number: "))
fact = 1

while n >= 1:
    fact = fact * n
    n = n - 1

print(fact)


---

6. Reverse of a Number

n = int(input("Enter the number: "))
rev = 0

while n > 0:
    digit = n % 10
    rev = rev * 10 + digit
    n = n // 10

print("Reverse:", rev)


---

7. Palindrome Number

n = int(input("Enter the number: "))
temp = n
rev = 0

while n > 0:
    digit = n % 10
    rev = rev * 10 + digit
    n = n // 10

if temp == rev:
    print("Palindrome")
else:
    print("Not Palindrome")


