---
layout: stdlib-reference
---

# TraceRay

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/TraceRay">TraceRay</a>&lt;payload_t&gt;(
    <a href="/stdlib-reference/types/RaytracingAccelerationStructure/index" class="code_type">RaytracingAccelerationStructure</a> <span class='code_param'>AccelerationStructure</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>RayFlags</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>InstanceInclusionMask</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>RayContributionToHitGroupIndex</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>MultiplierForGeometryContributionToHitGroupIndex</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>MissShaderIndex</span>,
    <a href="/stdlib-reference/types/RayDesc/index" class="code_type">RayDesc</a> <span class='code_param'>Ray</span>,
    <span class="code_keyword">inout</span> payload_t <span class='code_param'>Payload</span>);

</pre>

## Parameters

#### payload\_t
#### AccelerationStructure : RaytracingAccelerationStructure
#### RayFlags : uint
#### InstanceInclusionMask : uint
#### RayContributionToHitGroupIndex : uint
#### MultiplierForGeometryContributionToHitGroupIndex : uint
#### MissShaderIndex : uint
#### Ray : RayDesc
#### Payload : payload\_t

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `raygen`, `closesthit`, `miss`.

#### glsl
Available in stages: `raygen`, `closesthit`, `miss`.

#### cuda
Available in stages: `raygen`, `closesthit`, `miss`.

#### spirv
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capability: `spvRayTracingKHR`.

