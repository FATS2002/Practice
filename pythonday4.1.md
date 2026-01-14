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
````
a = 10
print(a)
b = float(a)
print(b)
print(type(a))  # int
print(type(b))  # float
````

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
23
26
23
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
# > , >=, < ,<=
```


##### practice program example
```
a= 10
b= 2
print('a>b', a>b)  # True
print('a>=b',a>=b) #  True
print('a<b', a<b)   # False
print('a<=b',a<=b)  # False
```
##### output
```
a>b True
a>=b True
a<b False
a<=b False
```
==========================================

##### Task: check out for strings and bool wrt to relational operators

##### chaining wrt to relational operators(all combinations are true then result is true)
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

##### 2.1 Equality operators AND(comparision operator )

##### Example:-
```
# == (equal to )
# != (not equal to)

a = 10
b = 2 
print('a==b', a==b)   # False
print('a!=b', a!=b)
print(10!= 20 )   # true  
```
##### in programming double equal (==) is called as 'equal' & single equal is called "assignment operator"
##### note: chaining of  relational operator is possible if all the results are true then</br> end result will be true else it will be false
</br>
##### logical operators : </br> the logical operators are:</br> and or not
##### For boolean values types:
##### and -> if both inputs are true then end result is true</br> or -> if atleast one input is true then the result is true</br> not -> complement or reverse of the input

##### bool datatype(and)
##### Ex
```
print(False and False) # False
print(False and True) # False
print (True and False) # False
print(True and True) # True
```
</br>
##### bool datatype(or)
#### Ex
```
print(False or False)  # False  # 0 with 0 is 0  and other combinations are true
print(False or True) # True
print(True or False) # True
print(True or True)  # True
```


#### logical operators on non-bool datatype
```
print(4 and 5) # 5    (4 is true so itll return 5)
print(0 and 5 ) # 0 ( 0 is false so itll return 0)
print('abcd' and 'xyx') # xyx     (abcd is true so it'll return xyx)
print('' and 'xyz')  # empty string (empty string is false itll return empty string)
```
##### For non-boolean types:
#####  0 means False </br>non-zero means True </br>empty string is always treated as False</br> even single alphbet is treated as false
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
print(not 10)  # False(10 is true , so res is false)
print(not 0)   # True(0 is false , so res is true)
```







###### other notes:
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
###### & -> and operator </br> | -> or operator </br>^-> xor operator</br> ~ not operator</br> << -> left shift operator </br> >> -> right shift operator 
```
##### and operator(when both are zero ,res is zero,only when both are one ,res is one)
```
print(4 & 5) #4
# 0000 0100  (4)
# 0000 0101 (5)
----
0000 0100  (4)

```
```
print('abcd' & 'xyz')  # Invalid(bitwise and operator)
print('abcd' and 'xyz') # valid (logical and operator)
print(4 | 5) # 5
```

##### xor(both 1's are there ,res will be zero, if both 0's are there , itll be zero)
```
print(4 ^ 5) 
00000100
00000101
-------
0000 0001  -> 1
```


```
x y res
0 0 0
0 1 1
1 0 1
1 1 0
```


#### not 
```
print(~20)  # -21
print(~5)  # -6
~ 00001 0100 --> 1's compliment
  1110 1011 --> 2's compliment
