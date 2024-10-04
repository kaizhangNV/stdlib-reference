---
layout: stdlib-reference
---

# EvaluateAttributeAtSample

## Description





## Signature 

<pre>
T <a href="/stdlib-reference/global-decls/EvaluateAttributeAtSample">EvaluateAttributeAtSample</a>&lt;T&gt;(
    T <span class='code_param'>x</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>sampleindex</span>)
    <span class='code_keyword'>where</span> T : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index" class="code_type">__BuiltinArithmeticType</a>;

<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;T, N&gt; <a href="/stdlib-reference/global-decls/EvaluateAttributeAtSample">EvaluateAttributeAtSample</a>&lt;T, N:<span class="code_keyword">int</span>&gt;(
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;T, N&gt; <span class='code_param'>x</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>sampleindex</span>)
    <span class='code_keyword'>where</span> T : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index" class="code_type">__BuiltinArithmeticType</a>;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T">T</a>, N, M&gt; <a href="/stdlib-reference/global-decls/EvaluateAttributeAtSample">EvaluateAttributeAtSample</a>&lt;T, N:<span class="code_keyword">int</span>, M:<span class="code_keyword">int</span>&gt;(
    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T">T</a>, N, M&gt; <span class='code_param'>x</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>sampleindex</span>)
    <span class='code_keyword'>where</span> T : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Parameters

#### T
#### N : int
#### M : int
#### x : T
#### sampleindex : uint
#### x : vector\<T,N\>
#### x : matrix\<T,N,M\>

## Availability and Requirements

Defined for the following targets:

#### glsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### spirv
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

Requires capabilities: `SPV_NV_compute_shader_derivatives`, `spvMeshShadingEXT`.

