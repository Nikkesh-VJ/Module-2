#Exp.No:2(b)	FUNCTIONS-PERFECT NUMBER
- **Name:** Nikkesh V
- **Registration Number:** 212222050042


### AIM
To write a Python Program to check if a number is a Perfect number using the concept of functions.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Read the number n from the user using input().

Step 3:	 Convert the input to an integer.

Step 4:	 Define the Function perfectNumber(n) with below steps.

Step 5:	 Initialize a variable factor_sum to 0

Step 6:	Iterate through all numbers from 1 to n//2 (as divisors of a number can't be greater than half of it).

Step 7:	If a number i divides n perfectly (i.e., n % i == 0), add i to factor_sum.

Step 8:	If factor_sum is equal to n, then print the number is a perfect number.Otherwise, print it's not a perfect number.

Step 9:	 Terminate the program.


### PROGRAM


```
def perfectnumber(n):
    factor_sum=0
    for i in range(1,n//2+1):
        if(n%i==0):
            factor_sum+=i
    if(n==factor_sum):
        print("The number is a Perfect number!")	
    else:
        print("The number is not a Perfect number!")
num=int(input())
perfectnumber(num)
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/cc9562f9-e9f5-4989-82fc-6fcea0ec493f)

### RESULT
Thus the python program to check if a number is a perfect number or not has been implemented and executed successfully.
