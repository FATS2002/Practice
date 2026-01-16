##### missing: - introduction to datatypes</br>lang fundamentals</br>1.identifiers</br>2.reserved keywords</br>3.datatypes</br> 3.1typecasting</br>4. python stmts </br>4.1condition stmt (if,if-elif,if-elif,else)</br>4.2Iterative stmts(looping statements)for loops and while loop(in java ,we have do while loop)




#for loop
a= 10
for iterable_variable in  dataset:
  body of the loop
##### Ex:- 
```
a=10
for i in a:
  print(i)
```
```
a=10
for i in a:
  print(i)
```

##### output:
```
Traceback (most recent call last):
  File "c:\Users\SINDHUBR CHINTU\Desktop\PDBC\test3.py", line 10, in <module>
    for i in a:
             ^
TypeError: 'int' object is not iterable

[Done] exited with code=1 in 0.224 seconds
```

##### note: the only fundatmental datatype where you can apply looping stmt is "string"

```
a ='s'
for i in a:
  print(i)
```
##### output:
```
s
```
##### "for loop" is not applicable on "fundmental datatypes", "string" is the collection of character,it can be  one char, or collection of char,but for loop can be applicable for string datatype,</br>"for loop" is not applicable on "fundmental datatypes"because they hold only one element at the time,it is applicatble on string datatype becasue it holds multiple elements.
##### example
```
lst=[10,20,30,40]
for i in lst:  # iterable var(i) that is applying on dataset(lst),by default it will start from first element present in the dataset,whatever present in 0th index ,from there it will start
  print(i)
```
##### output
```
10
20
30
40
```
##### java
```
for (int i =1;i<5;i++)
{
print()
}

```

##### note:-if you are applying on dataset. 1.loop start from 1st element</br>2.loop iterate till last element.</br>3.step size is +1 from left to right.
##### bcuz unlike other languages,not gonna divide into diff datatypes primitive and nonprimitive,everything will come under one concept called datatype.</br> the moment you tell "list","tuple","set","dict"(dictionary),they have a boundary,what is the "starting point",what is the "ending point",they have the boundary.</br> so when ever there is boundary why i should  tell the starting point ,</br>the moment i knw i have to reach till lst element,then why i have to tell last element.

##### important note: whenever you are using a "for loop" make sure that,if you are giving dataset as an input,the above three things will happend automatically



##### wap to print 1 to 10 using for loop.(we will be using "range")
```
for i in range(1,11,1) # start point"n",end point"n-1",stepsize
  print(i)
```
##### output:
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

##### if in case you want a mechanism,you have to tell the starting point,you have to tell the ending point,you have to tell the step size,you should be using "Range datatype".</br>if i apply on dataset things will happen automatically, </br>if i dont want to apply on dataset,then i should be using "range datatype"
##### in range datatype i can tell what i starting point,ending point,and the stepsize


##### ex:-

```
for i in range(2,21.2):
  print(i)
```
##### output
```
2
4
6
8
10
12
14
16
18
20
```
##### applying for loop on dataset and on natural numbers using "Range function"

##### wap to print string
```
s = 'sachin'
print(s)
```
##### output
```
sachin
```
##### wap
```
print(s[0]) # s
print(type(s)) # type
print(id(s)) # address
print(len(s)) # len is gonna provide me no of char's present in the string or no of elements present in the dataset
```
##### output
```
s
<class 'str'>
3110805770464
6 # sachin
```
##### applying for loop
```
for i in s: # for loop being applied on dataset
  print(i)
```
##### output
```
s
a
c
h
i
n
```
##### wap to display the str with its char and  +ve and -ve index number

```
# output
0 s -6
1 a -5
2 c -4
3 h -3
4 i -2
5 n -1
s = 'sachin' # two ways in which you can apply for loop
#type-1
for i in s:
  print(i)
#type-2
for i in range(len(s)):  # len of s means 6 ,range of 6 means (0 to 5)
  print(s[i])
```
#####
```
s
a
c
h
i
n
s
a
c
h
i
n
```
##### impt:if the focus is on element use type-1,</br> if your focus is on index number ,going forward,(ex :- there will be index no in list,tuple,indexing format for dict based on key-calye pair,for set there is not index,for other things you have index mechanism). </br> if you want to get the data through index mechanism, you want to go with "type-2".</br>if you are focusing on the element means,go with "type-1"


#### type-2
```
s='sachin'
print(s)
for i in range(len(s)):
  print(i,s[i],i -len(s))  #i - len(s),0-6= -6
```
##### output
```
0 s -6
1 a -5
2 c -4
3 h -3
4 i -2
5 n -1
```

##### in inteview:- programatical interview based question is given,if you want to solve first thing,am i applying on "dataset" directly or am i going through the index format.(if you are directly applying on dataset,type-1 or you want indexnumber to fetch the element,then go with type-2 with the help of "Range datatype")



##### wap tp print number of consonents and vowels in the string
```
s='sachin'
[a,e,i,o,u] -> vowels rest are consonants
vowels - 2
consonants - 4

s='sachin'
print(s)
for in s:
  print(i) # traverse from first element to last element

```

```
s='sachin'  # string concept taking input
print(s)
lst= ['a', 'e', 'i', 'o','u']   # list concept
# i want to take count of consonants and vowels
vo, co = 0,0 # basic declaration of any data
for i in s:  # for loop
  if i is lst:  # condition
    vo = vo+1 # vo+=1
  else:   # in conditon im using membership mechanism
    co = co+1  # co+=1
print('vowels',,vo)
print('consonats',co)
```

##### output:
```
sachin
vowels 2
consonate 4
```

#### now it is giving me mechanism called "List",i will store my values in list,and it is giving me mechanism called as "membership operator",i can use that membership opertor? im asking question.(if alphabet "s" is present in list ,if "yes" it is vowel,"no" then it is  consonant)







