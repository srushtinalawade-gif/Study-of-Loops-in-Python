# Study-of-Loops-in-Python
## Name- Srushti J. Nalawade
## PRN- 25070123157
## Batch- A1

## Aim: To understand and implement for loops, while loops, and the control statements break, continue, and pass.
## 1. Overview of Looping StructuresTheory: 
Looping is a fundamental programming concept that allows a block of code to execute repeatedly. Python provides two primary mechanisms for iteration:
### For Loop: 
Primarily used for "definite iteration," where the number of repetitions is known or determined by a sequence (like a list, string, or range). It automatically steps through the items in the collection.

Syntax:

   for variable in sequence:
    
        statements

The loop variable takes each value from the sequence one by one, and the statements inside the loop are executed for each value.
### Program:

for i in range(1, 6):
    
    print(i)

Output:

1

2

3

4

5

### While Loop: 
Used for "indefinite iteration," where the loop continues as long as a specific logical condition remains True. It requires a manual update of the loop variable to prevent infinite execution.

Syntax:

while condition:

    statements

The condition is checked before every iteration. If the condition becomes false, the loop terminates.

### Program:

i = 1


while i <= 5:

    print(i)
    
    i += 1

Output:

1

2

3

4

5

Difference Between For Loop and While Loop:

>For loop is used when the number of iterations is known.

>While loop is used when the number of iterations depends on a condition.

>For loop automatically handles iteration over a sequence.

>While loop requires manual updating of the loop variable.

## Title: Study of for loop with break, continue, and pass statements in Python

### Aim:

To study and implement the use of break, continue, and pass statements in a for loop in Python.
Theory:

1.break statement
The break statement is used to terminate the loop immediately when a specified condition is satisfied. Control transfers to the first statement outside the loop.

2.continue statement
The continue statement skips the remaining statements in the current iteration and moves to the next iteration of the loop.

3.pass statement
The pass statement is a null statement. It performs no action and is used as a placeholder where a statement is syntactically required.

for i in range(1, 11):
    
    if i == 3:
        pass       # Placeholder: No action taken, 3 is printed
    
    if i == 5:
        continue   # Skips the print statement for 5
        
    if i == 8:
        break      # Terminates the loop when i reaches 8
        
    print(i)
     
     Output: 1, 2, 3, 4, 6, 7

# Algorithms

1. Factorial of a Number

Start

Initialize loop counter i = 1 and accumulator fac = 1.

Input the target number n.

Repeat while i <= n:

Multiply fac by i.

Increment i by 1.

Print the final value of fac.

Stop

2. Reverse a Number

Start

Input the number a.

Initialize rev = 0.

Repeat while a > 0:

Find the last digit using modulo: dig = a % 10.

Update reverse: rev = (rev * 10) + dig.

Remove the last digit from a using floor division: a //= 10.

Print the reversed number rev.

Stop

3. Count Digits in a Number

Start

Input the number n.

Initialize count = 0.

Repeat while n > 0:

Increment count by 1.

Remove the last digit: n //= 10.

Print the value of count.

Stop

4. Armstrong Number

Start

Input number N as a string to easily iterate over characters.

Initialize total = 0.

Repeat for each character i in N:

Convert i to integer and raise it to the power of the length of N.

Add the result to total.

Condition Check: If total is equal to the integer value of N:

Print "It is an Armstrong Number".

Else, Print "It is not an Armstrong Number".

Stop

5. All Possible Combinations of 3 Digits

Start

Input a 3-digit number N.

Extract each digit and store them in a list d.

Use three nested loops (i, j, k) to iterate through the indices (0 to 2) of the list d.

Condition Check: Within the innermost loop, check if i, j, and k are all distinct (i != j, j != k, and k != i).

Print the combination d[i], d[j], d[k] if the condition is met.

Stop

## Conclusion: 
This experiment successfully explored the syntax and logic of Python loops. We verified that for and while loops serve different iterative needs, while control statements like break, continue, and pass offer precise management over how and when code blocks are executed.
