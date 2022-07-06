# m4m.framework.meshRenderer

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / meshRenderer

## Class: meshRenderer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).meshRenderer

**`language`** zh\_CN

**`classdesc`** mesh的渲染组件

**`version`** m4m 1.0

### Implements

* [`IRendererGpuIns`](../interfaces/m4m.framework.IRendererGpuIns.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.meshRenderer.md#constructor)

#### Accessors

* [filter](m4m.framework.meshRenderer.md#filter)
* [queue](m4m.framework.meshRenderer.md#queue)
* [renderLayer](m4m.framework.meshRenderer.md#renderlayer)

#### Properties

* [gameObject](m4m.framework.meshRenderer.md#gameobject)
* [layer](m4m.framework.meshRenderer.md#layer)
* [materials](m4m.framework.meshRenderer.md#materials)
* [ClassName](m4m.framework.meshRenderer.md#classname)

#### Methods

* [isGpuInstancing](m4m.framework.meshRenderer.md#isgpuinstancing)
* [onPlay](m4m.framework.meshRenderer.md#onplay)
* [refreshLayerAndQue](m4m.framework.meshRenderer.md#refreshlayerandque)
* [render](m4m.framework.meshRenderer.md#render)
* [start](m4m.framework.meshRenderer.md#start)
* [update](m4m.framework.meshRenderer.md#update)
* [GpuInstancingRender](m4m.framework.meshRenderer.md#gpuinstancingrender)
* [GpuInstancingRenderBatcher](m4m.framework.meshRenderer.md#gpuinstancingrenderbatcher)
* [instanceDrawType](m4m.framework.meshRenderer.md#instancedrawtype)
* [setInstanceOffsetMatrix](m4m.framework.meshRenderer.md#setinstanceoffsetmatrix)

### Constructors

#### constructor

• **new meshRenderer**()

**Defined in**

[framework/component/meshrenderer.ts:175](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L175)

### Accessors

#### filter

• `get` **filter**(): [`meshFilter`](m4m.framework.meshFilter.md)

渲染使用 meshFilter

**Returns**

[`meshFilter`](m4m.framework.meshFilter.md)

**Defined in**

[framework/component/meshrenderer.ts:261](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L261)

• `set` **filter**(`val`): `void`

渲染使用 meshFilter

**Parameters**

| Name  | Type                                        |
| ----- | ------------------------------------------- |
| `val` | [`meshFilter`](m4m.framework.meshFilter.md) |

**Returns**

`void`

**Defined in**

[framework/component/meshrenderer.ts:267](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L267)

***

#### queue

• `get` **queue**(): `number`

**`language`** zh\_CN

**`classdesc`** 返回此组件的场景渲染层级排序依据queue大小

**`version`** m4m 1.0

**Returns**

`number`

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[queue](../interfaces/m4m.framework.IRendererGpuIns.md#queue)

**Defined in**

[framework/component/meshrenderer.ts:248](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L248)

• `set` **queue**(`value`): `void`

**`language`** zh\_CN

**`classdesc`** 返回此组件的场景渲染层级排序依据queue大小

**`version`** m4m 1.0

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `value` | `number` |

**Returns**

`void`

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[queue](../interfaces/m4m.framework.IRendererGpuIns.md#queue)

**Defined in**

[framework/component/meshrenderer.ts:251](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L251)

***

#### renderLayer

• `get` **renderLayer**(): `number`

**`language`** zh\_CN

**`classdesc`** 渲染mask层级（和相机相对应）

**`version`** m4m 1.0

**Returns**

`number`

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[renderLayer](../interfaces/m4m.framework.IRendererGpuIns.md#renderlayer)

**Defined in**

[framework/component/meshrenderer.ts:232](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L232)

• `set` **renderLayer**(`layer`): `void`

**`language`** zh\_CN

**`classdesc`** 渲染mask层级（和相机相对应）

**`version`** m4m 1.0

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `layer` | `number` |

**Returns**

`void`

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[renderLayer](../interfaces/m4m.framework.IRendererGpuIns.md#renderlayer)

**Defined in**

[framework/component/meshrenderer.ts:233](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L233)

### Properties

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh\_CN

**`classdesc`** 挂载的gameobject

**`version`** m4m 1.0

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[gameObject](../interfaces/m4m.framework.IRendererGpuIns.md#gameobject)

**Defined in**

[framework/component/meshrenderer.ts:185](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L185)

***

#### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Common`

**`language`** zh\_CN

**`classdesc`** 场景渲染层级（common、transparent、overlay）

**`version`** m4m 1.0

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[layer](../interfaces/m4m.framework.IRendererGpuIns.md#layer)

**Defined in**

[framework/component/meshrenderer.ts:222](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L222)

***

#### materials

• **materials**: [`material`](m4m.framework.material.md)\[] = `[]`

**`language`** zh\_CN

**`classdesc`** mesh的材质数组

**`version`** m4m 1.0

**Defined in**

[framework/component/meshrenderer.ts:195](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L195)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"meshRenderer"`

**Defined in**

[framework/component/meshrenderer.ts:173](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L173)

### Methods

#### isGpuInstancing

▸ **isGpuInstancing**(): `boolean`

是否开启 GPU Instancing 绘制

**Returns**

`boolean`

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[isGpuInstancing](../interfaces/m4m.framework.IRendererGpuIns.md#isgpuinstancing)

**Defined in**

[framework/component/meshrenderer.ts:520](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L520)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[onPlay](../interfaces/m4m.framework.IRendererGpuIns.md#onplay)

**Defined in**

[framework/component/meshrenderer.ts:285](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L285)

***

#### refreshLayerAndQue

▸ **refreshLayerAndQue**(): `void`

刷新 渲染layer 和 渲染 queueId （切换了材质时需要手动刷新） \*优化了自动处理的消耗

**Returns**

`void`

**Defined in**

[framework/component/meshrenderer.ts:293](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L293)

***

#### render

▸ **render**(`context`, `assetmgr`, `camera`): `void`

**Parameters**

| Name       | Type                                    |
| ---------- | --------------------------------------- |
| `context`  | `renderContext`                         |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `camera`   | [`camera`](m4m.framework.camera.md)     |

**Returns**

`void`

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[render](../interfaces/m4m.framework.IRendererGpuIns.md#render)

**Defined in**

[framework/component/meshrenderer.ts:311](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L311)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[start](../interfaces/m4m.framework.IRendererGpuIns.md#start)

**Defined in**

[framework/component/meshrenderer.ts:277](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L277)

***

#### update

▸ **update**(`delta`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Implementation of**

[IRendererGpuIns](../interfaces/m4m.framework.IRendererGpuIns.md).[update](../interfaces/m4m.framework.IRendererGpuIns.md#update)

**Defined in**

[framework/component/meshrenderer.ts:308](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L308)

***

#### GpuInstancingRender

▸ `Static` **GpuInstancingRender**(`context`, `instanceArray`, `cacheBuffer?`): `void`

**Parameters**

| Name            | Type                                                                                                        |
| --------------- | ----------------------------------------------------------------------------------------------------------- |
| `context`       | `renderContext`                                                                                             |
| `instanceArray` | [`ReuseArray`](m4m.math.ReuseArray.md)<[`IRendererGpuIns`](../interfaces/m4m.framework.IRendererGpuIns.md)> |
| `cacheBuffer?`  | `Float32Array`                                                                                              |

**Returns**

`void`

**Defined in**

[framework/component/meshrenderer.ts:391](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L391)

***

#### GpuInstancingRenderBatcher

▸ `Static` **GpuInstancingRenderBatcher**(`context`, `batcher`): `void`

**Parameters**

| Name      | Type                                                      |
| --------- | --------------------------------------------------------- |
| `context` | `renderContext`                                           |
| `batcher` | [`meshGpuInsBatcher`](m4m.framework.meshGpuInsBatcher.md) |

**Returns**

`void`

**Defined in**

[framework/component/meshrenderer.ts:436](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L436)

***

#### instanceDrawType

▸ `Static` **instanceDrawType**(): `string`

**Returns**

`string`

**Defined in**

[framework/component/meshrenderer.ts:499](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L499)

***

#### setInstanceOffsetMatrix

▸ `Static` **setInstanceOffsetMatrix**(`tran`, `mat`, `pass`): `void`

设置 OffsetMatrix

**Parameters**

| Name   | Type                                      | Description |
| ------ | ----------------------------------------- | ----------- |
| `tran` | [`transform`](m4m.framework.transform.md) | transform   |
| `mat`  | [`material`](m4m.framework.material.md)   | 材质对象        |
| `pass` | `glDrawPass`                              | 绘制通道对象      |

**Returns**

`void`

**Defined in**

[framework/component/meshrenderer.ts:479](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L479)
