###### pythonday10.1:  (python day 10)
*wap to print the even numbers with the help of list*
##### list comprehension:-

##### Without LC
```
lst1=[1,2,3,4,5,6,7,8,9,10]
print(lst1)
lst2=[]
for i in lst1:
  if i%2==0:
    lst2.append(i)
print(lst2)
```
*concept: List comprehension:*

##### using LC
#### syntax:(take a list , and assig it to square bracket)
```
lst=[what i want from where i want  based on what]
list_variable=[ expression looping stmt condition stmt]
```
*Example:- to reduce number of lines of code*
```
lst1=[1,2,3,4,5,6,7,8,9,10]
print(lst1)
lst2=[i for in lst1 if i%2==0]  # "i"  "for in lst1" "if i%2==0"
# i = expression,  for i in lst1 (looping stmt), if i%2==0 = condition stmt
print(lst2)
```
##### 2. wap with and without LC.(To chk int or non integer)
```
input=[10,2.5,2+3j, True,'abcd',20,50]
output=[10,30,20,50]
```
```
lst1=[10,2.5,2+3j, True,'abcd',20,50]
print(lst1)
lst2=[]  # create empty list
for i in lst1:# traverse
  if type(i) == int:
    lst2.append(i)
print(lst2)
```
```
if i%==1
if i%2== 0 # to fetch even number
10, abcd  # isalpha or isdigit
```
*using LC*
```
lst1=[10,2.5,2+3j, True,'abcd',20,50]
print(lst1)
lst2= [i for in lst1 if type(i)==int ]
print(lst2)
```
##### output:-
```
```
##### 3.wap to get the even number greater than 4
```
input=[1,2,3,4,5,6,7,8,9,10]
output=[6,8,10]
```
##### without LC
```
lst1=[1,2,3,4,5,6,7,8,9,10]
lst2=[]
print(lst1)
for i in lst:
  if i>4:
    lst2.append(i)
print(lst2)
```
##### with LC
```
lst1=[1,2,3,4,5,6,7,8,9,10]
lst2=[]
print(lst1)
lst2=[i for in lst1 if i>4]
```
      