------------
1110 1011 --> -21
```
##### ex
```
print(10<<2)
```
```
0000 1010 -> 10
00<-
0000 1010 <-
0010 1000 -> 40
```


```
print(10>>2)
```

```
0000 1010 -> 10
-> 00
00 0000 1010
0000  0010 ->
```





##### assignment operator

```
a = 10 
print(a)  # 10
# b = 2
#a = a + b  
#print(a)   # 12 
a += 2 (a=a+2)
print(a) # 2
a *= 5
print(a) # 60
```


#### example:-
```
a = 'sachin'
a+="tendulker"
print(a)  # sachintendulker
```

##### 6. ternery operator
x = firstValue if condition is true else secondValue

##### ex:-
```
a,b  = 10,20
x = 30 if a<b else 40
```


##### 7.special operators:</br> python 3 has two sepecial operator such as:</br> 1.identity operator</br>2.membership operator
##### identity operator:- is --> is operator will check the address of the object and the address</br> based on the if address are same it will return true else false.</br> is not --> same as "is" operator but gived the reverded result of it.

##### identity operator
```
a= 10
b = 2
print(a == b) #compariny data of a and b
print(id(a))
print(id(b))
print(a is b) # comparing the address of a and b(comparing the memory add of the data)
print(a is not b)
```
#### output
```
False
140704617362632
140704617362376
```

##### membership check operator
##### ex:
```
s= 'sachin tendulker'
print(s)
print(a[7])  # t
print('t' in s)  # true(checking the data present in the dataset
)
print('z' in s) # false
print('n' not in s) # false
```


##### Flow control statements in python:</br> there are 3 diff types of flow control stmts in python such as;</br>1.conditional stmt</br>2.iterative stmt</br>3.transfer stmt.</br>1.conditional stmt;conditional statements consists of 3 variants such as:</br>

##### 1.if</br> syntax;</br> 
```
if conditional : statement
```
#### or
```
if  condition :
        statement1
        statement2
        statement3
```
##### example:
```
# if condition
name = input('enter the name')
if name =='sagar':
  print('hello sagar how are you?')
```

```
# input function in python
name= input('enter your name')
print(name)
print(type(name))
```
##### output
```
enter your namesagar
sagar
<class 'str'>
```

```
num = input('enter your roll no')
print(num)
print(type(num))
```
#### bydefault the "input" function will accept datatype in format of string


#### typecasting
```
num = input('enter your roll num')
num= int(num)
print(num)
print(type(num))
```
##### or 

```
num = int(input('enter your roll num'))
num= int(num)
print(num)
print(type(num))
```
##### flow control stmts
##### condition stmt
##### if condition:</br>(if condition is true execute the body)
```
if condition: #if the condition is true then execute the cboyd 
body
```

```
data= input('which chocolate you want?...')
if data == 'dairymilk':
  print('bring it..!')
```
##### output
```
which chocolate you want?...dairy milk
bring it..!

```
data= input('which chocolate you want?...')
if data == 'dairymilk':
  print('bring it..!')
else: 
  print('ice cream')
```

##### if else condition
```
if condition:
  body
else:
  body
```

##### ex:-
```
if elif else condition
if condition:
  body
elif condition:
  body
else:
  body
```

```
data= input('which chocolate you want?...')
if data == 'dairymilk':
  print('bring dairymilk')
elif data == 'kitkat:' #else if
  print('bring kitkat')
else: 
  print('bring ice cream')

```
##### no switch cases in python,but in java switch cases are present
##### nested if
```
if condition:
  if condition:
    body
  else:
    body
else: 
  body
```
##### problem statements:-
##### wap to fine the biggest number of the given two numbers.</br>wap to find the biggest number of the given three numbers
```
num1 = int(input('enter the num1 \n'))
num2 = int(input('enter the num2 \n'))
if num1> num2:
  print('num1 is greater than num2')
else:
  print('num1 is lesser than num2')
```
##### output
```
enter the num1
10
enter the num2
2
num1 is greater than num2
```
```
enter the num1
2
enter the num2
10
num1 is lesser than num2
```
##### and
```
num1 = int(input('enter the num1 \n'))
num2 = int(input('enter the num2 \n'))
num3 = int(input('enter the num3 \n'))
if (num1> num2) and (num1> num3):
  print('num1 is greater')
elif(num2 > num3):
  print('num2 is greater')
else:
  print('num3 is greater')
```
##### output
```
```

##### 2. wap to check whether the given number is even or odd.</br>3.wap to check whether number is b/w 1 to 100


```
data= int(input('enter the number \n'))
if data<=100:
  print(data, 'with in 100')
else:
  print(data, 'greater than 100')

```
```
```

