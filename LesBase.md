
## Variable 


| Type de variable | Description |
|-----------------|-------------|
| `nil` | Valeur absente |
| `boolean` | `true` ou `false` |
| `number` | Nombre (entier ou flottant) |
| `string` | Chaîne de caractères |
| `table` | Objet clé-valeur |
| `function` | Fonction |
| `thread` | Coroutine |
| `userdata` | Objet C |
| **Globales** | Accessibles partout |
| **Locales** | Accessibles uniquement dans un bloc |
| **Upvalues** | Fermeture de fonction |

## Opérateur 

| Catégorie | Opérateur | Description |
|-----------|-----------|-------------|
| **Arithmétiques** | `+` | Addition |
|  | `-` | Soustraction |
|  | `*` | Multiplication |
|  | `/` | Division |
|  | `%` | Modulo (reste de division) |
|  | `^` | Exponentiation |
|  | `-` | Négation (unaire) |
| **Relationnels** | `==` | Égalité |
|  | `~=` | Inégalité |
|  | `<` | Inférieur à |
|  | `>` | Supérieur à |
|  | `<=` | Inférieur ou égal à |
|  | `>=` | Supérieur ou égal à |
| **Logiques** | `and` | ET logique |
|  | `or` | OU logique |
|  | `not` | NON logique |
| **Concaténation** | `..` | Concaténation de chaînes |
| **Longueur** | `#` | Longueur d'une chaîne ou d'une table |
| **Indexation** | `[]` | Accès aux éléments d'une table |
| **Affectation** | `=` | Affectation simple |
| **Autres** | `()` | Appel de fonction |
|  | `;` | Séparateur d'instructions |

### if 
```lua 
local six = 6 
if six == 6 then 
print("je suis egale a " .. six )
end
```
### if else 
```lua 
local six = 6
if six == 8 then 
print("je suis egale a 8")
else 
print("je suis egale a " .. six)
end
```
### if elseif else
```lua
local six = 6
if six == 8 then 
print("je suis egale a 8" )
else if six == 6 then 
print("je suis egale a 6")
else 
print("je suis egale a " .. six)
end
```
### if not
```lua
local six = 6
if not six == 5 then 
print("c'est pas égale a 5")
end
### boucle for 
```
```lua
for x = 1, 10 do -- compte de 1 a 10 
    print(x) -- affichage
end -- fin de la boucle 
```

### une boucle for avec une conditionnel
```lua 
for x = 1, 10 do 
    if x == 1 then 
    print("Mon nombre est " .. x )
    elseif x == 2 then 
    print("Mon nombre est ".. x)
    elseif x == 3 then  
        print("Mon nombre est " .. x)
    elseif x == 4 then
        print("Mon nombre est " .. x)
    elseif x == 5 then
        print("Mon nombre est " .. x)
    elseif x == 6 then
        print("Mon nombre est " .. x)
    elseif x == 7 then
        print("Mon nombre est " .. x)
    elseif x == 8 then
        print("Mon nombre est " .. x)
    elseif x == 9 then
        print("Mon nombre est " .. x)
    else 
        print("Mon nombre est " .. x)
    end 
end   
```

### function 

```lua
function calcul(a,b)-- a et b les paramettre
return a + b -- ici seras fait le calcul
end -- fin de la fonction 

print(calcul(14,16)) -- affichage de la function et on donne une valeur aux paramettre 
```
### repeat & until
```lua 
local chiffre = 1 -- la variable qu'on incrémente
repeat -- le repeteur 
print("le chiffre est " .. chiffre) -- le print pour voir le resultat
    chiffre = chiffre +1 -- incrémentation de chiffre
until chiffre > 10 -- la condition de la répétition
```
### while 

```lua 
local compteur = 1 -- la variable du compteur 

while compteur <= 10 do -- tant que le compteur est inférieur à 10
    print(compteur) -- affiche le compteur
    compteur = compteur + 1 -- incrémente le compteur
end
```
