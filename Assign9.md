# Python-Assignment-codes
All the question and answers are available, Do try solving for your knowledge
#q1 to check common in two sets
"""l=set([10,20,30,40])
k=set([10,20,25])
print(l.intersection(k))"""


#q2 create set of first n prime numbers 
"""i=int(input("Enter the number:"))
i=i*2
a=[]
b={}
k=0
while i>k:
    for k in range(2,i+2):
        if k%2==1:
            a.append(k)
            k+=1

b=set(a)
print(b)
print(type(b))"""


#q3 union of two sets
"""i=eval(input("Enter the numbers:"))
j=eval(input("Enter the numbers:"))
s=set(i)
f=set(j)
print(s.union(f))"""

#q4 count elements of set given by user
"""j=[]
a=int(input("How many digits to insert:"))
for x in range(a):
    b=int(input())
    j.append(b)

i=set(j)
print("Set is:",i)
print("Length of set is:",len(i))"""


#q5 count distinct elements of list using set
"""k=[10,20,30,30,40,10,50]
j=set(k)
print(k)
print(j)
print("Distinct elelmts in set are:%x"%len(j))"""

#q6 python program to calculate power set of given set
"""s=eval(input("enter list="))
s2=[]
for a in s:
    if s.count(a)>2:
        continue
    else:
        s2.append(a)
x=set(s2)
y=len(x)
print("power of set=",2**y)"""

# another method
"""s1=eval(input("enter tuple/list="))
s1=set(s1)
print("power of set=",2**len(s1))"""
    

#q7 program to check whether given set is subset or not
"""A = {1, 2, 3}
B = {1, 2, 3, 4, 5}
C = {1, 2, 4, 5}
print(A.issubset(B))
print(B.issubset(A))
print(A.issubset(C))
print(C.issubset(B))"""


#q8 python script to print all possible subset of r elements each given from a set of n elelemts


#q9 find cartesian product of 2 given sets
"""setA = set([1, 2, 3])
setB = set(['a', 'b'])
c={}
c = set([(i,j) for i in setA for j in setB])
print(c)"""

#q10 two sets represent two identical dices,(dice value are from 1 to 6).
# write python script to produce sample space to get a sum of dice values when
# rolled isN. N is given by user.
