# ConstructN
t =int(input())
while t:
    n = int(input())
    print("No" if (n%7)%2 != 0 and n < 7 else "Yes")
    t-=1
