## ici seras noté comment faire des petite choses d'algo en Lua 

### gsub

gsub permet de remplacer un élément par un autre dans une chaine de caractère 

```lua 
local string = "Bonjour Lundi"
local result = string:gsub("Lundi", "Mardi") -- remplace Lundi par mardi 
print(result) => -- Bonjour Mardi 
``` 
gsub a d'autre utilité 

```lua 
gsub("%s","") -- remplace les espace par rien 
gsub("%d","") -- remplace les chiffre par rien 
gsub("%a","") -- remplace les lettre majuscule ou minuscule
gsub(".","") -- remplace tout les caractère 
```

