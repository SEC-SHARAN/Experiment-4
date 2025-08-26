# Experiment-4
## ARMSTRONG NUMBER 
# Aim
Write a python program to check the number is Armstrong number or not and inspect for failures. 
# Name: SHARAN S
# Register number: 212224040309
# Algorithm
1.	Start the program.
2. Read an integer input number.
3. Initialize the variables current_digit, sum = 0, and num = number.
4. Repeat Steps 5 to 7 until num > 0
5. current_digit = (num % 10).
6. sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7. num = num / 10.
8. Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9. Stop the program. 

# Program

```
number = int(input("Enter a number: "))
num = number
sum = 0

while num > 0:
    digit = num % 10
    sum += digit ** 3
    num //= 10

if sum == number:
    print("It is an Armstrong Number.")
else:
    print("It is not an Armstrong Number.")

```
# Output
<img width="414" height="316" alt="image" src="https://github.com/user-attachments/assets/668c77cd-a457-4a54-81cd-e717c94ff8c3" />
<img width="419" height="312" alt="image" src="https://github.com/user-attachments/assets/1b347a32-6b78-4e74-a084-86b426414f8c" />


# Result
Thus, the python program to check the number is Armstrong number or not and inspect for failures.
