[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / meshGpuInsBatcher

# Class: meshGpuInsBatcher

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).meshGpuInsBatcher

meshRenderer GpuInstancing 合批类

## Table of contents

### Properties

- [bufferDArrs](m4m.framework.meshGpuInsBatcher.md#bufferdarrs)
- [count](m4m.framework.meshGpuInsBatcher.md#count)
- [gameLayer](m4m.framework.meshGpuInsBatcher.md#gamelayer)
- [materials](m4m.framework.meshGpuInsBatcher.md#materials)
- [mesh](m4m.framework.meshGpuInsBatcher.md#mesh)
- [passArr](m4m.framework.meshGpuInsBatcher.md#passarr)
- [passIdMap](m4m.framework.meshGpuInsBatcher.md#passidmap)

### Constructors

- [constructor](m4m.framework.meshGpuInsBatcher.md#constructor)

### Methods

- [dispose](m4m.framework.meshGpuInsBatcher.md#dispose)

## Properties

### bufferDArrs

• **bufferDArrs**: [`ExtenArray`](m4m.math.ExtenArray.md)<`Float32Array`\>[]

batcher 缓存的array

#### Defined in

[framework/component/meshrenderer.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L17)

___

### count

• **count**: `number` = `0`

实例数量

#### Defined in

[framework/component/meshrenderer.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L9)

___

### gameLayer

• **gameLayer**: `number`

游戏标记layer

#### Defined in

[framework/component/meshrenderer.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L15)

___

### materials

• **materials**: [`material`](m4m.framework.material.md)[]

材质数组（应对submesh）

#### Defined in

[framework/component/meshrenderer.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L13)

___

### mesh

• **mesh**: [`mesh`](m4m.framework.mesh.md)

渲染使用mesh

#### Defined in

[framework/component/meshrenderer.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L11)

___

### passArr

• **passArr**: `glDrawPass`[]

当前材质上 使用到的通道列表

#### Defined in

[framework/component/meshrenderer.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L19)

___

### passIdMap

• **passIdMap**: `Object`

passId 对应 passArr 中的索引map

#### Index signature

▪ [id: `number`]: `number`

#### Defined in

[framework/component/meshrenderer.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L21)

## Constructors

### constructor

• **new meshGpuInsBatcher**(`_glayer`, `_mesh`, `_mats`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `_glayer` | `number` |
| `_mesh` | [`mesh`](m4m.framework.mesh.md) |
| `_mats` | [`material`](m4m.framework.material.md)[] |

#### Defined in

[framework/component/meshrenderer.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L22)

## Methods

### dispose

▸ **dispose**(): `void`

清理

#### Returns

`void`

#### Defined in

[framework/component/meshrenderer.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshrenderer.ts#L41)
