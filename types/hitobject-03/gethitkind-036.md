---
layout: stdlib-reference
---

# HitObject\.GetHitKind

## Description

Returns the hit kind. Valid if the hit object represents a hit.




## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/index" class="code_type">HitObject</a>.<a href="/stdlib-reference/types/hitobject-03/gethitkind-036">GetHitKind</a>();

</pre>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capability: `hlsl_nvapi`.
#### glsl
Available in stages: `raygen`, `closesthit`, `miss`.

#### spirv
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capabilities: `spvRayTracingKHR`, `spvShaderInvocationReorderNV`.


