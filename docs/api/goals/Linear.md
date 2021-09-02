
<h2> Methods </h2>

Linear.new

```lua
local Linear = Linear.new(TargetValue, [options])
```

This function will create a new linear goal with a specified target value. The second parameter is an optional table that specifies the velocity. If nothing is passed as the second parameter it will default the velocity to 1.

```lua
local Linear = Linear.new(TargetValue, {velocity = 1})
```

<hr>

Linear:step()

```lua
Linear:step(value, dt)
```

This function will step the current goal to the specified value and return a table consisting of a ```complete```, ```value``` and ```velocity```


```lua
local state = Linear:step(value, dt)

print("is complete: "..state.complete)
print("alpha is: "..state.complete)
print("velocity is: "..state.velocity)
```
