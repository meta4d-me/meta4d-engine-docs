[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / NavMeshLoadManager

# Class: NavMeshLoadManager

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).NavMeshLoadManager

## Table of contents

### Constructors

- [constructor](m4m.framework.NavMeshLoadManager.md#constructor)

### Methods

- [dispose](m4m.framework.NavMeshLoadManager.md#dispose)
- [loadNavMesh](m4m.framework.NavMeshLoadManager.md#loadnavmesh)
- [loadNavMeshByDate](m4m.framework.NavMeshLoadManager.md#loadnavmeshbydate)
- [moveToPoints](m4m.framework.NavMeshLoadManager.md#movetopoints)
- [showNavmesh](m4m.framework.NavMeshLoadManager.md#shownavmesh)
- [findtriIndex](m4m.framework.NavMeshLoadManager.md#findtriindex)

### Properties

- [navMesh](m4m.framework.NavMeshLoadManager.md#navmesh)
- [navTrans](m4m.framework.NavMeshLoadManager.md#navtrans)
- [navigate](m4m.framework.NavMeshLoadManager.md#navigate)

### Accessors

- [navmeshJson](m4m.framework.NavMeshLoadManager.md#navmeshjson)
- [Instance](m4m.framework.NavMeshLoadManager.md#instance)

## Constructors

### constructor

• **new NavMeshLoadManager**()

## Methods

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:178](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L178)

___

### loadNavMesh

▸ **loadNavMesh**(`navMeshUrl`, `app`, `onstate?`): `void`

加载NavMesh

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `navMeshUrl` | `string` | 要加载的navMesh完整路径 |
| `app` | [`application`](m4m.framework.application.md) |  |
| `onstate?` | (`state`: [`stateLoad`](m4m.framework.stateLoad.md)) => `void` | 加载反馈信息 |

#### Returns

`void`

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L29)

___

### loadNavMeshByDate

▸ **loadNavMeshByDate**(`dataStr`, `app`, `callback`): `void`

通过数据 装载NavMesh

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `dataStr` | `string` | navmesh 的字符串数据 |
| `app` | [`application`](m4m.framework.application.md) | - |
| `callback` | () => `any` | 完成回调 |

#### Returns

`void`

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L56)

___

### moveToPoints

▸ **moveToPoints**(`startPos`, `endPos`): `vector3`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `startPos` | `vector3` |
| `endPos` | `vector3` |

#### Returns

`vector3`[]

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:196](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L196)

___

### showNavmesh

▸ **showNavmesh**(`isshow`, `material?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `isshow` | `boolean` | `undefined` |
| `material` | [`material`](m4m.framework.material.md) | `null` |

#### Returns

`void`

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:155](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L155)

___

### findtriIndex

▸ `Static` **findtriIndex**(`point`, `trans`): `number`

获取指定位置的三角形索引

#### Parameters

| Name | Type |
| :------ | :------ |
| `point` | `vector3` |
| `trans` | [`transform`](m4m.framework.transform.md) |

#### Returns

`number`

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:222](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L222)

## Properties

### navMesh

• **navMesh**: [`mesh`](m4m.framework.mesh.md)

场景中的寻路Mesh

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L13)

___

### navTrans

• **navTrans**: [`transform`](m4m.framework.transform.md)

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L16)

___

### navigate

• **navigate**: [`Navigate`](m4m.framework.Navigate.md)

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L15)

## Accessors

### navmeshJson

• `get` **navmeshJson**(): `string`

导航网格Json数据

#### Returns

`string`

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L20)

___

### Instance

• `Static` `get` **Instance**(): [`NavMeshLoadManager`](m4m.framework.NavMeshLoadManager.md)

#### Returns

[`NavMeshLoadManager`](m4m.framework.NavMeshLoadManager.md)

#### Defined in

[framework/navmesh/NavMeshLoadManager.ts:190](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/NavMeshLoadManager.ts#L190)
