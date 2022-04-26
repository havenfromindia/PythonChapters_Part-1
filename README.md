#making a list(mutable/changeble).use "[]" to make a list.
values = [23,45,68,'henry','nobita',2.3]
print (values)
#inex values
print (values[2])
#it print 68
print (values[-2])
# it print nobita
print (values[3:6])
# it print ['henry', 'nobita', 2.3]

# to add 2 list
names = ['shiro','nick','mj']
joined = [values,names]
print (joined)
# it print [[23, 45, 68, 'henry', 'nobita', 2.3], ['shiro', 'nick', 'mj']]
join = [values,'justin']
print (join)
# it prints [[23, 45, 68, 'henry', 'nobita', 2.3], 'justin']

# functions in a list

#1)to add value (add at the end)
values.append(20)
print (values)
#it print [23, 45, 68, 'henry', 'nobita', 2.3, 20]

#2)to add a value with the help of index number
values.insert(2,90)
print (values)
#it print [23, 45, 90, 68, 'henry', 'nobita', 2.3, 20]

#3) to remove values
values.remove('henry')
print (values)

#4) to remove a value with the help of index numbers
values.pop(5)
print (values)
# 2.3(inex = 5) is removed
#[23, 45, 90, 68, 'nobita', 20]
#if not mentioned the index number it remove the the end value(20)
values.pop()
print (values)

#5)to remove multiple value by using index number(like insert function)
del values[3:5]
print (values)
#gives [23, 45, 90]
#if not mentioned the end it go till the end of list

# to add 2 list/tuple/set. adding multiple values
nums = [23,56,70]
values.extend(nums)
print (values)

#for the least value
print (min(values))

#for the highest value. if it have a str value it will be the max value
print (max(values))

# sum of all values
print (sum(values))

#for asending order
values.sort()
print (values)
# gives [23, 23, 45, 56, 70, 90]

# arranging in alphabetic order
print(sorted())

