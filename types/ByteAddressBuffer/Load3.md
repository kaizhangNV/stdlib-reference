---
layout: stdlib-reference
---

# ByteAddressBuffer\.Load3

## Description





## Signature 

<pre>
/// Requires Capability Set 1:
<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;uint, 3&gt; <a href="/stdlib-reference/types/ByteAddressBuffer/index" class="code_type">ByteAddressBuffer</a>.<a href="/stdlib-reference/types/ByteAddressBuffer/Load3">Load3</a>(int <a href="/stdlib-reference/types/ByteAddressBuffer/Load3#decl-location" class="code_param">location</a>);

/// Requires Capability Set 1:
<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;uint, 3&gt; <a href="/stdlib-reference/types/ByteAddressBuffer/index" class="code_type">ByteAddressBuffer</a>.<a href="/stdlib-reference/types/ByteAddressBuffer/Load3">Load3</a>(
<a href="/stdlib-reference/types/ByteAddressBuffer/Load3#decl-location" class="code_param">location</a>    int ,
alignment    int );

/// Requires Capability Set 2:
<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;uint, 3&gt; <a href="/stdlib-reference/types/ByteAddressBuffer/index" class="code_type">ByteAddressBuffer</a>.<a href="/stdlib-reference/types/ByteAddressBuffer/Load3">Load3</a>(
<a href="/stdlib-reference/types/ByteAddressBuffer/Load3#decl-location" class="code_param">location</a>    int ,
status    out uint );

</pre>

## Parameters

#### location  : int {#decl-location}
#### alignment  : int {#decl-alignment}
#### status  : uint {#decl-status}

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.


### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.


