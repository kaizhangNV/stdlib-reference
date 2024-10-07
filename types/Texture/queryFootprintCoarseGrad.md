---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.queryFootprintCoarseGrad

## Description

Query the footprint that would be accessed by a texture sampling operation.

This operation queries the footprint that would be accessed
by a comparable call to:

t.SampleGrad(sampler, coords, dx, dy);




## Signature 

<pre>
<a href="/stdlib-reference/types/TextureFootprint/index" class="code_type">TextureFootprint</a>&lt;Shape.dimensions&gt; <a href="/stdlib-reference/types/Texture/index" class="code_type">_Texture</a>&lt;<a href="/stdlib-reference/types/Texture/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/Texture/index#typeparam-Shape" class="code_type">Shape</a>, <a href="/stdlib-reference/types/Texture/index#decl-isArray" class="code_var">isArray</a>, <a href="/stdlib-reference/types/Texture/index#decl-isMS" class="code_var">isMS</a>, <a href="/stdlib-reference/types/Texture/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="/stdlib-reference/types/Texture/index#decl-access" class="code_var">access</a>, <a href="/stdlib-reference/types/Texture/index#decl-isShadow" class="code_var">isShadow</a>, <a href="/stdlib-reference/types/Texture/index#decl-isCombined" class="code_var">isCombined</a>, <a href="/stdlib-reference/types/Texture/index#decl-format" class="code_var">format</a>&gt;.<a href="/stdlib-reference/types/Texture/queryFootprintCoarseGrad">queryFootprintCoarseGrad</a>(
<a href="/stdlib-reference/types/Texture/queryFootprintCoarseGrad#decl-granularity" class="code_param">granularity</a>    uint ,
<a href="/stdlib-reference/types/Texture/queryFootprintCoarseGrad#decl-sampler" class="code_param">sampler</a>    <a href="/stdlib-reference/types/SamplerState/index" class="code_type">SamplerState</a> ,
<a href="/stdlib-reference/types/Texture/queryFootprintCoarseGrad#decl-coords" class="code_param">coords</a>    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;float, Shape.dimensions&gt; ,
<a href="/stdlib-reference/types/Texture/queryFootprintCoarseGrad#decl-dx" class="code_param">dx</a>    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;float, Shape.dimensions&gt; ,
<a href="/stdlib-reference/types/Texture/queryFootprintCoarseGrad#decl-dy" class="code_param">dy</a>    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;float, Shape.dimensions&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/Texture/index#typeparam-Shape" class="code_type">Shape</a> : <a href="/stdlib-reference/interfaces/ITextureShape/index">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/Texture/index#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/Texture/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/Texture/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/Texture/index#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

#### granularity  : uint {#decl-granularity}
#### sampler  : [SamplerState](/stdlib-reference/types/SamplerState/index) {#decl-sampler}
#### coords  : [vector](/stdlib-reference/types/vector/index)\<float, Shape\.dimensions\> {#decl-coords}
#### dx  : [vector](/stdlib-reference/types/vector/index)\<float, Shape\.dimensions\> {#decl-dx}
#### dy  : [vector](/stdlib-reference/types/vector/index)\<float, Shape\.dimensions\> {#decl-dy}
