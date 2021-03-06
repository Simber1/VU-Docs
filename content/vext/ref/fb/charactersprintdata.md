---
title: CharacterSprintData
---

Inherits from [DataContainer](/vext/ref/shared/type/datacontainer)

## Summary

### Constructors

|  |
| --- |
| **[CharacterSprintData](#constructor-0)**() |
| **[CharacterSprintData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[CharacterSprintData](#constructor-2)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "sprintPowerDecreasePerSecond" >}} | float |
| {{< prop "sprintPowerIncreasePerSecond" >}} | float |
| {{< prop "sprintMinimumPower" >}} | float |
| {{< prop "allowContinousSprinting" >}} | bool |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "CharacterSprintData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### CharacterSprintData {#constructor-0}

> **CharacterSprintData**()

Creates a new [CharacterSprintData](/vext/ref/fb/charactersprintdata) frostbite instance.

### CharacterSprintData {#constructor-1}

> **CharacterSprintData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [CharacterSprintData](/vext/ref/fb/charactersprintdata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### CharacterSprintData {#constructor-2}

> **CharacterSprintData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [CharacterSprintData](/vext/ref/fb/charactersprintdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [CharacterSprintData](/vext/ref/fb/charactersprintdata). |

## Properties

### {{% prop-heading "sprintPowerDecreasePerSecond" %}}

> **float**

### {{% prop-heading "sprintPowerIncreasePerSecond" %}}

> **float**

### {{% prop-heading "sprintMinimumPower" %}}

> **float**

### {{% prop-heading "allowContinousSprinting" %}}

> **bool**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [CharacterSprintData](/vext/ref/fb/charactersprintdata) type.

