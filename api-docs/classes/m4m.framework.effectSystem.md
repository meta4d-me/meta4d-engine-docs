# m4m.framework.effectSystem

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / effectSystem

## Class: effectSystem

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).effectSystem

**`language`** zh\_CN

**`classdesc`** 特效组件

**`version`** m4m 1.0

### Implements

* [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)

### Table of contents

#### Properties

* [autoplay](m4m.framework.effectSystem.md#autoplay)
* [beLoop](m4m.framework.effectSystem.md#beloop)
* [gameObject](m4m.framework.effectSystem.md#gameobject)
* [layer](m4m.framework.effectSystem.md#layer)
* [queue](m4m.framework.effectSystem.md#queue)
* [ClassName](m4m.framework.effectSystem.md#classname)
* [fps](m4m.framework.effectSystem.md#fps)

#### Constructors

* [constructor](m4m.framework.effectSystem.md#constructor)

#### Accessors

* [jsonData](m4m.framework.effectSystem.md#jsondata)
* [renderLayer](m4m.framework.effectSystem.md#renderlayer)

#### Methods

* [onPlay](m4m.framework.effectSystem.md#onplay)
* [pause](m4m.framework.effectSystem.md#pause)
* [play](m4m.framework.effectSystem.md#play)
* [render](m4m.framework.effectSystem.md#render)
* [reset](m4m.framework.effectSystem.md#reset)
* [setJsonData](m4m.framework.effectSystem.md#setjsondata)
* [setJsonDataStr](m4m.framework.effectSystem.md#setjsondatastr)
* [start](m4m.framework.effectSystem.md#start)
* [stop](m4m.framework.effectSystem.md#stop)
* [update](m4m.framework.effectSystem.md#update)
* [updateJsonData](m4m.framework.effectSystem.md#updatejsondata)
* [updateJsonDataStr](m4m.framework.effectSystem.md#updatejsondatastr)

### Properties

#### autoplay

• **autoplay**: `boolean` = `true`

**`language`** zh\_CN

**`classdesc`** 自动播放

**`version`** m4m 1.0

**Defined in**

[framework/component/effectsystem.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L54)

***

#### beLoop

• **beLoop**: `boolean`

**`language`** zh\_CN

**`classdesc`** 特效是否循环

**`version`** m4m 1.0

**Defined in**

[framework/component/effectsystem.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L63)

***

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh\_CN

**`classdesc`** 挂载的gameobject

**`version`** m4m 1.0

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[gameObject](../interfaces/m4m.framework.IRenderer.md#gameobject)

**Defined in**

[framework/component/effectsystem.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L24)

***

#### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Transparent`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[layer](../interfaces/m4m.framework.IRenderer.md#layer)

**Defined in**

[framework/component/effectsystem.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L25)

***

#### queue

• **queue**: `number` = `0`

**`language`** zh\_CN

**`classdesc`** 同层级渲染排序依据

**`version`** m4m 1.0

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[queue](../interfaces/m4m.framework.IRenderer.md#queue)

**Defined in**

[framework/component/effectsystem.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L45)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"effectSystem"`

**Defined in**

[framework/component/effectsystem.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L15)

***

#### fps

▪ `Static` **fps**: `number` = `30`

**`language`** zh\_CN

**`classdesc`** 特效播放速度

**`version`** m4m 1.0

**Defined in**

[framework/component/effectsystem.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L77)

### Constructors

#### constructor

• **new effectSystem**()

### Accessors

#### jsonData

• `get` **jsonData**(): [`textasset`](m4m.framework.textasset.md)

**Returns**

[`textasset`](m4m.framework.textasset.md)

**Defined in**

[framework/component/effectsystem.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L112)

• `set` **jsonData**(`text`): `void`

**Parameters**

| Name   | Type                                      |
| ------ | ----------------------------------------- |
| `text` | [`textasset`](m4m.framework.textasset.md) |

**Returns**

`void`

**Defined in**

[framework/component/effectsystem.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L106)

***

#### renderLayer

• `get` **renderLayer**(): `number`

**`language`** zh\_CN

**`classdesc`** 渲染层级

**`version`** m4m 1.0

**Returns**

`number`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

**Defined in**

[framework/component/effectsystem.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L34)

• `set` **renderLayer**(`layer`): `void`

**`language`** zh\_CN

**`classdesc`** 渲染层级

**`version`** m4m 1.0

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `layer` | `number` |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

**Defined in**

[framework/component/effectsystem.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L35)

### Methods

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[onPlay](../interfaces/m4m.framework.IRenderer.md#onplay)

**Defined in**

[framework/component/effectsystem.ts:190](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L190)

***

#### pause

▸ **pause**(): `void`

**`language`** zh\_CN

**`classdesc`** 暂停播放

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/component/effectsystem.ts:529](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L529)

***

#### play

▸ **play**(`speed?`): `void`

**`language`** zh\_CN

**`classdesc`** 播放特效

**`version`** m4m 1.0

**Parameters**

| Name    | Type     | Default value | Description |
| ------- | -------- | ------------- | ----------- |
| `speed` | `number` | `1`           | 播放速度        |

**Returns**

`void`

**Defined in**

[framework/component/effectsystem.ts:512](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L512)

***

#### render

▸ **render**(`context`, `assetmgr`, `camera`): `void`

提交各个EffectBatcher中的数据进行渲染

**`memberof`** effectSystem

**Parameters**

| Name       | Type                                    |
| ---------- | --------------------------------------- |
| `context`  | `renderContext`                         |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `camera`   | [`camera`](m4m.framework.camera.md)     |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[render](../interfaces/m4m.framework.IRenderer.md#render)

**Defined in**

[framework/component/effectsystem.ts:432](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L432)

***

#### reset

▸ **reset**(`restSinglemesh?`, `resetParticle?`): `void`

**`language`** zh\_CN

**`classdesc`** 重置到初始状态

**`version`** m4m 1.0

**Parameters**

| Name             | Type      | Default value |
| ---------------- | --------- | ------------- |
| `restSinglemesh` | `boolean` | `true`        |
| `resetParticle`  | `boolean` | `true`        |

**Returns**

`void`

**Defined in**

[framework/component/effectsystem.ts:554](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L554)

***

#### setJsonData

▸ **setJsonData**(`_jsonData`): `void`

**`language`** zh\_CN

**`classdesc`** 设置特效数据 textasset

**`version`** m4m 1.0

**Parameters**

| Name        | Type                                      |
| ----------- | ----------------------------------------- |
| `_jsonData` | [`textasset`](m4m.framework.textasset.md) |

**Returns**

`void`

**Defined in**

[framework/component/effectsystem.ts:123](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L123)

***

#### setJsonDataStr

▸ **setJsonDataStr**(`_jsonStr`): `void`

**Parameters**

| Name       | Type     |
| ---------- | -------- |
| `_jsonStr` | `string` |

**Returns**

`void`

**Defined in**

[framework/component/effectsystem.ts:129](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L129)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[start](../interfaces/m4m.framework.IRenderer.md#start)

**Defined in**

[framework/component/effectsystem.ts:185](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L185)

***

#### stop

▸ **stop**(): `void`

**`language`** zh\_CN

**`classdesc`** 停止播放

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/component/effectsystem.ts:541](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L541)

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

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[update](../interfaces/m4m.framework.IRenderer.md#update)

**Defined in**

[framework/component/effectsystem.ts:195](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L195)

***

#### updateJsonData

▸ **updateJsonData**(`_jsonData`): `void`

更新特效数据

**Parameters**

| Name        | Type                                      |
| ----------- | ----------------------------------------- |
| `_jsonData` | [`textasset`](m4m.framework.textasset.md) |

**Returns**

`void`

**Defined in**

[framework/component/effectsystem.ts:140](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L140)

***

#### updateJsonDataStr

▸ **updateJsonDataStr**(`_jsonStr`): `void`

**Parameters**

| Name       | Type     |
| ---------- | -------- |
| `_jsonStr` | `string` |

**Returns**

`void`

**Defined in**

[framework/component/effectsystem.ts:145](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsystem.ts#L145)
