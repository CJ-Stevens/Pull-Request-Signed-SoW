# Pull-Request-Signed-SoW
Assignment for week6

    def lone_sum(a, b, c):
        if a >= b:
            return c
        elif a == c:
            return b
        elif b == c:
            return a
        elif a == b and a == c and b == c:
            return 0
        else:
            return a+b+c
    x = lone_sum(15, 13, 12)
    print(x)
