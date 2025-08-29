## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```

dict1 = {'a': 10, 'b': 20, 'c': 30}
dict2 = {'d': 40, 'e': 50, 'b': 60}


merged_dict = {**dict1, **dict2}

print("Dictionary 1:", dict1)
print("Dictionary 2:", dict2)
print("Merged Dictionary:", merged_dict)
```

## Output

## Result
Thus the program is executed successfully.
