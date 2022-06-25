[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / navMeshInfo

# Class: navMeshInfo

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).navMeshInfo

## Table of contents

### Properties

- [borders](m4m.framework.navMeshInfo.md#borders)
- [max](m4m.framework.navMeshInfo.md#max)
- [min](m4m.framework.navMeshInfo.md#min)
- [nodes](m4m.framework.navMeshInfo.md#nodes)
- [vecs](m4m.framework.navMeshInfo.md#vecs)

### Methods

- [calcBound](m4m.framework.navMeshInfo.md#calcbound)
- [genBorder](m4m.framework.navMeshInfo.md#genborder)
- [inPoly](m4m.framework.navMeshInfo.md#inpoly)
- [LoadMeshInfo](m4m.framework.navMeshInfo.md#loadmeshinfo)

### Constructors

- [constructor](m4m.framework.navMeshInfo.md#constructor)

## Properties

### borders

• **borders**: `Object` = `null`

#### Index signature

▪ [id: `string`]: [`navBorder`](m4m.framework.navBorder.md)

#### Defined in

[framework/navmesh/MeshInfo.ts:185](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L185)

___

### max

• **max**: [`navVec3`](m4m.framework.navVec3.md) = `null`

#### Defined in

[framework/navmesh/MeshInfo.ts:187](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L187)

___

### min

• **min**: [`navVec3`](m4m.framework.navVec3.md) = `null`

#### Defined in

[framework/navmesh/MeshInfo.ts:186](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L186)

___

### nodes

• **nodes**: [`navNode`](m4m.framework.navNode.md)[] = `null`

#### Defined in

[framework/navmesh/MeshInfo.ts:184](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L184)

___

### vecs

• **vecs**: [`navVec3`](m4m.framework.navVec3.md)[] = `null`

#### Defined in

[framework/navmesh/MeshInfo.ts:183](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L183)

## Methods

### calcBound

▸ **calcBound**(): `void`

#### Returns

`void`

#### Defined in

[framework/navmesh/MeshInfo.ts:188](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L188)

___

### genBorder

▸ **genBorder**(): `void`

#### Returns

`void`

#### Defined in

[framework/navmesh/MeshInfo.ts:266](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L266)

___

### inPoly

▸ **inPoly**(`p`, `poly`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p` | [`navVec3`](m4m.framework.navVec3.md) |
| `poly` | `number`[] |

#### Returns

`boolean`

#### Defined in

[framework/navmesh/MeshInfo.ts:227](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L227)

___

### LoadMeshInfo

▸ `Static` **LoadMeshInfo**(`s`): [`navMeshInfo`](m4m.framework.navMeshInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `s` | `string` |

#### Returns

[`navMeshInfo`](m4m.framework.navMeshInfo.md)

#### Defined in

[framework/navmesh/MeshInfo.ts:341](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L341)

## Constructors

### constructor

• **new navMeshInfo**()
