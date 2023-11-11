# Couple
<deflist type="narrow">
    <def title="Symbol">
        <code>⊟</code>
    </def>
    <def title="Names">
        <p><code>couple</code></p>
    </def>
    <def title="Arguments">
        <p id="arg_second">second <i>(?)</i></p>
        <p id="arg_first">first <i>(?)</i></p>
    </def>
    <def title="Output">
        <p id="out">output <i>(array)</i></p>
    </def>
</deflist>

## Behaviour
Creates a new array with the two given arguments as rows.

Scalars get converted to arrays.

## Examples
```Python
1 2 ⊟
# outputs: [[1] [2]]
```
```Python
1 [2 3] ⊟
# outputs: [[1] [2 3]]
```
```Python
[0 1] [2 3] ⊟
# outputs: [[0 1] [2 3]]
```