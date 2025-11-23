# 8d)  Hackerrank: Finding the simple interest.

##  AIM:
To Find the simple interest by getting the principal, rate and time value from the usersimple interest = (principal*rate*time)/100
---

##  ALGORITHM:
1.Define a function named simpleInterest that takes three values: principal (p), time (t), and rate (r).

2.Inside the function, calculate simple interest using the formula:
si = (p * r * t) / 100

3.Return the calculated value si from the function.

4.Take input from the user for p, the principal amount.

5.Take input from the user for r, the rate of interest.

6.Take input from the user for t, the time period.

7.Call the function simpleInterest(p, t, r).

8.Store or print the returned simple interest value.

##  PROGRAM:
```
def simpleInterest(p,t,r):
    si=(p*r*t)/100
    return si
p,r,t=eval(input()),eval(input()),eval(input())
```
## OUTPUT
<img width="1126" height="283" alt="image" src="https://github.com/user-attachments/assets/16c7a266-02ca-49db-9842-0fde56543097" />

## RESULT
Program executed Successfully.
