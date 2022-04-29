# python_chapters
In this repository i input all what i learned about the programming language ''python''.

# to create a dictinary use "{}" which make a set.
#here you assign a value to key.
data = {'tony stark':'iron man','peter':'spider man','allauddin':'lamp'}
print (data)
# print {'peter': 'spider man', 'tony stark': 'iron man', 'allauddin': 'lamp'}
# as it is a set there is no sequence.

# index in dict use "[]".insert key inside it
print (data['tony stark'])
# a function to print it.
print (data.get('peter'))
# print spider man
# if the key provided is wrong
print (data.get('pete'))
# print None .this methoid can be used to avoid error if the key provided is wrong.
# you can input a value('not found') to print instead of none if the value is not found.
print (data.get('pete','not found'))
#print not found

# to make a dictionary from 2 lists. same like extend
keys = ['pikachu','squirtle','bulbasaur','charmeleon']
values = ['electric','water','grass','fire']
pokemon = dict(zip(keys,values))
print (pokemon)
# print {'charmeleon': 'fire', 'pikachu': 'electric', 'squirtle': 'water', 'bulbasaur': 'grass'}
print (pokemon['squirtle'])
# print water

#to add values
pokemon['pidgeot'] = 'flying'
print (pokemon)
# {'charmeleon': 'fire', 'pidgeot': 'flying', 'pikachu': 'electric', 'squirtle': 'water', 'bulbasaur': 'grass'}

# to delete values
del  pokemon['squirtle']
print (pokemon)
# {'charmeleon': 'fire', 'pidgeot': 'flying', 'pikachu': 'electric', 'bulbasaur': 'grass'}

# creatind a dictionary with a key with multiple values
pokemonster = {'bulbasaur': 'grass','pikachu': 'electric','charizard':['fire','dragon'],'evolution':{'charizard':'charmelion','bulbasour':'venasour'}}
print (pokemonster)
#a key('charizard') with multiple values(['fire', 'dragon'])
#a dict with multiple keys & multiple values('evolution': {'bulbasour': 'venasour', 'charmelion':'charizard'})
print (pokemonster['charizard'])
print (pokemonster['charizard'][1])
# print dragon
print (pokemonster['evolution']['bulbasour'])
# print venasour

