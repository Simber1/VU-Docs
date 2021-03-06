---
title: LevelAudioObstructionAsset
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[LevelAudioObstructionAsset](#constructor-0)**() |
| **[LevelAudioObstructionAsset](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[LevelAudioObstructionAsset](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[LevelAudioObstructionAsset](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "materialMap" >}} | [AudioObstructionMaterialInfo](/vext/ref/fb/audioobstructionmaterialinfo)[] |
| {{< prop "frequencySlewRate" >}} | float |
| {{< prop "gainSlewRate" >}} | float |
| {{< prop "maxRaycastDistanceSquared" >}} | float |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "LevelAudioObstructionAsset" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### LevelAudioObstructionAsset {#constructor-0}

> **LevelAudioObstructionAsset**()

Creates a new [LevelAudioObstructionAsset](/vext/ref/fb/levelaudioobstructionasset) frostbite instance.

### LevelAudioObstructionAsset {#constructor-1}

> **LevelAudioObstructionAsset**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [LevelAudioObstructionAsset](/vext/ref/fb/levelaudioobstructionasset) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### LevelAudioObstructionAsset {#constructor-2}

> **LevelAudioObstructionAsset**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [LevelAudioObstructionAsset](/vext/ref/fb/levelaudioobstructionasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [LevelAudioObstructionAsset](/vext/ref/fb/levelaudioobstructionasset). |

### LevelAudioObstructionAsset {#constructor-3}

> **LevelAudioObstructionAsset**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [LevelAudioObstructionAsset](/vext/ref/fb/levelaudioobstructionasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [LevelAudioObstructionAsset](/vext/ref/fb/levelaudioobstructionasset). |

## Properties

### {{% prop-heading "materialMap" %}}

> **[AudioObstructionMaterialInfo](/vext/ref/fb/audioobstructionmaterialinfo)**[]

### {{% prop-heading "frequencySlewRate" %}}

> **float**

### {{% prop-heading "gainSlewRate" %}}

> **float**

### {{% prop-heading "maxRaycastDistanceSquared" %}}

> **float**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [LevelAudioObstructionAsset](/vext/ref/fb/levelaudioobstructionasset) type.

