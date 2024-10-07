---
layout: stdlib-reference
---

# SetMeshOutputCounts

## Description





## Signature 

<pre>
void <a href="/stdlib-reference/global-decls/SetMeshOutputCounts">SetMeshOutputCounts</a>(
<a href="/stdlib-reference/global-decls/SetMeshOutputCounts#decl-vertexCount" class="code_param">vertexCount</a>    uint ,
<a href="/stdlib-reference/global-decls/SetMeshOutputCounts#decl-primitiveCount" class="code_param">primitiveCount</a>    uint );

</pre>

## Parameters

#### vertexCount  : uint {#decl-vertexCount}
#### primitiveCount  : uint {#decl-primitiveCount}

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

