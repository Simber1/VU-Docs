---
title: GunSwayStanceZoomModifierData
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                                                        | Description                                              |
| ------------------------------------------------------------------ | -------------------------------------------------------- |
| GunSwayStanceZoomModifierData()                                    | Create a new instance of this structure type.            |
| GunSwayStanceZoomModifierData(GunSwayStanceZoomModifierData other) | Create a reference copy of a structure of the same type. |

## Properties

| Name               | Type                                                 | Description |
| ------------------ | ---------------------------------------------------- | ----------- |
| dispersionMod      | [GunSwayDispersionModData](GunSwayDispersionModData) |             |
| recoilMagnitudeMod | number                                               |             |
| recoilAngleMod     | number                                               |             |
| lagYawMod          | number                                               |             |
| lagPitchMod        | number                                               |             |

## Methods

| Type                                                           | Name            | Parameters |
| -------------------------------------------------------------- | --------------- | ---------- |
| [GunSwayStanceZoomModifierData](GunSwayStanceZoomModifierData) | [Clone](#clone) |            |

### Clone

> [GunSwayStanceZoomModifierData](GunSwayStanceZoomModifierData) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone).