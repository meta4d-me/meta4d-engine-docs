[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IRenderer

# Interface: IRenderer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IRenderer

**`language`** zh_CN

**`classdesc`**
渲染器接口 继承自组件接口

**`version`** m4m 1.0

## Hierarchy

- [`INodeComponent`](m4m.framework.INodeComponent.md)

  ↳ **`IRenderer`**

  ↳↳ [`IRendererGpuIns`](m4m.framework.IRendererGpuIns.md)

## Implemented by

- [`LineRenderer`](../classes/m4m.framework.LineRenderer.md)
- [`ParticleSystem`](../classes/m4m.framework.ParticleSystem.md)
- [`TestEffectSystem`](../classes/m4m.framework.TestEffectSystem.md)
- [`TrailRenderer`](../classes/m4m.framework.TrailRenderer.md)
- [`canvasRenderer`](../classes/m4m.framework.canvasRenderer.md)
- [`effectSystem`](../classes/m4m.framework.effectSystem.md)
- [`f14EffectSystem`](../classes/m4m.framework.f14EffectSystem.md)
- [`f4skinnedMeshRenderer`](../classes/m4m.framework.f4skinnedMeshRenderer.md)
- [`skinnedMeshRenderer`](../classes/m4m.framework.skinnedMeshRenderer.md)
- [`trailRender`](../classes/m4m.framework.trailRender.md)

## Table of contents

### Methods

- [clone](m4m.framework.IRenderer.md#clone)
- [onPlay](m4m.framework.IRenderer.md#onplay)
- [remove](m4m.framework.IRenderer.md#remove)
- [render](m4m.framework.IRenderer.md#render)
- [start](m4m.framework.IRenderer.md#start)
- [update](m4m.framework.IRenderer.md#update)

### Properties

- [gameObject](m4m.framework.IRenderer.md#gameobject)
- [layer](m4m.framework.IRenderer.md#layer)
- [queue](m4m.framework.IRenderer.md#queue)
- [renderLayer](m4m.framework.IRenderer.md#renderlayer)

## Methods

### clone

▸ **clone**(): `any`

#### Returns

`any`

#### Inherited from

[INodeComponent](m4m.framework.INodeComponent.md).[clone](m4m.framework.INodeComponent.md#clone)

#### Defined in

[framework/interfaces.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L20)

___

### onPlay

▸ **onPlay**(): `any`

#### Returns

`any`

#### Inherited from

[INodeComponent](m4m.framework.INodeComponent.md).[onPlay](m4m.framework.INodeComponent.md#onplay)

#### Defined in

[framework/interfaces.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L15)

___

### remove

▸ **remove**(): `any`

#### Returns

`any`

#### Inherited from

[INodeComponent](m4m.framework.INodeComponent.md).[remove](m4m.framework.INodeComponent.md#remove)

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

#### Defined in

[framework/interfaces.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L81)

___

### start

▸ **start**(): `any`

#### Returns

`any`

#### Inherited from

[INodeComponent](m4m.framework.INodeComponent.md).[start](m4m.framework.INodeComponent.md#start)

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

[INodeComponent](m4m.framework.INodeComponent.md).[update](m4m.framework.INodeComponent.md#update)

#### Defined in

[framework/interfaces.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L17)

## Properties

### gameObject

• **gameObject**: [`gameObject`](../classes/m4m.framework.gameObject.md)

#### Inherited from

[INodeComponent](m4m.framework.INodeComponent.md).[gameObject](m4m.framework.INodeComponent.md#gameobject)

#### Defined in

[framework/interfaces.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L18)

___

### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md)

#### Defined in

[framework/interfaces.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L77)

___

### queue

• **queue**: `number`

#### Defined in

[framework/interfaces.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L79)

___

### renderLayer

• **renderLayer**: `number`

#### Defined in

[framework/interfaces.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L78)
