##### pattern programming
##### p-1
```
*
```
##### output ("*" symbol is actually multiplication operator)
```
print(*) # invalid
print('*') # valid
```
##### output:-
```
invalid star expression
```

##### p-2 (horizontal  star)
```
* * * * *
```
##### output:
```
print('*' * 5)
```
##### vertical stars
```
print('*\n' * 5)
```
##### output:
```
*
*
*
*
*
```



##### using "Range"
```
for i in range(5):
  print(i) # it will print numbers 0 ,1,2,3, 4
  print('*')
```
##### output
```
0
1
2
3
4
```

```
for i in range(5):
  print('*')
```
```
*
*
*
*
*
```

##### p-3 (horizontal star)
```
for i in range(5):
  print('*',end=' ') # end var with empty string
# println
```
##### output
```
* * * * *
```

##### p-4
```
* * * * *
* * * * *
* * * * *
* * * * *
* * * * *
rows = 5
stars = 5
```
```
n = 5
for i in range(n):  # rows (take caring abour the rows)
  print('*',end=' ')  #endl =' '
print()
```
```
n = 5
for i in range(n):  # rows (take caring abour the rows)
  for j in range(n):  # star (take care of printing of stars)
    print('*', endl=' ')

##### where ever i hear the word repetation, use looping stmts

# 1st iteration
i=0 j=0
    j=1
    j=2
    j=3
    j=4
i=1 j=0
    j=1
    j=2
    j=3
    j=4
```


##### P-5
```
*
* *
* * *
* * * *
* * * * *
Rows = 5
star= 1,2,3,4,5(iterable variable)
```
```

n = 6
for i in range(1, n) # staring from 1 going till 6 (6-1),this tinecounting will start from 1.
  print(i)
```
##### output
```
1
2
3
4
5
```
```
n = 6
for i in range(1, n) # rows.
  for j in range(i):  # range(1,i)
    print('*', end= ' ')
  print()
```


```
range(1) # 0, 1  (*)    # 0, 1 and 1 is valid , condition will become true ,if conddition is true ,you are asking to print *
range(2) # 0, 1, 2 (* * )
range(3) # 0, 1 ,2 ,3(* * * )
| Code       | Values generated | Stars printed     |
| ---------- | ---------------- | ----------------- |
| `range(1)` | `0`              | `*` (1 star)      |
| `range(2)` | `0, 1`           | `* *` (2 stars)   |
| `range(3)` | `0, 1, 2`        | `* * *` (3 stars) |

explantion:-
i = 1 j = 1
i = 2 j = 1
      j = 2
i= 3  j = 1
      j = 2
      j = 3
      

```
##### p-6

```
* * * * *
* * * *
* * *
* *
*
rows= 5
stars = 5, 4, 3, 2, 1(n-i)
```



```
n = 6 # when i take n = 6,i should start from 1 else i should start from -0
for i in range(1,n):
  for j in range(n-1):
    print('*', end= ' ')
  print()
```


##### *P-7*
```
- * * * * * 
- - * * * *
- - - * * *
- - - - * *
- - - - - *
rows = 5
space = 1 , 2 ,3, 4 ,5(i)
star = 5, 4, 3 , 2 , 1(n-i)
```

```
n = 6
for i in range(1, n ):
  for j in range(i):
    print('-', end= ' ')
  print( )

```

##### *1st-part*
```
-  
- - 
- - -
- - - - 
- - - - - 
```
##### *2nd-part*
```
n = 6
for i in range(1, n ): # rows
  for j in range(i): # space
    print('-', end= ' ')
  for k in range(n-i): # stars
    print('*', end= '')
  print()  # next row
```

```
n = 6
for i in range(1, n ): # rows
  for j in range(i): # space
    print('-', end= ' ')
  for k in range(n-i): # stars
    print('*', end= ' ')
  for z in range(1, n)
    print('+', end= ' ')
  print()  # next row
```
##### *output*
```
- * * * * * + + + + + 
- - * * * * + + + + +
 - - - * * * + + + + +
- - - -  * * + + + + + 
- - - - - * + + + + +
 ```
##### *p-8*
```
- - - - - *  
- - - - * *
- - - * * *
- - * * * *
- * * * * *
rows = 5
space = 5 , 4, 3 ,2, 1(n-1)
star = 1, 2, 3, 4, 5 (i)
```
```
n = 6
for i in range(1, n):
  for j in range(n-i): # stars
    print('-', end= ' ')
  for k in range(i):
    print('*', end= ' ')
  print() # next row

```

##### p-8
```
- - - - -  *
C
- - - * * * * *
- -  * * * * * * *
-  * * * * * *  * * *
rows = 5
space = 5, 4, 3, 2, 1(n-i)
stars= 1, 3 , 5, 7, 9 #odd number logic (2*i-1)

2*1 = 2-1 = 1
2*2 =4-1 = 3
```
```
n = 6
for i in range(1, n ) # rows
  for j in range(n-1) #space
    print('-',endl=' ')
  for k in range(2*i-1) # stars
    print()
```

```
n  = 6

```

##### *p-9*
```
- * * * * * * * * *
- - * * * * * * *
- - - * * * * *
- - - - * * *
- - - - - * 
rows = 5
space= 1, 2, 3, 4 ,5(i)
stars= 9, 7, 5, 3, 1 (2 *(n-1)-1)
2*(5-0)=10-1 = 9
2*(5-1) =8-1 = 7
```
```
n = 6
for i in range(1, n ) # rows
  for j in range(i) #space
    print('-',end=' ')
  for k in range(2*(n-i)-1) # stars
    print()

n = 6
for i in range(1, n):                 # rows
    for j in range(i):                # spaces
        print('-', end=' ')
    for k in range(2*(n-i)-1):        # stars
        print('*', end=' ')
    print()


```



##### *homework:-*
```
- - - - -  *
- - - - * * *
- - - * * * * *
- -  * * * * * * *
-  * * * * * *  * * *
- * * * * * * * * *
- - * * * * * * *
- - - * * * * *
- - - - * * *
- - - - - * 
```






