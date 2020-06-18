Python 3.8.3 (tags/v3.8.3:6f8c832, May 13 2020, 22:20:19) [MSC v.1925 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> 
>>> ('Hello word')
'Hello word'
>>> # this is the first list
>>> (2+2)
4
>>> (4-2)
2
>>> (25/5)
5.0
>>> (3880-2336)
1544
>>> (*)
SyntaxError: invalid syntax
>>> (*+10)
SyntaxError: can't use starred expression here
>>> x
Traceback (most recent call last):
  File "<pyshell#9>", line 1, in <module>
    x
NameError: name 'x' is not defined
>>> (x)
Traceback (most recent call last):
  File "<pyshell#10>", line 1, in <module>
    (x)
NameError: name 'x' is not defined
>>> (x=15)
SyntaxError: invalid syntax
>>> print (pow (3,4))
81
>>> print (abs (-12))
12
>>> print (abs(6))
6
>>> print (math.floor(17.6))
Traceback (most recent call last):
  File "<pyshell#15>", line 1, in <module>
    print (math.floor(17.6))
NameError: name 'math' is not defined
>>> (math.floor(17.6))
Traceback (most recent call last):
  File "<pyshell#16>", line 1, in <module>
    (math.floor(17.6))
NameError: name 'math' is not defined
>>> a="Ali "
>>> b='mohammed'
>>> print(a)
Ali 
>>> print(b)
mohammed
>>> print(a+b)
Ali mohammed
>>> print ("HI 'mostafa' ")
HI 'mostafa' 
>>> mm=str(44)
>>> print("the number is " + mm)
the number is 44
>>> str = 'Hello world!'
>>> print str
SyntaxError: Missing parentheses in call to 'print'. Did you mean print(str)?
>>> print str [0]
SyntaxError: Missing parentheses in call to 'print'. Did you mean print(str [0])?
>>> str = 'Hello World!'
>>> print str
SyntaxError: Missing parentheses in call to 'print'. Did you mean print(str)?
>>> 
>>> y
Traceback (most recent call last):
  File "<pyshell#31>", line 1, in <module>
    y
NameError: name 'y' is not defined
>>> print str[0]
SyntaxError: Missing parentheses in call to 'print'. Did you mean print(str[0])?
>>> str = 'Hello World!'
>>> print str[2:5]
SyntaxError: Missing parentheses in call to 'print'. Did you mean print(str[2:5])?
>>> str=('Hello World!')
>>> print (str)
Hello World!
>>> print (str[0])
H
>>> print(str[2:5])
llo
>>> print (str[2:])
llo World!
>>> print (str*2)
Hello World!Hello World!
>>> print (str*4)
Hello World!Hello World!Hello World!Hello World!
>>> print(str+"test")
Hello World!test
>>> 
