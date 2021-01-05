# Python
# How to make a faulty calculator.

print("Enter 1st number")
num1 = int(input())
print("Enter 2nd number")
num2 = int(input())
print('So what you want?'+' +, -, *, /, %')
num3 = input()

# Yaha par Kuchh number ko default liya gaya hain jisase ki calculator galat anwser print kare.

if num1== 44 and num2== 7 and num3=='*':
    print(77)
elif num1 == 56 and num2 == 9 and num3== '+':
    print(26)
elif num1 ==56 and num2 == 6 and num3=='/':
    print(4)
elif num3=='+':
    num4 =num1+num2
    print(num4)
elif num3=='-':
    one = num1-num2
    print(one)
elif num3== '*':
    two = num1*num2
    print(two)
elif num3== '/':
    four = num1/num2
    print(four)
elif num3 == '%':
    five = num1%num2
    print(five)
else:
    print("Error! Check Your Number")
