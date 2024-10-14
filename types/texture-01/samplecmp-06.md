---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.SampleCmp

## Description





## Signature 

<pre>
<span class="code_keyword">float</span> <a href="/stdlib-reference/types/texture-01/index" class="code_type">_Texture</a>&lt;<a href="/stdlib-reference/types/texture-01/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="/stdlib-reference/types/texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="/stdlib-reference/types/texture-01/index#decl-access" class="code_var">access</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="/stdlib-reference/types/texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="/stdlib-reference/types/texture-01/samplecmp-06">SampleCmp</a>(
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="/stdlib-reference/types/texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-compareValue" class="code_param">compareValue</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="/stdlib-reference/interfaces/itextureshape-0123a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

<span class="code_keyword">float</span> <a href="/stdlib-reference/types/texture-01/index" class="code_type">_Texture</a>&lt;<a href="/stdlib-reference/types/texture-01/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="/stdlib-reference/types/texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="/stdlib-reference/types/texture-01/index#decl-access" class="code_var">access</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="/stdlib-reference/types/texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="/stdlib-reference/types/texture-01/samplecmp-06">SampleCmp</a>(
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="/stdlib-reference/types/texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="/stdlib-reference/interfaces/itextureshape-0123a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

<span class="code_keyword">float</span> <a href="/stdlib-reference/types/texture-01/index" class="code_type">_Texture</a>&lt;<a href="/stdlib-reference/types/texture-01/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="/stdlib-reference/types/texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="/stdlib-reference/types/texture-01/index#decl-access" class="code_var">access</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="/stdlib-reference/types/texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="/stdlib-reference/types/texture-01/samplecmp-06">SampleCmp</a>(
    <a href="/stdlib-reference/types/samplercomparisonstate-07h/index" class="code_type">SamplerComparisonState</a> <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-s" class="code_param">s</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="/stdlib-reference/types/texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-compareValue" class="code_param">compareValue</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="/stdlib-reference/interfaces/itextureshape-0123a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

<span class="code_keyword">float</span> <a href="/stdlib-reference/types/texture-01/index" class="code_type">_Texture</a>&lt;<a href="/stdlib-reference/types/texture-01/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="/stdlib-reference/types/texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="/stdlib-reference/types/texture-01/index#decl-access" class="code_var">access</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="/stdlib-reference/types/texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="/stdlib-reference/types/texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="/stdlib-reference/types/texture-01/samplecmp-06">SampleCmp</a>(
    <a href="/stdlib-reference/types/samplercomparisonstate-07h/index" class="code_type">SamplerComparisonState</a> <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-s" class="code_param">s</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="/stdlib-reference/types/texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="/stdlib-reference/types/texture-01/samplecmp-06#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="/stdlib-reference/interfaces/itextureshape-0123a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

#### location  : [vector](/stdlib-reference/types/vector/index)\<float, isArray + Shape\.dimensions\> {#decl-location}
#### compareValue  : float {#decl-compareValue}
#### offset  : [vector](/stdlib-reference/types/vector/index)\<int, Shape\.planeDimensions\> {#decl-offset}
#### s  : [SamplerComparisonState](/stdlib-reference/types/samplercomparisonstate-07h/index) {#decl-s}

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### metal
Available in all stages.

#### wgsl
Available in all stages.

#### spirv
Available in all stages.

Requires capabilities: `spvImageQuery`, `spvSparseResidency`.

