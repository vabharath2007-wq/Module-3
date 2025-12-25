# Regex - sequences of one upper case letter followed by number

## 🎯 Aim
Write a Python program to find the sequences of one upper case letter followed by number.

## 🧠 Algorithm
1. import re
2. get a user input
3. define the pattern
4. if re.match(pattern,user input) print found a match
5. else print not matched

## 💻 Program

import re

abc=input()

pattern='[A-Z]+[0-9]'

if re.match(pattern,abc):
   
    print("Found a match!")

else:
   
   print("Not matched!")

## Output

<img width="727" height="181" alt="image" src="https://github.com/user-attachments/assets/94888c00-3c08-45be-923f-009f2a04f037" />


## Result
Thus, the program is simulated sucessfully
