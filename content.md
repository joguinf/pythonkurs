- http://docs.python.org/2/tutorial/index.html
- http://peak5390.wordpress.com/2013/09/22/how-ipython-notebook-and-github-have-changed-the-way-i-teach-python/

Tag 1
=====

- Literale + Kommentare
  - Kommentare
  - bool
  - int
  - float
  - str/unicode
  - triviale "casts"
  - type-Kommando
  - Triviale Operationen +, -, *, **, /, %, in, not, and, or, bin, hex, ^, | , &, <<
  - ``"na"*10+" Batman!"``

  - Task: ``(a**p) % p``
  - Task: Fix this code in two different ways: ``print 99 + " bottles of beer on the wall, " + 99 + " bottles of beer."``
  
- Datenstrukturen
  - list  (append, del, [], extend, +)
  - tuple (immutable!)
  - dict  (key immutable!)
  - set/frozenset (&, | , -, ^)

  - List-Slicing ``[from:to:stepsize]`` (``[::-1]``)
  - Tausche zwei Variablen in Python ``(a, b) = (b, a)``

  - Task: Entferne alle Duplikate aus einer Liste.

- Kontrollstrukturen
  - if/else
  - for/enumerate
  - while

  - Task: Schreibe eine Prefixsumme. (for, enumerate)
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
  - min, max, ``sort(key=lambda x: -x)``

  - Task: Finde alle Zahlen in einer Liste, die sich zu 5 aufaddieren. (map, dict bzw. sort by |key|)
  - Task: ``print [x for x in range(2,1000) if not [y for y in range(2, int(x**0.5)+1) if x%y == 0]]``
  - Task: ``reduce(lambda x,y: x+y+x*y, primes)`` http://spikedmath.com/374.html

- Funktionales Programmieren II: Generatoren/Iteratoren
  - generator expressions
  - enumerate/sorted/reversed/zip
  - itertools
  - partials with lambda (forget about functool!)
  - yield
  
  - Task: Fibonacci- und Fakultätsgenerator bauen.
  - Task: Rekursiven Generator bauen.
  
- Funktionen
  - ``*args``, ``**kwargs``
  - First-Class-Citizens

Tag 2
=====

- Module
- ``import x``, ``from x import y``, ``import x as y``

- OOP
  - Klassen
  - Methoden
  - Duck-Typing
  - Magic methods (``__call__``)
- Dekoratoren

Tag 3
=====

- Standardbibliothek
  - random
  - ``python -m SimpleHTTPServer``
- Third-Party-Packaging (Distribution vs. PyPI)
  - virtualenv
  - easy_install/pip
  - Packages
      - requests
