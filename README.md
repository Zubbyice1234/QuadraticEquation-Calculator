# QuadraticEquation-Calculator
import math

a = eval(input("Enter the value of a: "))
b = eval(input("Enter the value of b: "))
c = eval(input("Enter the value of c: "))
d = (b**2) - (4*a*c)

x1 = (-b + math.sqrt(d))/(2*a)
x2 = (-b - math.sqrt(d))/(2*a)

print('x1 = ', x1)
print('x2 = ', x2)  
