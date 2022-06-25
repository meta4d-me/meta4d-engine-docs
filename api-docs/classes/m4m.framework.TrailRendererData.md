[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / TrailRendererData

# Class: TrailRendererData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).TrailRendererData

拖尾染器数据

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Methods

- [caclByteLength](m4m.framework.TrailRendererData.md#caclbytelength)
- [dispose](m4m.framework.TrailRendererData.md#dispose)
- [getGUID](m4m.framework.TrailRendererData.md#getguid)
- [getName](m4m.framework.TrailRendererData.md#getname)
- [setData](m4m.framework.TrailRendererData.md#setdata)
- [unuse](m4m.framework.TrailRendererData.md#unuse)
- [use](m4m.framework.TrailRendererData.md#use)
- [get](m4m.framework.TrailRendererData.md#get)

### Constructors

- [constructor](m4m.framework.TrailRendererData.md#constructor)

### Properties

- [defaultAsset](m4m.framework.TrailRendererData.md#defaultasset)
- [objectData](m4m.framework.TrailRendererData.md#objectdata)
- [trailRenderer](m4m.framework.TrailRendererData.md#trailrenderer)
- [ClassName](m4m.framework.TrailRendererData.md#classname)

### Accessors

- [value](m4m.framework.TrailRendererData.md#value)

## Methods

### caclByteLength

▸ **caclByteLength**(): `number`

**`language`** zh_CN

**`classdesc`**
计算资源字节大小

**`version`** m4m 1.0

#### Returns

`number`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[caclByteLength](../interfaces/m4m.framework.IAsset.md#caclbytelength)

#### Defined in

[framework/effects/TrailRendererData.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L134)

___

### dispose

▸ **dispose**(): `void`

**`language`** zh_CN

**`classdesc`**
释放资源

**`version`** m4m 1.0

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[dispose](../interfaces/m4m.framework.IAsset.md#dispose)

#### Defined in

[framework/effects/TrailRendererData.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L101)

___

### getGUID

▸ **getGUID**(): `number`

**`language`** zh_CN

**`classdesc`**
获取资源唯一id

**`version`** m4m 1.0

#### Returns

`number`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[getGUID](../interfaces/m4m.framework.IAsset.md#getguid)

#### Defined in

[framework/effects/TrailRendererData.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L89)

___

### getName

▸ **getName**(): `string`

**`language`** zh_CN

**`classdesc`**
获取资源名称

**`version`** m4m 1.0

#### Returns

`string`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[getName](../interfaces/m4m.framework.IAsset.md#getname)

#### Defined in

[framework/effects/TrailRendererData.ts:73](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L73)

___

### setData

▸ **setData**(`v`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `string` |

#### Returns

`void`

#### Defined in

[framework/effects/TrailRendererData.ts:140](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L140)

___

### unuse

▸ **unuse**(`disposeNow?`): `void`

**`language`** zh_CN

**`classdesc`**
引用计数减一

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `disposeNow` | `boolean` | `false` |

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[unuse](../interfaces/m4m.framework.IAsset.md#unuse)

#### Defined in

[framework/effects/TrailRendererData.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L122)

___

### use

▸ **use**(): `void`

**`language`** zh_CN

**`classdesc`**
引用计数加一

**`version`** m4m 1.0

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[use](../interfaces/m4m.framework.IAsset.md#use)

#### Defined in

[framework/effects/TrailRendererData.ts:111](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L111)

___

### get

▸ `Static` **get**(`valueName`): [`TrailRendererData`](m4m.framework.TrailRendererData.md)

获取已经创建了的粒子系统数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `valueName` | `string` |

#### Returns

[`TrailRendererData`](m4m.framework.TrailRendererData.md)

#### Defined in

[framework/effects/TrailRendererData.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L20)

## Constructors

### constructor

• **new TrailRendererData**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/effects/TrailRendererData.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L57)

## Properties

### defaultAsset

• **defaultAsset**: `boolean` = `false`

**`language`** zh_CN

**`classdesc`**
是否为默认资源

**`version`** m4m 1.0

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

#### Defined in

[framework/effects/TrailRendererData.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L35)

___

### objectData

• **objectData**: `any`

#### Defined in

[framework/effects/TrailRendererData.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L149)

___

### trailRenderer

• **trailRenderer**: [`TrailRenderer`](m4m.framework.TrailRenderer.md)

#### Defined in

[framework/effects/TrailRendererData.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L13)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"TrailRendererData"`

#### Defined in

[framework/effects/TrailRendererData.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L9)

## Accessors

### value

• `get` **value**(): `string`

粒子系统资源名称

#### Returns

`string`

#### Defined in

[framework/effects/TrailRendererData.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L41)

• `set` **value**(`v`): `void`

粒子系统资源名称

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `string` |

#### Returns

`void`

#### Defined in

[framework/effects/TrailRendererData.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRendererData.ts#L45)
