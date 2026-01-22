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
n = 5 # no of rows
j  
```


##### *homework:-</br>*practice all star patterns*



###### *transfer stmts*</br>1.break stmt</br>continue stmt</br>3.pass stmt. </br>break stmt:the moment it sees 5 itll break

```
for i in range(1, 11):
  if i == 5:
    print(i)
    break
```
##### invalid
```
for i in range(1, 11):  # invalid
  if i == 5:
    break
    print(i) # we should not place any statement below the break statement
```
```
for i in range(1, 11):
    print(i)
    if i == 5:
        break

```
*you break at particular loop based onthe condition provided.it will stop the iteration based on condition provided*

```
lst = [20,35,115,60,45,39,88,105,156,91]  # price of some elements
print(lst)
for i in lst:  # bcuz im directly chking content"lst",if im checkng index no "range(len(lst))"
  print(i)
  if i> 100:
    break
```
*output*
```
20
30
115
```
```
lst = [20,35,115,60,45,39,88,105,156,91]  # price of some elements
print(lst)
for i in lst:  # bcuz im directly chking content"lst",if im checkng index no "range(len(lst))"
  if i 100:
    print(i)
    break
```
```
lst = [20,35,115,60,45,39,88,105,156,91]  # price of some elements
print(lst)
for i in lst:  # bcuz im directly chking content"lst",if im checkng index no "range(len(lst))"
  if i<=100:
    print(i)
    break
```
*doubt: should ask sir*
```
lst = [20,35,115,60,45,39,88,105,156,91]  # price of some elements
print(lst)
for i in lst:  # bcuz im directly chking content"lst",if im checkng index no "range(len(lst))"
#  print(i)
  if i>100:
    print(i)
    break
```




*continue*
```
for i in range(1,11):
  print(i)
  if i ==5:
    continue
```
```
for i in range(1,11):
  print(i)
  if i ==5:
    print('condition satisfied')
    continue
```
```
for i in range(1,11):
  if i ==5:
  print(i)
  print('condition satisfied')
continue
```
*output*
```
5
condition satisfied
```
```
lst = [20,35,115,60,45,39,88,105,156,91]  # price of some elements
print(lst)
for i in lst:  # bcuz im directly chking content"lst",if im checkng index no "range(len(lst))"
#  print(i)
  if i>100:
    print(i, 'greater than 100 can not buy this product')
    continue
  print(i)
```
*output*
```
[20,35,115,60,45,39,88,105,156,91]
20
35
115 greater than 100 can not buy this product
60
45
39
88
105 greater than 100 can not buy this product
156 greater than 100 can not buy this product
91 
```


*break will break the iteration based on condition</br> continue will skip the particular iteration based on the condition.*

###### *break example:*
```
cart=[10,20,600,60,70]
print(cast)
for item in cart:
  if item>500:
    print(item ,'insufficient balance')
    break
print(item)
```
*output*
```
[10,20,600,60,70]
10
20
600 insufficient balance
```

```
lst=[20,35,115,60,45,39,88,105,156,91]
print(lst)
  if i>100:
    break
  print(i)
```
```
[20,35,115,60,45,39,88,105,156,91]
20
35
```

```
lst=[20,35,115,60,45,39,88,105,156,91]
print(lst)
  if i>100:
    print(i,'grater than 100')
    break
  print(i)
```
*output*
```
[20,35,115,60,45,39,88,105,156,91]
20
35
115 greater than 100
```

*pass stmt: i dont know what to write in the body,like what conditinn idk*
```
for i in range(1, 11):
  pass # as of now idk what to write there i will keep it as pass stmt.so it wont give me error
```


