Tag 1
=====

- Literale + Kommentare
  - bool
  - int
  - float
  - str/unicode
  - Kommentare
  - Task: (a^p) % p
  - Task: Fix this code: print 99+" bottles of beer on the wall, "+99+" bottles of beer."
  
- Datenstrukturen
  - list
  - tuple
  - dict
  - set/frozenset
  
  - Task: Tausche zwei Variablen in Python (a, b) = (b, a)
  - Task: List-Slicing [from:to:stepsize] ([::-1])
  - Task: Entferne alle Duplikate aus einer Liste.

- Kontrollstrukturen
  - if/else
  - for/enumerate
  - while
  - goto/do-while :D

  - Task: Zerlege Zahl in die Koeffizientendarstellung zur Basis b (while)
  - Task: Baue aus Koeffizientendarstellung zur Basis b wieder die Zahl (for, enumerate)
  - Task: Square & Multiply (Binärdarstellung, for, if)

- I/O und Exception-Handling
  - with open (with allgemein, Tag 2), modes "rw+b"
  - binary vs. acsii / array-Modul
  - try/except
  - assert  

  - Task: Handle IOError
  - Task: Doubles aus einer Datei einlesen und das Doppelte wegschreiben ASCII. (with)
  - Task: Doubles aus einer Datei einlesen und das Doppelte wegschreiben Binary. (with, array)
  - Task: Doubles aus einer Datei einlesen ASCII, ignoriere invalide Zeilen. (with, try)

- Funktionales Programmieren I: Lambda/Comprehensions

  - Comprehensions: list, set, dict
  - lambda 
  - map, filter, reduce, sum
  - zip, X, Y = zip(*zip(X, Y))
  - min, max, sort (key=lambda x: -x)

  - Task: Finde alle Zahlen in einer Liste, die sich zu 5 aufaddieren. (dict bzw. sort by |key|)
  - Task: reduce(lambda x,y: x+y+x*y, primes) http://spikedmath.com/374.html

- Funktionales Programmieren II: Generatoren/Iteratoren
  - generator expressions
  - enumerate/sorted/reversed
  - itertools
  - partials with lambda (forget about functool!)
  - yield
  
  - Task: Fibonacci- und Fakultätsgenerator bauen.
  - Task: Rekursiven Generator bauen.
  
- Funktionen
  - *args, **kwargs
  - First-Class-Citizens
  - Switch-Statement :D

Tag 2
=====

- OOP
  - Klassen
  - Methoden
  - Duck-Typing

