[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14LayerData

# Class: F14LayerData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14LayerData

## Table of contents

### Properties

- [Name](m4m.framework.F14LayerData.md#name)
- [elementdata](m4m.framework.F14LayerData.md#elementdata)
- [frames](m4m.framework.F14LayerData.md#frames)
- [type](m4m.framework.F14LayerData.md#type)

### Constructors

- [constructor](m4m.framework.F14LayerData.md#constructor)

### Methods

- [parse](m4m.framework.F14LayerData.md#parse)

## Properties

### Name

• **Name**: `string` = `"newLayer"`

#### Defined in

[framework/component/f14effectsystem/data/f14effectdata.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/f14effectdata.ts#L43)

___

### elementdata

• **elementdata**: [`F14ElementData`](../interfaces/m4m.framework.F14ElementData.md)

#### Defined in

[framework/component/f14effectsystem/data/f14effectdata.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/f14effectdata.ts#L45)

___

### frames

• **frames**: `Object` = `{}`

#### Index signature

▪ [frame: `number`]: [`F14FrameData`](m4m.framework.F14FrameData.md)

#### Defined in

[framework/component/f14effectsystem/data/f14effectdata.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/f14effectdata.ts#L51)

___

### type

• **type**: [`F14TypeEnum`](../enums/m4m.framework.F14TypeEnum.md) = `F14TypeEnum.SingleMeshType`

#### Defined in

[framework/component/f14effectsystem/data/f14effectdata.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/f14effectdata.ts#L44)

## Constructors

### constructor

• **new F14LayerData**()

#### Defined in

[framework/component/f14effectsystem/data/f14effectdata.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/f14effectdata.ts#L53)

## Methods

### parse

▸ **parse**(`json`, `assetmgr`, `assetbundle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `json` | `any` |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `assetbundle` | `string` |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/data/f14effectdata.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/f14effectdata.ts#L57)
