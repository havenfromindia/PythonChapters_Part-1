# python_chapters
In this repository i input all what i learned about the programming language ''python''.
#F8 for new line in debug fuction

# function to check whether a number is prime or not.
# prime numbers are numbers having only 1 & itself as its factors.
nums = int(input('enter the number : '))
for i in range(2, nums):
    if nums % i == 0:
        print(nums, 'is not prime')
    else:
        print(nums, 'is prime')
    break

# modified
values = [4, 5, 6, 12]
for j in values:
    for i in range(2, j):
        if j % i == 0:
            print(j, 'is not prime')
        else:
            print(j, 'is prime')
        break
