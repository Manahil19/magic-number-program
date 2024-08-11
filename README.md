# magic-number-program
n=int(input("enter a three digit number:"))
if n>99 and n<1000:
    print("Valid number")
else:
    print("invalid number")
s=int(input("enter the first digit from the three digit number :"))
u=int(input("enter the second digit from the three digit number :"))
m=int(input("enter the third digit from the three digit number :"))
SUM=s+u+m
print("the sum is :",SUM)
if SUM%n==0:
    print("THE THREE DIGIT NUMBER IS A MAGIC NUMBER:")
else:
    print("THE THREE DIGIT NUMBER IS NOT A MAGIC NUMBER:")
