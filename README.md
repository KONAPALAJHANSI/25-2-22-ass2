n=int(input())
l=[]
t=[]
for i in range(n):
    x=int(input())
    l.append(x)
x=0
for i in range(n):
    if l[i]!=0:
        t.append(l[i])
        x=x+1
for i in range(x,n):
    t.append(0)
print('count of non zeros:',x)
print(t)
