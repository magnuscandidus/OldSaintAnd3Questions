# OldSaintAnd3Questions
# cook your dish here
t=int(input())
while t:
    a=str(input())
    b=str(input())
    c=a.count('1')
    d=b.count('1')
    if(c==d):
        print("Pass")
    else:
        print("Fail")
    t-=1
        
