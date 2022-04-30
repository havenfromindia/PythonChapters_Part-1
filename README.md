# python_chapters
In this repository i input all what i learned about the programming language ''python''.

# range
# to get till 10 use 11
print (range(10))
# [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
print (range(2,10))
# [2, 3, 4, 5, 6, 7, 8, 9]
# for division
# print all who are divisible by 2
print (range(2,10,2))
# [2, 4, 6, 8]

# you can use variables as well
king = range(2,10)
print (king)
# [2, 3, 4, 5, 6, 7, 8, 9]
print (tuple(king))
# (2, 3, 4, 5, 6, 7, 8, 9)

# type of range is list
queen = tuple(range(2,10))
print (queen)
# (2, 3, 4, 5, 6, 7, 8, 9)

#dictonary function
data = {'dog':'animal','parrot':'bird','butterfly':'bug'}
# to get keys
print (data.keys())
#['butterfly', 'dog', 'parrot']
#to get values
print (data.values())
# ['bug', 'animal', 'bird']

#variables
creatures = data.keys()
print (creatures)
print (tuple(creatures))
# ('butterfly', 'dog', 'parrot')

