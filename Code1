def solve(n):
    sign = '-' if n<0 else ''
    n = abs(n)
    if n < 3:
        return str(n)
    s = ''
    while n != 0:
        s = str(n%3) + s
        n = n//3
    print(sign+s)

n = int(input())
solve(n)
