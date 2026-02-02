# program-to-find-the-2nd-largest-number-from-the-list-of-the-numbers-entered-through-keyboard.-
a=[]
n=int(input("Enter number of elements:"))
for i in range(1,n+1):
    b=int(input("Enter element:"))
    a.append(b)
a.sort()
print("Second largest element is:",a[n-2])

OUTPUT:

Enter number of elements:5
Enter element:1
Enter element:10
Enter element:6
Enter element:26
Enter element:68
Second largest element is: 26
