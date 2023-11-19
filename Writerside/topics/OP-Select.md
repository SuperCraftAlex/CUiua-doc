# Select
<deflist type="narrow">
    <def title="Symbol">
        <code>⊏</code>
    </def>
    <def title="Names">
        <p><code>select</code></p>
    </def>
    <def title="Arguments">
        <p id="arg_indices">indices <i>(array)</i></p>
        <p id="arg_arr">array <i>(array)</i></p>
    </def>
    <def title="Output">
        <p id="out">out <i>(array)</i></p>
    </def>
</deflist>

## Behaviour
<a anchor="out">Outputs</a> an array of all elements
in the argument <a anchor="arg_arr">array</a> at the
<a anchor="arg_indices">given indices</a>.

## Examples
```Python
[9 4 1 2 5 3] [1 2 3] ⊏
# outputs: [4 1 2]
```