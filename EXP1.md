# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 13-03-205                                                                            
### REGISTER NUMBER : 212222040182

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
### 1.Do...While
```
def display(): 
    start=input("Enter a positive value for START: ") 
    end=input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric(): 
        while True: 
            start=int(start) 
            end=int(end) 
            print(start,end='') 
            if start<end: 
                start+=1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.") 
display()

```
### 2.While...Do
```
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric(): 
    start=int(start) 
    end=int(end) 
    while start<end: 
        print(start) 
        start+=1 
else:
    print("Enter a valid positive number.")

```
### 3.Switch
```
def switch(): 
    switcher={ 
    0:"even", 
        1:"odd" 
    } 
    n=input('Enter a value for N: ')
    try: 
        n=int(n) 
        print(switcher[n%2]) 
    except ValueError: 
        print("Enter a valid number.")
switch()

```
### 4.If...Else
```
def compare(): 
    a=input("Enter a value for A: ") 
    b=input("Enter a value for B: ") 
    try: 
        a=int(a) 
        b=int(b) 
        if a>b: 
            print("A is greater than") 
        elif a<b: 
            print("B is greater than") 
        else: 
            print("A is equal to B") 
    except ValueError: 
        print("Enter a valid number.")
compare()

```
### 5.For
```
def iterate(): 
    string=input("Enter a string: ")
    for i in string: 
        print(ord(i),end=" ")
iterate()

```

### Output:
### 1.Do...While:
![Screenshot 2025-03-13 083612](https://github.com/user-attachments/assets/582f8376-dc06-4449-b19d-339a88216244)

### 2.While...Do:
![Screenshot 2025-03-13 083817](https://github.com/user-attachments/assets/2a33feac-9b3e-4474-b6a1-3f28c46474cd)

### 3.Switch:
![Screenshot 2025-03-13 083953](https://github.com/user-attachments/assets/88a8fa5b-42ab-4172-b77a-a59628972278)

### 4.If...else:
![Screenshot 2025-03-13 084308](https://github.com/user-attachments/assets/7bb5bbd8-52d0-4814-bcb8-9910936c6399)

### 5.for:
![Screenshot 2025-03-13 084936](https://github.com/user-attachments/assets/f9b60dfd-c617-4f3c-9d4a-e616ab590c4c)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


