
<h2> Methods </h2>

Spring.new

```lua
local Spring = Spring.new(TargetValue, [options])
```

This function will create a new Spring goal with a specified target value. The second parameter is an optional table that specifies the frequency and dampingRatio. If nothing is passed as the second parameter it will default the frequency to 4 and the dampingRatio to 1.

```lua
local Spring = Spring.new(TargetValue, {
    frequency = 3, 
    dampingRatio = 4
})
```

<hr>

Spring:step()

```lua
Spring:step(value, dt)
```

This function will step the current goal to the specified value and return a table consisting of ```complete```, ```value``` and ```velocity``` 


```lua
local state = Spring:step(value, dt)

print("is complete: "..state.complete)
print("alpha is: "..state.complete)
print("velocity is: "..state.velocity)
```

<h2> Replicating Specific Easing Styles </h2>

If you want to replicate a certain easing style with springs you will need to modify the alpha that is returned with certain math functions. 

!!! note "Further reading"
    You may notice a linear tween isnt shown. This is intentional since its recommend you use the Linear goal which can be found in the previous section.
    

<h3> Sine </h3>

<hr>

<h3> Back </h3>

<hr>

<h3> Quad </h3>

<hr>

<h3> Quart </h3>

<hr>

<h3> Quint </h3>

<hr>

<h3> Bounce </h3>

<hr>

<h3> Elastic </h3>

<hr>

<h3> Exponential </h3>

<hr>

<h3> Circular </h3>

<hr>

<h3> Cubic </h3>

<hr>


