---
layout: stdlib-reference
---

# InterlockedAdd

## Description





## Signature 

<pre>
/// Requires Capability Set 1:
<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/InterlockedAdd">InterlockedAdd</a>(
    <span class="code_keyword">int</span> <span class='code_param'>dest</span>,
    <span class="code_keyword">int</span> <span class='code_param'>value</span>);

/// Requires Capability Set 1:
<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/InterlockedAdd">InterlockedAdd</a>(
    <span class="code_keyword">int</span> <span class='code_param'>dest</span>,
    <span class="code_keyword">int</span> <span class='code_param'>value</span>,
    <span class="code_keyword">out</span> <span class="code_keyword">int</span> <span class='code_param'>original_value</span>);

/// Requires Capability Set 1:
<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/InterlockedAdd">InterlockedAdd</a>(
    <span class="code_keyword">uint</span> <span class='code_param'>dest</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>value</span>);

/// Requires Capability Set 1:
<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/InterlockedAdd">InterlockedAdd</a>(
    <span class="code_keyword">uint</span> <span class='code_param'>dest</span>,
    <span class="code_keyword">uint</span> <span class='code_param'>value</span>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <span class='code_param'>original_value</span>);

<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/InterlockedAdd">InterlockedAdd</a>(
    <span class="code_keyword">uint</span> <span class='code_param'>dest</span>,
    <span class="code_keyword">int</span> <span class='code_param'>value</span>);

/// Requires Capability Set 2:
<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/InterlockedAdd">InterlockedAdd</a>(
    int64_t <span class='code_param'>dest</span>,
    int64_t <span class='code_param'>value</span>);

<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/InterlockedAdd">InterlockedAdd</a>(
    int64_t <span class='code_param'>dest</span>,
    int64_t <span class='code_param'>value</span>,
    <span class="code_keyword">out</span> int64_t <span class='code_param'>original_value</span>);

/// Requires Capability Set 2:
<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/InterlockedAdd">InterlockedAdd</a>(
    uint64_t <span class='code_param'>dest</span>,
    uint64_t <span class='code_param'>value</span>);

<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/InterlockedAdd">InterlockedAdd</a>(
    uint64_t <span class='code_param'>dest</span>,
    uint64_t <span class='code_param'>value</span>,
    <span class="code_keyword">out</span> uint64_t <span class='code_param'>original_value</span>);

</pre>

## Parameters

#### dest : int
#### value : int
#### original\_value : int
#### dest : uint
#### value : uint
#### original\_value : uint
#### dest : int64\_t
#### value : int64\_t
#### original\_value : int64\_t
#### dest : uint64\_t
#### value : uint64\_t
#### original\_value : uint64\_t

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
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

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.


