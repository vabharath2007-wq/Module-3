# Tuple in Python: multiples of 5 up to N

## 🎯 Aim
Write a python program to create the tuple by the multiples of 5 up to N. Get the N value from the user.

## 🧠 Algorithm
1. get a user input assign it to 'a'
2. define a empty list
3. loop from 1 to a
4. write a if statement to define the logic to find multiples of 5
5. append the numbers to the empty list
6. convert the list to a tuple
7. Print the tuple.

## 🧾 Program

a=eval(input())

lst=[]

for i in range(1,a):

    if i%5==0:
   
        lst.append(i)
        
t=tuple(lst)

print(t)

## Output

<img width="868" height="172" alt="image" src="https://github.com/user-attachments/assets/6305b207-8d4d-4aa2-818a-41f40000d547" />


## Result
Thus, the program is simulated sucessfully
