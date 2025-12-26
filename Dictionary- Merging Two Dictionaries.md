## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
dict1 = eval(input())
dict2 = eval(input())

# Merge dict2 into dict1
dict2.update(dict1)

print(dict2)

## Output
	Input	Expected	Got	
{1:10,2:20,3:30}
{5:50,2:"two"}
{5: 50, 2: 20, 1: 10, 3: 30}
{5: 50, 2: 20, 1: 10, 3: 30}
{'a':'apple','p':'papaya'}
{'b':'banana','p':'pomogranate','m':'mango'}
{'b': 'banana', 'p': 'papaya', 'm': 'mango', 'a': 'apple'}
{'b': 'banana', 'p': 'papaya', 'm': 'mango', 'a': 'apple'}


## Result
Two dictionaries are merged using dictionary operations 
