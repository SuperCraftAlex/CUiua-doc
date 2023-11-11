# Reduce

<deflist type="narrow">
    <def title="Symbol">
        <code>/</code>
    </def>
    <def title="Names">
        <p><code>reduce</code></p>
    </def>
    <def title="Arguments">
        <p id="arg_fun">function <i>(function)</i></p>
        <p id="arg_arr">array <i>(array)</i></p>
    </def>
    <def title="Output">
        <p id="out">result <i>(?)</i></p>
    </def>
</deflist>

## Behaviour
Reduces the given <a anchor="arg_arr">array</a> with the given <a anchor="arg_fun">function</a>.
The first argument to the function is the current element. The second argument is the accumulator.

The <a anchor="out">output</a> of the operator is the accumulator.

## Examples
```Python
[1 2 3 4] (+) /
# outputs: 10
```