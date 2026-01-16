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
#####

##### p-2
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


##### using Range
```
for i in range(5):
  print(i) # it will print numbers 0 ,1,2,3, 4
  print('*')

```
##### output
```
```


##### p-3
```
for i in range(5):
  print('*',endl='') # end var with empty string

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
  print('*',end=' ')  #endl =''
print()
```
```
n = 5
for i in range(n):  # rows (take caring abour the rows)
  for j in range(n):  # star (take care of printing of stars)
    print('*', endl=' ')

##### where ever i hear the word repetation, use looping stmts









