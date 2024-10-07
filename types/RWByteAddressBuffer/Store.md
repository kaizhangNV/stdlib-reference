---
layout: stdlib-reference
---

# RWByteAddressBuffer\.Store

## Description





## Signature 

<pre>
void <a href="/stdlib-reference/types/RWByteAddressBuffer/index" class="code_type">RWByteAddressBuffer</a>.<a href="/stdlib-reference/types/RWByteAddressBuffer/Store">Store</a>(
<a href="/stdlib-reference/types/RWByteAddressBuffer/Store#decl-address" class="code_param">address</a>    uint ,
<a href="/stdlib-reference/types/RWByteAddressBuffer/Store#decl-value" class="code_param">value</a>    uint );

void <a href="/stdlib-reference/types/RWByteAddressBuffer/index" class="code_type">RWByteAddressBuffer</a>.<a href="/stdlib-reference/types/RWByteAddressBuffer/Store">Store</a>&lt;T&gt;(
offset    int ,
<a href="/stdlib-reference/types/RWByteAddressBuffer/Store#decl-value" class="code_param">value</a>    T );

void <a href="/stdlib-reference/types/RWByteAddressBuffer/index" class="code_type">RWByteAddressBuffer</a>.<a href="/stdlib-reference/types/RWByteAddressBuffer/Store">Store</a>&lt;T&gt;(
offset    int ,
<a href="/stdlib-reference/types/RWByteAddressBuffer/Store#decl-value" class="code_param">value</a>    T ,
alignment    uint );

</pre>

## Generic Parameters

#### T {#typeparam-T}

## Parameters

#### address  : uint {#decl-address}
#### value  : uint {#decl-value}
#### offset  : int {#decl-offset}
#### value  : T {#decl-value}
#### alignment  : uint {#decl-alignment}

## Availability and Requirements

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


