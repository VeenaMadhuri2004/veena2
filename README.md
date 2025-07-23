#fibonacci 1 1 2 3 5 8 13 21 34 55

def fib(n):
    if n<=1:
        return n
    else:
        return fib(n-1)+fib(n-2)
num=int(input ("enter the terms:"))
for i in range(num):
    print(fib(i), end=' ')# veena2
