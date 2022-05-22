# python_chapters
In this repository i input all what i learned about the programming language ''python''.

# adding value given by the user
x = input('enter the 1st value to add : ')
y = input('enter the 2nd value to add : ')
print (x+y)
#enter the 1st value to add : 4
#enter the 2nd value to add : 5
#9

# while entering a string value put it in ''/""
name = input('enter your name : ')
print (name)
#enter your name : 'stark'
#stark

#type
print (type(name))
#<type 'tuple'>
#so if you input more than 1 value it print in tuple
#enter your name : 'you','me'
#('you', 'me')

#indexing in input function
birth = input('enter your birth of date in the form "DD MM YYYY" : ')
print (birth)
#enter your birth of date in the form "DD MM YYYY" : '16 10 2006'
#16 10 2006
print ('the day he was born',birth[0:2])
print ('the month he was born',birth[3:5])
print ('the year he was born',birth[6:10])
#('the day he was born', '16')
#('the month he was born', '10')
#('the year he was born', '2006')


#the input in python 3 is different
