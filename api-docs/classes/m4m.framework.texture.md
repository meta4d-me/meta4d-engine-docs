# m4m.framework.texture

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / texture

## Class: texture

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).texture

**`language`** zh\_CN

**`classdesc`** texture资源

**`version`** m4m 1.0

### Implements

* [`IAsset`](../interfaces/m4m.framework.IAsset.md)

### Table of contents

#### Methods

* [caclByteLength](m4m.framework.texture.md#caclbytelength)
* [dispose](m4m.framework.texture.md#dispose)
* [getGUID](m4m.framework.texture.md#getguid)
* [getName](m4m.framework.texture.md#getname)
* [unuse](m4m.framework.texture.md#unuse)
* [use](m4m.framework.texture.md#use)

#### Constructors

* [constructor](m4m.framework.texture.md#constructor)

#### Properties

* [defaultAsset](m4m.framework.texture.md#defaultasset)
* [ClassName](m4m.framework.texture.md#classname)

#### Accessors

* [realName](m4m.framework.texture.md#realname)

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

[framework/asset/resource/texture.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L106)

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

[framework/asset/resource/texture.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L88)

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

[framework/asset/resource/texture.ts:55](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L55)

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

[framework/asset/resource/texture.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L43)

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

[framework/asset/resource/texture.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L77)

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

[framework/asset/resource/texture.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L66)

### Constructors

#### constructor

• **new texture**(`assetName?`)

**Parameters**

| Name        | Type     | Default value |
| ----------- | -------- | ------------- |
| `assetName` | `string` | `null`        |

**Defined in**

[framework/asset/resource/texture.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L28)

### Properties

#### defaultAsset

• **defaultAsset**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 是否为默认资源

**`version`** m4m 1.0

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

**Defined in**

[framework/asset/resource/texture.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L27)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"texture"`

**Defined in**

[framework/asset/resource/texture.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L15)

### Accessors

#### realName

• `get` **realName**(): `string`

**`language`** zh\_CN

**`classdesc`** 如果是imgdesc加载来的图片，通过这个可以获取到真实的图片名字

**`version`** m4m 1.0

**Returns**

`string`

**Defined in**

[framework/asset/resource/texture.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L122)

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

[framework/asset/resource/texture.ts:133](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/texture.ts#L133)
