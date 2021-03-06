---
title: SpawnEvent
---

Inherits from [MetricEvent](/vext/ref/fb/metricevent)

## Summary

### Constructors

|  |
| --- |
| **[SpawnEvent](#constructor-0)**() |
| **[SpawnEvent](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[SpawnEvent](#constructor-2)**(other: [MetricEvent](/vext/ref/fb/metricevent)) |
| **[SpawnEvent](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "position" >}} | [Vec3](/vext/ref/shared/type/vec3) |
| {{< prop "time" >}} | float |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "SpawnEvent" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### SpawnEvent {#constructor-0}

> **SpawnEvent**()

Creates a new [SpawnEvent](/vext/ref/fb/spawnevent) frostbite instance.

### SpawnEvent {#constructor-1}

> **SpawnEvent**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [SpawnEvent](/vext/ref/fb/spawnevent) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### SpawnEvent {#constructor-2}

> **SpawnEvent**(other: [MetricEvent](/vext/ref/fb/metricevent))

Casts an instance of type [MetricEvent](/vext/ref/fb/metricevent) to [SpawnEvent](/vext/ref/fb/spawnevent). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [MetricEvent](/vext/ref/fb/metricevent) | The instance to cast to [SpawnEvent](/vext/ref/fb/spawnevent). |

### SpawnEvent {#constructor-3}

> **SpawnEvent**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [SpawnEvent](/vext/ref/fb/spawnevent). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [SpawnEvent](/vext/ref/fb/spawnevent). |

## Properties

### {{% prop-heading "position" %}}

> **[Vec3](/vext/ref/shared/type/vec3)**

### {{% prop-heading "time" %}}

> **float**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [SpawnEvent](/vext/ref/fb/spawnevent) type.

