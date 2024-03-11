# dictionary
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
print(d)

#acccesing the elements
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
print(d)
for i in d:
  print(i)
for i in d:
  print(d[i])
print(i,"->",d[i])
