
n=int(input("Enter the Limit:"))
s=0
for i in range(1,n+1):
    print("Enter ",i,end='')
    a=int(input("th number:"))
    s=s+a
avg=s/n
print("The sum of entered numbers:",s)
print("The Average of entered numbers:",avg)









OUTPUT:

Enter the Limit:6
Enter  1th number:2
Enter  2th number:7
Enter  3th number:8
Enter  4th number:9
Enter  5th number:3
Enter  6th number:1
The sum of entered numbers: 30
The Average of entered numbers: 5.0


