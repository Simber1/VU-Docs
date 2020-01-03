---
title: VoiceOverTriggerNode
---
### Base Classes

[VoiceOverStructureNode](VoiceOverStructureNode)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                     | Description                                                                                                                     |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| VoiceOverTriggerNode()                                                          | Create a new instance of this container type.                                                                                   |
| VoiceOverTriggerNode(VoiceOverTriggerNode other)                                | Create a reference copy of an instance of the same type.                                                                        |
| VoiceOverTriggerNode([VoiceOverStructureNode](VoiceOverStructureNode) other)    | Upcast an instance of type [VoiceOverStructureNode](VoiceOverStructureNode) to [VoiceOverTriggerNode](VoiceOverTriggerNode).    |
| VoiceOverTriggerNode([VoiceOverNode](VoiceOverNode) other)                      | Upcast an instance of type [VoiceOverNode](VoiceOverNode) to [VoiceOverTriggerNode](VoiceOverTriggerNode).                      |
| VoiceOverTriggerNode([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [VoiceOverTriggerNode](VoiceOverTriggerNode). |

## Properties

| Name       | Type                                                       | Description |
| ---------- | ---------------------------------------------------------- | ----------- |
| parameters | [VoiceOverTriggerParameter](VoiceOverTriggerParameter)\[\] |             |
| delay      | number                                                     |             |
| event      | [VoiceOverEvent](VoiceOverEvent)                           |             |

## Methods

| Type                                         | Name            | Parameters                                     |
| -------------------------------------------- | --------------- | ---------------------------------------------- |
| [VoiceOverTriggerNode](VoiceOverTriggerNode) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [VoiceOverTriggerNode](VoiceOverTriggerNode) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |