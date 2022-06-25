[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / atlas

# Class: atlas

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).atlas

**`language`** zh_CN

**`classdesc`**
图集资源

**`version`** m4m 1.0

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Methods

- [Parse](m4m.framework.atlas.md#parse)
- [caclByteLength](m4m.framework.atlas.md#caclbytelength)
- [dispose](m4m.framework.atlas.md#dispose)
- [getGUID](m4m.framework.atlas.md#getguid)
- [getName](m4m.framework.atlas.md#getname)
- [unuse](m4m.framework.atlas.md#unuse)
- [use](m4m.framework.atlas.md#use)

### Constructors

- [constructor](m4m.framework.atlas.md#constructor)

### Properties

- [defaultAsset](m4m.framework.atlas.md#defaultasset)
- [sprites](m4m.framework.atlas.md#sprites)
- [textureheight](m4m.framework.atlas.md#textureheight)
- [texturewidth](m4m.framework.atlas.md#texturewidth)
- [ClassName](m4m.framework.atlas.md#classname)

### Accessors

- [texture](m4m.framework.atlas.md#texture)

## Methods

### Parse

▸ **Parse**(`jsonStr`, `assetmgr`, `bundleName?`): [`atlas`](m4m.framework.atlas.md)

**`language`** zh_CN

**`classdesc`**
解析资源

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `jsonStr` | `string` | `undefined` | json数据 |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) | `undefined` | 资源管理实例 |
| `bundleName` | `string` | `null` | - |

#### Returns

[`atlas`](m4m.framework.atlas.md)

#### Defined in

[framework/asset/resource/atlas.ts:176](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L176)

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

[framework/asset/resource/atlas.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L101)

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

[framework/asset/resource/atlas.ts:85](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L85)

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

[framework/asset/resource/atlas.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L52)

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

[framework/asset/resource/atlas.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L41)

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

[framework/asset/resource/atlas.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L74)

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

[framework/asset/resource/atlas.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L63)

## Constructors

### constructor

• **new atlas**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/asset/resource/atlas.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L26)

## Properties

### defaultAsset

• **defaultAsset**: `boolean`

**`language`** zh_CN

**`classdesc`**
是否为默认资源

**`version`** m4m 1.0

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

#### Defined in

[framework/asset/resource/atlas.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L25)

___

### sprites

• **sprites**: `Object` = `{}`

**`language`** zh_CN

**`classdesc`**
解析得到的sprite列表 key-->name

**`version`** m4m 1.0

#### Index signature

▪ [id: `string`]: [`sprite`](m4m.framework.sprite.md)

#### Defined in

[framework/asset/resource/atlas.ts:165](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L165)

___

### textureheight

• **textureheight**: `number`

**`language`** zh_CN

**`classdesc`**
贴图像素高度

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/atlas.ts:126](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L126)

___

### texturewidth

• **texturewidth**: `number`

**`language`** zh_CN

**`classdesc`**
贴图像素宽度

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/atlas.ts:118](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L118)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"atlas"`

#### Defined in

[framework/asset/resource/atlas.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L13)

## Accessors

### texture

• `get` **texture**(): [`texture`](m4m.framework.texture.md)

**`language`** zh_CN

**`classdesc`**
获取当前texture

**`version`** m4m 1.0

#### Returns

[`texture`](m4m.framework.texture.md)

#### Defined in

[framework/asset/resource/atlas.ts:137](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L137)

• `set` **texture**(`value`): `void`

**`language`** zh_CN

**`classdesc`**
设置当前texture

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`texture`](m4m.framework.texture.md) |

#### Returns

`void`

#### Defined in

[framework/asset/resource/atlas.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/atlas.ts#L149)
