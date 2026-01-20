###### pythonday6.2

##### while loop </br> *syntax:*
```
initialization
while(condition):
  body of the loop
  increment/ decrement
```

##### *wap to print 1-10 using while loop*

```
i = 1
while i<= 1-:
  print(i, end=' ')
  i=i+1  #i+=1

```
##### *output*
```
1
2
3
4
5
6
7
8
9
10
```
```
1 2 3 4 5 6 7 8 9 10
```
##### *wap to print 10-1 using while loop*
```
i= 10
while i>=1:
  print(i , end= ' ')
  i=i-1
 ```

##### *wap to display the str with its char and +ve and -ve index number using while loop*
```
0 s -6
1 a -5
2 c -4
3 h -3
4 i -2
5 n -1
```


##### *output:*
###### *person1: s= 'sachin' # i need string </br> i = 0       # starting no zero</br>n = len(s)   # ending no  i will get from s*

```
# you need "starting point","condition"and "incr/decr"
s= 'sachin' # take a string
print(s)
i = 0       # starting no zero
n = len(s)   # ending n
while i< n:
  print(i,s[i],i-n)
  i=i+1
```



##### *wap to count the number of even and odd numbers using while loop*
```
ip-> lst= [4,6,3,23,72,81]
even-> 4
odd-> 3
```
```
lst= [4,6,3,8,23,72,81]
print[lst]
i = 0  # initial value
n = end(lst)
while i<n: # condtion
  print(lst(i))
  i+i+1  # incrementation/step size


lst= [4,6,3,8,23,72,81]
print[lst]
i = 0  # initial value
n = len(lst)
while i<n: # condition
  if lst[i]%2 == 0:
    even = even+1
  else:
    odd = odd +1
  i=i+1
print('even count is:', even)
print('odd count is: , odd')




# claude ai 
lst = [4, 6, 3, 8, 23, 72, 81]
even = 0
odd = 0
i = 0
n = len(lst)
while i < n:
    if lst[i] % 2 == 0:
        even += 1
    else:
        odd += 1
    i += 1

print("Even =", even)
print("Odd =", odd)

```
##### *wap to print number of consonants and vowels in the str using while loop*
##### *input -> sachin </br>[a,e,i,o,u] -> vowels</br>rest are consonants</br>vowles -2</br>consonants -4*





##### refer the for loop practice programs and convert all of those programs to "while loop" 



