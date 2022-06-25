[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / font

# Class: font

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).font

**`language`** zh_CN

**`classdesc`**
字体资源

**`version`** m4m 1.0

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Methods

- [Parse](m4m.framework.font.md#parse)
- [caclByteLength](m4m.framework.font.md#caclbytelength)
- [dispose](m4m.framework.font.md#dispose)
- [getGUID](m4m.framework.font.md#getguid)
- [getName](m4m.framework.font.md#getname)
- [unuse](m4m.framework.font.md#unuse)
- [use](m4m.framework.font.md#use)

### Properties

- [atlasHeight](m4m.framework.font.md#atlasheight)
- [atlasWidth](m4m.framework.font.md#atlaswidth)
- [baseline](m4m.framework.font.md#baseline)
- [cmap](m4m.framework.font.md#cmap)
- [defaultAsset](m4m.framework.font.md#defaultasset)
- [fontname](m4m.framework.font.md#fontname)
- [lineHeight](m4m.framework.font.md#lineheight)
- [padding](m4m.framework.font.md#padding)
- [pointSize](m4m.framework.font.md#pointsize)
- [ClassName](m4m.framework.font.md#classname)

### Constructors

- [constructor](m4m.framework.font.md#constructor)

### Accessors

- [texture](m4m.framework.font.md#texture)

## Methods

### Parse

▸ **Parse**(`jsonStr`, `assetmgr`, `bundleName?`): [`font`](m4m.framework.font.md)

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

[`font`](m4m.framework.font.md)

#### Defined in

[framework/asset/resource/font.ts:159](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L159)

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

[framework/asset/resource/font.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L100)

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

[framework/asset/resource/font.ts:84](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L84)

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

[framework/asset/resource/font.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L51)

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

[framework/asset/resource/font.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L40)

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

[framework/asset/resource/font.ts:73](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L73)

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

[framework/asset/resource/font.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L62)

## Properties

### atlasHeight

• **atlasHeight**: `number`

字符容器图的高度

#### Defined in

[framework/asset/resource/font.ts:148](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L148)

___

### atlasWidth

• **atlasWidth**: `number`

字符容器图的宽度

#### Defined in

[framework/asset/resource/font.ts:146](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L146)

___

### baseline

• **baseline**: `number`

基线

#### Defined in

[framework/asset/resource/font.ts:144](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L144)

___

### cmap

• **cmap**: `Object`

**`language`** zh_CN

**`classdesc`**
字体信息map

**`version`** m4m 1.0

#### Index signature

▪ [id: `string`]: `charinfo`

#### Defined in

[framework/asset/resource/font.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L134)

___

### defaultAsset

• **defaultAsset**: `boolean`

**`language`** zh_CN

**`classdesc`**
是否为默认资源

**`version`** m4m 1.0

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

#### Defined in

[framework/asset/resource/font.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L24)

___

### fontname

• **fontname**: `string`

字体名

#### Defined in

[framework/asset/resource/font.ts:136](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L136)

___

### lineHeight

• **lineHeight**: `number`

行高

#### Defined in

[framework/asset/resource/font.ts:142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L142)

___

### padding

• **padding**: `number`

填充间隔

#### Defined in

[framework/asset/resource/font.ts:140](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L140)

___

### pointSize

• **pointSize**: `number`

像素尺寸

#### Defined in

[framework/asset/resource/font.ts:138](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L138)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"font"`

#### Defined in

[framework/asset/resource/font.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L13)

## Constructors

### constructor

• **new font**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/asset/resource/font.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L25)

## Accessors

### texture

• `get` **texture**(): [`texture`](m4m.framework.texture.md)

#### Returns

[`texture`](m4m.framework.texture.md)

#### Defined in

[framework/asset/resource/font.ts:111](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L111)

• `set` **texture**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`texture`](m4m.framework.texture.md) |

#### Returns

`void`

#### Defined in

[framework/asset/resource/font.ts:115](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/font.ts#L115)
