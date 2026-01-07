##### python day 4.1

##### 1.identifiers </br>2.reserved keywords </br>3. dataypes </br> 4. mutability and immutability(modifiable and non modifiable) </br >typecasting

Missing concepts:- Range and none
##### all fundamental datatypes are immutable in nature,tuple is immutable,frozenset is immutable
</br>and list,set and dict are mutable in nature


##### type casting: - changing the datatype to one datatype to another datatype is known as type casting.

##### type casting in other languagues,you are range of memory for every datatypes,int means 4 bytes</br>
double means 8 bytes, </br> implicit type casting and explicit typecasting.
converting form lower datatype to higher datatype, or higher datatype to lower datatype
Example:-
```
a= 10
print(a)
print(type(a))
```

##### changing to float
```
a = 10
print(a)
b = float(a)
print(b)
print(type(a))  # int
print(type(b))  # float
```

#### wap 
```
lst=[10,20,30]
print(lst)
print(type(lst))
t = tuple(lst)
print(t)
print(type(t))

```
##### output
```
```


###### hw:- int -> float </br> int -> complex </br> int -> bool</br> int -> str</br> float -> int </br> float -> complex </br> float -> bool </br> float with string, </br> complex -> integer </br> complex-> float </br> all combinations with fundamental datypes we need to try it out. 

##### int to List:- 
```
a = 10
print(a)
print(type(a))
lst = lst(a) # converting to list
print(lst)
print(type(lst))
```
##### output
```
```
##### 1.all fundamental datatypes are capable of holding one element</br>2.all advance datatypes are holding multuiple elements</br> or more than one elements
#### reverse

```
a= [10]
print(a)
print(type(a))
lst = int(a)
print(lst)
print(type(lst))
```
##### output
```

```

##### all fundamental datatypes are holding single elements, so hence it is not possible.

a = 'python'  # string
print(type(a))
lst = lst(a)
print(lst)
print(type(lst))

# string is collection of char's and iterable in nature.</br>integer can hold only one element and string can hold "single alphabet" also group of elements also.

##### output
```
```

##### operators in python
operators is a symbol that performs certain operations.python provides the following set of operators.
1.aritmetic operators.</br>
2. relational operatos or comparision operators</br>
3.logical operators</br>
4.bitwise operators</br>
5.assignment opertors</br>
6.special operators</br>



##### arithmetic operators:-

```
+ --> addition
- --> subtraction
* --> multiplication
/ --> division
% --> modulo
// --> floor division
** --> exponent of power

```

```
a= 10
b = 2
print('a+b' , a+b)
print('a-b', a-b)
print('a*b', a*b)
print('a/b', a/b)
print('a%b',a%b)
print('a//b',a// b)
print('a**b', a**b)
```
##### output
```
```

###### Example:-
```
a = 'Sagar'
# b= 10
b ='10' # 10 is integer g which is presenet inside the string(datatype of b is string)
print('a+b', a+b)
```

##### output:-(string concatination)
```
```


##### integer and string with mul  (valid)
```
a = 5
b = 'sagar'

print('a*b', a*b)
print('sagar\n' * 5)  # prints ur name 5 times
```
#### Examplees:- 
```
str+ str  -> valid </br>
str * int -> valid (reverse of this is invalid)
```




##### WAP to get the result for a plus b whole square.  (a + b) square

```
# input value of a and b  
a = 5
b = 2
a square + b square + 2ab 
# PEMDAS rule (Paranthesis,Exponents, multiplication, division ,addition ,& multiplication)
print( 3+10 * 2)  # result = 23
print((3+10)* 2)  # result = 26 
print(3+(10* 2)) # result = 23
```



```
a = 30 
b = 20
c = 10 
d = 5
print((a+b) * (c/d)) # paranthesis(30 + 20)
#  division (10/5)
# multipliation   50 * 2 (result = 100)
print(a+(b+c)/d)
# paranthesis (20+10)
# division 30/ 5 (result = 3)
# addition (30 +3) result 33


```

























