[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / pathFinding

# Class: pathFinding

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).pathFinding

## Table of contents

### Constructors

- [constructor](m4m.framework.pathFinding.md#constructor)

### Methods

- [FindPath](m4m.framework.pathFinding.md#findpath)
- [calcAStarPolyPath](m4m.framework.pathFinding.md#calcastarpolypath)
- [calcWayPoints](m4m.framework.pathFinding.md#calcwaypoints)
- [intersectBorder](m4m.framework.pathFinding.md#intersectborder)

## Constructors

### constructor

• **new pathFinding**()

## Methods

### FindPath

▸ `Static` **FindPath**(`info`, `startPos`, `endPos`, `offset?`): [`navVec3`](m4m.framework.navVec3.md)[]

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `info` | [`navMeshInfo`](m4m.framework.navMeshInfo.md) | `undefined` |
| `startPos` | [`navVec3`](m4m.framework.navVec3.md) | `undefined` |
| `endPos` | [`navVec3`](m4m.framework.navVec3.md) | `undefined` |
| `offset` | `number` | `0.1` |

#### Returns

[`navVec3`](m4m.framework.navVec3.md)[]

#### Defined in

[framework/navmesh/PathFinding.ts:154](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/PathFinding.ts#L154)

___

### calcAStarPolyPath

▸ `Static` **calcAStarPolyPath**(`info`, `startPoly`, `endPoly`, `endPos?`, `offset?`): `number`[]

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `info` | [`navMeshInfo`](m4m.framework.navMeshInfo.md) | `undefined` |
| `startPoly` | `number` | `undefined` |
| `endPoly` | `number` | `undefined` |
| `endPos` | [`navVec3`](m4m.framework.navVec3.md) | `null` |
| `offset` | `number` | `0.1` |

#### Returns

`number`[]

#### Defined in

[framework/navmesh/PathFinding.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/PathFinding.ts#L31)

___

### calcWayPoints

▸ `Static` **calcWayPoints**(`info`, `startPos`, `endPos`, `polyPath`, `offset?`): [`navVec3`](m4m.framework.navVec3.md)[]

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `info` | [`navMeshInfo`](m4m.framework.navMeshInfo.md) | `undefined` |
| `startPos` | [`navVec3`](m4m.framework.navVec3.md) | `undefined` |
| `endPos` | [`navVec3`](m4m.framework.navVec3.md) | `undefined` |
| `polyPath` | `number`[] | `undefined` |
| `offset` | `number` | `0.1` |

#### Returns

[`navVec3`](m4m.framework.navVec3.md)[]

#### Defined in

[framework/navmesh/PathFinding.ts:171](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/PathFinding.ts#L171)

___

### intersectBorder

▸ `Static` **intersectBorder**(`a`, `b`, `c`, `d`): [`navVec3`](m4m.framework.navVec3.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | [`navVec3`](m4m.framework.navVec3.md) |
| `b` | [`navVec3`](m4m.framework.navVec3.md) |
| `c` | [`navVec3`](m4m.framework.navVec3.md) |
| `d` | [`navVec3`](m4m.framework.navVec3.md) |

#### Returns

[`navVec3`](m4m.framework.navVec3.md)

#### Defined in

[framework/navmesh/PathFinding.ts:368](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/PathFinding.ts#L368)
