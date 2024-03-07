#approach-1(without list)
s,e=map(int,input().split())
z=0
for i in range(s,e+1):
  r=1 
  for j in range(1,i+1):
    r=r*j 
  z=z+r 
print(z)

#approach-2
s,e=map(int,input().split())
a=[]
for i in range(s,e+1):
  r=1 
  for j in range(1,i+1):
    r=r*j 
  a.append(r)
print(a)
print(sum(a))
