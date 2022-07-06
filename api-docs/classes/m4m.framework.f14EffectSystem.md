# m4m.framework.f14EffectSystem

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / f14EffectSystem

## Class: f14EffectSystem

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).f14EffectSystem

### Implements

* [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)

### Table of contents

#### Properties

* [VF](m4m.framework.f14EffectSystem.md#vf)
* [\_root](m4m.framework.f14EffectSystem.md#\_root)
* [beref](m4m.framework.f14EffectSystem.md#beref)
* [data](m4m.framework.f14EffectSystem.md#data)
* [enableDraw](m4m.framework.f14EffectSystem.md#enabledraw)
* [enabletimeFlow](m4m.framework.f14EffectSystem.md#enabletimeflow)
* [gameObject](m4m.framework.f14EffectSystem.md#gameobject)
* [layer](m4m.framework.f14EffectSystem.md#layer)
* [layers](m4m.framework.f14EffectSystem.md#layers)
* [mvpMat](m4m.framework.f14EffectSystem.md#mvpmat)
* [queue](m4m.framework.f14EffectSystem.md#queue)
* [renderBatch](m4m.framework.f14EffectSystem.md#renderbatch)
* [restartFrame](m4m.framework.f14EffectSystem.md#restartframe)
* [totalFrame](m4m.framework.f14EffectSystem.md#totalframe)
* [webgl](m4m.framework.f14EffectSystem.md#webgl)
* [ClassName](m4m.framework.f14EffectSystem.md#classname)

#### Methods

* [changeAlpha](m4m.framework.f14EffectSystem.md#changealpha)
* [changeColor](m4m.framework.f14EffectSystem.md#changecolor)
* [clone](m4m.framework.f14EffectSystem.md#clone)
* [getElementCount](m4m.framework.f14EffectSystem.md#getelementcount)
* [onPlay](m4m.framework.f14EffectSystem.md#onplay)
* [pause](m4m.framework.f14EffectSystem.md#pause)
* [play](m4m.framework.f14EffectSystem.md#play)
* [remove](m4m.framework.f14EffectSystem.md#remove)
* [render](m4m.framework.f14EffectSystem.md#render)
* [reset](m4m.framework.f14EffectSystem.md#reset)
* [setData](m4m.framework.f14EffectSystem.md#setdata)
* [start](m4m.framework.f14EffectSystem.md#start)
* [stop](m4m.framework.f14EffectSystem.md#stop)
* [update](m4m.framework.f14EffectSystem.md#update)

#### Constructors

* [constructor](m4m.framework.f14EffectSystem.md#constructor)

#### Accessors

* [renderCamera](m4m.framework.f14EffectSystem.md#rendercamera)
* [renderLayer](m4m.framework.f14EffectSystem.md#renderlayer)
* [root](m4m.framework.f14EffectSystem.md#root)

### Properties

#### VF

• **VF**: `number`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L38)

***

#### \_root

• **\_root**: [`transform`](m4m.framework.transform.md)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L121)

***

#### beref

• **beref**: `boolean` = `false`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:129](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L129)

***

#### data

• **data**: [`F14EffectData`](m4m.framework.F14EffectData.md)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L35)

***

#### enableDraw

• **enableDraw**: `boolean` = `false`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:350](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L350)

***

#### enabletimeFlow

• **enabletimeFlow**: `boolean` = `false`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:349](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L349)

***

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[gameObject](../interfaces/m4m.framework.IRenderer.md#gameobject)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L31)

***

#### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Transparent`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[layer](../interfaces/m4m.framework.IRenderer.md#layer)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L9)

***

#### layers

• **layers**: [`F14Layer`](m4m.framework.F14Layer.md)\[] = `[]`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L36)

***

#### mvpMat

• **mvpMat**: `matrix`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:243](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L243)

***

#### queue

• **queue**: `number` = `10`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[queue](../interfaces/m4m.framework.IRenderer.md#queue)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L17)

***

#### renderBatch

• **renderBatch**: [`F14Basebatch`](../interfaces/m4m.framework.F14Basebatch.md)\[] = `[]`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:124](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L124)

***

#### restartFrame

• **restartFrame**: `number`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:261](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L261)

***

#### totalFrame

• **totalFrame**: `number` = `0`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:262](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L262)

***

#### webgl

• **webgl**: `WebGLRenderingContext`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L39)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"f14EffectSystem"`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L7)

### Methods

#### changeAlpha

▸ **changeAlpha**(`newAlpha`): `void`

**Parameters**

| Name       | Type     |
| ---------- | -------- |
| `newAlpha` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:405](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L405)

***

#### changeColor

▸ **changeColor**(`newcolor`): `void`

**Parameters**

| Name       | Type    |
| ---------- | ------- |
| `newcolor` | `color` |

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:397](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L397)

***

#### clone

▸ **clone**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[clone](../interfaces/m4m.framework.IRenderer.md#clone)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:421](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L421)

***

#### getElementCount

▸ **getElementCount**(): `number`

**Returns**

`number`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:331](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L331)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[onPlay](../interfaces/m4m.framework.IRenderer.md#onplay)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L26)

***

#### pause

▸ **pause**(): `void`

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:385](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L385)

***

#### play

▸ **play**(`onFinish?`, `PlayRate?`): `void`

**Parameters**

| Name       | Type         | Default value |
| ---------- | ------------ | ------------- |
| `onFinish` | () => `void` | `null`        |
| `PlayRate` | `number`     | `1.0`         |

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:352](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L352)

***

#### remove

▸ **remove**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[remove](../interfaces/m4m.framework.IRenderer.md#remove)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:425](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L425)

***

#### render

▸ **render**(`context`, `assetmgr`, `camera`, `Effqueue?`): `void`

**Parameters**

| Name       | Type                                    | Default value |
| ---------- | --------------------------------------- | ------------- |
| `context`  | `renderContext`                         | `undefined`   |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) | `undefined`   |
| `camera`   | [`camera`](m4m.framework.camera.md)     | `undefined`   |
| `Effqueue` | `number`                                | `0`           |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[render](../interfaces/m4m.framework.IRenderer.md#render)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:245](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L245)

***

#### reset

▸ **reset**(): `void`

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:412](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L412)

***

#### setData

▸ **setData**(`data`, `bundleName`): `void`

**Parameters**

| Name         | Type                                              |
| ------------ | ------------------------------------------------- |
| `data`       | [`F14EffectData`](m4m.framework.F14EffectData.md) |
| `bundleName` | `string`                                          |

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L78)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[start](../interfaces/m4m.framework.IRenderer.md#start)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L18)

***

#### stop

▸ **stop**(): `void`

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:374](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L374)

***

#### update

▸ **update**(`deltaTime`): `void`

**Parameters**

| Name        | Type     |
| ----------- | -------- |
| `deltaTime` | `number` |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[update](../interfaces/m4m.framework.IRenderer.md#update)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:130](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L130)

### Constructors

#### constructor

• **new f14EffectSystem**(`bundleName`)

**Parameters**

| Name         | Type     |
| ------------ | -------- |
| `bundleName` | `string` |

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L98)

### Accessors

#### renderCamera

• `get` **renderCamera**(): [`camera`](m4m.framework.camera.md)

**Returns**

[`camera`](m4m.framework.camera.md)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:233](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L233)

***

#### renderLayer

• `get` **renderLayer**(): `number`

**Returns**

`number`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L12)

• `set` **renderLayer**(`layer`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `layer` | `number` |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L13)

***

#### root

• `get` **root**(): [`transform`](m4m.framework.transform.md)

ref effect 增加transform层控制

**Returns**

[`transform`](m4m.framework.transform.md)

**Defined in**

[framework/component/f14effectsystem/f14effect.ts:113](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14effect.ts#L113)
