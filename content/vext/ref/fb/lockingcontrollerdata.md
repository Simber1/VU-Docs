---
title: LockingControllerData
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                      | Description                                                                                                                       |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| LockingControllerData()                                                          | Create a new instance of this container type.                                                                                     |
| LockingControllerData(LockingControllerData other)                               | Create a reference copy of an instance of the same type.                                                                          |
| LockingControllerData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [LockingControllerData](LockingControllerData). |

## Properties

| Name                     | Type                                       | Description |
| ------------------------ | ------------------------------------------ | ----------- |
| zoomLevelLock            | [ZoomLevelLockData](ZoomLevelLockData)\[\] |             |
| lockTime                 | number                                     |             |
| releaseTime              | number                                     |             |
| releaseOnNewTargetTime   | number                                     |             |
| sampleRate               | number                                     |             |
| holdStillThreshold       | number                                     |             |
| rayLength                | number                                     |             |
| acceptanceAngle          | number                                     |             |
| minimumLockTime          | number                                     |             |
| sensitivity              | number                                     |             |
| angleConstant            | number                                     |             |
| distanceConstant         | number                                     |             |
| lockOnWorldSpacePos      | bool                                       |             |
| lockOnVisibleTargetsOnly | bool                                       |             |
| positionOnly             | bool                                       |             |
| lockOnEmptyVehicles      | bool                                       |             |
| ignoreHeigthLockDistance | bool                                       |             |

## Methods

| Type                                           | Name            | Parameters                                     |
| ---------------------------------------------- | --------------- | ---------------------------------------------- |
| [LockingControllerData](LockingControllerData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [LockingControllerData](LockingControllerData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |