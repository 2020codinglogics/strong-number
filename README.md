# strong-numberprint("Try programiz.pro")
sum=0
num=int(input("enter the number"))
temp=num
while num!=0:
    i,f=1, 1
    r=num%10
    while i<r:
        f*=i
        i+=1
        sum+=f
        num//=10
        if sum==temp:
            print("strong number")
    else:
                print("not")
