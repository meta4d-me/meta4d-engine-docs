[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / gltf

# Class: gltf

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).gltf

**`language`** zh_CN

**`classdesc`**
json资源

**`version`** m4m 1.0

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Properties

- [buffers](m4m.framework.gltf.md#buffers)
- [data](m4m.framework.gltf.md#data)
- [defaultAsset](m4m.framework.gltf.md#defaultasset)
- [ClassName](m4m.framework.gltf.md#classname)

### Methods

- [caclByteLength](m4m.framework.gltf.md#caclbytelength)
- [dispose](m4m.framework.gltf.md#dispose)
- [getGUID](m4m.framework.gltf.md#getguid)
- [getName](m4m.framework.gltf.md#getname)
- [hexToRgb](m4m.framework.gltf.md#hextorgb)
- [load](m4m.framework.gltf.md#load)
- [unuse](m4m.framework.gltf.md#unuse)
- [use](m4m.framework.gltf.md#use)

### Constructors

- [constructor](m4m.framework.gltf.md#constructor)

### Accessors

- [realName](m4m.framework.gltf.md#realname)

## Properties

### buffers

• **buffers**: [`bin`](m4m.framework.bin.md)[]

#### Defined in

[framework/asset/resource/gltf.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L122)

___

### data

• **data**: `any`

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

[framework/asset/resource/gltf.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L25)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"json"`

#### Defined in

[framework/asset/resource/gltf.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L13)

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

[framework/asset/resource/gltf.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L90)

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

[framework/asset/resource/gltf.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L80)

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

[framework/asset/resource/gltf.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L50)

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

[framework/asset/resource/gltf.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L39)

___

### hexToRgb

▸ **hexToRgb**(`hex`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `hex` | `any` |

#### Returns

`any`

#### Defined in

[framework/asset/resource/gltf.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L116)

___

### load

▸ **load**(`mgr`, `ctx`, `folder`, `brdf`, `env`, `irrSH`, `exposure?`, `specFactor?`, `irrFactor?`, `uvChecker?`): `Promise`<[`transform`](m4m.framework.transform.md)\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `mgr` | [`assetMgr`](m4m.framework.assetMgr.md) | `undefined` |
| `ctx` | `WebGLRenderingContext` | `undefined` |
| `folder` | `string` | `undefined` |
| `brdf` | [`texture`](m4m.framework.texture.md) | `undefined` |
| `env` | [`texture`](m4m.framework.texture.md) | `undefined` |
| `irrSH` | [`texture`](m4m.framework.texture.md) | `undefined` |
| `exposure?` | `any` | `undefined` |
| `specFactor` | `number` | `1` |
| `irrFactor` | `number` | `1` |
| `uvChecker?` | [`texture`](m4m.framework.texture.md) | `undefined` |

#### Returns

`Promise`<[`transform`](m4m.framework.transform.md)\>

#### Defined in

[framework/asset/resource/gltf.ts:123](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L123)

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

[framework/asset/resource/gltf.ts:70](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L70)

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

[framework/asset/resource/gltf.ts:60](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L60)

## Constructors

### constructor

• **new gltf**(`assetName?`, `data`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |
| `data` | `any` | `undefined` |

#### Defined in

[framework/asset/resource/gltf.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L26)

## Accessors

### realName

• `get` **realName**(): `string`

**`language`** zh_CN

**`classdesc`**
如果是imgdesc加载来的图片，通过这个可以获取到真实的图片名字

**`version`** m4m 1.0

#### Returns

`string`

#### Defined in

[framework/asset/resource/gltf.ts:102](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L102)

• `set` **realName**(`name`): `void`

**`language`** zh_CN

**`classdesc`**
设置图片名称

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`void`

#### Defined in

[framework/asset/resource/gltf.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L112)
