---
layout: stdlib-reference
---

# RasterizerOrderedStructuredBuffer\<T, L\>\.Load

## Description





## Signature 

<pre>
<a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/index#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/index" class="code_type">RasterizerOrderedStructuredBuffer</a>&lt;<a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/index#typeparam-L" class="code_type">L</a>&gt;.<a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0">Load</a>&lt;<a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0#typeparam-TIndex" class="code_type">TIndex</a>&gt;(
    <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0#typeparam-TIndex" class="code_type">TIndex</a> <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0#typeparam-TIndex" class="code_type">TIndex</a> : <a href="/stdlib-reference/interfaces/0_builtinintegertype-029g/index" class="code_type">__BuiltinIntegerType</a>
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/index#typeparam-L" class="code_type">L</a> : <a href="/stdlib-reference/interfaces/ibufferdatalayout-017b/index" class="code_type">IBufferDataLayout</a>;

<a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/index#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/index" class="code_type">RasterizerOrderedStructuredBuffer</a>&lt;<a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/index#typeparam-L" class="code_type">L</a>&gt;.<a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0">Load</a>&lt;<a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0#typeparam-TIndex" class="code_type">TIndex</a>&gt;(
    <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0#typeparam-TIndex" class="code_type">TIndex</a> <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0#decl-location" class="code_param">location</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0#typeparam-TIndex" class="code_type">TIndex</a> : <a href="/stdlib-reference/interfaces/0_builtinintegertype-029g/index" class="code_type">__BuiltinIntegerType</a>
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/index#typeparam-L" class="code_type">L</a> : <a href="/stdlib-reference/interfaces/ibufferdatalayout-017b/index" class="code_type">IBufferDataLayout</a>;

</pre>

## Generic Parameters

#### TIndex: [\_\_BuiltinIntegerType](/stdlib-reference/interfaces/0_builtinintegertype-029g/index) {#typeparam-TIndex}

## Parameters

#### location  : [TIndex](/stdlib-reference/types/rasterizerorderedstructuredbuffer-0ahr/load-0#typeparam-TIndex) {#decl-location}
#### status  : uint {#decl-status}

