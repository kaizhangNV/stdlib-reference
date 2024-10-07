---
layout: stdlib-reference
---

# DispatchMesh

## Description





## Signature 

<pre>
void <a href="/stdlib-reference/global-decls/DispatchMesh">DispatchMesh</a>&lt;<a href="/stdlib-reference/global-decls/DispatchMesh#typeparam-P" class="code_type">P</a>&gt;(
threadGroupCountX    uint ,
threadGroupCountY    uint ,
threadGroupCountZ    uint ,
meshPayload    <a href="/stdlib-reference/global-decls/DispatchMesh#typeparam-P" class="code_type">P</a> );

</pre>

## Generic Parameters

#### P {#typeparam-P}

## Generic Parameters

#### P {#typeparam-P}

## Parameters

#### threadGroupCountX  : uint {#decl-threadGroupCountX}
#### threadGroupCountY  : uint {#decl-threadGroupCountY}
#### threadGroupCountZ  : uint {#decl-threadGroupCountZ}
#### meshPayload  : [P](/stdlib-reference/global-decls/DispatchMesh#typeparam-P) {#decl-meshPayload}

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `amplification`, `mesh`.

#### glsl
Available in stages: `amplification`, `mesh`.

#### metal
Available in stages: `amplification`, `mesh`.

#### spirv
Available in stages: `amplification`, `mesh`.

Requires capability: `spvMeshShadingEXT`.

