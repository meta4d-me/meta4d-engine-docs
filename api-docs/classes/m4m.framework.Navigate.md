[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / Navigate

# Class: Navigate

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).Navigate

## Table of contents

### Constructors

- [constructor](m4m.framework.Navigate.md#constructor)

### Methods

- [dispose](m4m.framework.Navigate.md#dispose)
- [pathPoints](m4m.framework.Navigate.md#pathpoints)

### Properties

- [navindexmap](m4m.framework.Navigate.md#navindexmap)
- [navinfo](m4m.framework.Navigate.md#navinfo)

## Constructors

### constructor

• **new Navigate**(`navinfo`, `navindexmap`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `navinfo` | [`navMeshInfo`](m4m.framework.navMeshInfo.md) |
| `navindexmap` | `any` |

#### Defined in

[framework/navmesh/Navigate.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/Navigate.ts#L6)

## Methods

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Defined in

[framework/navmesh/Navigate.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/Navigate.ts#L38)

___

### pathPoints

▸ **pathPoints**(`start`, `end`, `startIndex`, `endIndex`): `vector3`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `start` | `vector3` |
| `end` | `vector3` |
| `startIndex` | `number` |
| `endIndex` | `number` |

#### Returns

`vector3`[]

#### Defined in

[framework/navmesh/Navigate.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/Navigate.ts#L11)

## Properties

### navindexmap

• **navindexmap**: `Object`

#### Index signature

▪ [id: `number`]: `number`

#### Defined in

[framework/navmesh/Navigate.ts:3](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/Navigate.ts#L3)

___

### navinfo

• **navinfo**: [`navMeshInfo`](m4m.framework.navMeshInfo.md)

#### Defined in

[framework/navmesh/Navigate.ts:4](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/Navigate.ts#L4)
