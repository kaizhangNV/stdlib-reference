---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.queryFootprintFineGradClamp

## Description

Query the footprint that would be accessed by a texture sampling operation.

This operation queries the footprint that would be accessed
by a comparable call to:

t.SampleGradClamp(sampler, coords, dx, dy, lodClamp);




## Signature 

<pre>
<a href="/stdlib-reference/types/TextureFootprint/index" class="code_type">TextureFootprint</a>&lt;Shape.dimensions&gt; <a href="/stdlib-reference/types/Texture/index" class="code_type">_Texture</a>&lt;T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format&gt;.<a href="/stdlib-reference/types/Texture/queryFootprintFineGradClamp">queryFootprintFineGradClamp</a>(
    <span class="code_keyword">uint</span> <span class='code_param'>granularity</span>,
    <a href="/stdlib-reference/types/SamplerState/index" class="code_type">SamplerState</a> <span class='code_param'>sampler</span>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, Shape.dimensions&gt; <span class='code_param'>coords</span>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, Shape.dimensions&gt; <span class='code_param'>dx</span>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, Shape.dimensions&gt; <span class='code_param'>dy</span>,
    <span class="code_keyword">float</span> <span class='code_param'>lodClamp</span>)
    <span class='code_keyword'>where</span> Shape : <a href="/stdlib-reference/interfaces/ITextureShape/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> isArray == 0
    <span class='code_keyword'>where</span> isMS == 0
    <span class='code_keyword'>where</span> access == 0
    <span class='code_keyword'>where</span> isCombined == 0;

</pre>

## Parameters

#### granularity : uint
#### sampler : SamplerState
#### coords : vector\<float,Shape\.dimensions\>
#### dx : vector\<float,Shape\.dimensions\>
#### dy : vector\<float,Shape\.dimensions\>
#### lodClamp : float
