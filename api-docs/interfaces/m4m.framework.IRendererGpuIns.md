[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IRendererGpuIns

# Interface: IRendererGpuIns

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IRendererGpuIns

## Hierarchy

- [`IRenderer`](m4m.framework.IRenderer.md)

  ↳ **`IRendererGpuIns`**

## Implemented by

- [`meshRenderer`](../classes/m4m.framework.meshRenderer.md)

## Table of contents

### Methods

- [clone](m4m.framework.IRendererGpuIns.md#clone)
- [isGpuInstancing](m4m.framework.IRendererGpuIns.md#isgpuinstancing)
- [onPlay](m4m.framework.IRendererGpuIns.md#onplay)
- [remove](m4m.framework.IRendererGpuIns.md#remove)
- [render](m4m.framework.IRendererGpuIns.md#render)
- [start](m4m.framework.IRendererGpuIns.md#start)
- [update](m4m.framework.IRendererGpuIns.md#update)

### Properties

- [gameObject](m4m.framework.IRendererGpuIns.md#gameobject)
- [layer](m4m.framework.IRendererGpuIns.md#layer)
- [queue](m4m.framework.IRendererGpuIns.md#queue)
- [renderLayer](m4m.framework.IRendererGpuIns.md#renderlayer)

## Methods

### clone

▸ **clone**(): `any`

#### Returns

`any`

#### Inherited from

[IRenderer](m4m.framework.IRenderer.md).[clone](m4m.framework.IRenderer.md#clone)

#### Defined in

[framework/interfaces.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L20)

___

### isGpuInstancing

▸ **isGpuInstancing**(): `boolean`

是否开启 GPU Instancing 绘制

#### Returns

`boolean`

#### Defined in

[framework/interfaces.ts:96](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L96)

___

### onPlay

▸ **onPlay**(): `any`

#### Returns

`any`

#### Inherited from

[IRenderer](m4m.framework.IRenderer.md).[onPlay](m4m.framework.IRenderer.md#onplay)

#### Defined in

[framework/interfaces.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L15)

___

### remove

▸ **remove**(): `any`

#### Returns

`any`

#### Inherited from

[IRenderer](m4m.framework.IRenderer.md).[remove](m4m.framework.IRenderer.md#remove)

#### Defined in

[framework/interfaces.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L19)

___

### render

▸ **render**(`context`, `assetmgr`, `camera`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | `renderContext` |
| `assetmgr` | [`assetMgr`](../classes/m4m.framework.assetMgr.md) |
| `camera` | [`camera`](../classes/m4m.framework.camera.md) |

#### Returns

`any`

#### Inherited from

[IRenderer](m4m.framework.IRenderer.md).[render](m4m.framework.IRenderer.md#render)

#### Defined in

[framework/interfaces.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L81)

___

### start

▸ **start**(): `any`

#### Returns

`any`

#### Inherited from

[IRenderer](m4m.framework.IRenderer.md).[start](m4m.framework.IRenderer.md#start)

#### Defined in

[framework/interfaces.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L16)

___

### update

▸ **update**(`delta`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`any`

#### Inherited from

[IRenderer](m4m.framework.IRenderer.md).[update](m4m.framework.IRenderer.md#update)

#### Defined in

[framework/interfaces.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L17)

## Properties

### gameObject

• **gameObject**: [`gameObject`](../classes/m4m.framework.gameObject.md)

#### Inherited from

[IRenderer](m4m.framework.IRenderer.md).[gameObject](m4m.framework.IRenderer.md#gameobject)

#### Defined in

[framework/interfaces.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L18)

___

### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md)

#### Inherited from

[IRenderer](m4m.framework.IRenderer.md).[layer](m4m.framework.IRenderer.md#layer)

#### Defined in

[framework/interfaces.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L77)

___

### queue

• **queue**: `number`

#### Inherited from

[IRenderer](m4m.framework.IRenderer.md).[queue](m4m.framework.IRenderer.md#queue)

#### Defined in

[framework/interfaces.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L79)

___

### renderLayer

• **renderLayer**: `number`

#### Inherited from

[IRenderer](m4m.framework.IRenderer.md).[renderLayer](m4m.framework.IRenderer.md#renderlayer)

#### Defined in

[framework/interfaces.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L78)
