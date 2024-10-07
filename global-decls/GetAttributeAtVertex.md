---
layout: stdlib-reference
---

# GetAttributeAtVertex

## Description

Get the value of a vertex attribute at a specific vertex.

The <span class='code'><a href="/stdlib-reference/global-decls/GetAttributeAtVertex">GetAttributeAtVertex</a>()</span> function can be used in a fragment shader
to get the value of the given <span class='code'>attribute</span> at the vertex of the primitive
that corresponds to the given <span class='code'>vertexIndex</span>.

Note that the <span class='code'>attribute</span> must have been a declared varying input to
the fragment shader with the <span class='code'>nointerpolation</span> modifier.

This function can be applied to scalars, vectors, and matrices of
built-in scalar types.




## Signature 

<pre>
<a href="/stdlib-reference/global-decls/GetAttributeAtVertex#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/GetAttributeAtVertex">GetAttributeAtVertex</a>&lt;<a href="/stdlib-reference/global-decls/GetAttributeAtVertex#typeparam-T" class="code_type">T</a>&gt;(
attribute    <a href="/stdlib-reference/global-decls/GetAttributeAtVertex#typeparam-T" class="code_type">T</a> ,
vertexIndex    uint )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/GetAttributeAtVertex#typeparam-T" class="code_type">T</a> : __BuiltinType;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/GetAttributeAtVertex">GetAttributeAtVertex</a>&lt;<a href="/stdlib-reference/global-decls/GetAttributeAtVertex#typeparam-T" class="code_type">T</a>, N:int&gt;(
attribute    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; ,
vertexIndex    uint )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/GetAttributeAtVertex#typeparam-T" class="code_type">T</a> : __BuiltinType;

<a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; <a href="/stdlib-reference/global-decls/GetAttributeAtVertex">GetAttributeAtVertex</a>&lt;<a href="/stdlib-reference/global-decls/GetAttributeAtVertex#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
attribute    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; ,
vertexIndex    uint )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/GetAttributeAtVertex#typeparam-T" class="code_type">T</a> : __BuiltinType;

</pre>

## Generic Parameters

#### T: \_\_BuiltinType {#typeparam-T}

## Generic Parameters

#### T: \_\_BuiltinType {#typeparam-T}
#### N  : int {#decl-N}
#### M  : int {#decl-M}

## Parameters

#### attribute  : [T](/stdlib-reference/global-decls/GetAttributeAtVertex#typeparam-T) {#decl-attribute}
#### vertexIndex  : uint {#decl-vertexIndex}
#### attribute  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-attribute}
#### attribute  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, M\> {#decl-attribute}

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in `fragment` stage only.

#### glsl
Available in `fragment` stage only.

#### spirv
Available in `fragment` stage only.

Requires capability: `spvFragmentBarycentricKHR`.

