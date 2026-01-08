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

##### string is collection of char's and iterable in nature.</br>integer can hold only one</br> element and string can hold "single alphabet" also group of elements also.

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
##### output 
```
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
##### output
```
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
##### output
```
```

#### Notes : refer day-6 sir notes for operator.


##### relational operator </br> Examples
```
# , >=, < ,<=
```


##### practice program example
```
a= 10
b= 2
print('a>b', a>b)
print('a>=b',a>=b)
print('a<b', a<b)
print('a<=b',a<=b)
```
##### output
```
a>b True
a>=b True
a<b False
a<=b False
```


##### Task: check out for strings and bool wrt to relational operators

##### chaining wrt to relational operators
```
print(10<20)  # true
print(10<20<30)  # true
print(10<20<30>40)  # false
print(10<20>30<40) # false
```
##### output
```
True
True
False
False
```
##### note: chaining of  relational operator is possible if all the results are true then</br> end result will be true else it will be false


##### 2.1 Equality operators AND(comparision operator )

##### Example:-
```
# == (equal to )
# != (not equal to)

a = 10
b = 2
print('a==b', a==b)
print(10!= 20 )   # true
```
##### in programming double equal (==) is called as 'equal' & single equal is called "assignment operator"



```
print(10==10! = 20) # true
```
##### ex
```
a= 10
b = 2
print('a==b', a==b)
print('a!=b', a!=b)
print(10!= 20) # true
```
##### output
```
a==b False
a!=b True
```








##### logical operators : </br> the logical operators are:</br> and or not


##### For boolean values types:
##### and -> if both inputs are true then end reult is true</br> or -> if atleast one input is true then the result is true</br> not -> complement or reverse of the input

##### bool datatype(and)

##### Ex
```
print(False and False) # False
print(False and True) # False
print (True and False) # False
print(True and True) # True
```
##### bool datatype(or)
#### Ex
```
print(False or False)  # False
print(False or True) # True
print(True or False) # True
print(True or True)  # True
```
#### logical operators on non bool datatype
```
print(4 and 5) # 5
print(0 and 5 ) # 0
print('abcd' and 'xyx') # xyx
print('' and 'xyz')  # empty string
```




##### For non-boolean types:
#####  0 means False </br>non-zero means True </br>empty string is always treated as False

#### x and y: </br> if x is evalutes to false return x otherwise return y. 
```
print (10 and 20)
print(0 and 20)
print('subbu' and 'anu')
print("" and'anu')
```

##### x or y: if x is evalutes to true return x otherwise return y

```
print(10 or 20)   # 10
print(0 or 20)    # 20
print('subbu' or 'anu') # subbu
print("" or "anu")   # anu
```


##### not x: if x is false then result is true else result is false.
##### Ex
```
# not
print(not 10)  # False
print(not 0)   # True
```
```
0 1 -> bit
00000000 -> 1 byte
1024 -> 1KB
1024KB -> 1Mb
1024 Mb -> 1gb
1024gb -> 1Tb
```

##### 4.bitwise operators
##### 1 byte = 8 bits</br>1 bit can store either 0 or 1. </br>we can apply the following operators bitwise</br> & | ^ ~ << >> </br>


```
###### & -> and operator </br> | -> or operator </br>^-> xor operator</br> ~ not operator</br> << -> left shift operator </br>
>> -> right shift operator 
```

```
print(4 & 5) #4
# 0000 0100  (4)
# 0000 0101 (5)
----
0000 0100  (4)

```
```
print('abcd' & 'xyz')  # Invalid
print('abcd' and 'xyz') # valid

print(4 | 5) # 5

 


```


##### xor
```
print(4 ^ 5)
00000100
00000101
-------
0000 0001  -> 1
```









