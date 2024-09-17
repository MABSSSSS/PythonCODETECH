**Class:1**
Prolog in AI:

Intro to AI:
Intelligence is abilty attributed to people such as to know,think,talk and learn.

Intelligence = knowledge + abilty to percieve,feel,process,communicate,judge and leran.

study of complex information processing probelms that often have their rooms in some bioloigcal information processing. goal is to identify solvalbe and interseting inofrmation solving probelm;

AI is enterprise of construcuting physical problem system that can reliably pass turing test.

Goal of AI:
Scientific(mechanism behind human intelligence) , Engineering(capableof solving real world problems).

E.g: game playing, intelligent robots, speech and vision recoginition.

Learning systems., Natural language understanding systems.

Prolog:
is logical and declarative programming language,
mjor example of fourth gen programming langauge supporting declarative programming paradigm.
Relational databases owe something to prolog,(how to solve a problem).

Applications of prolog:
fast incre development sycle and rapid protoyping capabilites encourage use of langauge as tool for solving AI problems.
 powerful tool for building robust commercial applications.
 include interfaces to other languages and database products. standlone apps generators and support for techniques.

 Object oriented extensions .
 Cinctant replace prologs usual pattern matching mechanism with constraint  satisfaction"
 constrait are powerful tool to reduce siz of space and increase efficency of sceduler.

 INstallation of GNU prolog:

 Relations in prolog:
 among objects and properties of objects.
 Rule allow us to find out about relationship even if the relationship isnt explicitly stated as a fact. careful about phrasing things.

 **Class2**

 Prolog facts,rules and queries.
  
  facts based on explicit relations berween objects and properties mght have.

  rules implicit relationships between objects and defining object relationships.

  use sytem to generate queries by asking questions above reltion objects properties and .

  Name of reltions start with lowercase letter.
  relationship appear as first term.
  object appeared as comma seperated arguments within parenthesis.
   period ""  must end a fact.

   object begin with lowercase .also begin with digits and strings of character enclosed in quotes.
   phoneno also call predicate or clause.

   together these facts will form database.

   Rules:
   non unit clauses.
   Variables name start with a capital letter.

   Goal or query:
   Query based on facts and rules. ask question based on information.
   GNU quereis teminate by fullstop.
   to ans query prolog consult its datbase to see this is known facts or not.

   Syntax of clause:
   :- means if or "is implied by" .also neck symbol.
   left handside of neck is head.
   right handside of neck is body.
   comma "," stands for and / conjunction.
   semi-colon ";" stands for or/disjunction.

   program consist of three clauese: facts, rules and questions . Process is set of claueses about same relation.


Declarative sementics whether goal is true with respect to given program.
Procedural sementics: for satisfying list of goals in context of given program. automatically backtracks to examine alternatives.

Family relationships:
it is well suited for probrlms that invlove objects and relations between objects
Arguments of relations can be: concrete objects or constatns. first kind is atoms and second type is variables.

Dataobjects :
simple objects and structures.
simpleobjects to constants and variables.
constants to atoms and numbers.

**Class3**:
Atoms and numbers:

Atoms constructed in three ways: 
string of letters, digits andunderscore char,'_', starting with lowercase letter.
strings of special characters.<-->
it may have predfeined meaning:-

Strings of chars enclosed in single quotes. this is useful if we want. 
Numbers a can be of two types : int and real
treatment of real numbers depends on the implementation of prolog.

Varaiables:
 are strings of letters , digits and undersocre chars. start with uppercase or underscore characters.
 anonymous var written as single undersocre character.

 Structures:
  are objects that have multiple components.
  components themselves can, inturn, be structures.
  it can be naturally pictured as trees.pROLOG CAN BE viewed as language for processing trees.

  Representation of lists:
  collection of multiple elments. it canbe empty.
  used in nonnumeric morely.
  [a,b,c,d]
  first case written as prolog atoms. 
  Second case consist of two things: 
  1. first item, called head of list
  2. remaining part of list callled the tail.

  tail and a head. tail itself has to be list.
  vertical bar sep the head and tail.

  List operations:
  Membership
  member(X,L)
  x is an object and L is list.

  Concatenation:
  of two lists.(l=l1+l2)

  Union of two lists.
  union(l1,l2,l)
  Intersection of two lists:
  
**Class:4**
  Merge Sort of elements of list:
  define the procedure
  mergesort(L,SL)

