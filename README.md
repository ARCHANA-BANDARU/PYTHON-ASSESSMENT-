#min sum of array
n=5
arr=[1,2,3,4,5]
arr.sort()
a,b=arr[-1],arr[-2]
avg=(a+b)/2
for i in range(n):
 if arr[i]<avg:
    arr[i]=0
print(sum(arr))


                
    
