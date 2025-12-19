# Employee-Overtime-Pay-Calculation-Using-Loops-and-Conditionals

ovpay=0
sum=0
for i in range(1,11):
    print("Enter Working Hours of Emp ",i,":")
    h=int(input())
    if(h>40):
        extra=h-40
        ovpay=extra*12
        print("Over time pay of emp ",i,"is",ovpay)
        sum=sum+ovpay
    else:
        print("No Overtime Pay")
print("Total Overtime Pay of all employees : ", sum)

Output:
Enter Working Hours of Emp  1 :
29
No Overtime Pay
Enter Working Hours of Emp  2 :
45
Over time pay of emp  2 is 60
Enter Working Hours of Emp  3 :
34
No Overtime Pay
Enter Working Hours of Emp  4 :
67
