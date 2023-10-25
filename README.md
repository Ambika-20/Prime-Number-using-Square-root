# Prime-Number-using-Square-root
#To find the prime numbers using square root
import math
num = int(input("Enter the value of num: "))
a = int(math.sqrt(num))
b = 0
for i in range(2, a):
    if num % i == 0:
        b += 1
if b == 0:
    print(num, 'is a prime number.')
else:
    print(num, 'is not prime.')
