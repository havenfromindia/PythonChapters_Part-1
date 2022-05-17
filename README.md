# python_chapters
In this repository i input all what i learned about the programming language ''python''.
#F8 for new line in debug fuction

#**************---using break----************

#how break work?
#consider there is a box having 9 blue balls & 1 red ball. our job is to find this red ball.
#once the red ball is found stop searching.break : once the required value is found jump out to stop the loop
#similar to police.once the theif is found they stop investigation.
#another example is searching something

#onces the value is found it stop the loop
#vending machine
x = 2
#int(input('how many candies do you want '))
av = 10
for i in range(x):
    if x > av:
        print('sorry the available candies are', av)
        print('out of stock')
        break
    print('candies')

for i in range(20):
    break
    print(i)
#print nothing

for i in range(20):
    print(i)
    break
    print(i)
#it print '0'.
#'break' break the loop/stop the loop & jump out

#***********--------using continue--------**************

#how continue works?
#consider there is a box having multiple blue balls & red balls. our job is to find these red ball.
#remove all red balls & pass (print) blue balls

#onces the value is found it take it & print the rest

#printing values which are not divisible by 5,3
test_trial = []
for i in range(30):
    if i%3 != 0:
        test_trial.append(i)
print(test_trial)
#[1, 2, 4, 5, 7, 8, 10, 11, 13, 14, 16, 17, 19, 20, 22, 23, 25, 26, 28, 29]

#with the help of continue
test_trial2 = []
for i in range(30):
    if i%3 == 0:
        continue
    test_trial2.append(i)
print(test_trial2)
#[1, 2, 4, 5, 7, 8, 10, 11, 13, 14, 16, 17, 19, 20, 22, 23, 25, 26, 28, 29]


#pass
#pass say the machine to ignore it
for i in range(10):
    if i%2 != 0:
        pass
    else :
        print(i)
#we left the if block idle & tell to ignore the code
#majorly used when we don't know what to print
#0
#2
#4
#6
#8
