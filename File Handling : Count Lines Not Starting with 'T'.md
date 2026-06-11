# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
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

<img width="891" height="397" alt="568127807-33d0f5bf-d853-44fa-8e5b-8f9a34450c03" src="https://github.com/user-attachments/assets/59e8b3f3-00b2-46a6-89bc-f00bf5050b42" />


## Result
Thus, the program to merge two files into a third file using File Handling in Python was executed successfully
