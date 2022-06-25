[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / textasset

# Class: textasset

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).textasset

**`language`** zh_CN

**`classdesc`**
文本资源

**`version`** m4m 1.0

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Methods

- [caclByteLength](m4m.framework.textasset.md#caclbytelength)
- [dispose](m4m.framework.textasset.md#dispose)
- [getGUID](m4m.framework.textasset.md#getguid)
- [getName](m4m.framework.textasset.md#getname)
- [unuse](m4m.framework.textasset.md#unuse)
- [use](m4m.framework.textasset.md#use)

### Constructors

- [constructor](m4m.framework.textasset.md#constructor)

### Properties

- [content](m4m.framework.textasset.md#content)
- [defaultAsset](m4m.framework.textasset.md#defaultasset)
- [ClassName](m4m.framework.textasset.md#classname)

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

[framework/asset/resource/textasset.ts:108](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/textasset.ts#L108)

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

[framework/asset/resource/textasset.ts:87](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/textasset.ts#L87)

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

[framework/asset/resource/textasset.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/textasset.ts#L54)

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

[framework/asset/resource/textasset.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/textasset.ts#L43)

___

### unuse

▸ **unuse**(): `void`

**`language`** zh_CN

**`classdesc`**
引用计数减一

**`version`** m4m 1.0

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[unuse](../interfaces/m4m.framework.IAsset.md#unuse)

#### Defined in

[framework/asset/resource/textasset.ts:76](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/textasset.ts#L76)

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

[framework/asset/resource/textasset.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/textasset.ts#L65)

## Constructors

### constructor

• **new textasset**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/asset/resource/textasset.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/textasset.ts#L28)

## Properties

### content

• **content**: `string`

**`language`** zh_CN

**`classdesc`**
文本内容

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/textasset.ts:99](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/textasset.ts#L99)

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

[framework/asset/resource/textasset.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/textasset.ts#L27)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"textasset"`

#### Defined in

[framework/asset/resource/textasset.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/textasset.ts#L15)
