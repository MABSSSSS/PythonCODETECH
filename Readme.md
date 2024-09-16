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