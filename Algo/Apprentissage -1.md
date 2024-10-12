# Algorithme leçon 1
```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
### Premier élément 
#### Instruction de sortie 
Dans un algorithme, nous avons dans un premier temps le texte de début de l'algorithme, pour ensuite faire des actions dans cet algorithme et par la suite terminer chaque premier itération par un "fin". 

- on a donc par exemple `si` et donc on aura `fin si` a la fin de cette itération.

Un code d'algo ressemble normalement à ce type de 
``` algo
Algorithme NomAlgorithme 
Début
	... actions
Fin
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTgyMDgzNjg0OCwxMTMxNTgyNDM5XX0=
-->