*1.wap to reverse a given str with and without using slicing mechanism(with slicing and without slicing)*
```
input=sachin
output=ihcas
s= 'sachin'
print(s)
# 1st way using slicing
print(s[::-1])
#2nd way using loop
n = len(s)-1
s1=''
while n>=0:
  s1+=s[n]
  n-=1
print(s1)
# 3rd way
print(''.join(reversed(s)))
```
*2.reverse the words present in the str</br>ip->Learning python is easy</br>op->easy is python Learning*
```
s= 'Learning python is easy'
print(s)
lst=s.split()
print(lst)  #list
lst =lst[::-1]
s1=' '.join(lst)
print(s1)
# wo slicing
lst=s.split()
print(lst)  #list
n = len(lst)-1
lst1=[]
while n>=0
  lst1.append(lst[n])
  n-=1
s1=' '.join(lst)
print(s1)

```
*output*
```
```

*1.use split method</br>2.reverse the string.</br>3.convert list to string*

*2. reverse the internal char present in the str*
```
ip-> knowledge is power
op->egdelwonk si rewop

```
*4.seperate the char based on even and odd index number with and with out using slicing*
```
ip->sachin
op->even char-> sci
odd char->ahn
s= 'sachin'
print(s)
# using slicing
print(s[::2]) # even char
print(s[1::2]) # odd char





```


