---
title: UIMapmarkerCompData
---
### Base Classes

[UIComponentData](UIComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| UIMapmarkerCompData()                                                          | Create a new instance of this container type.                                                                                 |
| UIMapmarkerCompData(UIMapmarkerCompData other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| UIMapmarkerCompData([UIComponentData](UIComponentData) other)                  | Upcast an instance of type [UIComponentData](UIComponentData) to [UIMapmarkerCompData](UIMapmarkerCompData).                  |
| UIMapmarkerCompData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIMapmarkerCompData](UIMapmarkerCompData).                                      |
| UIMapmarkerCompData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UIMapmarkerCompData](UIMapmarkerCompData). |

## Properties

| Name               | Type       | Description |
| ------------------ | ---------- | ----------- |
| proximityIntervals | number\[\] |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [UIMapmarkerCompData](UIMapmarkerCompData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UIMapmarkerCompData](UIMapmarkerCompData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |