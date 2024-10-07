---
layout: stdlib-reference
---

# WavePrefixSum

## Description





## Signature 

<pre>
<a href="/stdlib-reference/global-decls/WavePrefixSum#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/WavePrefixSum">WavePrefixSum</a>&lt;<a href="/stdlib-reference/global-decls/WavePrefixSum#typeparam-T" class="code_type">T</a>&gt;(<a href="/stdlib-reference/global-decls/WavePrefixSum#typeparam-T" class="code_type">T</a> expr)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/WavePrefixSum#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/WavePrefixSum">WavePrefixSum</a>&lt;<a href="/stdlib-reference/global-decls/WavePrefixSum#typeparam-T" class="code_type">T</a>, N:int&gt;(<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; expr)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/WavePrefixSum#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

<a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; <a href="/stdlib-reference/global-decls/WavePrefixSum">WavePrefixSum</a>&lt;<a href="/stdlib-reference/global-decls/WavePrefixSum#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(<a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; expr)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/WavePrefixSum#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

#### T: [\_\_BuiltinArithmeticType](/stdlib-reference/interfaces/BuiltinArithmeticType/index) {#typeparam-T}

## Generic Parameters

#### T: [\_\_BuiltinArithmeticType](/stdlib-reference/interfaces/BuiltinArithmeticType/index) {#typeparam-T}
#### N  : int {#decl-N}
#### M  : int {#decl-M}

## Parameters

#### expr  : [T](/stdlib-reference/global-decls/WavePrefixSum#typeparam-T) {#decl-expr}
#### expr  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-expr}
#### expr  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, M\> {#decl-expr}

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvGroupNonUniformArithmetic`.

