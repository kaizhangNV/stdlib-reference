---
layout: stdlib-reference
---

# Atomic\<T\>\.or

## Description





## Signature 

<pre>
<a href="/stdlib-reference/types/Atomic/index#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/types/Atomic/index" class="code_type">Atomic</a>&lt;<a href="/stdlib-reference/types/Atomic/index#typeparam-T" class="code_type">T</a>&gt;.<a href="/stdlib-reference/types/Atomic/or">or</a>(
<a href="/stdlib-reference/types/Atomic/or#decl-value" class="code_param">value</a>    <a href="/stdlib-reference/types/Atomic/index#typeparam-T" class="code_type">T</a> ,
<a href="/stdlib-reference/types/Atomic/or#decl-order" class="code_param">order</a>    <a href="/stdlib-reference/types/MemoryOrder/index" class="code_type">MemoryOrder</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/Atomic/index#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/IBitAtomicable/index">IBitAtomicable</a>;

</pre>

## Parameters

#### value  : [T](/stdlib-reference/types/Atomic/index#typeparam-T) {#decl-value}
#### order  : [MemoryOrder](/stdlib-reference/types/MemoryOrder/index) = [MemoryOrder](/stdlib-reference/types/MemoryOrder/index)\.[Relaxed](/stdlib-reference/types/MemoryOrder/index#decl-Relaxed) {#decl-order}
