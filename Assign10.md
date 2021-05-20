# Python-Assignment-codes
All the question and answers are available, Do try solving for your knowledge
#q1 python script to print dict items(Key,Value) each in one line.
"""d={1:'apple',2:'ball',3:'cat',4:'dog'}
for key,value in d.items():
    print(key, ":" ,d[key])"""


#q2 create dictionary in which each item is pair of roll number as key and student name as value.
"""n=int(input("How much elements to be stored:"))
a={}
for i in range(0,n):
    k=int(input("Enter key:"))
    v=input("ENter value:")
    a.update({k:v})
for i,value in a.items():
    print(i,":",a[i])

print(type(a))"""

#q3 sort using key
"""d={1:'apple',3:'cat',4:'dog',2:'ball'}
print(sorted(d.keys()))"""

#q4 sort using values
"""a = {1:2 ,2:1 ,4:3 ,3:4 ,6:5 ,5:6 }
print(sorted(a.values()))"""


#q5 add key values
n=int(input("How much elements to be stored:"))
a={}
c=0
for i in range(0,n):
    k=int(input("Enter key:"))
    v=int(input("Enter value:"))
    c=c+v
    a.update({k:v})
print(c)
