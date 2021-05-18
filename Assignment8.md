# Python-Assignment-codes
All the question and answers are available, Do try solving for your knowledge
#q1 Average of tuple values
"""a=eval(input("Enter tuples:"))
b=0
for i in a:
    b=b+i
c=b//len(a)
print(c)"""


#q2 sort tuple
"""a=eval(input("Enter a tuple:"))
print(sorted(a))"""

#q3 merge 2 sorted tuple
"""e=eval(input("Enter 1st tuple"))
f=eval(input("Enter 2nd tuple:"))
d=sorted(e)
a=sorted(f)
c=d+a
c=sorted(c)("Either sort or not your wish")
print(c)"""

#q4 reverse a tuple
"""a=eval(input("Enter tuple:"))
len(a)
print(a[len(a)::-1])"""


#q5 count elements in tuple
"""a=eval(input("Enter a tuple:"))
print(len(a))"""


#q6 calculate sum of elements in tuple
"""k=eval(input("Enter tuple:"))
c=0

for e in k:
    c=c+e

print(c)"""


#q7 creating homogeneous tuple from hetrogeneous elements of tuple
"""f=eval(input("Enter data:\n"))
a,b,c,d,g=[],[],[],[],[]
for e in f:
    if type(e) == int:
        a.append(e)
    elif type(e) == float:
        b.append(e)
    elif type(e) == bool:
        c.append(e)
    elif type(e) == complex:
        d.append(e)
    elif type(e) == str:
        g.append(e)
a=tuple(a)
b=tuple(b)
c=tuple(c)
d=tuple(d)
g=tuple(g)
print(a,b,c,d,g,sep='\n')"""


#q9 compare values of tuple to see they are in same order or not
"""print("Enter elements of 1st tuple:")
x=tuple([eval(e) for e in input().split(',')])
print("Elements of 2nd tuple:")
y=tuple([eval(e) for e in input().split(',')])
if x==y:
    print("Yes same")
else:
    print("Not")"""


#q8 compare in any order or not
"""print("Enter elements of 1st tuple:")
x=tuple([eval(e) for e in input().split(',')])
print("Elements of 2nd tuple:")
y=tuple([eval(e) for e in input().split(',')])
if x==y:
    print("Yes same")
else:
    print("Not")"""

#q10 print maximum value in tuple
"""a=eval(input("Enter tuple:"))
print(max(a))"""


#q11 subset or not

#q12 count frequency of elements in tuple
"""a=eval(input("Enter a tuple:"))
i=0
for e in a:
    if a.index(e)==i:
        print(e,'----',a.count(e))
    i+=1"""
