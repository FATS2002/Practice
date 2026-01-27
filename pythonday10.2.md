###### pythonday10.2:  (python day 10)
###### 3.WAP to get the even number greater than 4.
```
input=[1,2,3,4,5,6,7,8,9,10]
output =[6,8,10]
```
##### *without LC* because im focusing on the element,content and not the index number  
```
lst1=[1,2,3,4,5,6,7,8,9,10]
print(lst1)
lst2=[]
for i in lst1:
  if i%2==o:
    if i>4:
      lst2.append(i)
print(lst2)    
```

##### using LC

```
lst2=[i for i in lst1 if i%2==0 if i>4]
print(lst2)
```

##### output
```
```

##### 4.wap to get the even number and off number as *
```
input=[ 1,2,3,4,5]
output=[*,2,*,4,*]  # if odd number it should be printed as * otherwise it should be added as even no.

lst1= [1,2,3,4,5]
print(lst1)
for i in lst1:
  if i%2==0:
    lst2.append(i)
  else:
    lst2.append('*')
print(lst2)

```
##### using LC (if 2 expressions,how to handle)
```
lst3=[i and '*']
lst3=[i if i%2==0 else '*' for i in lst1]
print(lst3)
```

*whenever you have if-else condition,then in comp cond comes first ,looping will come at the end.(expr cond,and at the end loop)*
*can you have the print stmt btween the comprehension?no,only logical mechanism* can be added in comprehension

</br>
*note: no print stmts or generic stmts allowed in comprehension*
</br>

```
task
1.
input = [1,2,3,4]
hint[1, 1+2, 1+2+3, 1+2+3+4]
output=[1,2,6,10]


lst=[1,2,3,4]
print(lst)
res=[]
data=0
for i in lst:
  s+=i
  res.append(s)
print(res)

res=[]
data=0  # sum of it
for i in lst:
  data+=i
  res.append(data)
print(data)

```
##### output:
```
```

##### 2.fibonaci series
```
input=6
basic number = 0,1
output= [0,1,1,2,3,5,8,12]
0,1  0+1 1
     1+1 2
`    2+1 3
     3+2 5
0 <- previous number
1 <- curr number
prev + curr-> next_num

when you move forward ,ur curr no will become previous no, ur next number will become curr no 
```


```
num=6
prev,curr = 0,2
print(f'fibo series: {prev}, {curr}',end=' ')
for i in range(num):  # range(1,7)
  next_num=prev+curr
  prev=curr
  curr=next_num
  print(f'{next_num}', end=' ')
print()
```


##### Ex:
```
input=[1,2,3,4,5,6,7]  # we are focucing on element or focusing on index num er
output=[1.5,2.5,3.5,4.5, 5.5,6.5]
1+2/2= 1.5 ,2+3/2=2.5,
i element, and i+! element divided by zero
```
```
lst=[1,2,3,4,5,6,7]
print(lst)
data=0
lst1=[]
for i in range(0,len(lst)-1):
  data=(lst[i]+ lst[i+1])/2
  lst1.append(data)
print(lst1)
```

*note:when you  c the question pls observe, is ur focusing on content or focusing on index number*



##### ex
```
4.
input=[1,2,3,4,5,6]
output=[[1,2],[2,3],[3,4],[4,5],[5,6]]
```
##### index number

```
lst=[1,2,3,4,5,6]
print(lst)
data= [[lst[i],lst[i+1]] for i in range(len(lst)-1)]
print(data)
```

##### ex


```
input= [10,2,56]
hint:- [1+0+2+5+6]
output= 14
```



