# m4m.framework.bin

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / bin

## Class: bin

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).bin

**`language`** zh\_CN

**`classdesc`** json资源

**`version`** m4m 1.0

### Implements

* [`IAsset`](../interfaces/m4m.framework.IAsset.md)

### Table of contents

#### Methods

* [caclByteLength](m4m.framework.bin.md#caclbytelength)
* [dispose](m4m.framework.bin.md#dispose)
* [getGUID](m4m.framework.bin.md#getguid)
* [getName](m4m.framework.bin.md#getname)
* [unuse](m4m.framework.bin.md#unuse)
* [use](m4m.framework.bin.md#use)

#### Constructors

* [constructor](m4m.framework.bin.md#constructor)

#### Properties

* [data](m4m.framework.bin.md#data)
* [defaultAsset](m4m.framework.bin.md#defaultasset)
* [ClassName](m4m.framework.bin.md#classname)

#### Accessors

* [realName](m4m.framework.bin.md#realname)

### Methods

#### caclByteLength

▸ **caclByteLength**(): `number`

**`language`** zh\_CN

**`classdesc`** 计算资源字节大小

**`version`** m4m 1.0

**Returns**

`number`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[caclByteLength](../interfaces/m4m.framework.IAsset.md#caclbytelength)

**Defined in**

[framework/asset/resource/bin.ts:99](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L99)

***

#### dispose

▸ **dispose**(): `void`

**`language`** zh\_CN

**`classdesc`** 释放资源

**`version`** m4m 1.0

**Returns**

`void`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[dispose](../interfaces/m4m.framework.IAsset.md#dispose)

**Defined in**

[framework/asset/resource/bin.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L88)

***

#### getGUID

▸ **getGUID**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取资源唯一id

**`version`** m4m 1.0

**Returns**

`number`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[getGUID](../interfaces/m4m.framework.IAsset.md#getguid)

**Defined in**

[framework/asset/resource/bin.ts:55](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L55)

***

#### getName

▸ **getName**(): `string`

**`language`** zh\_CN

**`classdesc`** 获取资源名称

**`version`** m4m 1.0

**Returns**

`string`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[getName](../interfaces/m4m.framework.IAsset.md#getname)

**Defined in**

[framework/asset/resource/bin.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L43)

***

#### unuse

▸ **unuse**(`disposeNow?`): `void`

**`language`** zh\_CN

**`classdesc`** 引用计数减一

**`version`** m4m 1.0

**Parameters**

| Name         | Type      | Default value |
| ------------ | --------- | ------------- |
| `disposeNow` | `boolean` | `false`       |

**Returns**

`void`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[unuse](../interfaces/m4m.framework.IAsset.md#unuse)

**Defined in**

[framework/asset/resource/bin.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L77)

***

#### use

▸ **use**(): `void`

**`language`** zh\_CN

**`classdesc`** 引用计数加一

**`version`** m4m 1.0

**Returns**

`void`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[use](../interfaces/m4m.framework.IAsset.md#use)

**Defined in**

[framework/asset/resource/bin.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L66)

### Constructors

#### constructor

• **new bin**(`assetName?`, `data`)

**Parameters**

| Name        | Type          | Default value |
| ----------- | ------------- | ------------- |
| `assetName` | `string`      | `null`        |
| `data`      | `ArrayBuffer` | `undefined`   |

**Defined in**

[framework/asset/resource/bin.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L28)

### Properties

#### data

• **data**: `ArrayBuffer`

***

#### defaultAsset

• **defaultAsset**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 是否为默认资源

**`version`** m4m 1.0

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

**Defined in**

[framework/asset/resource/bin.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L27)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"json"`

**Defined in**

[framework/asset/resource/bin.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L15)

### Accessors

#### realName

• `get` **realName**(): `string`

**`language`** zh\_CN

**`classdesc`** 如果是imgdesc加载来的图片，通过这个可以获取到真实的图片名字

**`version`** m4m 1.0

**Returns**

`string`

**Defined in**

[framework/asset/resource/bin.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L112)

• `set` **realName**(`name`): `void`

**`language`** zh\_CN

**`classdesc`** 设置图片名称

**`version`** m4m 1.0

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

`void`

**Defined in**

[framework/asset/resource/bin.ts:123](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/bin.ts#L123)
