---
layout: stdlib-reference
---

# WaveMultiPrefixBitOr

## Description





## Signature 

<pre>
/// Requires Capability Set 1:
<a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr">WaveMultiPrefixBitOr</a>&lt;<a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr#typeparam-T" class="code_type">T</a>&gt;(
expr    <a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr#typeparam-T" class="code_type">T</a> ,
mask    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;uint, 4&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

/// Requires Capability Set 1:
<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr">WaveMultiPrefixBitOr</a>&lt;<a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr#typeparam-T" class="code_type">T</a>, N:int&gt;(
expr    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; ,
mask    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;uint, 4&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

/// Requires Capability Set 2:
<a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; <a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr">WaveMultiPrefixBitOr</a>&lt;<a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
expr    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; ,
mask    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;uint, 4&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/WaveMultiPrefixBitOr#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

#### T: [\_\_BuiltinArithmeticType](/stdlib-reference/interfaces/BuiltinArithmeticType/index) {#typeparam-T}

## Generic Parameters

#### T: [\_\_BuiltinArithmeticType](/stdlib-reference/interfaces/BuiltinArithmeticType/index) {#typeparam-T}
#### N  : int {#decl-N}
#### M  : int {#decl-M}

## Parameters

#### expr  : [T](/stdlib-reference/global-decls/WaveMultiPrefixBitOr#typeparam-T) {#decl-expr}
#### mask  : [vector](/stdlib-reference/types/vector/index)\<uint, 4\> {#decl-mask}
#### expr  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-expr}
#### expr  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, M\> {#decl-expr}

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.


### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.

#### cuda
Available in all stages.


