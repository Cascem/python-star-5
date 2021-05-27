# python-star-5
print star pattern python(5)
import sys
n = int(sys.stdin.readline())
for i in range(n*2):
    for j in range(n):
        if i%2==0 and j%2==0:
            print("*",end="")
        elif i%2==1 and j%2==1:
            print("*",end="")
        else:
            print(" ",end="")
    print("")
