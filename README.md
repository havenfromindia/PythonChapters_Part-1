# python_chapters
In this repository i input all what i learned about the programming language ''python''.

# using a library named maths
import math

# squart root function
x=math.sqrt(25)
print (x)
print (math.sqrt(25))
#5.0

# pi function
y=math.pi
#3.14159265359
print (y)
# floor & ceil function
print (math.floor(4.56))
# 4.0
print (math.ceil(4.56))
#5.0

# pi + floor & ceil
print ('value of pi :',int(math.floor(3.14159265359)))
print ('value of pi :',int(math.ceil(3.14159265359)))

#power off function
print (4**2)
print (int(math.pow(3,2)))

# for the easy use of programmer import in a short form(like 'm')
import math as m
print (m.sqrt(25))
# 5.0
print (int(m.sqrt(25)))
#5

# if only need some certain function use this statements
from math import sqrt,pow,floor,ceil
print (int(pow(2,3)))
print (int(floor((3.45))))

