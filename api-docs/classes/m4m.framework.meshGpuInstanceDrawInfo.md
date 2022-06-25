[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / meshGpuInstanceDrawInfo

# Class: meshGpuInstanceDrawInfo

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).meshGpuInstanceDrawInfo

mesh  Gpu 实例 绘制info数据类

## Implements

- [`DrawInstanceInfo`](../interfaces/m4m.framework.DrawInstanceInfo.md)

## Table of contents

### Methods

- [activeAttributes](m4m.framework.meshGpuInstanceDrawInfo.md#activeattributes)
- [disableAttributes](m4m.framework.meshGpuInstanceDrawInfo.md#disableattributes)
- [initBuffer](m4m.framework.meshGpuInstanceDrawInfo.md#initbuffer)
- [del\_info](m4m.framework.meshGpuInstanceDrawInfo.md#del_info)
- [new\_info](m4m.framework.meshGpuInstanceDrawInfo.md#new_info)

### Properties

- [bufferIdMap](m4m.framework.meshGpuInstanceDrawInfo.md#bufferidmap)
- [cacheBuffers](m4m.framework.meshGpuInstanceDrawInfo.md#cachebuffers)
- [helpDArray](m4m.framework.meshGpuInstanceDrawInfo.md#helpdarray)
- [instanceArray](m4m.framework.meshGpuInstanceDrawInfo.md#instancearray)
- [instanceCount](m4m.framework.meshGpuInstanceDrawInfo.md#instancecount)
- [mid](m4m.framework.meshGpuInstanceDrawInfo.md#mid)
- [onDisableAttribute](m4m.framework.meshGpuInstanceDrawInfo.md#ondisableattribute)
- [vbo](m4m.framework.meshGpuInstanceDrawInfo.md#vbo)

### Constructors

- [constructor](m4m.framework.meshGpuInstanceDrawInfo.md#constructor)

## Methods

### activeAttributes

▸ **activeAttributes**(`gl`, `pass`): `void`

启用批量渲染相关顶点属性

#### Parameters

| Name | Type |
| :------ | :------ |
| `gl` | `WebGLRenderingContext` |
| `pass` | `glDrawPass` |

#### Returns

`void`

#### Implementation of

[DrawInstanceInfo](../interfaces/m4m.framework.DrawInstanceInfo.md).[activeAttributes](../interfaces/m4m.framework.DrawInstanceInfo.md#activeattributes)

#### Defined in

[framework/component/meshrenderer.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L71)

___

### disableAttributes

▸ **disableAttributes**(`gl`, `pass`): `void`

禁用批量渲染相关顶点属性

#### Parameters

| Name | Type |
| :------ | :------ |
| `gl` | `WebGLRenderingContext` |
| `pass` | `glDrawPass` |

#### Returns

`void`

#### Implementation of

[DrawInstanceInfo](../interfaces/m4m.framework.DrawInstanceInfo.md).[disableAttributes](../interfaces/m4m.framework.DrawInstanceInfo.md#disableattributes)

#### Defined in

[framework/component/meshrenderer.ts:114](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L114)

___

### initBuffer

▸ **initBuffer**(`gl`): `void`

初始化Buffer

#### Parameters

| Name | Type |
| :------ | :------ |
| `gl` | `WebGLRenderingContext` |

#### Returns

`void`

#### Implementation of

[DrawInstanceInfo](../interfaces/m4m.framework.DrawInstanceInfo.md).[initBuffer](../interfaces/m4m.framework.DrawInstanceInfo.md#initbuffer)

#### Defined in

[framework/component/meshrenderer.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L68)

___

### del\_info

▸ `Static` **del_info**(`info`): `void`

放回池子

#### Parameters

| Name | Type |
| :------ | :------ |
| `info` | [`meshGpuInstanceDrawInfo`](m4m.framework.meshGpuInstanceDrawInfo.md) |

#### Returns

`void`

#### Defined in

[framework/component/meshrenderer.ts:157](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L157)

___

### new\_info

▸ `Static` **new_info**(): [`meshGpuInstanceDrawInfo`](m4m.framework.meshGpuInstanceDrawInfo.md)

池子中取出一个

#### Returns

[`meshGpuInstanceDrawInfo`](m4m.framework.meshGpuInstanceDrawInfo.md)

#### Defined in

[framework/component/meshrenderer.ts:148](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L148)

## Properties

### bufferIdMap

• **bufferIdMap**: `Object`

#### Index signature

▪ [passId: `number`]: `number`

#### Defined in

[framework/component/meshrenderer.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L64)

___

### cacheBuffers

• **cacheBuffers**: [`ExtenArray`](m4m.math.ExtenArray.md)<`Float32Array`\>[]

#### Defined in

[framework/component/meshrenderer.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L63)

___

### helpDArray

• **helpDArray**: [`ExtenArray`](m4m.math.ExtenArray.md)<`Float32Array`\>

#### Defined in

[framework/component/meshrenderer.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L66)

___

### instanceArray

• **instanceArray**: [`ReuseArray`](m4m.math.ReuseArray.md)<[`IRendererGpuIns`](../interfaces/m4m.framework.IRendererGpuIns.md)\>

#### Defined in

[framework/component/meshrenderer.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L65)

___

### instanceCount

• **instanceCount**: `number`

渲染数量

#### Implementation of

[DrawInstanceInfo](../interfaces/m4m.framework.DrawInstanceInfo.md).[instanceCount](../interfaces/m4m.framework.DrawInstanceInfo.md#instancecount)

#### Defined in

[framework/component/meshrenderer.ts:60](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L60)

___

### mid

• **mid**: `number`

#### Defined in

[framework/component/meshrenderer.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L61)

___

### onDisableAttribute

• **onDisableAttribute**: (`info`: [`meshGpuInstanceDrawInfo`](m4m.framework.meshGpuInstanceDrawInfo.md)) => `any`

#### Type declaration

▸ (`info`): `any`

Disable 结束回调

##### Parameters

| Name | Type |
| :------ | :------ |
| `info` | [`meshGpuInstanceDrawInfo`](m4m.framework.meshGpuInstanceDrawInfo.md) |

##### Returns

`any`

#### Defined in

[framework/component/meshrenderer.ts:143](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L143)

___

### vbo

• **vbo**: `WebGLBuffer`

#### Defined in

[framework/component/meshrenderer.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L62)

## Constructors

### constructor

• **new meshGpuInstanceDrawInfo**()
