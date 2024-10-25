---
layout: stdlib-reference
---

# lerp

## Description

Computes linear interpolation.



## Signature 

<pre>
<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/lerp">lerp</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>&gt;(
    <a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/lerp#decl-x" class="code_param">x</a>,
    <a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/lerp#decl-y" class="code_param">y</a>,
    <a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/lerp#decl-s" class="code_param">s</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/lerp#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/lerp">lerp</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/lerp#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/lerp#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/lerp#decl-x" class="code_param">x</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/lerp#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/lerp#decl-y" class="code_param">y</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/lerp#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/lerp#decl-s" class="code_param">s</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/lerp#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/lerp#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/lerp">lerp</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/lerp#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="/stdlib-reference/global-decls/lerp#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/lerp#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/lerp#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/lerp#decl-x" class="code_param">x</a>,
    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/lerp#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/lerp#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/lerp#decl-y" class="code_param">y</a>,
    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/lerp#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/lerp#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/lerp#decl-s" class="code_param">s</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/lerp#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

#### T: [\_\_BuiltinFloatingPointType](/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index) {#typeparam-T}
#### N  : int {#decl-N}
#### M  : int {#decl-M}

## Parameters

#### x  : [T](/stdlib-reference/global-decls/lerp#typeparam-T) {#decl-x}
#### y  : [T](/stdlib-reference/global-decls/lerp#typeparam-T) {#decl-y}
#### s  : [T](/stdlib-reference/global-decls/lerp#typeparam-T) {#decl-s}
#### x  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-x}
#### y  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-y}
#### s  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-s}
#### x  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/t-0), [N](/stdlib-reference/types/matrix/index#decl-N), [M](/stdlib-reference/types/matrix/index#decl-M)\> {#decl-x}
#### y  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/t-0), [N](/stdlib-reference/types/matrix/index#decl-N), [M](/stdlib-reference/types/matrix/index#decl-M)\> {#decl-y}
#### s  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/t-0), [N](/stdlib-reference/types/matrix/index#decl-N), [M](/stdlib-reference/types/matrix/index#decl-M)\> {#decl-s}

## Return value
Returns <span class='code'><a href="/stdlib-reference/global-decls/lerp#decl-x" class="code_param">x</a>+(<a href="/stdlib-reference/global-decls/lerp#decl-y" class="code_param">y</a>-<a href="/stdlib-reference/global-decls/lerp#decl-x" class="code_param">x</a>)*<a href="/stdlib-reference/global-decls/lerp#decl-s" class="code_param">s</a></span>.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.



