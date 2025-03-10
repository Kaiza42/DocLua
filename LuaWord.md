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

### tostring, tonumber 

```lua
local chiffre = 14523
local string = tostring(chiffre) -- convertie chiffre en string "14523"
local number = tonumber(chiffre) -- converti chiffre en number 14523
```
### math.random
```lua 
local caracteres = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789!@#$%^&*()"
-- plusieur façon de l'utiliser 
local indice = math.random(10) -- genere un chiffre entre 1 et 10 
local random = math.random(1, #caracteres) -- va me generer un caractere aléatoire de ma chaine de caractère 
local random = math.random(5, 10) -- va me generer un chiffre aléatoire entre 5 et 10
```

### sub: 

```lua 
local phrases = "Bonjour je m'appelle Jean" 
local sousPhrases = phrases:sub(1,7) -- 1 le debut 7 la fin, sa prendre une partie de la string 
```





