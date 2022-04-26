# python_chapters
In this repository i input all what i learned about the programming language ''python''.

#movies is a tuple because it is inside "()"
movies = ('allauddin','spiderman','interstellar')
print (type(movies))
# gives <type 'tuple'>
#can use index values
print (movies[2])
print (movies[1:3])

#because it is inmutable(unchangable) we cant use functions like "append,insert,pop,remove & del.
nums = (34,67,20,5.6)
print (sum(nums))
# gives 126.6
print (sorted(nums))
#[5.6, 20, 34, 67]
print (min(nums))
print (max(nums))



# creating set.any thing in "{}" is a set. values are muatable but dont follow any sequence.
# as it doesnt follow any sequence it doesnt support index value.
song = {'faded','alone','sorry'}
print (song)

#doesnt support append,insert,pop
song.remove('faded')
print (song)
# set(['alone', 'sorry'])
#while printimg it print 'set' at first
