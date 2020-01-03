---
title: RoundOverEvent
---
### Base Classes

[MetricEvent](MetricEvent)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                               | Description                                                                                                         |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| RoundOverEvent()                                                          | Create a new instance of this container type.                                                                       |
| RoundOverEvent(RoundOverEvent other)                                      | Create a reference copy of an instance of the same type.                                                            |
| RoundOverEvent([MetricEvent](MetricEvent) other)                          | Upcast an instance of type [MetricEvent](MetricEvent) to [RoundOverEvent](RoundOverEvent).                          |
| RoundOverEvent([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [RoundOverEvent](RoundOverEvent). |

## Properties

| Name        | Type   | Description |
| ----------- | ------ | ----------- |
| winningTeam | number |             |
| ticketsLeft | number |             |

## Methods

| Type                             | Name            | Parameters                                     |
| -------------------------------- | --------------- | ---------------------------------------------- |
| [RoundOverEvent](RoundOverEvent) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [RoundOverEvent](RoundOverEvent) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |