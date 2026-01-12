# Integer-is-a-prime-number-or-not
num = int(input("Enter an integer: "))
isprime = 1  
for i in range(2, num // 2):
    if num % i == 0:
        isprime = 0
        break

if isprime == 1:
    print(num, "is a prime number")
else:
    print(num, "is not a prime number")

output:
Enter an integer: 29
29 is a prime number
