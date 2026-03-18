# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim

To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm

1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
string = "google"
reversed_string = string[::-1]
if string == reversed_string:
    print(f"{string} is a palindrome.")
else:
    print(f"{string} is not a palindrome.")

```

## Output

![530370369-8badb420-22c9-4b8a-97bd-a7eb529b93c2](https://github.com/user-attachments/assets/4a24eeea-9546-45d1-bc6a-ab1e21f5ae7e)

## Result

Thus , the program has been executed successfully.
