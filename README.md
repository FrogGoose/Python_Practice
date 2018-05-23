# Python_Practice
Using small projects from Euler to get familiar with Python

Multiples of 3 and 5--Problem 1 
If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.
Find the sum of all the multiples of 3 or 5 below 1000.

a = list(range(1,10))
def Sums3_5(a): #'a' is a list of integers
    total = 0
    for i in a:
        if i%3==0 or i%5==0:
            print(i)
            total += i
    return total
a = list(range(1,1000))
Sums3_5(a)
