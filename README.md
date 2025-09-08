# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
 DO WHLIE
 def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)

        while True:
            print(start, end=' ')  # Corrected quote

            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")

display()
## Output
<img width="577" height="81" alt="image" src="https://github.com/user-attachments/assets/61291f20-1a5f-420b-837f-6de522596a1f" />
 WHILE DO
 start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
##OUTPUT
<img width="850" height="169" alt="image" src="https://github.com/user-attachments/assets/a34078bc-cce4-4a18-b6c5-f8ef1cbafa8c" />

 IF ELSE
 def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)

        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")

compare()
##OUTPUT
<img width="868" height="80" alt="image" src="https://github.com/user-attachments/assets/aa5dd9e1-0c3b-4f86-9487-20eeca237898" />
SWITCH
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }

    n = input("Enter a value for N: ")
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
##OUTPUT
<img width="859" height="67" alt="image" src="https://github.com/user-attachments/assets/4b24f750-54ed-40e7-9662-2e90e73bc81d" />
FOR 
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
##OUTPUT
<img width="864" height="62" alt="image" src="https://github.com/user-attachments/assets/ddca9b9c-07be-4166-865d-e9aa302be14a" />

## Result
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.



