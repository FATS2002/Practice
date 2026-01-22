###### pythonday6.2:(starting_no, cond,incr/decr)
```
* * * * *
```
```
i = 1  # starting no is 1, and i want it if format of "rows",where in that rows i need to print all stars
n = 5 # rows
while i<=n: #(i<=n,if you forget to give proper logic still also loop will go for infinite.)
  print(i , end=' ')
  i = i+1 #if u forget to give incr/decr,your loop will go infinite
```
##### *output*
```
1 2 3 4 5
```


```
i = 1  # starting no is 1, and i want it if format of "rows",where in that rows i need to print all stars
n = 5 # rows
while i<=n: #(i<=n,if you forget to give proper logic still also loop will go for infinite.)
  print(* , end=' ')
  i = i +1
```


##### *p-4*
```
* * * * *
* * * * *
* * * * *
* * * * *
* * * * *
rows=5
stars=5
```
```
n = 5 # rows
i = 1 # from where it has to start
while i<=n:
  j= 1
  while j<=n:
    print('*',end=' ')
    j+=1
  i+=1
  print()
# or

n = 5 # rows
i = 1 # from where it has to start
while i<=n:  # condition
  j= 1  # starting point
  while j<=n: # condition
    print('*',end=' ')
    j+=1
  print()
  i+=1   # incr
```


##### *p-5*
```
*
* *
* * *
* * * *
* * * * *
rows =5
stars= 1,2,3,4,5 (iterable variable)
```

```
n = 5
i = 1 # row
while i<= 5: # rows
  j=1
  while j<=i: # stars
    print('*',end=' ')
    j+=1
i+=1
print()
```
##### *p-6*
```
* * * * *
* * * *
* * *
* *
* 
rows= 5
stars= 5,4,3, 2 ,1(n-i)
```
##### output:
```
n = 5
i = 1
while i<=5:
  while j<=5:
    print(* ,end=' ')
  j=j-1
i=i-1
```











