
n,sv,rv=map(int,input().split())
new=0
c=0
p=0
while n:
    r=n%10
    n=n//10
if r%sv==0:
        c+=1
print(c)
       #for i in range(0,c,-1):
while (c>=0):
            r=c+rv
            new=new+r*pow(10,p)
            p+=1
            c-=1
        
else:
         new=new+r*pow(10,p)
         p+=1
print(new)

