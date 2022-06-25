[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / navNode

# Class: navNode

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).navNode

## Table of contents

### Properties

- [borderByPoint](m4m.framework.navNode.md#borderbypoint)
- [borderByPoly](m4m.framework.navNode.md#borderbypoly)
- [center](m4m.framework.navNode.md#center)
- [nodeID](m4m.framework.navNode.md#nodeid)
- [poly](m4m.framework.navNode.md#poly)

### Constructors

- [constructor](m4m.framework.navNode.md#constructor)

### Methods

- [genBorder](m4m.framework.navNode.md#genborder)
- [genCenter](m4m.framework.navNode.md#gencenter)
- [getLinked](m4m.framework.navNode.md#getlinked)
- [isLinkTo](m4m.framework.navNode.md#islinkto)

## Properties

### borderByPoint

• **borderByPoint**: `string`[] = `null`

#### Defined in

[framework/navmesh/MeshInfo.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L81)

___

### borderByPoly

• **borderByPoly**: `string`[] = `null`

#### Defined in

[framework/navmesh/MeshInfo.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L80)

___

### center

• **center**: [`navVec3`](m4m.framework.navVec3.md) = `null`

#### Defined in

[framework/navmesh/MeshInfo.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L82)

___

### nodeID

• **nodeID**: `number` = `0`

#### Defined in

[framework/navmesh/MeshInfo.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L78)

___

### poly

• **poly**: `number`[] = `null`

#### Defined in

[framework/navmesh/MeshInfo.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L79)

## Constructors

### constructor

• **new navNode**()

## Methods

### genBorder

▸ **genBorder**(): `void`

#### Returns

`void`

#### Defined in

[framework/navmesh/MeshInfo.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L83)

___

### genCenter

▸ **genCenter**(`info`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `info` | [`navMeshInfo`](m4m.framework.navMeshInfo.md) |

#### Returns

`void`

#### Defined in

[framework/navmesh/MeshInfo.ts:156](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L156)

___

### getLinked

▸ **getLinked**(`info`): `number`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `info` | [`navMeshInfo`](m4m.framework.navMeshInfo.md) |

#### Returns

`number`[]

#### Defined in

[framework/navmesh/MeshInfo.ts:133](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L133)

___

### isLinkTo

▸ **isLinkTo**(`info`, `nid`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `info` | [`navMeshInfo`](m4m.framework.navMeshInfo.md) |
| `nid` | `number` |

#### Returns

`string`

#### Defined in

[framework/navmesh/MeshInfo.ts:104](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L104)
