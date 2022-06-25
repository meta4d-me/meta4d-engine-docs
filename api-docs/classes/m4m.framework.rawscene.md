[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / rawscene

# Class: rawscene

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).rawscene

**`language`** zh_CN

**`classdesc`**
场景数据资源

**`version`** m4m 1.0

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Methods

- [Parse](m4m.framework.rawscene.md#parse)
- [caclByteLength](m4m.framework.rawscene.md#caclbytelength)
- [dispose](m4m.framework.rawscene.md#dispose)
- [getGUID](m4m.framework.rawscene.md#getguid)
- [getName](m4m.framework.rawscene.md#getname)
- [getSceneRoot](m4m.framework.rawscene.md#getsceneroot)
- [resetLightMap](m4m.framework.rawscene.md#resetlightmap)
- [unuse](m4m.framework.rawscene.md#unuse)
- [use](m4m.framework.rawscene.md#use)
- [useFog](m4m.framework.rawscene.md#usefog)
- [useLightMap](m4m.framework.rawscene.md#uselightmap)
- [useNavMesh](m4m.framework.rawscene.md#usenavmesh)

### Properties

- [assetbundle](m4m.framework.rawscene.md#assetbundle)
- [defaultAsset](m4m.framework.rawscene.md#defaultasset)
- [fog](m4m.framework.rawscene.md#fog)
- [ClassName](m4m.framework.rawscene.md#classname)

### Constructors

- [constructor](m4m.framework.rawscene.md#constructor)

## Methods

### Parse

▸ **Parse**(`txt`, `assetmgr`): `Promise`<[`rawscene`](m4m.framework.rawscene.md)\>

**`language`** zh_CN

**`classdesc`**
解析资源

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `txt` | `string` | json数据 |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) | 资源管理实例 |

#### Returns

`Promise`<[`rawscene`](m4m.framework.rawscene.md)\>

#### Defined in

[framework/asset/resource/rawscene.ts:136](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L136)

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

[framework/asset/resource/rawscene.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L101)

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

[framework/asset/resource/rawscene.ts:272](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L272)

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

[framework/asset/resource/rawscene.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L59)

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

[framework/asset/resource/rawscene.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L48)

___

### getSceneRoot

▸ **getSceneRoot**(): [`transform`](m4m.framework.transform.md)

**`language`** zh_CN

**`classdesc`**
获取场景根节点的克隆

**`version`** m4m 1.0

#### Returns

[`transform`](m4m.framework.transform.md)

#### Defined in

[framework/asset/resource/rawscene.ts:212](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L212)

___

### resetLightMap

▸ **resetLightMap**(`assetmgr`, `bundleName?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) | `undefined` |
| `bundleName` | `string` | `null` |

#### Returns

`void`

#### Defined in

[framework/asset/resource/rawscene.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L106)

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

[framework/asset/resource/rawscene.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L89)

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

[framework/asset/resource/rawscene.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L78)

___

### useFog

▸ **useFog**(`scene`): `void`

**`language`** zh_CN

**`classdesc`**
应用雾效到场景中

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `scene` | [`scene`](m4m.framework.scene.md) | 场景实例 |

#### Returns

`void`

#### Defined in

[framework/asset/resource/rawscene.ts:241](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L241)

___

### useLightMap

▸ **useLightMap**(`scene`): `void`

**`language`** zh_CN

**`classdesc`**
应用lightmap到场景中

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `scene` | [`scene`](m4m.framework.scene.md) | 场景实例 |

#### Returns

`void`

#### Defined in

[framework/asset/resource/rawscene.ts:225](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L225)

___

### useNavMesh

▸ **useNavMesh**(`scene`): `boolean`

**`language`** zh_CN

**`classdesc`**
应用导航网格到场景中

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `scene` | [`scene`](m4m.framework.scene.md) | 场景实例 |

#### Returns

`boolean`

#### Defined in

[framework/asset/resource/rawscene.ts:254](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L254)

## Properties

### assetbundle

• **assetbundle**: `string` = `null`

**`language`** zh_CN

**`classdesc`**
依赖的AssetBundle

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/rawscene.ts:70](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L70)

___

### defaultAsset

• **defaultAsset**: `boolean` = `false`

**`language`** zh_CN

**`classdesc`**
是否为默认资源

**`version`** m4m 1.0

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

#### Defined in

[framework/asset/resource/rawscene.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L24)

___

### fog

• **fog**: `Fog`

**`language`** zh_CN

**`classdesc`**
雾效

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/rawscene.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L32)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"rawscene"`

#### Defined in

[framework/asset/resource/rawscene.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L13)

## Constructors

### constructor

• **new rawscene**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/asset/resource/rawscene.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/rawscene.ts#L33)
