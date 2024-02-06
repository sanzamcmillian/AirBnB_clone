# 0x00. AirBnB_clone - The Console

This is a team project to clone the Airbnb web app[Airbnb](https://www.airbnb.co.za)

The console is a command interpreter to manage on objects abstraction between objects and how they are stored.

The console will perform the following:
- create a new object
- retrieve an object from a file
- do operations on objects
- destroy an object

All classes are handled by the "Storage" engine in the "file storage" class for now, since we haven't started on SQL.

# Execution 
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$

# Non-interactive mode
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
