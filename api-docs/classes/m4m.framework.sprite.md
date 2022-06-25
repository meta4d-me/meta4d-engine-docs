[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / sprite

# Class: sprite

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).sprite

**`language`** zh_CN

**`classdesc`**
sprite资源

**`version`** m4m 1.0

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Properties

- [atlas](m4m.framework.sprite.md#atlas)
- [border](m4m.framework.sprite.md#border)
- [bundle](m4m.framework.sprite.md#bundle)
- [defaultAsset](m4m.framework.sprite.md#defaultasset)
- [rect](m4m.framework.sprite.md#rect)
- [ClassName](m4m.framework.sprite.md#classname)

### Methods

- [caclByteLength](m4m.framework.sprite.md#caclbytelength)
- [dispose](m4m.framework.sprite.md#dispose)
- [getGUID](m4m.framework.sprite.md#getguid)
- [getName](m4m.framework.sprite.md#getname)
- [unuse](m4m.framework.sprite.md#unuse)
- [use](m4m.framework.sprite.md#use)

### Constructors

- [constructor](m4m.framework.sprite.md#constructor)

### Accessors

- [texture](m4m.framework.sprite.md#texture)
- [urange](m4m.framework.sprite.md#urange)
- [vrange](m4m.framework.sprite.md#vrange)

## Properties

### atlas

• **atlas**: `string`

**`language`** zh_CN

**`classdesc`**
所属图集

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/sprite.ts:147](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L147)

___

### border

• **border**: `border`

**`language`** zh_CN

**`classdesc`**
边距

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/sprite.ts:163](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L163)

___

### bundle

• **bundle**: [`assetBundle`](m4m.framework.assetBundle.md)

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[bundle](../interfaces/m4m.framework.IAsset.md#bundle)

#### Defined in

[framework/asset/resource/sprite.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L17)

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

[framework/asset/resource/sprite.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L25)

___

### rect

• **rect**: `rect`

**`language`** zh_CN

**`classdesc`**
有效区域

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/sprite.ts:155](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L155)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"sprite"`

#### Defined in

[framework/asset/resource/sprite.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L13)

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

[framework/asset/resource/sprite.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L100)

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

[framework/asset/resource/sprite.ts:85](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L85)

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

[framework/asset/resource/sprite.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L52)

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

[framework/asset/resource/sprite.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L41)

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

[framework/asset/resource/sprite.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L74)

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

[framework/asset/resource/sprite.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L63)

## Constructors

### constructor

• **new sprite**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/asset/resource/sprite.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L26)

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

[framework/asset/resource/sprite.ts:119](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L119)

• `set` **texture**(`value`): `void`

**`language`** zh_CN

**`classdesc`**
设置texture

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | [`texture`](m4m.framework.texture.md) | texture实例 |

#### Returns

`void`

#### Defined in

[framework/asset/resource/sprite.ts:131](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L131)

___

### urange

• `get` **urange**(): `vector2`

**`language`** zh_CN

**`classdesc`**
uv的u范围

**`version`** m4m 1.0

#### Returns

`vector2`

#### Defined in

[framework/asset/resource/sprite.ts:173](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L173)

___

### vrange

• `get` **vrange**(): `vector2`

**`language`** zh_CN

**`classdesc`**
uv的v范围

**`version`** m4m 1.0

#### Returns

`vector2`

#### Defined in

[framework/asset/resource/sprite.ts:190](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/sprite.ts#L190)
