# m4m.framework.material

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / material

## Class: material

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).material

**`language`** zh\_CN

**`classdesc`** 材质资源

**`param`** buffer数组

**`version`** m4m 1.0

### Implements

* [`IAsset`](../interfaces/m4m.framework.IAsset.md)

### Table of contents

#### Methods

* [Parse](m4m.framework.material.md#parse)
* [caclByteLength](m4m.framework.material.md#caclbytelength)
* [clone](m4m.framework.material.md#clone)
* [dispose](m4m.framework.material.md#dispose)
* [draw](m4m.framework.material.md#draw)
* [getGUID](m4m.framework.material.md#getguid)
* [getLayer](m4m.framework.material.md#getlayer)
* [getName](m4m.framework.material.md#getname)
* [getQueue](m4m.framework.material.md#getqueue)
* [getShader](m4m.framework.material.md#getshader)
* [save](m4m.framework.material.md#save)
* [setCubeTexture](m4m.framework.material.md#setcubetexture)
* [setQueue](m4m.framework.material.md#setqueue)
* [setShader](m4m.framework.material.md#setshader)
* [unuse](m4m.framework.material.md#unuse)
* [uploadInstanceAtteribute](m4m.framework.material.md#uploadinstanceatteribute)
* [uploadUnifoms](m4m.framework.material.md#uploadunifoms)
* [use](m4m.framework.material.md#use)

#### Constructors

* [constructor](m4m.framework.material.md#constructor)

#### Properties

* [defaultAsset](m4m.framework.material.md#defaultasset)
* [gpuInstancingGUID](m4m.framework.material.md#gpuinstancingguid)
* [instanceAttribValMap](m4m.framework.material.md#instanceattribvalmap)
* [statedMapUniforms](m4m.framework.material.md#statedmapuniforms)
* [ClassName](m4m.framework.material.md#classname)

#### Accessors

* [enableGpuInstancing](m4m.framework.material.md#enablegpuinstancing)

### Methods

#### Parse

▸ **Parse**(`assetmgr`, `json`, `bundleName?`): [`material`](m4m.framework.material.md)

**`language`** zh\_CN

**`classdesc`** 解析资源

**`version`** m4m 1.0

**Parameters**

| Name         | Type                                    | Default value | Description |
| ------------ | --------------------------------------- | ------------- | ----------- |
| `assetmgr`   | [`assetMgr`](m4m.framework.assetMgr.md) | `undefined`   | 资源管理实例      |
| `json`       | `any`                                   | `undefined`   | json数据      |
| `bundleName` | `string`                                | `null`        | -           |

**Returns**

[`material`](m4m.framework.material.md)

**Defined in**

[framework/asset/resource/material.ts:724](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L724)

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

[framework/asset/resource/material.ts:176](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L176)

***

#### clone

▸ **clone**(): [`material`](m4m.framework.material.md)

**`language`** zh\_CN

**`classdesc`** 克隆

**`version`** m4m 1.0

**Returns**

[`material`](m4m.framework.material.md)

**Defined in**

[framework/asset/resource/material.ts:794](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L794)

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

[framework/asset/resource/material.ts:136](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L136)

***

#### draw

▸ **draw**(`context`, `mesh`, `sm`, `basetype?`, `drawInstanceInfo?`): `void`

**`language`** zh\_CN

**`classdesc`** 绘制

**`version`** m4m 1.0

**Parameters**

| Name               | Type                                                                  | Default value | Description  |
| ------------------ | --------------------------------------------------------------------- | ------------- | ------------ |
| `context`          | `renderContext`                                                       | `undefined`   | 渲染上下文        |
| `mesh`             | [`mesh`](m4m.framework.mesh.md)                                       | `undefined`   | 渲染的mesh      |
| `sm`               | `subMeshInfo`                                                         | `undefined`   | 渲染的submesh信息 |
| `basetype`         | `string`                                                              | `"base"`      | -            |
| `drawInstanceInfo` | [`DrawInstanceInfo`](../interfaces/m4m.framework.DrawInstanceInfo.md) | `undefined`   | -            |

**Returns**

`void`

**Defined in**

[framework/asset/resource/material.ts:659](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L659)

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

[framework/asset/resource/material.ts:125](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L125)

***

#### getLayer

▸ **getLayer**(): [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md)

**`language`** zh\_CN

**`classdesc`** 获取shader的layer

**`version`** m4m 1.0

**Returns**

[`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md)

**Defined in**

[framework/asset/resource/material.ts:385](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L385)

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

[framework/asset/resource/material.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L112)

***

#### getQueue

▸ **getQueue**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取shader的queue

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/asset/resource/material.ts:396](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L396)

***

#### getShader

▸ **getShader**(): [`shader`](m4m.framework.shader.md)

**`language`** zh\_CN

**`classdesc`** 获取shader

**`version`** m4m 1.0

**Returns**

[`shader`](m4m.framework.shader.md)

**Defined in**

[framework/asset/resource/material.ts:409](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L409)

***

#### save

▸ **save**(): `string`

**Returns**

`string`

**Defined in**

[framework/asset/resource/material.ts:836](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L836)

***

#### setCubeTexture

▸ **setCubeTexture**(`_id`, `_texture`): `void`

**Parameters**

| Name       | Type                                  |
| ---------- | ------------------------------------- |
| `_id`      | `string`                              |
| `_texture` | [`texture`](m4m.framework.texture.md) |

**Returns**

`void`

**Defined in**

[framework/asset/resource/material.ts:619](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L619)

***

#### setQueue

▸ **setQueue**(`queue`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `queue` | `number` |

**Returns**

`void`

**Defined in**

[framework/asset/resource/material.ts:399](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L399)

***

#### setShader

▸ **setShader**(`shader`): `void`

**`language`** zh\_CN

**`classdesc`** 设置shader 不保留原有数据

**`version`** m4m 1.0

**Parameters**

| Name     | Type                                | Description |
| -------- | ----------------------------------- | ----------- |
| `shader` | [`shader`](m4m.framework.shader.md) | shader实例    |

**Returns**

`void`

**Defined in**

[framework/asset/resource/material.ts:339](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L339)

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

[framework/asset/resource/material.ts:165](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L165)

***

#### uploadInstanceAtteribute

▸ **uploadInstanceAtteribute**(`pass`, `darr`): `void`

上传InstanceAtteribute 数据

**Parameters**

| Name   | Type                                                   | Description |
| ------ | ------------------------------------------------------ | ----------- |
| `pass` | `glDrawPass`                                           | 绘制通道        |
| `darr` | [`ExtenArray`](m4m.math.ExtenArray.md)<`Float32Array`> | 数组对象        |

**Returns**

`void`

**Defined in**

[framework/asset/resource/material.ts:295](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L295)

***

#### uploadUnifoms

▸ **uploadUnifoms**(`pass`, `context`, `lastMatSame?`): `void`

**Parameters**

| Name          | Type            | Default value |
| ------------- | --------------- | ------------- |
| `pass`        | `glDrawPass`    | `undefined`   |
| `context`     | `renderContext` | `undefined`   |
| `lastMatSame` | `boolean`       | `false`       |

**Returns**

`void`

**Defined in**

[framework/asset/resource/material.ts:234](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L234)

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

[framework/asset/resource/material.ts:155](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L155)

### Constructors

#### constructor

• **new material**(`assetName?`)

**Parameters**

| Name        | Type     | Default value |
| ----------- | -------- | ------------- |
| `assetName` | `string` | `null`        |

**Defined in**

[framework/asset/resource/material.ts:96](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L96)

### Properties

#### defaultAsset

• **defaultAsset**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 是否为默认资源

**`version`** m4m 1.0

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

**Defined in**

[framework/asset/resource/material.ts:73](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L73)

***

#### gpuInstancingGUID

• **gpuInstancingGUID**: `string` = `""`

gpuInstancing 材质唯一ID

**Defined in**

[framework/asset/resource/material.ts:94](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L94)

***

#### instanceAttribValMap

• **instanceAttribValMap**: `Object` = `{}`

**Index signature**

▪ \[id: `string`]: `number`\[]

**Defined in**

[framework/asset/resource/material.ts:270](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L270)

***

#### statedMapUniforms

• **statedMapUniforms**: `Object` = `{}`

**Index signature**

▪ \[id: `string`]: `any`

**Defined in**

[framework/asset/resource/material.ts:421](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L421)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"material"`

**Defined in**

[framework/asset/resource/material.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L61)

### Accessors

#### enableGpuInstancing

• `get` **enableGpuInstancing**(): `boolean`

**Returns**

`boolean`

**Defined in**

[framework/asset/resource/material.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L80)

• `set` **enableGpuInstancing**(`enable`): `void`

**Parameters**

| Name     | Type      |
| -------- | --------- |
| `enable` | `boolean` |

**Returns**

`void`

**Defined in**

[framework/asset/resource/material.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L81)
