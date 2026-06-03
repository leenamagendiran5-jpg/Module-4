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
def merge(dict1, dict2):
    merged = {**dict1, **dict2}
    return merged

dict1 = {'a': 10, 'b': 20}
dict2 = {'b': 30, 'c': 40}

result = merge(dict1, dict2)
print("Merged dictionary:", result)
```

## Output

<img width="942" height="605" alt="image" src="https://github.com/user-attachments/assets/58350e51-538d-4457-ba43-05470fef36fd" />

## Result

The program successfully merges two dictionaries, combining all key-value pairs. If a key exists in both, the value from the second dictionary overwrites the first.

