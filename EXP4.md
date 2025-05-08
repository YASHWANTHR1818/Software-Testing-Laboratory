# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE:                                                                            
### REGISTER NUMBER : 
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:
```
number = int(input("Enter a number: "))
sum = 0
num = number

while num > 0:
    current_digit = num % 10
    sum += current_digit ** 3
    num //= 10

if sum == number:
    print("It is an Armstrong Number.")
else:
    print("It is not an Armstrong Number.")
```














### Output:
![WhatsApp Image 2025-05-08 at 08 18 26_c74918fb](https://github.com/user-attachments/assets/cb168054-ae29-4db5-9a96-3d062c6c105b)








### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


