[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / TestEffectSystem

# Class: TestEffectSystem

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).TestEffectSystem

**`language`** zh_CN

**`classdesc`**
特效组件

**`version`** m4m 1.0

## Implements

- [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)

## Table of contents

### Methods

- [addEmissionElement](m4m.framework.TestEffectSystem.md#addemissionelement)
- [onPlay](m4m.framework.TestEffectSystem.md#onplay)
- [pause](m4m.framework.TestEffectSystem.md#pause)
- [play](m4m.framework.TestEffectSystem.md#play)
- [render](m4m.framework.TestEffectSystem.md#render)
- [reset](m4m.framework.TestEffectSystem.md#reset)
- [setJsonData](m4m.framework.TestEffectSystem.md#setjsondata)
- [start](m4m.framework.TestEffectSystem.md#start)
- [stop](m4m.framework.TestEffectSystem.md#stop)
- [update](m4m.framework.TestEffectSystem.md#update)

### Properties

- [autoplay](m4m.framework.TestEffectSystem.md#autoplay)
- [beLoop](m4m.framework.TestEffectSystem.md#beloop)
- [gameObject](m4m.framework.TestEffectSystem.md#gameobject)
- [layer](m4m.framework.TestEffectSystem.md#layer)
- [queue](m4m.framework.TestEffectSystem.md#queue)
- [ClassName](m4m.framework.TestEffectSystem.md#classname)
- [fps](m4m.framework.TestEffectSystem.md#fps)

### Constructors

- [constructor](m4m.framework.TestEffectSystem.md#constructor)

### Accessors

- [renderLayer](m4m.framework.TestEffectSystem.md#renderlayer)

## Methods

### addEmissionElement

▸ **addEmissionElement**(`data?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `data` | `EffectElementData` | `null` |

#### Returns

`void`

#### Defined in

[framework/component/effectsytemfortest.ts:445](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L445)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[onPlay](../interfaces/m4m.framework.IRenderer.md#onplay)

#### Defined in

[framework/component/effectsytemfortest.ts:159](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L159)

___

### pause

▸ **pause**(): `void`

**`language`** zh_CN

**`classdesc`**
暂停播放

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/component/effectsytemfortest.ts:333](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L333)

___

### play

▸ **play**(`speed?`): `void`

**`language`** zh_CN

**`classdesc`**
播放特效

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `speed` | `number` | `1` | 播放速度 |

#### Returns

`void`

#### Defined in

[framework/component/effectsytemfortest.ts:318](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L318)

___

### render

▸ **render**(`context`, `assetmgr`, `camera`): `void`

提交各个EffectBatcher中的数据进行渲染

**`memberof`** effectSystem

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

[framework/component/effectsytemfortest.ts:243](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L243)

___

### reset

▸ **reset**(`restSinglemesh?`, `resetParticle?`): `void`

**`language`** zh_CN

**`classdesc`**
重置到初始状态

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `restSinglemesh` | `boolean` | `true` |
| `resetParticle` | `boolean` | `true` |

#### Returns

`void`

#### Defined in

[framework/component/effectsytemfortest.ts:358](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L358)

___

### setJsonData

▸ **setJsonData**(`_jsonData`): `void`

**`language`** zh_CN

**`classdesc`**
设置特效数据 textasset

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `_jsonData` | [`textasset`](m4m.framework.textasset.md) |

#### Returns

`void`

#### Defined in

[framework/component/effectsytemfortest.ts:115](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L115)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[start](../interfaces/m4m.framework.IRenderer.md#start)

#### Defined in

[framework/component/effectsytemfortest.ts:154](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L154)

___

### stop

▸ **stop**(): `void`

**`language`** zh_CN

**`classdesc`**
停止播放

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/component/effectsytemfortest.ts:345](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L345)

___

### update

▸ **update**(`delta`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[update](../interfaces/m4m.framework.IRenderer.md#update)

#### Defined in

[framework/component/effectsytemfortest.ts:165](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L165)

## Properties

### autoplay

• **autoplay**: `boolean` = `true`

**`language`** zh_CN

**`classdesc`**
自动播放

**`version`** m4m 1.0

#### Defined in

[framework/component/effectsytemfortest.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L54)

___

### beLoop

• **beLoop**: `boolean`

**`language`** zh_CN

**`classdesc`**
特效是否循环

**`version`** m4m 1.0

#### Defined in

[framework/component/effectsytemfortest.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L63)

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

[framework/component/effectsytemfortest.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L24)

___

### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Transparent`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[layer](../interfaces/m4m.framework.IRenderer.md#layer)

#### Defined in

[framework/component/effectsytemfortest.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L25)

___

### queue

• **queue**: `number` = `0`

**`language`** zh_CN

**`classdesc`**
同层级渲染排序依据

**`version`** m4m 1.0

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[queue](../interfaces/m4m.framework.IRenderer.md#queue)

#### Defined in

[framework/component/effectsytemfortest.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L45)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"TestEffectSystem"`

#### Defined in

[framework/component/effectsytemfortest.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L15)

___

### fps

▪ `Static` **fps**: `number` = `30`

**`language`** zh_CN

**`classdesc`**
特效播放速度

**`version`** m4m 1.0

#### Defined in

[framework/component/effectsytemfortest.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L77)

## Constructors

### constructor

• **new TestEffectSystem**()

## Accessors

### renderLayer

• `get` **renderLayer**(): `number`

**`language`** zh_CN

**`classdesc`**
渲染层级

**`version`** m4m 1.0

#### Returns

`number`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

#### Defined in

[framework/component/effectsytemfortest.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L34)

• `set` **renderLayer**(`layer`): `void`

**`language`** zh_CN

**`classdesc`**
渲染层级

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

[framework/component/effectsytemfortest.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/effectsytemfortest.ts#L35)
