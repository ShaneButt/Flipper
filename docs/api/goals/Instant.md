
This instant goal is when you want the motion to be instanteous.

<h2> Methods </h2>


Instant.new

```lua
local Instant = Instant.new(TargetValue)
```

This function will create a new instant goal with a specified target value.

<hr>

Instant:step()

```lua
Instant:step()
```

This function will step the current goal to the ending state.

???+ warning
    This is the only goal that doesnt require any paremeters due to it being instant. 