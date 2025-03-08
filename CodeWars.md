## Kata fait sur [Codewars](https://www.codewars.com/kata/search/lua?q=&beta=false&order_by=sort_date%20desc)

### Even or Odd kyu 8 

```lua 
local kata = {}

function kata.even_or_odd(number)
  if number % 2 > 0 then
   return "Odd"
  end
  return "Even"
end

return kata
```

### Count Odd Numbers below n kyu 8

```lua 
local function odd_count(n)
 return math.floor(n/2) 
  end
  
return odd_count
```
### String repeat kyu 8

```lua 
kata = {}

function kata.repeatStr(r, string)
  return string.rep(string,r)
end

return kata
```

### Plural kyu 8

```lua 
function isPlural(n)
  -- Your code here :)
  if n == 1 then 
    return false 
    else 
    return true 
    end 
end
return isPlural
```

### MakeUpperCase kyu 8


```lua 
local function make_upper_case(str)
  return string.upper(str)
end

return make_upper_case
```

### multiply kyu 8

```lua 
local kata = {}

function kata.multiply(a, b)
 return a * b
end

return kata
```


### reverse string kyu 8

```lua 
local function solution(str)
  -- Implement me! :D
  return string.reverse(str)
end

return solution
```
### convert a number to string kyu 8

```lua 
local kata = {}

function kata.number_to_string(number)
  --Your solution here
  return tostring(number) 
end

return kata
```

### Convert boolean values to strings 'Yes' or 'No' kyu 8

```lua
local solution = {}
function solution.bool_to_word(boolean)
if boolean == true then 
    return "Yes"
    else
    return "No"
    end
  
end
return solution
```


### Function 1 - hello world 8 kyu 

```lua 
local kata = {}

  -- Write a function `kata.greet` that returns "hello world!"
function kata.greet()
  return "hello world!"
  end


return kata
```
### remove string spaces kyu 8 

```lua 

local kata = {}

function kata.noSpace(str)
  return str:gsub("%s+","")
end

return kata
```




