---
layout: stdlib-reference
---

# WaveReadLaneAt

## Description





## Signature 

<pre>
<a href="/stdlib-reference/global-decls/WaveReadLaneAt#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/WaveReadLaneAt">WaveReadLaneAt</a>&lt;<a href="/stdlib-reference/global-decls/WaveReadLaneAt#typeparam-T" class="code_type">T</a>&gt;(
value    <a href="/stdlib-reference/global-decls/WaveReadLaneAt#typeparam-T" class="code_type">T</a> ,
lane    int )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/WaveReadLaneAt#typeparam-T" class="code_type">T</a> : __BuiltinType;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/WaveReadLaneAt">WaveReadLaneAt</a>&lt;<a href="/stdlib-reference/global-decls/WaveReadLaneAt#typeparam-T" class="code_type">T</a>, N:int&gt;(
value    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; ,
lane    int )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/WaveReadLaneAt#typeparam-T" class="code_type">T</a> : __BuiltinType;

<a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; <a href="/stdlib-reference/global-decls/WaveReadLaneAt">WaveReadLaneAt</a>&lt;<a href="/stdlib-reference/global-decls/WaveReadLaneAt#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
value    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; ,
lane    int )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/WaveReadLaneAt#typeparam-T" class="code_type">T</a> : __BuiltinType;

</pre>

## Generic Parameters

#### T: \_\_BuiltinType {#typeparam-T}

## Generic Parameters

#### T: \_\_BuiltinType {#typeparam-T}
#### N  : int {#decl-N}
#### M  : int {#decl-M}

## Parameters

#### value  : [T](/stdlib-reference/global-decls/WaveReadLaneAt#typeparam-T) {#decl-value}
#### lane  : int {#decl-lane}
#### value  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-value}
#### value  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, M\> {#decl-value}

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

Requires capability: `spvGroupNonUniformShuffle`.

