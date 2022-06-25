[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / f14eff

# Class: f14eff

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).f14eff

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Methods

- [Parse](m4m.framework.f14eff.md#parse)
- [caclByteLength](m4m.framework.f14eff.md#caclbytelength)
- [dispose](m4m.framework.f14eff.md#dispose)
- [getDependents](m4m.framework.f14eff.md#getdependents)
- [getGUID](m4m.framework.f14eff.md#getguid)
- [getName](m4m.framework.f14eff.md#getname)
- [unuse](m4m.framework.f14eff.md#unuse)
- [use](m4m.framework.f14eff.md#use)

### Properties

- [assetbundle](m4m.framework.f14eff.md#assetbundle)
- [data](m4m.framework.f14eff.md#data)
- [defaultAsset](m4m.framework.f14eff.md#defaultasset)
- [delayTime](m4m.framework.f14eff.md#delaytime)
- [ClassName](m4m.framework.f14eff.md#classname)

### Constructors

- [constructor](m4m.framework.f14eff.md#constructor)

## Methods

### Parse

▸ **Parse**(`jsonStr`, `assetmgr`): [`F14EffectData`](m4m.framework.F14EffectData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `jsonStr` | `string` |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |

#### Returns

[`F14EffectData`](m4m.framework.F14EffectData.md)

#### Defined in

[framework/asset/resource/f14eff.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L58)

___

### caclByteLength

▸ **caclByteLength**(): `number`

#### Returns

`number`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[caclByteLength](../interfaces/m4m.framework.IAsset.md#caclbytelength)

#### Defined in

[framework/asset/resource/f14eff.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L50)

___

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[dispose](../interfaces/m4m.framework.IAsset.md#dispose)

#### Defined in

[framework/asset/resource/f14eff.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L46)

___

### getDependents

▸ **getDependents**(): [`IAsset`](../interfaces/m4m.framework.IAsset.md)[]

获取依赖资源 （mesh 、material）

#### Returns

[`IAsset`](../interfaces/m4m.framework.IAsset.md)[]

#### Defined in

[framework/asset/resource/f14eff.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L80)

___

### getGUID

▸ **getGUID**(): `number`

#### Returns

`number`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[getGUID](../interfaces/m4m.framework.IAsset.md#getguid)

#### Defined in

[framework/asset/resource/f14eff.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L34)

___

### getName

▸ **getName**(): `string`

#### Returns

`string`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[getName](../interfaces/m4m.framework.IAsset.md#getname)

#### Defined in

[framework/asset/resource/f14eff.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L26)

___

### unuse

▸ **unuse**(`disposeNow?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `disposeNow?` | `boolean` |

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[unuse](../interfaces/m4m.framework.IAsset.md#unuse)

#### Defined in

[framework/asset/resource/f14eff.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L42)

___

### use

▸ **use**(): `void`

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[use](../interfaces/m4m.framework.IAsset.md#use)

#### Defined in

[framework/asset/resource/f14eff.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L38)

## Properties

### assetbundle

• **assetbundle**: `string` = `null`

#### Defined in

[framework/asset/resource/f14eff.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L25)

___

### data

• **data**: [`F14EffectData`](m4m.framework.F14EffectData.md)

#### Defined in

[framework/asset/resource/f14eff.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L54)

___

### defaultAsset

• **defaultAsset**: `boolean` = `false`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

#### Defined in

[framework/asset/resource/f14eff.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L14)

___

### delayTime

• **delayTime**: `number`

#### Defined in

[framework/asset/resource/f14eff.ts:55](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L55)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"f14eff"`

#### Defined in

[framework/asset/resource/f14eff.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L12)

## Constructors

### constructor

• **new f14eff**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/asset/resource/f14eff.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/f14eff.ts#L17)
