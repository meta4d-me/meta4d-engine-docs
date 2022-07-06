# m4m.framework.ParticleSystemData

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystemData

## Class: ParticleSystemData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystemData

粒子系统数据

### Implements

* [`IAsset`](../interfaces/m4m.framework.IAsset.md)

### Table of contents

#### Methods

* [caclByteLength](m4m.framework.ParticleSystemData.md#caclbytelength)
* [dispose](m4m.framework.ParticleSystemData.md#dispose)
* [getGUID](m4m.framework.ParticleSystemData.md#getguid)
* [getName](m4m.framework.ParticleSystemData.md#getname)
* [setData](m4m.framework.ParticleSystemData.md#setdata)
* [unuse](m4m.framework.ParticleSystemData.md#unuse)
* [use](m4m.framework.ParticleSystemData.md#use)
* [get](m4m.framework.ParticleSystemData.md#get)

#### Constructors

* [constructor](m4m.framework.ParticleSystemData.md#constructor)

#### Properties

* [defaultAsset](m4m.framework.ParticleSystemData.md#defaultasset)
* [objectData](m4m.framework.ParticleSystemData.md#objectdata)
* [particleSystem](m4m.framework.ParticleSystemData.md#particlesystem)
* [ClassName](m4m.framework.ParticleSystemData.md#classname)

#### Accessors

* [value](m4m.framework.ParticleSystemData.md#value)

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

[framework/particlesystem/ParticleSystemData.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L134)

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

[framework/particlesystem/ParticleSystemData.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L101)

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

[framework/particlesystem/ParticleSystemData.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L89)

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

[framework/particlesystem/ParticleSystemData.ts:73](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L73)

***

#### setData

▸ **setData**(`v`): `void`

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `string` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystemData.ts:140](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L140)

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

[framework/particlesystem/ParticleSystemData.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L122)

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

[framework/particlesystem/ParticleSystemData.ts:111](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L111)

***

#### get

▸ `Static` **get**(`valueName`): [`ParticleSystemData`](m4m.framework.ParticleSystemData.md)

获取已经创建了的粒子系统数据

**Parameters**

| Name        | Type     |
| ----------- | -------- |
| `valueName` | `string` |

**Returns**

[`ParticleSystemData`](m4m.framework.ParticleSystemData.md)

**Defined in**

[framework/particlesystem/ParticleSystemData.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L20)

### Constructors

#### constructor

• **new ParticleSystemData**(`assetName?`)

**Parameters**

| Name        | Type     | Default value |
| ----------- | -------- | ------------- |
| `assetName` | `string` | `null`        |

**Defined in**

[framework/particlesystem/ParticleSystemData.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L57)

### Properties

#### defaultAsset

• **defaultAsset**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 是否为默认资源

**`version`** m4m 1.0

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

**Defined in**

[framework/particlesystem/ParticleSystemData.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L35)

***

#### objectData

• **objectData**: `any`

**Defined in**

[framework/particlesystem/ParticleSystemData.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L149)

***

#### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

**Defined in**

[framework/particlesystem/ParticleSystemData.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L13)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"ParticleSystemData"`

**Defined in**

[framework/particlesystem/ParticleSystemData.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L9)

### Accessors

#### value

• `get` **value**(): `string`

粒子系统资源名称

**Returns**

`string`

**Defined in**

[framework/particlesystem/ParticleSystemData.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L41)

• `set` **value**(`v`): `void`

粒子系统资源名称

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `string` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystemData.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystemData.ts#L45)
