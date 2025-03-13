# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 13.03.2025                                                                        
### REGISTER NUMBER : 212222040104

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
~~~
def display():
    start=input("Enter first number: ")
    end=input("Enter last number: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=' ')
            if start<end:
                start=start+1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
~~~
ii). while...do
~~~
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start=int(start)
    end=int(end)
    while start<=end:
        print(start)
        start+=1
else:
    print("Enter a valid positive number.")
~~~
iii). if...else
~~~
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
~~~
iv). switch
~~~
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
~~~
v). for
~~~
def iterate():
    string=input("Enter a string: ") 
    for i in string:
        print(ord(i),end=" ")
iterate() 
~~~


### Output:
i). do...while
![do while](https://github.com/user-attachments/assets/101bb8cf-e2ea-4d13-9b1d-ef847f1e0a88)

ii). while...do
![while do](https://github.com/user-attachments/assets/f87a9047-1b3e-4b3c-8d0e-82c9e61501f7)

iii). if...else
![if else](https://github.com/user-attachments/assets/a8f95842-d677-4819-9c85-4bca92d8becb)

iv). switch
![switch](https://github.com/user-attachments/assets/9716538a-e6e2-41bd-9588-bc20f2f5fc6d)

v). for
![for op](https://github.com/user-attachments/assets/40af7275-a50a-4f1c-99dc-f60f87fa970c)






### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


