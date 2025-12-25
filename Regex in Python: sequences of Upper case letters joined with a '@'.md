# Regex in Python: sequences of Upper case letters joined with a '@'

## 🎯 Aim
Write a Python program to find sequences of Upper case letters joined with a '@'.

## 🧠 Algorithm
1. Import the `re` module.
2. get user input.
3. define the pattern.
4. if re.match print found a match.
5. else print not matched.
6. end 

## 🧾 Program

import re

abc=input()

pattern='[A-Z]+@'

if re.match(pattern,abc):
    
    print("Found a match!")

else:
    
    print("Not matched!")

## Output

 <img width="722" height="211" alt="image" src="https://github.com/user-attachments/assets/7bd39b29-c33a-4517-b519-804138804087" />

## Result
Thus, the program is simulated sucessfully
