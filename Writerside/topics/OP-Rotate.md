# Rotate
<deflist type="narrow">
    <def title="Symbol">
        <code>↻</code>
    </def>
    <def title="Names">
        <p><code>rotate</code></p>
    </def>
    <def title="Arguments">
        <p id="arg_count">n <i>(number)</i></p>
        <p id="arg_array">array <i>(array)</i></p>
    </def>
    <def title="Output">
        <p id="out">out <i>(array)</i></p>
    </def>
</deflist>

## Behaviour
Moves the first
<a anchor="arg_count">n</a> elements in the
<a anchor="arg_array">given array</a>
to the end of the array.

## Examples
```Python
[1 2 3 4] 2 ↻
# outputs: [3 4 1 2]
```