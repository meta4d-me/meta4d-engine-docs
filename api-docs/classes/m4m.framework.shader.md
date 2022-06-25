[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / shader

# Class: shader

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).shader

**`language`** zh_CN

**`classdesc`**
shader资源

**`version`** m4m 1.0

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Methods

- [\_parseProperties](m4m.framework.shader.md#_parseproperties)
- [caclByteLength](m4m.framework.shader.md#caclbytelength)
- [dispose](m4m.framework.shader.md#dispose)
- [fillUnDefUniform](m4m.framework.shader.md#fillundefuniform)
- [getGUID](m4m.framework.shader.md#getguid)
- [getName](m4m.framework.shader.md#getname)
- [parse](m4m.framework.shader.md#parse)
- [unuse](m4m.framework.shader.md#unuse)
- [use](m4m.framework.shader.md#use)

### Constructors

- [constructor](m4m.framework.shader.md#constructor)

### Properties

- [defaultAsset](m4m.framework.shader.md#defaultasset)
- [layer](m4m.framework.shader.md#layer)
- [passes](m4m.framework.shader.md#passes)
- [ClassName](m4m.framework.shader.md#classname)

## Methods

### \_parseProperties

▸ **_parseProperties**(`assetmgr`, `properties`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `properties` | `any` |

#### Returns

`void`

#### Defined in

[framework/asset/resource/shader.ts:190](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L190)

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

[framework/asset/resource/shader.ts:105](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L105)

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

[framework/asset/resource/shader.ts:87](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L87)

___

### fillUnDefUniform

▸ **fillUnDefUniform**(`pass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pass` | `glDrawPass` |

#### Returns

`void`

#### Defined in

[framework/asset/resource/shader.ts:333](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L333)

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

[framework/asset/resource/shader.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L54)

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

[framework/asset/resource/shader.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L43)

___

### parse

▸ **parse**(`assetmgr`, `json`): `void`

**`language`** zh_CN

**`classdesc`**
解析资源

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `json` | `any` |

#### Returns

`void`

#### Defined in

[framework/asset/resource/shader.ts:138](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L138)

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

[framework/asset/resource/shader.ts:76](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L76)

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

[framework/asset/resource/shader.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L65)

## Constructors

### constructor

• **new shader**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/asset/resource/shader.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L28)

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

[framework/asset/resource/shader.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L27)

___

### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Common`

**`language`** zh_CN

**`classdesc`**
设置渲染的层级

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/shader.ts:125](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L125)

___

### passes

• **passes**: `Object` = `{}`

#### Index signature

▪ [id: `string`]: `m4m.render.glDrawPass`[]

#### Defined in

[framework/asset/resource/shader.ts:110](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L110)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"shader"`

#### Defined in

[framework/asset/resource/shader.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/shader.ts#L15)
