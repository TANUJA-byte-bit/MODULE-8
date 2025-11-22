# 8b) Hackerrank : Python to find out the string contents
This Python program defines a function that **Finds the contents of the string S**, ensuring each line does not exceed a specified width.

---

## Aim

To  to find out if the string  contains: alphanumeric characters, alphabetical characters, digits, lowercase and uppercase characters.
---

##  Algorithm
1.Start

2.Read the input string s

3.Initialize five counters:

    c = 0 → count of alphanumeric characters

    c1 = 0 → count of alphabetic characters

    c2 = 0 → count of digits

    c3 = 0 → count of lowercase letters

    c4 = 0 → count of uppercase letters

4.For each character in the string:

    If character is alphanumeric, increment c

    If character is alphabetic, increment c1

    If character is digit, increment c2

    If character is lowercase, increment c3

    If character is uppercase, increment c4

5.If c ≥ 1, print "True" else "False"

6.If c1 ≥ 1, print "True" else "False"

7.If c2 ≥ 1, print "True" else "False"

8.If c3 ≥ 1, print "True" else "False"

9.If c4 ≥ 1, print "True" else "False"

10.Stop


---


##  Program
```
s=input()
c,c1,c2,c3,c4=0,0,0,0,0
for i in range(len(s)):
    if s[i].isalnum():
        c+=1
    if s[i].isalpha():
        c1+=1
    if s[i].isdigit():
        c2+=1
    if s[i].islower():
        c3+=1
    if s[i].isupper():
        c4+=1
if c>=1:
    print("True")
else:
    print("False")
if c1>=1:
    print("True")
else:
    print("False")
if c2>=1:
    print("True")
else:
    print("False")
if c3>=1:
    print("True")
else:
    print("False")
if c4>=1:
    print("True") 
else:
    print("False")
```
## Sample Output
<img width="436" height="267" alt="image" src="https://github.com/user-attachments/assets/0a58c99e-624c-40ce-83c2-cb7a25dfb140" />

## Result
Program executed Successfully.
