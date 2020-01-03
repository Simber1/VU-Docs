---
title: MeshVariationDatabase
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                      | Description                                                                                                                       |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| MeshVariationDatabase()                                                          | Create a new instance of this container type.                                                                                     |
| MeshVariationDatabase(MeshVariationDatabase other)                               | Create a reference copy of an instance of the same type.                                                                          |
| MeshVariationDatabase([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [MeshVariationDatabase](MeshVariationDatabase).                                      |
| MeshVariationDatabase([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [MeshVariationDatabase](MeshVariationDatabase). |

## Properties

| Name            | Type                                                         | Description |
| --------------- | ------------------------------------------------------------ | ----------- |
| entries         | [MeshVariationDatabaseEntry](MeshVariationDatabaseEntry)\[\] |             |
| redirectEntries | [MeshVariationDatabaseEntry](MeshVariationDatabaseEntry)\[\] |             |

## Methods

| Type                                           | Name            | Parameters                                     |
| ---------------------------------------------- | --------------- | ---------------------------------------------- |
| [MeshVariationDatabase](MeshVariationDatabase) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [MeshVariationDatabase](MeshVariationDatabase) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |