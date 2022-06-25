[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / mesh

# Class: mesh

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).mesh

**`language`** zh_CN

**`classdesc`**
mesh资源

**`version`** m4m 1.0

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Methods

- [Parse](m4m.framework.mesh.md#parse)
- [caclByteLength](m4m.framework.mesh.md#caclbytelength)
- [calcVectexMinMax](m4m.framework.mesh.md#calcvectexminmax)
- [clone](m4m.framework.mesh.md#clone)
- [dispose](m4m.framework.mesh.md#dispose)
- [getGUID](m4m.framework.mesh.md#getguid)
- [getName](m4m.framework.mesh.md#getname)
- [intersects](m4m.framework.mesh.md#intersects)
- [parseCMesh](m4m.framework.mesh.md#parsecmesh)
- [unuse](m4m.framework.mesh.md#unuse)
- [use](m4m.framework.mesh.md#use)

### Constructors

- [constructor](m4m.framework.mesh.md#constructor)

### Properties

- [data](m4m.framework.mesh.md#data)
- [defaultAsset](m4m.framework.mesh.md#defaultasset)
- [maximun](m4m.framework.mesh.md#maximun)
- [minimun](m4m.framework.mesh.md#minimun)
- [onReadFinish](m4m.framework.mesh.md#onreadfinish)
- [submesh](m4m.framework.mesh.md#submesh)
- [updateByEffect](m4m.framework.mesh.md#updatebyeffect)
- [ClassName](m4m.framework.mesh.md#classname)
- [useThead](m4m.framework.mesh.md#usethead)

## Methods

### Parse

▸ **Parse**(`inData`, `webgl`): `Promise`<[`IAsset`](../interfaces/m4m.framework.IAsset.md)\>

**`language`** zh_CN

**`classdesc`**
解析资源

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `inData` | `any` | - |
| `webgl` | `WebGLRenderingContext` | webgl实例 |

#### Returns

`Promise`<[`IAsset`](../interfaces/m4m.framework.IAsset.md)\>

#### Defined in

[framework/asset/resource/mesh.ts:386](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L386)

___

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

[framework/asset/resource/mesh.ts:95](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L95)

___

### calcVectexMinMax

▸ **calcVectexMinMax**(`outMin`, `outMax`): `void`

**`language`** zh_CN

**`classdesc`**
计算模型顶点的 最大最小值

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `outMin` | `vector3` | 输出最小 |
| `outMax` | `vector3` | 输出最大 |

#### Returns

`void`

#### Defined in

[framework/asset/resource/mesh.ts:834](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L834)

___

### clone

▸ **clone**(): [`mesh`](m4m.framework.mesh.md)

**`language`** zh_CN

**`classdesc`**
克隆mesh

**`version`** m4m 1.0

#### Returns

[`mesh`](m4m.framework.mesh.md)

#### Defined in

[framework/asset/resource/mesh.ts:803](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L803)

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

[framework/asset/resource/mesh.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L82)

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

[framework/asset/resource/mesh.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L49)

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

[framework/asset/resource/mesh.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L34)

___

### intersects

▸ **intersects**(`ray`, `matrix`, `outInfo`): `boolean`

**`language`** zh_CN

**`classdesc`**
检测射线碰撞

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ray` | [`ray`](m4m.framework.ray.md) | 射线 |
| `matrix` | `matrix` | 所在transform的矩阵 |
| `outInfo` | `pickinfo` | - |

#### Returns

`boolean`

#### Defined in

[framework/asset/resource/mesh.ts:734](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L734)

___

### parseCMesh

▸ **parseCMesh**(`inData`, `webgl`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inData` | `any` |
| `webgl` | `any` |

#### Returns

`void`

#### Defined in

[framework/asset/resource/mesh.ts:405](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L405)

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

[framework/asset/resource/mesh.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L71)

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

[framework/asset/resource/mesh.ts:60](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L60)

## Constructors

### constructor

• **new mesh**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/asset/resource/mesh.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L19)

## Properties

### data

• **data**: `meshData`

**`language`** zh_CN

**`classdesc`**
mesh数据实例

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/mesh.ts:118](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L118)

___

### defaultAsset

• **defaultAsset**: `boolean` = `false`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

#### Defined in

[framework/asset/resource/mesh.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L18)

___

### maximun

• **maximun**: `vector3`

#### Defined in

[framework/asset/resource/mesh.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L14)

___

### minimun

• **minimun**: `vector3`

#### Defined in

[framework/asset/resource/mesh.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L15)

___

### onReadFinish

• **onReadFinish**: () => `void`

#### Type declaration

▸ (): `void`

##### Returns

`void`

#### Defined in

[framework/asset/resource/mesh.ts:133](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L133)

___

### submesh

• **submesh**: `subMeshInfo`[] = `[]`

**`language`** zh_CN

**`classdesc`**
submesh信息列表

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/mesh.ts:126](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L126)

___

### updateByEffect

• **updateByEffect**: `boolean` = `false`

#### Defined in

[framework/asset/resource/mesh.ts:110](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L110)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"mesh"`

#### Defined in

[framework/asset/resource/mesh.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L13)

___

### useThead

▪ `Static` **useThead**: `boolean` = `true`

是否使用多线程解析

#### Defined in

[framework/asset/resource/mesh.ts:131](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/mesh.ts#L131)
