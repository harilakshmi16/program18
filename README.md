a=[]
n=int(input("enter number of elements:"))
for i in range (1,n+1):
b=int(input("enter elements:"))

a.append(b)
a.sort()
print("second largest element is :",a[n-2])
Output:
enter number of elements:2
enter elements:12
second largest element is: 12
enter elements:5
second largest element is: 5
