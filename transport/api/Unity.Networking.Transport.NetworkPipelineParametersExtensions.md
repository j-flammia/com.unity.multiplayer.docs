---  
id: Unity.Networking.Transport.NetworkPipelineParametersExtensions  
title: Unity.Networking.Transport.NetworkPipelineParametersExtensions  
---

<div class="markdown level0 summary">

</div>

<div class="markdown level0 conceptual">

</div>

<div class="inheritance">

##### Inheritance

<div class="level0">

System.Dynamic.ExpandoObject

</div>

<div class="level1">

System.Dynamic.ExpandoObject

</div>

</div>

<div class="inheritedMembers">

##### Inherited Members

<div>

Object.Equals(Object)

</div>

<div>

Object.Equals(Object, Object)

</div>

<div>

Object.GetHashCode()

</div>

<div>

Object.GetType()

</div>

<div>

Object.MemberwiseClone()

</div>

<div>

Object.ReferenceEquals(Object, Object)

</div>

<div>

Object.ToString()

</div>

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: transport.dll

##### Syntax

``` lang-csharp
public static class NetworkPipelineParametersExtensions
```

## 

### GetPipelineParameters(ref NetworkSettings)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public static NetworkPipelineParams GetPipelineParameters(this ref NetworkSettings settings)
```

#### Parameters

| Type            | Name     | Description |
|-----------------|----------|-------------|
| NetworkSettings | settings |             |

#### Returns

| Type                  | Description |
|-----------------------|-------------|
| NetworkPipelineParams |             |

### WithPipelineParameters(ref NetworkSettings, Int32)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public static ref NetworkSettings WithPipelineParameters(this ref NetworkSettings settings, int initialCapacity = 0)
```

#### Parameters

| Type            | Name            | Description |
|-----------------|-----------------|-------------|
| NetworkSettings | settings        |             |
| System.Int32    | initialCapacity |             |

#### Returns

| Type            | Description |
|-----------------|-------------|
| NetworkSettings |             |