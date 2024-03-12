# python-perfect-no
n=int(input())
sum=0
for i in range(1,n):
  if n % i== 0:
    sum+=i
if(sum==n):
  print("the no is a perfect number")
else:
  print("the no is not a perfect number")
  
  
  
