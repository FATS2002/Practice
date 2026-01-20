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
```
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
for i in range(1, n)


```

##### output









