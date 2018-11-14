import os
cwd=os.getcwd()
os.chdir('C:\\Users\\d104-22\\Desktop')

name=input('?:')

with open("phone.txt") as f:
    lines=f.readlines()

for k in lines:
    a=k.split(',')
    if a[0]==name:
        print(a)
