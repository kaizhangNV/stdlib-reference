---
layout: stdlib-reference
---

# RWByteAddressBuffer\.InterlockedAdd64

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="/stdlib-reference/types/RWByteAddressBuffer/index" class="code_type">RWByteAddressBuffer</a>.<a href="/stdlib-reference/types/RWByteAddressBuffer/InterlockedAdd64">InterlockedAdd64</a>(
    <span class="code_keyword">uint</span> <span class='code_param'>byteAddress</span>,
    int64_t <span class='code_param'>valueToAdd</span>);

<span class="code_keyword">void</span> <a href="/stdlib-reference/types/RWByteAddressBuffer/index" class="code_type">RWByteAddressBuffer</a>.<a href="/stdlib-reference/types/RWByteAddressBuffer/InterlockedAdd64">InterlockedAdd64</a>(
    <span class="code_keyword">uint</span> <span class='code_param'>byteAddress</span>,
    int64_t <span class='code_param'>valueToAdd</span>,
    <span class="code_keyword">out</span> int64_t <span class='code_param'>outOriginalValue</span>);

<span class="code_keyword">void</span> <a href="/stdlib-reference/types/RWByteAddressBuffer/index" class="code_type">RWByteAddressBuffer</a>.<a href="/stdlib-reference/types/RWByteAddressBuffer/InterlockedAdd64">InterlockedAdd64</a>(
    <span class="code_keyword">uint</span> <span class='code_param'>byteAddress</span>,
    uint64_t <span class='code_param'>valueToAdd</span>);

<span class="code_keyword">void</span> <a href="/stdlib-reference/types/RWByteAddressBuffer/index" class="code_type">RWByteAddressBuffer</a>.<a href="/stdlib-reference/types/RWByteAddressBuffer/InterlockedAdd64">InterlockedAdd64</a>(
    <span class="code_keyword">uint</span> <span class='code_param'>byteAddress</span>,
    uint64_t <span class='code_param'>valueToAdd</span>,
    <span class="code_keyword">out</span> uint64_t <span class='code_param'>outOriginalValue</span>);

</pre>

## Parameters

#### byteAddress : uint
#### valueToAdd : int64\_t
#### outOriginalValue : int64\_t
#### valueToAdd : uint64\_t
#### outOriginalValue : uint64\_t

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvInt64Atomics`.

