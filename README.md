# Python-Micro-Project
To build strong Python programming fundamentals through hands-on micro projects using Google Colab / Jupiter Notebook for Artificial Intelligence &amp; Machine Learning
#Basic Code:01 simple calculator

num1 = int(input("Enter First Number: "))
num2 = int(input("Enter Second Number: "))

print(num1+num2, ' is Addition of Two numbers num1 & num2')

print(num1-num2, 'is Subtraction of Two numbers num1 & num2')

print(num1*num2, 'is Multiplication of Two numbers num1 & num2')

print(num1/num2, "is Division of Two numbers num1 & num2")
# Intermediate Code:01 simple calculator

num1=int(input("Enter First Number: "))
num2=int(input("Enter Second Number: "))

python_operator=input("Enter the operator you want : +,- ,*,/,//,%,**,>>")

if python_operator=="+":
  print("Result is ",num1+num2)
elif python_operator=="-":
  print("Result is ",num1-num2)

elif python_operator=="*":
  print("Result is ",num1*num2)

elif python_operator=="**":
  print("Result is Exponential Power )",num1**num2)

elif python_operator=="/":
  if num2!=0:
    print("Normal Division is ",num1/num2)
  else:
      print("Error! Division by zero")
elif python_operator=='//':
  if num2!=0:
    print("Floor Division is ",num1//num2)
  else:
      print("Error! Division by zero")
elif python_operator=='%':
        if num2!=0:
          print("Modulus Division is ",num1%num2)
        else:
          print("Error! Division by zero")
else:
  print("Invalid Operator")
  2. Even or Odd Checker Check whether a number is even or odd
  num = int(input("Enter First Number: "))
if num%2==0:
  print("Number is Even")
else:
    print("Number is Odd")
    3. Temperature Converter – Convert Celsius to Fahrenheit and vice versa.
    Celsius = float(input("Enter Celsius Degree: "))
print("Temperature in Fahrenheit is ",(Celsius*9/5)+32)

Fahrenheit = float(input("Enter Fahrenheit: "))
print("Temperature in Celsius is ",(Fahrenheit-32)*5/9)
4.Simple Interest Calculator – Calculate simple interest.
P=int(input("ENTER PRINCIPAL AMOUNT: "))
R=float(input("ENTER RATE OF INTEREST: "))
T=float(input("ENTER TIME PERIOD: "))
SI=(P*R*T)/100
print("Simple Interest is ",SI)
5. Age Category Finder – Classify age groups.
Age=int(input("Enter Age: "))
if Age <=12:
  print("Child")
elif Age <=19:
    print("Teenager")
elif Age <=35:
      print("Young Adult")
else:
        print("Adult")
        6. Multiplication Table Generator – Print table of a number.
        num=int(input("Enter Number for it's table "))
for n in range(1,11):
       print(num*n)
       7. Sum of N Numbers – Find sum of first N natural numbers.
       for N in range(1,10):
   Sn=int(N*(N+1/2))
print(Sn)
8.Factorial Calculator – Find factorial of a number.
number=4
guess=int(input("Guess a Random number from 1-10"))
if guess!=number:
  print("Alas! you are a loser")
else:
    print("Congrats you won!")
    9. 
  
