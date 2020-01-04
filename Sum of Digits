# https://www.codewars.com/kata/541c8630095125aba6000c00

def digital_root(n):
    sum = 0
    for i in str(n):
        sum += eval(i)
    while sum > 10:
        num = sum
        sum = 0
        for i in str(num):
            sum += eval(i)
    return sum
