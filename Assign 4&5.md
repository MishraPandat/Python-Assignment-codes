# Python-Assignment-codes
All the question and answers are available, Do try solving for your knowledge

q=int(input("Enter question no of assignment: "))

if q==1:
n=int(input("Enter the number:- "))
if n<2 :
print("Not a prime number")
else:
for x in range(2,n):
if n%x==0:
print("Prime number")
break
else:
print("Not prime number")

if q==2:
print("To print the next prime no to a number")
n=int(input("Enter the number:- "))
while True :
n=n+1
for x in range(2,n):
if n%x==0 :
break
else:
print(n)
break

if q==3:

count=2
print("To print first N prime no")
n=int(input("Enter the number:- "))
print("2")
x=2
while count<=n:
x+=1
for r in range(2,x):
if x%r==0:
break
else:
print(x)
count+=1

if q==4:
print("List of prime no between two nos")
a=int(input("Enter first number:- "))
b=int(input("Enter second number:- "))
x=a
while x<b:
x+=1
for r in range(2,x):
if x%r==0:
break
else:
print(x)

if q==5:
print("To check given no are coprime")
a=int(input("Enter first number:- "))
b=int(input("Enter second number:- "))
g=a if a>b else b
for i in range(1,g+1):
if(a%i==0 and b%i==0):
gcd=i
if(gcd==1):
print("Coprimes")
else:
print("Not coprimes")

if q==6:
print("Print N odd natural number in reverse using range")
n=int(input("Enter the number:- "))
s=range(n,0,-1)
for x in s:
print(2*x-1)

if q==7:
print("Print N even number in reverse order")
n=int(input("Enter the number:- "))
for x in range(n,0,-1):
print(2*x)

if q==8:
print("To print all prime factors of a number")
n=int(input("Enter the number:- "))
for i in range(2,n+1):

while(n%i==0):
  print(i)
  n=n/i
if q==9:
print("To calculate LCM of two numbers")
a=int(input("Enter first number:- "))
b=int(input("Enter second number:- "))
for i in range(1,(a*b)+1):
if(i%a==0 and i%b==0):
print("Lcm=%d " %i)
break

if q==10:
print("To calculate GCD of two numbers")
a=int(input("Enter first number:- "))
b=int(input("Enter second number:- "))
y=a if a>b else b
for i in range(1,y+1):
if(a%i==0 and b%i==0):
x=i
print(x)

assifn 4

#q1
"""a=int(input("enter:"))
if a<2:
print("not a prime")
else:
for i in range(2,a):
if a%i==0:
print("Is not prime number:",a)
break
else:
print("Yes %d is prime number"%a)"""

#q2 next prime number
"""
a=int(input("Enter the number:"))
k=a+1
while k:
for i in range(2,k+1):
if k%i==0:
break
if i==k:
print(k,"is next prime number")
break
else:
k+=1"""

#q4 prime number two numbers
"""a=int(input("enter:"))
b=int(input("enter:"))
for i in range(a,b+1):
if i>1:
for j in range(2,i):
if i%j==0:
break
else:
print(i)"""

#q6 print first n odd natural numbers in reverse order.
"""num=int(input("Enter odd number:"))
y=num*2
if(num%2==1):
for y in range(y,0,-2):
print(y-1)
else:
for y in range(y,0,-2):
print(y-1)"""

#q7 print first n even natural numbers in reverse order.
"""num=int(input("Enter the digit number:"))
y=num*2
if(y%2==0):
for y in range(y,0,-2):
print(y)"""

Assign 5

use of for and range(Start,Stop,Step)
#q1 Print table of 5
"""a=5
for i in range(1,11):
print(a*i)"""

#q2 print table of users choice
"""a=int(input("Enter a number:"))

for i in range(1,11):
print(a*i)"""

#q3 print armstrong number
"""num = int(input("Enter a number: "))
sum = 0
temp = num
while temp > 0:
digit = temp % 10
sum += digit ** 3
temp //= 10

if num == sum:
print(num,"is an Armstrong number")
else:
print(num,"is not an Armstrong number")"""

#q4 squares of numbers a to b given by user
"""a=int(input("enter number"))
b=int(input("enter another"))

for i in range(a,b+1):
t=i**0.5
print(t)"""

#q5 print boundary value step and size value. Ex bound=10 and 30 step=2
"""a=int(input("enter Small boundary value:"))
b=int(input("enter large boundary value:"))
c=int(input("enter step value:"))
for i in range(a,b+1,c):
print("range is",i)"""
