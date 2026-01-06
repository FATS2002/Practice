##### Notes day 2
##### Memory units available in  computer 
```
print('Hello world..!')
```

##### ctrl + L and cmd
 Examples:- <br>
python demo.py
```
import sys
print(sys.argv[0]) # argv - argument value
print(sys.argv[1])
print(sys.argv[2])
```
##### output
```
hello world..!!
demo.py
sagar
```

python demo.py

##### args for java, argv for python
##### Command Line argument (arguments means inputs)


##### memory management,<br> PRE PVM memory managment,<br>command line argument,<br> Interpretive mode/interactive mode,<br> File mode


```
print('hi')
```


##### Language fundamentals of python
##### 1.Identifiers <br> 2. Reserved keywords <br>3. data types<br> 4. operators<br> 5. python statements<br>
 5.1 conditional statements<br>
 5.2 Iterative statements (Loops)<br>
 5.3 Transfer statments<br>

#####  after covering lang fundaments , (Interview based programs)
##### Functions in python,<br> object orientation,<br> pillars of oops,<br> advance concepts

##### SQL + python (python database connectivity-PDBC) <br> python networking(socket programming)



##### Projects (framework)
##### django framework<br> MVT architecture<br>

##### Lang fundmentals

##### 1.Identifiers
'name' that is used in code
variable,class,methos,functions,constants...

```
a = 10 # a is variable which stores data # a is assigment operator
```
```java
int a = 10; # java 
```
```
a= 10 # python
```

##### Rules of identifiers
1. it should be a-z A-Z 0-9
Examples:-<br>
 sachin = 100<br>SACHIN = 100<br> Sachin = 100<br>$achine=100 (invalid)<br>
_ (underscore)
2. it should always starts with alpha and no digits
Examples:-
virat18=100
vi18rat=100
18virat=100 (invalid)


##### 3.python identifiers is case senstitive
sachin = 100<br>
SACHIN = 100<br>
Sachin = 100<br>
(all 3 are different variable)<br>

#### No length limit for identifiers(suggested 15 chr max) 
Examples
4.abcdefghijklmnopqrstuvwxyz =26 (valid)

5.no space btw the identifiers
Ex:-
sachin tendulker =100
sachin_tendulker = 100 (snake case convetion) python
sachinTendulker =100 (camel case covertion) java


6.Examples:-print = 10(invalid )<br> int =10(valid)<br> Integer = 100(valid)
```
int = 10
print(int)  
Integer = 10  # valid 
print(Integer)
```

7. only _ underscore special symbol is used in python identifiers
```
$achin =10  #invalid
print($achin)
```
```
_s = 10  #valid
print(_s)
```
underscore can be used in beginning ,inbtw and end

8. some of the builtin functions names can not be used as identifiers
```
print = 100
print(print)
```
##### 2.Reserved keywords: These are the builtin keywords used for specific task which can not be used as identifiers

```
from keywords import list
print(keyword.list)
```
```
import keyword
print(keyword.kwlist)
```
##### output (reserved keywords)
```
['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break',
 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally',
 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal',
 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
```


```
max =100
print(max) # valid
```
```
input =10
print(input) #valid
```






##### datatypes in python:-
Type of the data is called as datatype.  Every data is classified under certain types.
Fundam=mental datatypes
##### 1.int<br> 2.float 3.complex 4.bool 5.str 
##### Intermediate datatype
6.byte 
7 bytearray
##### advanced datatype
8.list
9.tuple
10.set
11.frozenset
12.dict
##### additional datatype
13.range
14.none         

```
a =10
print(a)
print(type(a))

a =10.5
print(a)
print(type(a))

a =10 +2j
print(a)
print(type(a))

a =True
print(a)
print(type(a))

int a = 10;
```

output:-
```
10
<class 'int'>
10.5
<class 'float'>
10 + 2j
<class 'complex'>
True
<class 'bool'>
```


##### python day -03
Lang fundmentals
Identifiers
2.reserved keywords
3. dataypes


##### meaning of datatype:- if you take any data if belong sto some types
#### how many datatypes available in python(14 types) (python3 version)
 fundamental datatype
   1.int
   2. float
   3.complex
   4. bool
   5. str
  intermediate datatype
  6.bytes
  7.bytearray

  
advanced datatype
8.list
9.typle
10.set
11.frozenset
12.dict

additional datatypes
13.range
14.None

Main pillars of datastructures in python.
'''
# java
int a = 10; (statically typed programming language) (our responsibility to tell the datatype in java)

# python (we need not to tell dataype ,dynamically it will take datatype)
a = 10 
'''




# integer
a= 10
print(a)
print(id(a))  #address (of that data where it is present in memory)
print(type(a)) #type is a buildin function(Type)


output: 
10
140522489325928
<class 'int'>


** Process exited - Return Code: 0 **


 
Important point:- everything you store in python is considered as data,and everydata in background is treated as object.


# float
a= 10.5
print(a)
print(id(a))
print(type(a))

10.5
139714664918992
<class 'float'>
** Process exited - Return Code: 0 **


# complex(real numbers and imaginary number)
```
a= 10+ 2j
print(a)
print(id(a))
print(type(a))
```
##### output
```
(10+2j)  # simple bracket means tuple datatype.
140561710906480
<class 'complex'>
** Process exited - Return Code: 0 **
```


# bool(binary value 0 or 1)
```
a = False
a= True
print(a)
print(id(a))
print(type(a))
```
#### output

```
True
139909092889504
<class 'bool'>

** Process exited - Return Code: 0 **
```



##### string :- alphabet,group of alphabets,


```
a= 's'
print(a)
print(type(a)) # type

a= ''   # empty string
print(a)
print(type(a)) # type


a= 'sagar'  # group of characters
print(a)
print(type(a)) # type

```

#### empty string is considered as string only in python 3
output
```
s
<class 'str'>

<class 'str'>
sagar
<class 'str'>
```


##### string datatyp in detail:

##### string objects: it is stored in<br> form of indexing mechanism.
<br> int datatype: multiple no formatting 
<br> 10 -> decimal format(default)
<br> binary format 0-1
<br> octal format 0-7
<br> hexa decimal format  0-9  a-f
#### examples for the above:-
```
a = 10
print(a)
a = 0b10
print(a)   
a= 0B11
print(a)
a= 0B12
print(a)
a = 123
print(a)

a = 0o123
print(a)

a = 0O123
print(a)

a = 0o148(0 to 7)
print(a)
a=349
a= 0x349
a=0xface
a= 0xbook
print(a)

```
##### output
```
10
2
3
```

#### in python3 ,for integer datatypes suppport 4 diff types of number formatting. decimal ,binary octal ,hexdecimal


#### Example:- for binary "0b"  <br> for octal "0o"  <br> for hexdecimal "0x"





##### base conversion
```
a =15   # decimal to binary
print(a)

b= bin(a) # builtin func for binary conversion
print(b)

a = 45
print(a)
o= oct(a)
print(o)


a =123
print(a)
h = hex(a)
print(h)



```
#### output
```

```




















