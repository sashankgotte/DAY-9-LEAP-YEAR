# Day 9: Leap Year Checker 🐍

## 📌 Description
This Python program checks whether a given year is a Leap Year or Not using conditional statements and arithmetic operators.

## 💻 Code
```python
year = int(input("Enter year: "))

if year % 400 == 0 or (year % 4 == 0 and year % 100 != 0):
    print("Leap Year")
else:
    print("Not a Leap Year")
```

## ⚙️ How It Works
- A year divisible by 400 is a Leap Year.
- A year divisible by 4 but not by 100 is a Leap Year.
- Otherwise, it is Not a Leap Year.

## ▶️ Example Output
```text
Enter year: 2024
Leap Year
```

## 🛠️ Technologies Used
- Python
- VS Code

## 🎯 Learning Outcomes
- Practiced `if-else` conditional statements.
- Learned to use the modulo operator `%`.
- Understood the rules for identifying Leap Years.

## 🚀 100 Days of Python Challenge
Day 9 of my 100 Days of Python Coding Challenge. Learning and improving my Python programming skills one day at a time!

**#Python #100DaysOfCode #PythonProgramming #GitHub #CodingChallenge**