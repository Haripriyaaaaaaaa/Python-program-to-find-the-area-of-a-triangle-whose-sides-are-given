import math
a = float(input("Enter the length of side a: "))
b = float(input("Enter the length of side b: "))
c = float(input("Enter the length of side c: "))

s = (a+b+c)/2
area = math.sqrt(s*(s-a)*(s-b)*(s-c))
print(" Area of the triangle is: ", area)

output
Enter the length of side a: 45
Enter the length of side b: 50
Enter the length of side c: 30
 Area of the triangle is:  666.5852814906732

