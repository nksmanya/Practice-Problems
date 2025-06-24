* <br>
* * <br>
* * * <br>
* * * * <br>
* * * * * etc depending on rows <br>
```
n = int(input("Enter rows: "))
for i in range(1,n+1):
    for j in range(i):
        print("*", end=' ')
    print()
```
