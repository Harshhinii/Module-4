## PYTHON PROGRAMMING MODULE 4
## NAME: HARSHINI R
## REGISTER NUMBER: 212223220033
## Ex 01: Calculate the Area of a Circle
##  Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

##  Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

##  Program
```
import math

class cse:
    def mech(self, r):
        c = math.pi * r**2
        print(f"Area of circle: {c:.2f}")

r = int(input("Enter radius: "))
ci = cse() 
ci.mech(r)
```

## Output

<img width="1046" height="512" alt="604177071-c2a7b0b4-133a-4122-b13c-b922cc144357" src="https://github.com/user-attachments/assets/a5b5439f-c59e-4170-887b-9712b22cbc5a" />


## Result
Thus, the program that calculates the area of a circle based on the radius provided by the user

## Ex 02: Merging Two Dictionaries

##  Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

##  Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

##  Program

```
dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}
dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}

def merge(dict1, dict2):
    res = {**dict1, **dict2}
    return res

dict3 = merge(dict1, dict2)
print(dict3)
```


## Output

<img width="1047" height="180" alt="604177416-cc8d94f4-3bbf-4aa9-84f9-08dba5254d7d" src="https://github.com/user-attachments/assets/0275803f-d254-4d89-a76d-78cd60d80465" />


## Result
Thus, the program that merges two dictionaries and combines their key-value pairs was executed successfully.

#  Ex 03: Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

##  Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

##  Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## Program
```
d={2:56,1:2,5:12,4:24,6:18,3:323}
l=[]
for i in d:
    l.append(i)
l.sort()
print("Keys and Values sorted in alphabetical order by the key")
for i in l:
    print(tuple([i,d[i]]),end=" ")
```
## Sample Output

<img width="1044" height="305" alt="604177890-9912c28f-d85e-4921-a6c0-2b750b3b3de3" src="https://github.com/user-attachments/assets/0c0536af-9ea8-4a5d-9a35-1a510f80ed23" />


## Result
Thus, the program that sorts a dictionary's Keys and Values in alphabetical order was executed successfully.

#  Ex 04: Avoiding Index Errors

##  Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

##  Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

##  Program
```
msg="You're out of list range"
lst=[5, 10, 20]

try:
    
    print(lst[5])

except:
    print(msg)

```

## Output

<img width="503" height="127" alt="604179395-90ac5d5f-7c02-4e0b-9897-9458636e805d" src="https://github.com/user-attachments/assets/033fd63c-d60f-42ce-8c58-b45a5840d805" />

## Result
Thus, the program to handle exceptions and avoid index errors in Python was executed successfully

# Ex 05: Count Lines Not Starting with 'T'

##  Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

##  Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

##  Program
```

def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)


def merge_files(file1_path, file2_path, output_file_path):
    f1=open(file1_path,"r")
    f2=open(file2_path,"r")
    f3=open(output_file_path,"w")
    f3.write(f1.read())
    f3.write(f2.read())
    


def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()

```

## Output

<img width="891" height="397" alt="604179130-59e8b3f3-00b2-46a6-89bc-f00bf5050b42" src="https://github.com/user-attachments/assets/0d230837-a034-4160-8e95-c51b08199f6e" />


## Result
Thus, the program to merge two files into a third file using File Handling in Python was executed successfully
