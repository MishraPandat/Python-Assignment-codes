# Python-Assignment-codes
All the question and answers are available, Do try solving for your knowledge
#q1 sort the numbers given by user
"""b=[]
a=int(input("Enter numbers to add:"))
for i in range(1,a+1):
    value=int(input("Enter the number of %d:"%i))
    b.append(value)
b.sort()
print(b)"""
    
#q2 print largest number in list
"""b=[]
a=int(input("Enter the number:"))
for i in range (1,a+1):
    c=int(input("Enter number:"))
    b.append(c)
b.sort()
print("Largest number is:",b[-1])"""

#q3 add all the numbers given by user
"""b=[]
d=0
a=int(input("Enter the number:"))
for i in range (1,a+1):
    c=int(input("Enter number:"))
    d=d+c
    b.append(c)
b.sort()
print(b)
print("Total of all numbers is:",d)"""

#q4 print first n prime numbers and insert in list
"""a=int(input("Enter a number:"))
b=[]
print("Nubers between 1 to",a,"is:")
for i in range(1,a+1):
    if i>2:
        for j in range(2,i):
            if (i%j)==0:
                break
        else:
            b.append(i)
print(b)"""


#q5 print the square roots of number entered by user
"""a=int(input("Enter nos:"))
b=[]
e=[]
for i in range(1,a+1):
    c=int(input("Enter no:"))
    d=c**0.5
    b.append(c)
    e.append(d)
print("The elelments inserted are:",b)
print("Square root of elements are:",e)"""

#q6 print all indices of an element given in list
"""l=[]
indices=[]
a=int(input("enter nos:"))
for i in range(1,a+1):
    c=int(input("enter it:"))
    l.append(c)
print(l)
b=int(input("Enter the number you want to see index of it:"))
for j in range(0,len(l)):
   if l[j] == b:
      indices.append(j)
print(indices)"""


#OR
"""l=[10,10,20,30,40,10,25,20,20,30]
print(l)
a=int(input("Enter number for index:"))
print(l.index(a))"""

#q7 print distinct elements along with frequency of occurrence
"""a=[]
b=[]
c=int(input("How many digits in first element:"))
d=int(input("How many digits in second element:"))

print("\n1st list elements are:")
for i in range(1,c+1):
    e=int(input("Enter digits:"))
    a.append(e)

print("\n2nd list elements are:")
for j in range(1,d+1):
    f=int(input("Enter digits:"))
    b.append(f)

print(a)
print(b)
g=int(input("Enter the list number:"))

if g==1:
    h=int(input("Enter the number to search:"))
    print(a.count(h))
if g==2:
    k=int(input("Enter the number to search:"))
    print(b.count(k))"""

    #OR
"""l=[10,20,30,40,10,10,20,30,30,30,60]
f=[35,75,75,12,75,35,40,12,40,12,60]
print(l)
print(f)
i=int(input("Enter no:"))
if i==1:
    c=int(input("Which number:"))
    print(l.count(c))
if i==2:
    c=int(input("Which number:"))
    print(f.count(c))
else:
    print("input is wrong enter 1 or 2")"""

#q8 to add all even numbers and even numbers in list

a=[]
b=[]
d=0
e=int(input("Enter 1 for even 2 for odd:"))

if e==1:
    c=int(input("Enter the numbers:"))

    for i in range(1,c+1):
        if i%2==0:
            d=d+i
            a.append(i)
    print(a)
    print("sum is:",d)
elif e==2:
    c=int(input("Enter the numbers:"))

    for i in range(1,c+1):
        if i%2==1:
            d=d+i
            b.append(i)
    print(b)
    print("sum is:",d)
