# python_chapters
In this repository i input all what i learned about the programming language ''python''.

#if true, then only it print the statements
#use tab as intentations
if 4==4:
    print ('true')
if 2<5 :
    print ('is right')
if 2>5 :
    print ('is right')


#even number finding system
use = 5
if use % 2 == 1:
    print ( use,' is odd')
if use % 2 == 0:
    print (use,'is even')
#(3, ' is odd')

#even number finding system
#use of else is that it wont check its statement when 'if' block is true
#else is used with if and elif
use = 4
if use % 2 == 1:
    print ( use,' is odd')
else:
    print (use,'is even')
#(3, ' is odd')

#                                      """""""""or""""""""""
take = 5
if take>10:
    print ('greater')
else:
    print ('not greater')
#you might think like else & elif perform the same function.but else is used when there is only 1 if staement
#but elif check the statement & if right it wont check any if/elif block below it
#updated form of else and if
#elif = if + else(give a condition + if it is correct it wont execute the rest of the function below it).
x = 5
if x == 1:
    print ('one')
elif x == 2:
    print ('two')
elif x == 3:
    print ('three')
elif x == 4:
    print ('four')
else:
    print ('not found')
