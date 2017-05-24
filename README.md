# Python-Factorial
# Task I solved for Python online course calculated factorial of non-negative number.

x=input('enter number')
def factorial(x):
    if x == 0:
        return 1
    print ("hello")
    return x*factorial(x-1)
print factorial(x)
