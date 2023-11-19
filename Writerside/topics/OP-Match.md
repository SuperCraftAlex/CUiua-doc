# Match
<deflist type="narrow">
    <def title="Symbol">
        <code>≅</code>
    </def>
    <def title="Names">
        <p><code>match</code></p>
    </def>
    <def title="Arguments">
        <p id="arg_1">array 1 <i>(array)</i></p>
        <p id="arg_2">array 2 <i>(array)</i></p>
    </def>
    <def title="Output">
        <p id="out">equals? <i>(number)</i></p>
    </def>
</deflist>

## Behaviour
Returns `⊤` if both arrays are equal.
Otherwise, returns `⊥`.

## Examples
```Python
[1 2 3] [1 2 3] ≅
# outputs: ⊤
```