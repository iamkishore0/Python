a = int(input('please input first number: '))
b = int(input('please input second number: '))
c = int(input('please select operator: \n1. (+) Addition, \n2. (-) Subtration, \n3. (*) Multiplication, \n4. (/) Diviion, \n5. (**) Power, \n6. (%) Modulus, \n7. (//) quotient'))

while True:
  if c == 1:
     Addition = (a+b)
     f = 'Your answer is : '
     print(f + str(Addition))
  elif c == 2:
    subtraction = (a-b)
    f = 'Your answer is : '
    print(f + str(subtraction))
  elif c == 3:
    multiplication = (a*b)
    f = 'Your answer is : '
    print(f + str(multiplication))
  elif c == 4:
    division = (a/b)
    f = 'Your answer is : '
    print(f + str(division))
  elif c == 5:
    power = (a**b)
    f = 'Your answer is : '
    print(f + str(power))
  elif c == 6:
    modulus = (a%b)
    f = 'Your answer is : '
    print(f + str(modulus))
  elif c == 7:
    quotient = (a//b)
    f = 'Your answer is : '
    print(f + str(quotient))

  exit_calculator = input('exit_calculator? (yes/no): ')
  if exit_calculator == 'yes':
    break

else:
 print('Invalid_Input')
