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
my_list=["Cion","Alice","Bob"]

try:
    print(my_list[5])
except IndexError:
    msg="You're out of list range"
    print(msg)

## Output
Expected	Got	
You're out of list range
You're out of list range


## Result
 File Handling in Python: Count Lines Not Starting with 'T' is verified
