## Reduce requirements

<ol class="li-margin"->
    <li>Return type must be the same as return type of map function (emit second arg).</li>
    <li>reduce(key, [A, reduce(key, [B, C])]) = reduce(key, [A, B, C])</li>
    <li>reduce(key, reduce(key, [A, B])) = reduce(key, [A, B])</li>
    <li>Result value MUST not depend on order of the arguments</li>
</ol>
