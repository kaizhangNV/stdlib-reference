---
layout: stdlib-reference
---

# matrix\<T, R:int, C:int, L:int\>\.init

## Description

Initialize a vector from a value of the same type




## Signature 

<pre>
<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>:int, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>:int, <a href="/stdlib-reference/types/matrix/index#decl-L" class="code_var">L</a>:int&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> <a href="/stdlib-reference/types/matrix/init#decl-val" class="code_param">val</a>);

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>:int, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>:int, <a href="/stdlib-reference/types/matrix/index#decl-L" class="code_var">L</a>:int&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value);

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(int v)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinFloatingPointType/index">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(float v)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinFloatingPointType/index">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(int value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> m00)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; row0)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 1, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 1, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 1, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 1&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 1&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 1&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; row0)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 1, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 1, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m02    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; row0)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 1, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m02    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m03    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; row0)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 1&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 1&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m11    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m02    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m11    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m12    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m02    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m03    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m11    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m12    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m13    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m20    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 1&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 1&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m11    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m20    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m21    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 2&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m02    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m11    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m12    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m20    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m21    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m22    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 3&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m02    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m03    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m11    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m12    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m13    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m20    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m21    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m22    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m23    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 2, 4&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m20    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m30    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; ,
row3    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 2&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 1&gt; ,
row3    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 1&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 1;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m11    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m20    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m21    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m30    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m31    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; ,
row3    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 3&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 2&gt; ,
row3    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 2&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 2;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m02    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m11    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m12    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m20    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m21    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m22    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m30    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m31    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m32    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; ,
row3    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 4, 4&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 3&gt; ,
row3    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 3&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 3;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m00    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m01    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m02    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m03    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m10    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m11    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m12    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m13    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m20    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m21    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m22    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m23    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m30    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m31    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m32    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> ,
m33    <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
row0    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; ,
row1    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; ,
row2    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; ,
row3    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(
m    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, 3, 4&gt; ,
row3    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, 4&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a> == 4;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == bool;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == int64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == intptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == half;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == float;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == double;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint8_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint16_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uintptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uint64_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;bool, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;int64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;intptr_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;half, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;float, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;double, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint8_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint16_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="/stdlib-reference/types/matrix/init">init</a>(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;uint64_t, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; value)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/matrix/T" class="code_type">T</a> == uintptr_t;

</pre>

## Parameters

#### val  : [T](/stdlib-reference/types/matrix/T) {#decl-val}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### v  : int {#decl-v}
#### v  : float {#decl-v}
#### value  : int {#decl-value}
#### value  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 4\> {#decl-value}
#### m00  : [T](/stdlib-reference/types/matrix/T) {#decl-m00}
#### row0  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 1\> {#decl-row0}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 1, 2\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 1, 3\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 1, 4\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 2, 1\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 2, 2\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 2, 3\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 2, 4\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 3, 1\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 3, 2\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 3, 3\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 3, 4\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 4, 1\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 4, 2\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 4, 3\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 4, 4\> {#decl-value}
#### m01  : [T](/stdlib-reference/types/matrix/T) {#decl-m01}
#### row0  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 2\> {#decl-row0}
#### m02  : [T](/stdlib-reference/types/matrix/T) {#decl-m02}
#### row0  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 3\> {#decl-row0}
#### m03  : [T](/stdlib-reference/types/matrix/T) {#decl-m03}
#### row0  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 4\> {#decl-row0}
#### m10  : [T](/stdlib-reference/types/matrix/T) {#decl-m10}
#### row1  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 1\> {#decl-row1}
#### m11  : [T](/stdlib-reference/types/matrix/T) {#decl-m11}
#### row1  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 2\> {#decl-row1}
#### m12  : [T](/stdlib-reference/types/matrix/T) {#decl-m12}
#### row1  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 3\> {#decl-row1}
#### m13  : [T](/stdlib-reference/types/matrix/T) {#decl-m13}
#### row1  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 4\> {#decl-row1}
#### m20  : [T](/stdlib-reference/types/matrix/T) {#decl-m20}
#### row2  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 1\> {#decl-row2}
#### m  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 2, 1\> {#decl-m}
#### m21  : [T](/stdlib-reference/types/matrix/T) {#decl-m21}
#### row2  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 2\> {#decl-row2}
#### m  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 2, 2\> {#decl-m}
#### m22  : [T](/stdlib-reference/types/matrix/T) {#decl-m22}
#### row2  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 3\> {#decl-row2}
#### m  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 2, 3\> {#decl-m}
#### m23  : [T](/stdlib-reference/types/matrix/T) {#decl-m23}
#### row2  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 4\> {#decl-row2}
#### m  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 2, 4\> {#decl-m}
#### m30  : [T](/stdlib-reference/types/matrix/T) {#decl-m30}
#### row3  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 1\> {#decl-row3}
#### m  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 3, 1\> {#decl-m}
#### m31  : [T](/stdlib-reference/types/matrix/T) {#decl-m31}
#### row3  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 2\> {#decl-row3}
#### m  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 3, 2\> {#decl-m}
#### m32  : [T](/stdlib-reference/types/matrix/T) {#decl-m32}
#### row3  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 3\> {#decl-row3}
#### m  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 3, 3\> {#decl-m}
#### m33  : [T](/stdlib-reference/types/matrix/T) {#decl-m33}
#### row3  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), 4\> {#decl-row3}
#### m  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), 3, 4\> {#decl-m}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<int8\_t, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<int16\_t, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<int, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<int64\_t, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<intptr\_t, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<half, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<float, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<double, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<uint8\_t, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<uint16\_t, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<uint, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<uint64\_t, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<uintptr\_t, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<bool, [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-value}

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.


