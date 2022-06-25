[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / skinnedMeshRenderer

# Class: skinnedMeshRenderer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).skinnedMeshRenderer

**`language`** zh_CN

**`classdesc`**
蒙皮网格渲染组件

**`version`** m4m 1.0

## Implements

- [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)

## Table of contents

### Properties

- [\_aabb](m4m.framework.skinnedMeshRenderer.md#_aabb)
- [\_queue](m4m.framework.skinnedMeshRenderer.md#_queue)
- [gameObject](m4m.framework.skinnedMeshRenderer.md#gameobject)
- [layer](m4m.framework.skinnedMeshRenderer.md#layer)
- [materials](m4m.framework.skinnedMeshRenderer.md#materials)
- [maxBoneCount](m4m.framework.skinnedMeshRenderer.md#maxbonecount)
- [ClassName](m4m.framework.skinnedMeshRenderer.md#classname)

### Accessors

- [aabb](m4m.framework.skinnedMeshRenderer.md#aabb)
- [mesh](m4m.framework.skinnedMeshRenderer.md#mesh)
- [player](m4m.framework.skinnedMeshRenderer.md#player)
- [queue](m4m.framework.skinnedMeshRenderer.md#queue)
- [renderLayer](m4m.framework.skinnedMeshRenderer.md#renderlayer)

### Methods

- [calActualVertexByIndex](m4m.framework.skinnedMeshRenderer.md#calactualvertexbyindex)
- [intersects](m4m.framework.skinnedMeshRenderer.md#intersects)
- [onPlay](m4m.framework.skinnedMeshRenderer.md#onplay)
- [render](m4m.framework.skinnedMeshRenderer.md#render)
- [start](m4m.framework.skinnedMeshRenderer.md#start)
- [update](m4m.framework.skinnedMeshRenderer.md#update)

### Constructors

- [constructor](m4m.framework.skinnedMeshRenderer.md#constructor)

## Properties

### \_aabb

• **\_aabb**: [`aabb`](m4m.framework.aabb.md)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:148](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L148)

___

### \_queue

• **\_queue**: `number` = `0`

#### Defined in

[framework/component/skinnedmeshrenderer.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L54)

___

### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

挂载的gameobject

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[gameObject](../interfaces/m4m.framework.IRenderer.md#gameobject)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L39)

___

### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Common`

场景渲染层级（common、transparent、overlay）

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[layer](../interfaces/m4m.framework.IRenderer.md#layer)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L43)

___

### materials

• **materials**: [`material`](m4m.framework.material.md)[]

材质数组

#### Defined in

[framework/component/skinnedmeshrenderer.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L74)

___

### maxBoneCount

• **maxBoneCount**: `number` = `55`

最大骨骼数量

**`version`** m4m 1.0

#### Defined in

[framework/component/skinnedmeshrenderer.ts:142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L142)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"skinnedMeshRenderer"`

#### Defined in

[framework/component/skinnedmeshrenderer.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L16)

## Accessors

### aabb

• `get` **aabb**(): [`aabb`](m4m.framework.aabb.md)

#### Returns

[`aabb`](m4m.framework.aabb.md)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L149)

___

### mesh

• `get` **mesh**(): [`mesh`](m4m.framework.mesh.md)

返回mesh数据

#### Returns

[`mesh`](m4m.framework.mesh.md)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:99](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L99)

• `set` **mesh**(`mesh`): `void`

设置mesh数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `mesh` | [`mesh`](m4m.framework.mesh.md) |

#### Returns

`void`

#### Defined in

[framework/component/skinnedmeshrenderer.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L106)

___

### player

• `get` **player**(): [`aniplayer`](m4m.framework.aniplayer.md)

返回动画播放组件

#### Returns

[`aniplayer`](m4m.framework.aniplayer.md)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L82)

• `set` **player**(`p`): `void`

返回动画播放组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `p` | [`aniplayer`](m4m.framework.aniplayer.md) |

#### Returns

`void`

#### Defined in

[framework/component/skinnedmeshrenderer.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L90)

___

### queue

• `get` **queue**(): `number`

返回此组件的场景渲染层级排序依据queue大小

#### Returns

`number`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[queue](../interfaces/m4m.framework.IRenderer.md#queue)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L58)

• `set` **queue**(`value`): `void`

设置此组件的场景渲染层级排序number大小

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[queue](../interfaces/m4m.framework.IRenderer.md#queue)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L65)

___

### renderLayer

• `get` **renderLayer**(): `number`

渲染mask层级（和相机相对应）

#### Returns

`number`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L48)

• `set` **renderLayer**(`layer`): `void`

渲染mask层级（和相机相对应）

#### Parameters

| Name | Type |
| :------ | :------ |
| `layer` | `number` |

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L49)

## Methods

### calActualVertexByIndex

▸ **calActualVertexByIndex**(`index`, `t`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |
| `t` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/component/skinnedmeshrenderer.ts:303](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L303)

___

### intersects

▸ **intersects**(`ray`, `outInfo`): `boolean`

**`language`** zh_CN

**`classdesc`**
射线检测

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ray` | [`ray`](m4m.framework.ray.md) | 射线 |
| `outInfo` | `pickinfo` | - |

#### Returns

`boolean`

#### Defined in

[framework/component/skinnedmeshrenderer.ts:332](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L332)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[onPlay](../interfaces/m4m.framework.IRenderer.md#onplay)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:189](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L189)

___

### render

▸ **render**(`context`, `assetmgr`, `camera`): `void`

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

[framework/component/skinnedmeshrenderer.ts:425](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L425)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[start](../interfaces/m4m.framework.IRenderer.md#start)

#### Defined in

[framework/component/skinnedmeshrenderer.ts:185](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L185)

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

[framework/component/skinnedmeshrenderer.ts:399](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L399)

## Constructors

### constructor

• **new skinnedMeshRenderer**()

#### Defined in

[framework/component/skinnedmeshrenderer.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/skinnedmeshrenderer.ts#L33)
