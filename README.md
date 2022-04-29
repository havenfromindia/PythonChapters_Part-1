# python_chapters
In this repository i input all what i learned about the programming language ''python''.

nums = 50
print (id(nums))
print (id(50))
# both print 33555272
# this is the adress of 50 & not of the variables(nums)

a = 10
b = a
print (a,b)
print (id(10))
# 31194944
print (id(a))
print (id(b))
# 31194944

a = 9
print (id(a))
# 31653720
print (b)
# 10
# even when the value of a changed b remains the same

b = 8
print (b)
# 8

k = a
print (k)
# 9

# in the beginning we had a value 50. now it is not assigned to nothing.this value is getting garbage collected.

