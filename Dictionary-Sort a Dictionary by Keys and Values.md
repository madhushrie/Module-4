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
```
mad=eval(input())
sort=sorted(mad.items())
print("Keys and Values sorted in alphabetical order by the key")
for key,value in sort:
    print(f"({key}, {value})",end=' ')
```

## Sample Output

<img width="1250" height="171" alt="image" src="https://github.com/user-attachments/assets/b740a87d-eac5-495d-9389-a4b0912cf61f" />

## Result
Thus the program is executed successfully.

