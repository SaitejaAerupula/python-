# python-
100codes
1)
import random
print(f"random num:{random.randint(1,100)}")

2)
a=1
b=2
a,b=b,a
print("as")
print("a:",a)
print("b:",b)


4)
a=int(input("enter"))
b=int(input("enter"))
sum=a+b
print("sum of two ",sum)


6)
b=int(input("enter a"))
h=int(input("enter b"))
t=1/2*b*h
print(t)

8)
a=input("a")
b=input("b")
print(f"before a={a},b={b}")
temp=a
a=b
b=temp
print(f"after a={a},b={b}")

9)
import random
print(f"random number",{random.randint(1,100)})

10)
km=float(input("enter km distance"))
conversion_factor=0.6121347
miles=km*conversion_factor
print(f"{km} is equal to{miles}miles")

11)
cel=float(input("enter temp in cel"))
fahrenhit = (cel*9/5)+32
print(f"{cel} is equal to {fahrenhit}")
11)
import calendar
y=int(input("enter year"))
m=int(input("enter month"))
cal=calendar.month(y,m)
print(cal)

12)
import math
a=int(input("enter coeff of a"))
b=int(input("enter coeff of b"))
c=int(input("enter coeff of c"))
discriminant= b**2-4*a*c
if discriminant > 0:
    r1 = (-b  + math.sqrt(discriminant))/(2*a)
    r2 = (-b - math.sqrt(discriminant))/(2*a)
    print(f"rt1:{r1}")
    print(f"rt2:{r2}")
elif discriminant==0:
    r=-b/(2*a)
else:
    real_part=-b/(2*a)
    imaginary_part=math.sqrt(abs(discriminant))/(2*a)
    print(f"Root 1:{real_part}+{imaginary_part}i")
    print(f"Root 2:{real_part}-{imaginary_part}i")
