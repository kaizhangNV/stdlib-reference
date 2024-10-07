---
layout: stdlib-reference
---

# RWByteAddressBuffer\.InterlockedMinU64

## Description





## Signature 

<pre>
uint64_t <a href="/stdlib-reference/types/RWByteAddressBuffer/index" class="code_type">RWByteAddressBuffer</a>.<a href="/stdlib-reference/types/RWByteAddressBuffer/InterlockedMinU64">InterlockedMinU64</a>(
<a href="/stdlib-reference/types/RWByteAddressBuffer/InterlockedMinU64#decl-byteAddress" class="code_param">byteAddress</a>    uint ,
<a href="/stdlib-reference/types/RWByteAddressBuffer/InterlockedMinU64#decl-value" class="code_param">value</a>    uint64_t );

</pre>

## Parameters

#### byteAddress  : uint {#decl-byteAddress}
#### value  : uint64\_t {#decl-value}

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

Requires capability: `hlsl_nvapi`.
#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvInt64Atomics`.

