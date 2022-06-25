[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / trailRender

# Class: trailRender

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).trailRender

**`language`** zh_CN

**`classdesc`**
拖尾组件

**`version`** m4m 1.0

## Implements

- [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)

## Table of contents

### Accessors

- [color](m4m.framework.trailRender.md#color)
- [material](m4m.framework.trailRender.md#material)
- [renderLayer](m4m.framework.trailRender.md#renderlayer)

### Constructors

- [constructor](m4m.framework.trailRender.md#constructor)

### Properties

- [extenedOneSide](m4m.framework.trailRender.md#extenedoneside)
- [gameObject](m4m.framework.trailRender.md#gameobject)
- [isAlphaGradual](m4m.framework.trailRender.md#isalphagradual)
- [layer](m4m.framework.trailRender.md#layer)
- [lookAtCamera](m4m.framework.trailRender.md#lookatcamera)
- [queue](m4m.framework.trailRender.md#queue)
- [ClassName](m4m.framework.trailRender.md#classname)

### Methods

- [onPlay](m4m.framework.trailRender.md#onplay)
- [play](m4m.framework.trailRender.md#play)
- [render](m4m.framework.trailRender.md#render)
- [setWidth](m4m.framework.trailRender.md#setwidth)
- [setspeed](m4m.framework.trailRender.md#setspeed)
- [start](m4m.framework.trailRender.md#start)
- [stop](m4m.framework.trailRender.md#stop)
- [update](m4m.framework.trailRender.md#update)

## Accessors

### color

• `get` **color**(): `color`

**`language`** zh_CN

**`classdesc`**
 返回 matrial调色

**`version`** m4m 1.0

#### Returns

`color`

#### Defined in

[framework/component/trailrender.ts:208](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L208)

• `set` **color**(`color`): `void`

**`language`** zh_CN

**`classdesc`**
设置 matrial颜色

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `color` | `color` |

#### Returns

`void`

#### Defined in

[framework/component/trailrender.ts:223](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L223)

___

### material

• `get` **material**(): [`material`](m4m.framework.material.md)

**`language`** zh_CN

**`classdesc`**
得到拖尾上的材质

**`version`** m4m 1.0

#### Returns

[`material`](m4m.framework.material.md)

#### Defined in

[framework/component/trailrender.ts:187](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L187)

• `set` **material**(`material`): `void`

**`language`** zh_CN

**`classdesc`**
设置拖尾的材质

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `material` | [`material`](m4m.framework.material.md) | 材质 |

#### Returns

`void`

#### Defined in

[framework/component/trailrender.ts:175](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L175)

___

### renderLayer

• `get` **renderLayer**(): `number`

**`language`** zh_CN

**`classdesc`**
渲染mask层级（和相机相对应）

**`version`** m4m 1.0

#### Returns

`number`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

#### Defined in

[framework/component/trailrender.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L32)

• `set` **renderLayer**(`layer`): `void`

**`language`** zh_CN

**`classdesc`**
渲染mask层级（和相机相对应）

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `layer` | `number` |

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

#### Defined in

[framework/component/trailrender.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L33)

## Constructors

### constructor

• **new trailRender**()

## Properties

### extenedOneSide

• **extenedOneSide**: `boolean` = `true`

**`language`** zh_CN

**`classdesc`**
拖尾mesh是否向经过路径的单边延展

**`version`** m4m 1.0

#### Defined in

[framework/component/trailrender.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L88)

___

### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh_CN

**`classdesc`**
挂载的gameobject

**`version`** m4m 1.0

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[gameObject](../interfaces/m4m.framework.IRenderer.md#gameobject)

#### Defined in

[framework/component/trailrender.ts:164](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L164)

___

### isAlphaGradual

• **isAlphaGradual**: `boolean` = `false`

#### Defined in

[framework/component/trailrender.ts:323](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L323)

___

### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Common`

**`language`** zh_CN

**`classdesc`**
场景渲染层级（common、transparent、overlay）

**`version`** m4m 1.0

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[layer](../interfaces/m4m.framework.IRenderer.md#layer)

#### Defined in

[framework/component/trailrender.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L23)

___

### lookAtCamera

• **lookAtCamera**: `boolean` = `false`

**`language`** zh_CN

**`classdesc`**
拖尾是否朝向相机

**`version`** m4m 1.0

#### Defined in

[framework/component/trailrender.ts:280](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L280)

___

### queue

• **queue**: `number` = `0`

**`language`** zh_CN

**`classdesc`**
同场景渲染层级时候先后排序依据

**`version`** m4m 1.0

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[queue](../interfaces/m4m.framework.IRenderer.md#queue)

#### Defined in

[framework/component/trailrender.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L43)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"trailRender"`

#### Defined in

[framework/component/trailrender.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L14)

## Methods

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[onPlay](../interfaces/m4m.framework.IRenderer.md#onplay)

#### Defined in

[framework/component/trailrender.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L72)

___

### play

▸ **play**(): `void`

**`language`** zh_CN

**`classdesc`**
开始拖尾

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/component/trailrender.ts:256](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L256)

___

### render

▸ **render**(`context`, `assetmgr`, `camera`): `void`

**`language`** zh_CN

**`classdesc`**
render

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | `renderContext` |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `camera` | [`camera`](m4m.framework.camera.md) |

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[render](../interfaces/m4m.framework.IRenderer.md#render)

#### Defined in

[framework/component/trailrender.ts:447](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L447)

___

### setWidth

▸ **setWidth**(`Width`): `void`

**`language`** zh_CN

**`classdesc`**
调节拖尾宽度

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `Width` | `number` |

#### Returns

`void`

#### Defined in

[framework/component/trailrender.ts:245](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L245)

___

### setspeed

▸ **setspeed**(`upspeed`): `void`

**`language`** zh_CN

**`classdesc`**
拖尾速度，调节拖尾长短（0-1）

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `upspeed` | `number` |

#### Returns

`void`

#### Defined in

[framework/component/trailrender.ts:234](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L234)

___

### start

▸ **start**(): `void`

**`language`** zh_CN

**`classdesc`**
start

**`version`** m4m 1.0

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[start](../interfaces/m4m.framework.IRenderer.md#start)

#### Defined in

[framework/component/trailrender.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L65)

___

### stop

▸ **stop**(): `void`

**`language`** zh_CN

**`classdesc`**
关闭拖尾

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/component/trailrender.ts:269](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L269)

___

### update

▸ **update**(`delta`): `void`

**`language`** zh_CN

**`classdesc`**
update

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[update](../interfaces/m4m.framework.IRenderer.md#update)

#### Defined in

[framework/component/trailrender.ts:96](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/trailrender.ts#L96)
