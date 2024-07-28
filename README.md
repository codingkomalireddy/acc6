n=int(input("enter the no. of children:"))
k=int(input("enter the no. of apples in the basket:"))
if n<1500 and k<1500:
    r=k%n
    print("the number of apples in the basket:",r)
