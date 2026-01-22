###### pythonday7:

###### *Lang fundamentals</br>1.identifiers</br>2.reserved keywords</br>3. datatypes</br>3.1 type casting</br>4.operators</br>5.python stmts</br>5.1 conditional stmt(if-elif-else)</br>5.2 iterative stmt.(for,while)</br>5.3 transfer stmt(break,continue,pass)*

*string datatype*
##### creation
```
s=''
s= ""
s = ''''''
s=str() #builtin function to create string
print(s)
print(type(s))
```
*output*
```
<class 'str'>
```

##### *single character*
```
s='a'
s="abcd"
s='India
is
my
country'   #error
s = '''India is my country''' # multiline string
print(s)
print(type(s))
```
*output*
```
a
<class 'str'>
```

###### *''' ''':- multi line comment,for multi line comment ,if i associate a variable it will become string*
##### quote mechanism
```
# s='This is a 'single' quote line' # how to overcome
# s="This is a 'single' quote line"
# s='This is a "double" quote line'
s='''This is a 'single' and "double" qupte line'''
s='This is a \'single\' quote line' # prefix with backslash "\"
```
*output*
```
```

##### memory management of str datatype

```
s1='hello'
print(s1)
s2='world'
print(s2)
print(id(s1))
print(id(s2))

print(s1[0])
print(id(s1[0]))

print(s2[0])
print(id(s2[0]))

```
*output*
```
```

##### example: the addr of l from string 1 and addr of string 2 same or different?add is same
```
s1='hello'
s2='world'
print(id(s1))
print(id(s2))

print(s1[2])  # l
print(id(s1[2]))

print(s2[3])   # l
print(id(s2[3]))
```

*output:*
```
```
*h&w -diff</br>l& l - same</br>o &o - same*

*checking memory address:-address is same, STRING MEMORY MANAGEMENT*
```
print(s1[4])
print(id(s1[4]))
print(s1[1])
print(id(s1[1]))
```
*Accessing the string*
s='learning python is easy'
*Accessing the complete str*
print(s)
*accessing the single element*
```
print(s[0])  # +ve index (l)
print(s[-1]) # -ve index (y)
```
*portion of the string(slicing mechanism)*
```
print(s[start:end:stepsize])
start -> inclusive (from where you have to start)
end-? exclusive(n-1) (from where you are going to stop)
stepsize->+1 left ot right 

print(s[1:5])
print(s[:])  # output:learing python is easy
print(s[::-1]) # reverse of that string (come from right to left)
print(s[9:16])  # word: "python"
print(s[-1:-4:-1])  # blank
print(s[-1:-5:-1])  # word: "easy"
print(s[19:]) # word: "easy"

```



##### homework: wap to print the char in forward and reverse direction using while loop.
```
input:- sachin
output:-
sachin
nihcas
```


```
#s= input('enter the string \n')
s= 'sachin'
print(s)
n = len(s)
print('forward direction')
i=0
while i<n: #forward direction
  print(s[i],end=' ')
  i++
print()
print('reverse direction')
i=0
n=len(s)-1
while n >=i:
  print(s[n], end=' ')
  n=n-1
```
