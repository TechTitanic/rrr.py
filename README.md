# rrr.py
Program to find greatest of 3 numbers entered by the user.

= int(input("enter first number: "))
b= int(input("enter second number: "))
c= int(input("enter third number: "))

if(a>=b and a>=c):
    print("greatest number is a")
elif(b>=a and b>=c):
    print("greatest number is b")
elif(c>=a and c>=b):
    print("greatest number is c")
else:
    print("invalid number ")
