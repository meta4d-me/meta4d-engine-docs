[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / f4skinnedMeshRenderer

# Class: f4skinnedMeshRenderer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).f4skinnedMeshRenderer

## Implements

- [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)

## Table of contents

### Properties

- [\_aabb](m4m.framework.f4skinnedMeshRenderer.md#_aabb)
- [\_queue](m4m.framework.f4skinnedMeshRenderer.md#_queue)
- [boneMatricesTexture](m4m.framework.f4skinnedMeshRenderer.md#bonematricestexture)
- [boneMatrixChunks](m4m.framework.f4skinnedMeshRenderer.md#bonematrixchunks)
- [gameObject](m4m.framework.f4skinnedMeshRenderer.md#gameobject)
- [ibm](m4m.framework.f4skinnedMeshRenderer.md#ibm)
- [ibmContainer](m4m.framework.f4skinnedMeshRenderer.md#ibmcontainer)
- [inverseRootBone](m4m.framework.f4skinnedMeshRenderer.md#inverserootbone)
- [layer](m4m.framework.f4skinnedMeshRenderer.md#layer)
- [materials](m4m.framework.f4skinnedMeshRenderer.md#materials)
- [tempMatrix](m4m.framework.f4skinnedMeshRenderer.md#tempmatrix)
- [useBoneTexture](m4m.framework.f4skinnedMeshRenderer.md#usebonetexture)
- [ClassName](m4m.framework.f4skinnedMeshRenderer.md#classname)

### Accessors

- [aabb](m4m.framework.f4skinnedMeshRenderer.md#aabb)
- [mesh](m4m.framework.f4skinnedMeshRenderer.md#mesh)
- [queue](m4m.framework.f4skinnedMeshRenderer.md#queue)
- [renderLayer](m4m.framework.f4skinnedMeshRenderer.md#renderlayer)

### Constructors

- [constructor](m4m.framework.f4skinnedMeshRenderer.md#constructor)

### Methods

- [initBoneMatrices](m4m.framework.f4skinnedMeshRenderer.md#initbonematrices)
- [initStaticPoseMatrices](m4m.framework.f4skinnedMeshRenderer.md#initstaticposematrices)
- [matrixMultiplyToArray](m4m.framework.f4skinnedMeshRenderer.md#matrixmultiplytoarray)
- [onPlay](m4m.framework.f4skinnedMeshRenderer.md#onplay)
- [render](m4m.framework.f4skinnedMeshRenderer.md#render)
- [start](m4m.framework.f4skinnedMeshRenderer.md#start)
- [update](m4m.framework.f4skinnedMeshRenderer.md#update)
- [updateBoneMatrix](m4m.framework.f4skinnedMeshRenderer.md#updatebonematrix)
- [updateBoneTexture](m4m.framework.f4skinnedMeshRenderer.md#updatebonetexture)

## Properties

### \_aabb

• **\_aabb**: [`aabb`](m4m.framework.aabb.md)

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:102](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L102)

___

### \_queue

• **\_queue**: `number` = `0`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L29)

___

### boneMatricesTexture

• **boneMatricesTexture**: [`texture`](m4m.framework.texture.md)

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:275](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L275)

___

### boneMatrixChunks

• **boneMatrixChunks**: `Float32Array`[]

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:273](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L273)

___

### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

挂载的gameobject

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[gameObject](../interfaces/m4m.framework.IRenderer.md#gameobject)

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L14)

___

### ibm

• **ibm**: `matrix`[]

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:267](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L267)

___

### ibmContainer

• **ibmContainer**: `vector4`[]

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:265](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L265)

___

### inverseRootBone

• **inverseRootBone**: `matrix`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:353](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L353)

___

### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Common`

场景渲染层级（common、transparent、overlay）

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[layer](../interfaces/m4m.framework.IRenderer.md#layer)

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L18)

___

### materials

• **materials**: [`material`](m4m.framework.material.md)[]

材质数组

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L49)

___

### tempMatrix

• **tempMatrix**: `matrix`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:352](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L352)

___

### useBoneTexture

• **useBoneTexture**: `boolean` = `true`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:260](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L260)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"f4skinnedMeshRenderer"`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L8)

## Accessors

### aabb

• `get` **aabb**(): [`aabb`](m4m.framework.aabb.md)

#### Returns

[`aabb`](m4m.framework.aabb.md)

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L103)

___

### mesh

• `get` **mesh**(): [`mesh`](m4m.framework.mesh.md)

返回mesh数据

#### Returns

[`mesh`](m4m.framework.mesh.md)

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L61)

• `set` **mesh**(`mesh`): `void`

设置mesh数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `mesh` | [`mesh`](m4m.framework.mesh.md) |

#### Returns

`void`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L68)

___

### queue

• `get` **queue**(): `number`

返回此组件的场景渲染层级排序依据queue大小

#### Returns

`number`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[queue](../interfaces/m4m.framework.IRenderer.md#queue)

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L33)

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

[framework/component/f4skinnedMeshRenderer.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L40)

___

### renderLayer

• `get` **renderLayer**(): `number`

渲染mask层级（和相机相对应）

#### Returns

`number`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L23)

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

[framework/component/f4skinnedMeshRenderer.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L24)

## Constructors

### constructor

• **new f4skinnedMeshRenderer**()

## Methods

### initBoneMatrices

▸ **initBoneMatrices**(): `void`

#### Returns

`void`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:276](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L276)

___

### initStaticPoseMatrices

▸ **initStaticPoseMatrices**(): `void`

#### Returns

`void`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:288](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L288)

___

### matrixMultiplyToArray

▸ **matrixMultiplyToArray**(`lhs`, `rhs`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `lhs` | `matrix` |
| `rhs` | `matrix` |
| `out` | `Float32Array` |

#### Returns

`void`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:366](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L366)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[onPlay](../interfaces/m4m.framework.IRenderer.md#onplay)

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:173](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L173)

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

[framework/component/f4skinnedMeshRenderer.ts:197](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L197)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[start](../interfaces/m4m.framework.IRenderer.md#start)

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:140](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L140)

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

[framework/component/f4skinnedMeshRenderer.ts:177](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L177)

___

### updateBoneMatrix

▸ **updateBoneMatrix**(): `void`

#### Returns

`void`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:354](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L354)

___

### updateBoneTexture

▸ **updateBoneTexture**(`context`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | `renderContext` |

#### Returns

`void`

#### Defined in

[framework/component/f4skinnedMeshRenderer.ts:307](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f4skinnedMeshRenderer.ts#L307)
