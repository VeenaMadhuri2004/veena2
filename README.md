#fibonacci 1 1 2 3 5 8 13 21 34 55

def fib(n):
    if n<=1:
        return n
    else:
        return fib(n-1)+fib(n-2)
num=int(input ("enter the terms:"))
for i in range(num):
    print(fib(i), end=' ')

def dsum(n):
    if n==0:
        return 0
    return n%10 + temp(n//10)
def temp(n):
    return dsum(n)
num=int(input("sum of digits numbers:"))
print("sum of digits:",dsum(num))


#indirect recursion
def one(n):
    if n==0:
        return True
    else:
        return two(n-1)
def two(n):
    if n==0:
        return False
    else:
        return one(n-1)
num=int(input("enter a number:"))
if one(num):
    print(num,"is even")
else:
    print(num,"is odd")



#indirect recursion
def A(n):
    if n<=0:
        return 
    print ("vijay",n)
    B(n-1)
def B(n):
    if n<=0:
        return 
    print("kommarapu",n)
    A(n-1)
num=int(input("enter a number:"))
A(num)



#indirect recursion
def player_A(n):
    if n<=0:
    print ("player A reached 0!! player A loses🤦‍♀️")
    return
print(f"\n player A's turn. current number {n}")
move=int(input("player A, subtract 1 or 2:"))
while move not in [1,2]:
    move=int(input("player A, subtract 1 or 2:"))
player_B(n-move)
def player_B(n):
    if n<=0:  
        print ("player B reached 0!! player A loses🤦‍♀️")
         return
print(f"\n player B's turn. current number {n}")
move=int(input("player B, subtract 1 or 2:"))
while move not in [1,2]:
    move=int(input("player B, subtract 1 or 2:"))
player_A(n-move) 
start=int(input("enter a number:"))
player A(num)

    

