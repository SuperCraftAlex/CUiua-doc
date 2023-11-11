# Join
<deflist type="narrow">
    <def title="Symbol">
        <code>⊂</code>
    </def>
    <def title="Names">
        <p><code>join</code></p>
    </def>
    <def title="Arguments">
        <p id="arg_second">second <i>(array | ?)</i></p>
        <p id="arg_first">first <i>(array | ?)</i></p>
    </def>
    <def title="Output">
        <p id="out">joined <i>(array)</i></p>
    </def>
</deflist>

## Behaviour
Joins both arrays / appends an element to an array / creates an array of two elements.

## Examples
```Python
[1 2 3] 4 ⊂
# outputs: [1 2 3 4]
```
```Python
1 2 ⊂
# outputs: [1 2]
```
```Python
[1 2 3] [4 5] ⊂
# outputs: [1 2 3 4 5]
```