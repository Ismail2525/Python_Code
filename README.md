# Python_Code
# Problem Solving
# question 2: factorial of number in comma-separated
def factorial(n):
    fact=1
    if n==0:
        return 1
    elif n==1:
        return n
    else:
        for i in range(1,n+1):
            fact = fact*i
        print("Factorial: ", fact)
n = int(input("Enter a no to find factorial"))
factorial(n)
