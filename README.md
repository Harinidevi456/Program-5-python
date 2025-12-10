a=int(input("Enter 1st number: "))
b=int(input("Enter 2nd number: "))
c=input("Entr the operation =,-,/,*:")
print("The result is : ",end='')
if c=='+':
    print(a+b)
elif c=='-':
    print(a-b)
elif c=='/':
    print(a/b)
elif c=='*':
    print(a*b)
else:
    print("Error : wrong operator entered")

Output:
Enter 1st number: 3
Enter 2nd number: 5
Entr the operation =,-,/,*:+
The result is : 8
Enter 1st number: 4
Enter 2nd number: 2
Entr the operation =,-,/,*:-
The result is : 2
Enter 1st number: 7
Enter 2nd number: 8
Entr the operation =,-,/,*:*
The result is : 56
Enter 1st number: 15
Enter 2nd number: 5
Entr the operation =,-,/,*:/
The result is : 3.0
