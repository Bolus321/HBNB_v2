80094392bf97
(hbnb) all
[]
(hbnb) quit
$
```

#### Non-Interactive Mode
```
$ echo "help" | ./console.py
(hbnb)
Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

(hbnb) $
$
$ echo "create BaseModel" | ./console.py
(hbnb) f09bfbad-532d-4bbe-a2c1-815b1958f01e
(hbnb) $
$ echo "all" | ./console.py
(hbnb) [[BaseModel] (f09bfbad-532d-4bbe-a2c1-815b1958f01e) {'id': 'f09bfbad-532d-4bbe-a2c1-815b1958f01e', 'updated_at': datetime.datetime(2018, 6, 13, 23, 16, 30, 420332), 'created_at': datetime.datetime(2018, 6, 13, 23, 16, 30, 420300)}]
(hbnb) $
$ echo "destroy BaseModel f09bfbad-532d-4bbe-a2c1-815b1958f01e" | ./console.py
(hbnb) (hbnb) $
$ echo "all" | ./console.py
(hbnb) []
(hbnb) $
$
```
---

