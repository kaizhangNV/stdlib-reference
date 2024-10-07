---
layout: stdlib-reference
---

# mul

## Description





## Signature 

<pre>
<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>&gt;(
x    <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> ,
y    <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int&gt;(
x    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; ,
y    <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int&gt;(
x    <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> ,
y    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

<a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
x    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; ,
y    <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

<a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
x    <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> ,
y    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinArithmeticType/index">__BuiltinArithmeticType</a>;

<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int&gt;(
x    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; ,
y    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinFloatingPointType/index">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int&gt;(
x    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; ,
y    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : __BuiltinIntegerType;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, M&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
left    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; ,
right    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinFloatingPointType/index">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, M&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
left    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; ,
right    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : __BuiltinIntegerType;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, M&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
left    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; ,
right    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinLogicalType/index">__BuiltinLogicalType</a>;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
left    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; ,
right    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, M&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinFloatingPointType/index">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
left    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; ,
right    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, M&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : __BuiltinIntegerType;

<a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
left    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt; ,
right    <a href="/stdlib-reference/types/vector/index">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, M&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinLogicalType/index">__BuiltinLogicalType</a>;

<a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, R:int, N:int, C:int&gt;(
left    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, N&gt; ,
right    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinFloatingPointType/index">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, R:int, N:int, C:int&gt;(
left    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, N&gt; ,
right    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : __BuiltinIntegerType;

<a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, R:int, N:int, C:int&gt;(
left    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, N&gt; ,
right    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinLogicalType/index">__BuiltinLogicalType</a>;

<a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, M&gt;&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
left    <a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt;&gt; ,
right    <a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt;&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinFloatingPointType/index">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/vector/index#decl-N" class="code_var">N</a>&gt;&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, N:int, M:int&gt;(
left    <a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, M&gt;&gt; ,
right    <a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/types/vector/index#typeparam-T" class="code_type">T</a>, M&gt;&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinFloatingPointType/index">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;&gt; <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, R:int, N:int, C:int&gt;(
left    <a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, N&gt;&gt; ,
right    <a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinFloatingPointType/index">__BuiltinFloatingPointType</a>;

void <a href="/stdlib-reference/global-decls/mul">mul</a>&lt;<a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a>, R:int, N:int, C:int&gt;(
left    inout <a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, N&gt;&gt; ,
right    inout <a href="/stdlib-reference/types/DifferentialPair/index">DifferentialPair</a>&lt;<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, N, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt;&gt; ,
dOut    <a href="/stdlib-reference/types/matrix/index">matrix</a>&lt;<a href="/stdlib-reference/types/matrix/T" class="code_type">T</a>, <a href="/stdlib-reference/types/matrix/index#decl-R" class="code_var">R</a>, <a href="/stdlib-reference/types/matrix/index#decl-C" class="code_var">C</a>&gt; )
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/mul#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/BuiltinFloatingPointType/index">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

#### T: [\_\_BuiltinArithmeticType](/stdlib-reference/interfaces/BuiltinArithmeticType/index) {#typeparam-T}

## Generic Parameters

#### T: [\_\_BuiltinArithmeticType](/stdlib-reference/interfaces/BuiltinArithmeticType/index) {#typeparam-T}
#### N  : int {#decl-N}
#### M  : int {#decl-M}
#### T: [\_\_BuiltinFloatingPointType](/stdlib-reference/interfaces/BuiltinFloatingPointType/index) {#typeparam-T}
#### T: \_\_BuiltinIntegerType {#typeparam-T}
#### T: [\_\_BuiltinLogicalType](/stdlib-reference/interfaces/BuiltinLogicalType/index) {#typeparam-T}
#### R  : int {#decl-R}
#### C  : int {#decl-C}

## Parameters

#### x  : [T](/stdlib-reference/global-decls/mul#typeparam-T) {#decl-x}
#### y  : [T](/stdlib-reference/global-decls/mul#typeparam-T) {#decl-y}
#### x  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-x}
#### y  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-y}
#### x  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, M\> {#decl-x}
#### y  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, M\> {#decl-y}
#### left  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-left}
#### right  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, M\> {#decl-right}
#### left  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, M\> {#decl-left}
#### right  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), M\> {#decl-right}
#### left  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), [R](/stdlib-reference/types/matrix/index#decl-R), N\> {#decl-left}
#### right  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-right}
#### left  : [DifferentialPair](/stdlib-reference/types/DifferentialPair/index)\<[vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N) \>\> {#decl-left}
#### right  : [DifferentialPair](/stdlib-reference/types/DifferentialPair/index)\<[matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, M \>\> {#decl-right}
#### left  : [DifferentialPair](/stdlib-reference/types/DifferentialPair/index)\<[matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, M \>\> {#decl-left}
#### right  : [DifferentialPair](/stdlib-reference/types/DifferentialPair/index)\<[vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), M \>\> {#decl-right}
#### left  : [DifferentialPair](/stdlib-reference/types/DifferentialPair/index)\<[matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), [R](/stdlib-reference/types/matrix/index#decl-R), N \>\> {#decl-left}
#### right  : [DifferentialPair](/stdlib-reference/types/DifferentialPair/index)\<[matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), N, [C](/stdlib-reference/types/matrix/index#decl-C) \>\> {#decl-right}
#### dOut  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/T), [R](/stdlib-reference/types/matrix/index#decl-R), [C](/stdlib-reference/types/matrix/index#decl-C)\> {#decl-dOut}

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


