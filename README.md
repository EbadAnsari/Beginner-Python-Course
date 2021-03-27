# Beginner-Python-Course
print('Calculation?')

sign_1 = input('Enter + - * / ? : ')

number_1 = int(input('Enter 1st : '))
number_2 = int(input('Enter 2nd : '))

#check number or anything in number_1 and number_2


#add
def add(number_1, number_2):
	return number_1 + number_2

if sign_1 == '+':
	print(number_1, sign_1, number_2, '=', add(number_1, number_2))
	
#minus
def minus(number_1, number_2):
	return number_1 - number_2

if sign_1 == '-':
	print(number_1, sign_1, number_2, '=', minus(number_1, number_2))

#multiply
def multiply(number_1, number_2):
	return number_1 * number_2

if sign_1 == '*':
	print(number_1, 'x', number_2, '=', multiply(number_1, number_2))

#divide
def divide(number_1, number_2):
	return number_1 / number_2

if sign_1 == '/':
	print(number_1, sign_1, number_2, '=', divide(number_1, number_2))
