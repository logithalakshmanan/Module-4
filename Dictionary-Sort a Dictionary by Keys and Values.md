# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

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

## 🧪Program
d={1:10,2:20,3:30,4:40,5:50,6:60}
sorted_keys=sorted(d.keys())
print("Keys are")
for key in sorted_keys:
    print(key,end=' ')

## Sample Output
	Expected	Got	
Keys are
1 2 3 4 5 6
Keys are
1 2 3 4 5 6

## Result
Dictionary-Python Program to Sort a Dictionary by Keys and Values ia verified

