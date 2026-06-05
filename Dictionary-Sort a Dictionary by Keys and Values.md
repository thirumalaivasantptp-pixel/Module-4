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
data=eval(input())
sort=dict(sorted(data.items()))
print("Keys and Values sorted in alphabetical order by the key")
for key, value in sort.items():
    print(f"({key}, {value}) ",end="")
```

## Sample Output

<img width="816" height="70" alt="518001880-e9a9e4e5-9b72-451b-a090-5df51d91358d" src="https://github.com/user-attachments/assets/615c731c-b18e-4110-b09b-0f941e1ec2e1" />

## Result
Thus the program executed successfully.
