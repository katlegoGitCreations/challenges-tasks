# challenges-tasks
# task 5
def get_area(a,b,c):
peram = (a + b + c) / 2
area = (peram*(peram-a)(peram -b)(peram -c))
return area

# sum of all multipl of 3 and 5 blow 1000
#1
# task 9
sum of all multipl of 3 and 5 blow 1000
def find_sum():
sum = 0
for number range(1,1000):
if number %3 == 0:
sum += number
elif number % 5== 0:
sum += number
elif number% 9 == 0:
sum += number
else:
pass
print(sum)

# vowel in the string function
# task 10
def get_vowels(string1):
vowels ="abcdeABCDE"
d_list=[]
for i in vowels:
if i string1:
d_list.append(i)
print(*d_list)

# task 11
# find common chars/letters #1
def find_common_chars(string1,string2)
common_chars=[]
for char in strig1:
for char in string2:
common_chars.append(char)

string1 = "hey"
string2 = "there"

find_common_chars(string1,string2)

# task 5
# return function
def get_area(a,b,c):
peram = (a + b + c) / 2
area = (peram*(peram-a)(peram -b)(peram -c))
return area

# task 1
# converting pseudocodes into actual code
x = 0
y = 1
x+=3
y+=x
print(x)
print(y)

# task 3
# def katlego(num1,num2):
if num1 + num2 == 65:
return true
else:
return false

# even or odd
even_OR_odd
number=input("enter number")

if (number):
print("even")
else:
print("odd")

# task 8
# convert any number into hours minutes
n = 24
hours = 0
minutes = 0

while n > 59:
n = n-60
hours = hours + 60

if n <= 60:
minutes = n
hours = hours/ 60
