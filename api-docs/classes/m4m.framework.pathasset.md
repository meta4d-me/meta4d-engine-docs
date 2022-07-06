# m4m.framework.pathasset

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / pathasset

## Class: pathasset

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).pathasset

**`language`** zh\_CN

**`classdesc`** 路径编辑资源

**`version`** m4m 1.0

### Implements

* [`IAsset`](../interfaces/m4m.framework.IAsset.md)

### Table of contents

#### Methods

* [Parse](m4m.framework.pathasset.md#parse)
* [caclByteLength](m4m.framework.pathasset.md#caclbytelength)
* [dispose](m4m.framework.pathasset.md#dispose)
* [getGUID](m4m.framework.pathasset.md#getguid)
* [getName](m4m.framework.pathasset.md#getname)
* [unuse](m4m.framework.pathasset.md#unuse)
* [use](m4m.framework.pathasset.md#use)

#### Constructors

* [constructor](m4m.framework.pathasset.md#constructor)

#### Properties

* [defaultAsset](m4m.framework.pathasset.md#defaultasset)
* [paths](m4m.framework.pathasset.md#paths)
* [ClassName](m4m.framework.pathasset.md#classname)

### Methods

#### Parse

▸ **Parse**(`json`): [`pathasset`](m4m.framework.pathasset.md)

**`language`** zh\_CN

**`classdesc`** 解析资源

**`version`** m4m 1.0

**Parameters**

| Name   | Type   | Description |
| ------ | ------ | ----------- |
| `json` | `JSON` | json数据      |

**Returns**

[`pathasset`](m4m.framework.pathasset.md)

**Defined in**

[framework/asset/resource/pathasset.ts:127](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L127)

***

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

[framework/asset/resource/pathasset.ts:99](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L99)

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

[framework/asset/resource/pathasset.ts:87](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L87)

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

[framework/asset/resource/pathasset.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L54)

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

[framework/asset/resource/pathasset.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L43)

***

#### unuse

▸ **unuse**(): `void`

**`language`** zh\_CN

**`classdesc`** 引用计数减一

**`version`** m4m 1.0

**Returns**

`void`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[unuse](../interfaces/m4m.framework.IAsset.md#unuse)

**Defined in**

[framework/asset/resource/pathasset.ts:76](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L76)

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

[framework/asset/resource/pathasset.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L65)

### Constructors

#### constructor

• **new pathasset**(`assetName?`)

**Parameters**

| Name        | Type     | Default value |
| ----------- | -------- | ------------- |
| `assetName` | `string` | `null`        |

**Defined in**

[framework/asset/resource/pathasset.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L28)

### Properties

#### defaultAsset

• **defaultAsset**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 是否为默认资源

**`version`** m4m 1.0

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

**Defined in**

[framework/asset/resource/pathasset.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L27)

***

#### paths

• **paths**: `vector3`\[] = `[]`

**`language`** zh\_CN

**`classdesc`** 路径节点数据

**`version`** m4m 1.0

**Defined in**

[framework/asset/resource/pathasset.ts:115](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L115)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"pathasset"`

**Defined in**

[framework/asset/resource/pathasset.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/pathasset.ts#L15)
