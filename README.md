![image](https://user-images.githubusercontent.com/81253558/187270948-9fb680ab-716e-4fe3-a51d-16d44683e7af.png)
Your shell should work like this in interactive mode:


$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
(hbnb) 
(hbnb) quit
$
But also in non-interactive mode: (like the Shell project in C)

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
All tests should also pass in non-interactive mode: $ echo "python3 -m unittest discover tests" | bash


![image](https://user-images.githubusercontent.com/81253558/187271199-09a6a253-fdcf-4c56-b088-93522d4ac226.png)
