# Exp.No:2(c)	BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS- RELATING TWO NUMBERS
- **Name:** Nikkesh V 
- **Registration Number:** 212222050042

### AIM
To write a python program to check the relation between them. That is if one number is greater or equal or lesser than another number using the lambda function.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Use eval() to get the two numbers (num1 and num2) from the user.

Step 3:	 Define a lambda function res that takes two arguments x and y

Step 4:	 The lambda function compares the numbers and prints which one is smaller: If x > y, it prints num2 is smaller than num1. Otherwise, it prints num1 is smaller than num2.

Step 5:	 Call the res Function: Pass num1 and num2 to the lambda function to perform the comparison.

Step 6:	 Terminate the program.

### PROGRAM
```
num1=eval(input())
num2=eval(input())
max=lambda x,y: print(f"{num2} is smaller than {num1}") if x>y else print(f"{num1} is smaller than {num2}")![image](https://github.com/user-attachments/assets/4a3ccdb3-e831-41b8-b783-4f58c664521e)

max(num1,num2)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/d6767aa8-b158-4f19-83f6-af03322a5b9d)


### RESULT
Thus the python program to check a relationship between two numbers has been implemented and executed successfully.
