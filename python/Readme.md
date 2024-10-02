**class 1**
ways of writing : 3 ways
immediate, scripts and IDE
and general introduction , installation

**class:2**
KEYWORDS AND IDENTIFIERS

keywords are reseve words in py.
KW cant be used as var name or identifier.Used to define syntax ans structure .
KW are case sensitive.

Identifier:
names given to identities like class, function and varibales. differentiate one entity from other 

Rules:
combination of upper and lower case or digits (0 to 9) an underscore too.

cant start with digit .
cant use special symbols.

**Class:3**
Namespace :
collection of names holds mapping of every name defined
diff can coexist at given time but completely isolated.
builtin namespace created when we start python interpreter.
Modules can have various functions and classees .
local creared when functioncalled which has all names feined.

module :global naemsapce
funtion local namespace.

Datatype conversion :
converting value of one datatatype toanother datttype .
implicit and explicit type conversion 

python statements:
istructuions python execute if,else,for and while
multiline stats:
can do by adding \ atlast \
Indentations:
e.g:  for i in range(1,22):
        for j in range(1,24):
            print(i,j)

Comments:
 use hash (#) symbol in start for commenting

 Mutliline comments:
  use hash symbol in start of evryline 
   also by triple quotes,either ''' or"""".
   triple for multiline strings as well.

   Docstrings:
    short from of documentation string.
     string that occurs as first stats in module,function .must write function/class does in docstring.

**Class :4**
python variables

location used to store data in memory.
 must hace unique name called identifiers.

 it dont need declaration to reserve memory space.
 var declaration happens automatically when we assign value to variable.
  e.g:
  koubt = 100
  a,b,c =12.32.45

  constant is var whose value cant be changes . container whose values not changed.

  Naming conventions for var and cons:
  Nomenclature should be purpose.
  use camelcase notation
  use capital letters to reprsen concstants
  symblos cnt used.
  constant not chagens
  use undersocre or lowercase for declarations .  

  python shallow and deep copy:
  which store diff of original elments not create copy of nested contents in shallow copy

  deep adds new object and recurcisvely adds the copy of nested objects present in original elments

  **Class 5**
  Python operators

  symbols that carry arithmetic or logical computtation. value that opt have is oprand
  .
  Arithmetic operators:
  +,-,*,/,%,//,..
  comparison oprtors:
   > < == != >= <=
  Logical operators:
  and or not

  Bitwise operators:
  & ! ~ ^ >> <<

  Assignment operators:
  = += -= *=

  Identify operators:
   is,  is not

   Membership operators:
   in , not in 

python error  and exception 

error occur not by folloeing structure of language is syntax error or parsing error

Exceptions:
Assertion error(when assert statement fails), attribute error, 
EOF error(when input hit ends of file section)
Floating PointError(when floating point error)
GeneratorExit (when gen closed method called)
Import error ( when import module not found)
index error( when inde xof sequence is out of range)

**Class 6**
python directory and file managment

directory or flder is set of files and subdirectories

has os model which give us many methods to work with directories.
directory management means creating dir and listing directories

Python input, output and Import:
input () and print() widely used for input and output operations

for ease development, def inside module can be imported to another module or interactve interpreter in python . 
Use import keyword to do this.

Python essentials and pass statments

pass is null statements,
pass is not ignored
when it executed nothing hapends, it result in no operations(NOP)
pass
we genrally use it as a placeholder

Python Global: dec outside function . it can be accessed in side or outside functions.

Local: define inside function body
NonLocal var:
used in nested function whose local scope is not defined,
Means variable can be neither in the local nor golbal scope

**File 7**
Python functions
function is group of related statments perform specific task in our program.

break prgram into small and modular chunks, makes modular,organized and easy to debug.
Reusuablity feature help us to avoid repetition of our prgram codes. 

syntax:
def func():
   '''docstring'''
   statements(s)
   return value

types of functions:

builtin functions: chr(),abs(),flaot() and print()

Userdefined fun: defined by users themselves to do certain specific tasks.

Different datatypes:
numbers, list, tuple , strings, Set and Dictionary
also conversion possible 

Decorators:
to add functionality to an existing code

also called metaprogramming as part of program tries to modify another part of prgram at compile time.

Python closures:
 is a function object that remember values in enclosing scopes even if they are not present in memory

 **Class 8**
 Python Regular Expressions
 allow to you locate and change strings .
 work same in every language

 used to search for specific string in large amount of data.
 verify proper format.
 find  string and replace it with other string 
 foramt data into proper format for importing for proper use

 Nested Dictionary Implementation:
 dict inside dictionary . in one single dictionary 
 e.g: a={
   'b':{'a':"Ali"},
   'c':{'a':"Ali"},

 }

 **Class :9**
 condtional statments
 
 if syntax:

 if :
 statements(s)

esle syntax:
 if :
 body of if
 else:
 Body of else

elif syntax
 if elif:
 if :
 body
 elif :
 body
 else:
 body
we can have nested statments .
indentation is the only way to demark the level of nested

User defined exceptions:

**Class 10**
While loop:
used to iterate over a block of code as long as test expression is true.

while loop with else syntax :
have optional while loop as well.

else part exxecuted if while loop evaluates to false. while loop terminated with break stats.

then else part is ignore.

Essentials:
@property of python.

**Class :11**

File methods in Python:
close().
detach().
fileno().
flush().
isatty().
read(n).
readable().
readline(n=-1).
seek()
seekable()
tell()
truncate(size=None).
writable().
write(s).
writelines(lines).


Python function Arguments:
Arguments passing is optional. function can have fixed or variable number of arguments.

default arguments.
keyword arguments.
Arbitrary arguments.

Break statement:
 can alter flow of normal loop.
 loops iterate over block of code until test expression is false,but sometimes we wnat to terminate current iteration without checking test expressions.

 break terminates the loop containing it . control of program flows the statment immediately after body of loop.

 If break statement is inside a nested loop , break will terminate the inner most loop. (break:)

 Exception handling:
 
 Try, Except and Finally:
 has many builtin exceptions which enables our program to output an error message when someting goes wrong.

 When these exceptions occur , causes current process to stop and passes to calling process it is handled. If not handled ,our program will crash.

 **Class:12**
 Lists:

 refereed to as sequences. versatile datatype in python and most frequently used in python.

 append()
 extend()
 insert()
 remove()
 pop()
 clear()
 index()
 count()
 sort()

 List built in functions:
 all()
 any()
 enumerate()
 len()
 list()
 max()
 sorted()
 sum()

 Continous Statment:
 skip the rest of code inside loop for current iteration only. loop isnt terminate but continues on with the next iteration.(CONTINUE)

 Iterartion using for:
 for used for iterate over sequence , iterating over a sequence is called traversal.

 range function:

 generate sequence of numers using range().
 start,stop and step size as range. step size default to 1 not.

 with else :
 A for loop can also have an optional else block. else part executed when items in sequence used in for loop exhausts.

 break can be used to stop for loop.
 for loop's else part runs if no break occurs.

 **Python Recursion**
 Process in which function call itself directly or indirectly call recursive function . recursive algorithm certain problems start quickly.

 Also there will be base case.In base cases for certain inputs, output will remain known to us.
 Supports recursion.

 makes cide clean and elegant.
 complex task broken down into simpler sub problems using recursion.
 Sequence generation is easier with recursion using some nested iteration.

 sometimes logic behid recursion is hard to follow thorugh.
 recursive calls are expensive as they takeup alot of memory ans time.
 Recursive functions are hard to debug.

 python Strings:
 sequence of characters .contain alphbets ,digit and special characters.

 computers convert chars to num in binary representation.internally it is stored and manipulated as combination of 0 and 1.
 conversion of character to number is called encoding and reverse process is decoding.
 ASCII and Unicode are some popular encoding used.

 Python Assert:
 Assertionsa re statements that are assert or staet a fact confidently in our program.
 Assertion are simply boolean expressions that checks if condition return true or not.If true program does nothing and move to next line of code. However if false program stops and throw an error.

 Also a debugging tool as it brings the program on halt as soon as any error is occured and shows on which point of program error has occured.

 **Class:14**

 Arrays Implementation:
 are fundamentals part .collection of single element dattype , e-g:array of string and integer.
 append()
extend()
insert()
remove()
pop()
clear()
index()
count()
sort()
reverse()
copy()

Iterators:
implemented within for loops,generators but hidden in plain sight.

an object that canbe iterated upon.
__iter__() and __next__() collectively called iterator protocol.

builtin containers: list,tuple, string are iterators.

iter() return iterator form them.
next() must return next item in sequence.

Operator overloading:
work ofr builtin classes. but same opt behave diff with diff types.
This allows same opt to have diff meaning according to context is called operator overloading.

comparison overloading :
less tha, or equal to and so on.

**Class:15**
OOp language is simply collection of data and methods that act on those data. Class is blueprint of data.
Object is an instance of class and process of creating object is call instantiation.

Tuples:
is similar to list . but cant change element of tuple.

Advantages:
for heterogenous datatypes and list for homogenous.
tuple are immutable, performance boost.

immutable lements are used as key for dictionary.
.
Builtin Func in tuples:
all()
any()
enumerate()
len()
max()
min()
sorted()
sum()
tuple()

**Class:16** 
OOP Approach:

mutli paradigm language. by creating objects. that why it is OOP.
 two chars:

 Attributes.
 Behaviours or methods.

OOP focuses on reusuable code. Also known as DRT(dont repaet yourself)

principles:
Inheritance:using details from new class without modifyiing existing details.
Encapsulation:hiding private daetails of class from other objects.
Polymorphism:using common opt in diff ways for diff data input.

Python Anonymous Or Lambda function:
defined without having any name.

are used the lambda keyowrd.

anonymous function also call lambda function.

**Class:17**
Numbers:
it supports three number datatypes.
int,float,complex 

type() function to know which class var or value belongs to and instance ()function to check if it belongs to particular class.

Number data types:
15 decimal places.
binary(2),octal(8) and hexa(16).

reperesent these numbers by appropriate placing prefix before that number.
OB or 0B as binary number prefix.
0o or 00 as Octal number prefix.
Ox or 0x as hexadecimal number prefix.

type conversion.
builtin func:
int()
float()
complex().

Different Looping techniques:

Loop in python with condition at the top:

this implemented using without break statement. condition of while loop is at the top and loop terminats when this condition is false.

in middle:
this kind of loop can be implemented using an infinite loop along with cond break in bw the body of loop.
At bottoom:
body of loop implemented at least once.can be implemented using infinte loop along with conditional break at hte end. this is similar to do_while loop in c.

INfinite loop:
using while loop .if condition of while loop is always True, get an infinite loop.

File read and write operations:
logical unit of related information stored on name location on disk.used permanenetly store data in non volatile memory.
Since RAM is volatile, so it cant be treated for permanent storage of data.
when we read or write file we have  to close it.

file opt take place in following sequence.
open a file.
read or write a file(perform operation)
close the file.
r -> open file for  reading
w-> open for writing ,create new one if not exist.
x-> for exclusicne creation,if already exist opt fails.
a-> OPEN FILE FOR apending at the end of filewithout truncating it.create new one if not exist.
t -> open in text mode (default)
b-> open in binary mode.
+ ->open file for updating (reading and writing)

closing a file:
it will free resources that are tight with fileand done using close() .
it has garbage collector to clean up unref objects but, we notrely on it close the file.

**Claas:18** 

python matrix implementation

python sets:
unordered colection of unique items. No duplicate elements are allowed in set and must be immuteable.
union.intersection and symmetric operations.

add(),clear(),copy(),difference(),difference_update(),discard(),intersection,intersection_update(),isdisjoint(),issubset(),issuperset(),pop(),remove(),union(),update(),all(),any(),
enumerate(),len(),max(),min(),sorted(),sum().

**Class:19**
Dictionary

unordered collection of items it has key value pair.
optimized to retrieve values when key is known.

clear(),copy(),fromkey(),get(key[]),items(),keys(),pop(),values(),popitem(),setdefault(),update().

Modules.
is simply python source file which can expose classes,function and global variables. when imported from another source file file name is treated as python source file.  python package is simply directory of python module(s).
e.g: import numpy or import numpy as np 

Global keyword:
allow us to modify variable outside of current scope. used to create var and make changes to variable in local context.

HOW TO USE:
when we create var inside a function its local by default.
define var outside function its global by default.

We use global keyword to read and write global variable inside function.

use of global keyword outside a function has no effect.


LIST COMPREHENSION:

**File Read And write operations:**

Clsoing file:
safer mode is try finally block.

try:
f =open("emp.dat",encoding ='utf-8')
finally:
f.close()

file is properly closed evenif an exception is rasoed, causing program flow to stop.

best way to do this is by using with statement.
ensures  that file is closed when block inside with is exited without explicitly calling the close() method.

with open("test.txt", encoding ='utf-8') as f:
#perform opeartions.

**Python Inheritance:**
refers to deifne a new class with little or no modifications.
new class is derived class or child class.
one from which it inherits is base (parent ) class.

single,multiple,hierarchical,multilevel and hybrid inheritance.

**Python Generators:**

iterator in python incur lot of overheads.
implementing a class with __iter__ and __next__()method. then leeping track of internal states, rasie stop iteration when thre was no values to be returned.

this is both lengthy and counter intuitive. it comes with more simplicities.

Are simple a=way of creitng iterators. All overhead auto handled by genrators in python.

Generator is function that returns an object which we can iterate over.


-->differnece between Gneerator and normal function:
Gen function contains one or more yield statement.
when called it returns an object(iterator) but doesnt start execution immediately.

methods like __iter__() and __next__() are implmented automatically.so can iterate over items using next().
once function iters, fucntion is paused and control is transfered to caller.
local variables and their states are remembered between successive calls.

fially when function terminates , stop iteration  is raised automatically on further calls.

**--> Python multiple Inheritance:**
 Class derived form one more than base classess is multiple inheritance.

 in it features of all base classes are inherited into derived class. The syntax for multiple inheritance is similar to single inheritance.
