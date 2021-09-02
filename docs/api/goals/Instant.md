
<h2> Methods </h2>

Instant.new

```lua
local Instant = Instant.new(TargetValue)
```

This function will create a new instant goal with a specified target value.

<hr>

Instant:step()

```lua
local state = Instant:step()
```

This function will step the current goal to the ending state and then return a table of the current state. The table consists of ```complete``` and ```value``` keys.

```lua
    local state = Instant:step()
    print("is complete: "..complete)
    print("current alpha: "..value)
``` 

???+ warning
    This is the only goal that doesnt require any paremeters due to it being instant. 