---
layout: stdlib-reference
---

# RasterizerOrderedByteAddressBuffer\.InterlockedCompareExchange

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="/stdlib-reference/types/RasterizerOrderedByteAddressBuffer/index" class="code_type">RasterizerOrderedByteAddressBuffer</a>.<a href="/stdlib-reference/types/RasterizerOrderedByteAddressBuffer/InterlockedCompareExchange">InterlockedCompareExchange</a>(
    <span class="code_keyword">uint</span> <span class='code_param'>dest</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>compare_value</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>value</span>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <span class='code_param'>original_value</span>);

</pre>

## Parameters

#### dest : uint
#### compare\_value : uint
#### value : uint
#### original\_value : uint

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.


