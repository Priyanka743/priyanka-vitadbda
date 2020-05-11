# Python Basics


**Q1.Swap two variables without using third variable:(minimum 3 solutions)**

**Ans:**

print("Before swapping:")
a=5
b=2
print("value of a:",a,"value of b",b)
print("After swapping:")
a=a+b
b=a-b
a=a-b
print("value of a:",a,"value of b",b)

**Ans:**

print("Before swapping:")
a=5
b=2
print("value of a:",a,"value of b",b)
print("After swapping:")
a=a*b
b=a//b
a=a//b
print("value of a:",a,"value of b",b)

**Ans:**

print("Before swapping:")
a=5
b=2
print("value of a:",a,"value of b",b)
print("After swapping:")
a=a^b
b=a^b
a=a^b
print("value of a:",a,"value of b",b)


**Q2.Accept the marks from the user and print corresponding grade:**

**Ans:**

marks=float(input("Entter the marks"))
if marks>=75:
    print("Grade A")
elif marks>=55:
    print("Grade B")
elif marks>=35:
    print("grade C")
else:
    print("Fail")


**Q3.Accept a number from user-if number is divisible by 3 print "Three",if number is divisible by 7          print "Seven", and if number is divisible by 3&7 print "Three-Seven":**

**Ans:**

num=int(input("Enter the number"))
if num%3==0 and num%7==0:
    print("Three-Seven")
elif num%3==0:
    print("Three")
else:
    print("Seven")


**Q4.Accept a number from user and check if it is odd or even:**

**Ans:**

num=int(input("Enter the number"))
if num%2==0:
    print("Number is even")
else:
    print("Number is odd")


**Q5.Accept a number from user and check if it is odd or even without using % operator:**

**Ans:**

num=int(input("Enter the number"))
if (int(num/2)*2==num):
    print("Number is even")
else:
    print("Number is odd")
