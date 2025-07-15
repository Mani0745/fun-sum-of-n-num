def nsum(n):
    if n==0:
        return 0
    return n+nsum(n-1)
num=int(input())
print(nsum(num))
