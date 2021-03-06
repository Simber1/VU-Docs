---
title: AudioLanguage
---

Inherits from [DataContainer](/vext/ref/shared/type/datacontainer)

## Summary

### Constructors

|  |
| --- |
| **[AudioLanguage](#constructor-0)**() |
| **[AudioLanguage](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[AudioLanguage](#constructor-2)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "name" >}} | string |
| {{< prop "languageMapping" >}} | [LanguageFormat](/vext/ref/fb/languageformat) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "AudioLanguage" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### AudioLanguage {#constructor-0}

> **AudioLanguage**()

Creates a new [AudioLanguage](/vext/ref/fb/audiolanguage) frostbite instance.

### AudioLanguage {#constructor-1}

> **AudioLanguage**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [AudioLanguage](/vext/ref/fb/audiolanguage) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### AudioLanguage {#constructor-2}

> **AudioLanguage**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [AudioLanguage](/vext/ref/fb/audiolanguage). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [AudioLanguage](/vext/ref/fb/audiolanguage). |

## Properties

### {{% prop-heading "name" %}}

> **string**

### {{% prop-heading "languageMapping" %}}

> **[LanguageFormat](/vext/ref/fb/languageformat)**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [AudioLanguage](/vext/ref/fb/audiolanguage) type.

