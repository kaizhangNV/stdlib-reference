---
layout: stdlib-reference
---

# HitObject\.MakeMotionHit

## Description

See MakeHit but handles Motion
Currently only supported on VK




## Signature 

<pre>
/// Requires Capability Set 1:
<span class='code_keyword'>static</span> <a href="/stdlib-reference/types/HitObject/index" class="code_type">HitObject</a> <a href="/stdlib-reference/types/HitObject/index" class="code_type">HitObject</a>.<a href="/stdlib-reference/types/HitObject/MakeMotionHit">MakeMotionHit</a>&lt;attr_t&gt;(
    <a href="/stdlib-reference/types/RaytracingAccelerationStructure/index" class="code_type">RaytracingAccelerationStructure</a> <span class='code_param'>AccelerationStructure</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>InstanceIndex</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>GeometryIndex</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>PrimitiveIndex</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>HitKind</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>RayContributionToHitGroupIndex</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>MultiplierForGeometryContributionToHitGroupIndex</span>,
    <a href="/stdlib-reference/types/RayDesc/index" class="code_type">RayDesc</a> <span class='code_param'>Ray</span>,
    <span class="code_keyword">float</span> <span class='code_param'>CurrentTime</span>,
    attr_t <span class='code_param'>attributes</span>);

/// Requires Capability Set 2:
<span class='code_keyword'>static</span> <a href="/stdlib-reference/types/HitObject/index" class="code_type">HitObject</a> <a href="/stdlib-reference/types/HitObject/index" class="code_type">HitObject</a>.<a href="/stdlib-reference/types/HitObject/MakeMotionHit">MakeMotionHit</a>&lt;attr_t&gt;(
    <span class="code_keyword">uint</span> <span class='code_param'>HitGroupRecordIndex</span>,
    <a href="/stdlib-reference/types/RaytracingAccelerationStructure/index" class="code_type">RaytracingAccelerationStructure</a> <span class='code_param'>AccelerationStructure</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>InstanceIndex</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>GeometryIndex</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>PrimitiveIndex</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>HitKind</span>,
    <a href="/stdlib-reference/types/RayDesc/index" class="code_type">RayDesc</a> <span class='code_param'>Ray</span>,
    <span class="code_keyword">float</span> <span class='code_param'>CurrentTime</span>,
    attr_t <span class='code_param'>attributes</span>);

</pre>

## Parameters

#### attr\_t
#### AccelerationStructure : RaytracingAccelerationStructure
#### InstanceIndex : uint
#### GeometryIndex : uint
#### PrimitiveIndex : uint
#### HitKind : uint
#### RayContributionToHitGroupIndex : uint
#### MultiplierForGeometryContributionToHitGroupIndex : uint
#### Ray : RayDesc
#### CurrentTime : float
#### attributes : attr\_t
#### HitGroupRecordIndex : uint

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capability: `hlsl_nvapi`.
#### glsl
Available in stages: `raygen`, `closesthit`, `miss`.

#### spirv
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capabilities: `spvRayTracingMotionBlurNV`, `spvRayTracingKHR`, `spvShaderInvocationReorderNV`.

### Capability Set 2

Defined for the following targets:

#### glsl
Available in stages: `raygen`, `closesthit`, `miss`.

#### spirv
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capabilities: `spvRayTracingMotionBlurNV`, `spvRayTracingKHR`, `spvShaderInvocationReorderNV`.

