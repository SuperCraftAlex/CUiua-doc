# Range
<deflist type="narrow">
    <def title="Symbol">
        <code>⇡</code>
    </def>
    <def title="Names">
        <p><code>range</code></p>
    </def>
    <def title="Arguments">
        <p id="arg_count">count <i>(number)</i></p>
    </def>
    <def title="Output">
        <p id="out">array <i>(array)</i></p>
    </def>
</deflist>

## Behaviour
Creates an array where the size matches
the argument <a anchor="arg_count">"count"</a>.
Every element is one bigger than the
previous element. (starting with zero)

## Examples
```Python
10 ⇡
# outputs: [0 1 2 3 4 5 6 7 8 9]
```