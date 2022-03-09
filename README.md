# mar-9-assignment-
x=input()
u=0
l=0
d=0
s=0
for i in x:
    if(i.islower()):
        l=l+1
    elif(i.isupper()):
        u=u+1
    elif(i.isdigit()):
        d=d+1
    else:
        s=s+1
print('lowercase letters:',l)
print('uppercase letters:',u)
print('digits:',d)
print('symbols:',s)
