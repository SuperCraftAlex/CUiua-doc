# Pick
<deflist type="narrow">
    <def title="Symbol">
        <code>⊡</code>
    </def>
    <def title="Names">
        <p><code>pick</code></p>
    </def>
    <def title="Arguments">
        <p id="arg_indices">index <i>(number)</i></p>
        <p id="arg_arr">array <i>(array of Ts)</i></p>
    </def>
    <def title="Output">
        <p id="out">out <i>(T)</i></p>
    </def>
</deflist>

## Behaviour
<a anchor="out">Outputs</a> the element at the given
<a anchor="arg_indices">index</a> in the given
<a anchor="arg_arr">array</a>.

## Examples
```Python
[1 2 3] 1 ⊡
# outputs: [2]
```