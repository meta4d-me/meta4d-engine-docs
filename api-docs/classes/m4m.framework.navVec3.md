[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / navVec3

# Class: navVec3

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).navVec3

## Table of contents

### Methods

- [clone](m4m.framework.navVec3.md#clone)
- [Angle](m4m.framework.navVec3.md#angle)
- [Border](m4m.framework.navVec3.md#border)
- [Cross](m4m.framework.navVec3.md#cross)
- [DistAZ](m4m.framework.navVec3.md#distaz)
- [DotAZ](m4m.framework.navVec3.md#dotaz)
- [NormalAZ](m4m.framework.navVec3.md#normalaz)
- [lerp](m4m.framework.navVec3.md#lerp)

### Constructors

- [constructor](m4m.framework.navVec3.md#constructor)

### Properties

- [realy](m4m.framework.navVec3.md#realy)
- [x](m4m.framework.navVec3.md#x)
- [y](m4m.framework.navVec3.md#y)
- [z](m4m.framework.navVec3.md#z)

## Methods

### clone

▸ **clone**(): [`navVec3`](m4m.framework.navVec3.md)

#### Returns

[`navVec3`](m4m.framework.navVec3.md)

#### Defined in

[framework/navmesh/MeshInfo.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L8)

___

### Angle

▸ `Static` **Angle**(`start`, `end`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `start` | [`navVec3`](m4m.framework.navVec3.md) |
| `end` | [`navVec3`](m4m.framework.navVec3.md) |

#### Returns

`number`

#### Defined in

[framework/navmesh/MeshInfo.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L42)

___

### Border

▸ `Static` **Border**(`start`, `end`, `dist`): [`navVec3`](m4m.framework.navVec3.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `start` | [`navVec3`](m4m.framework.navVec3.md) |
| `end` | [`navVec3`](m4m.framework.navVec3.md) |
| `dist` | `number` |

#### Returns

[`navVec3`](m4m.framework.navVec3.md)

#### Defined in

[framework/navmesh/MeshInfo.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L52)

___

### Cross

▸ `Static` **Cross**(`start`, `end`): [`navVec3`](m4m.framework.navVec3.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `start` | [`navVec3`](m4m.framework.navVec3.md) |
| `end` | [`navVec3`](m4m.framework.navVec3.md) |

#### Returns

[`navVec3`](m4m.framework.navVec3.md)

#### Defined in

[framework/navmesh/MeshInfo.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L32)

___

### DistAZ

▸ `Static` **DistAZ**(`start`, `end`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `start` | [`navVec3`](m4m.framework.navVec3.md) |
| `end` | [`navVec3`](m4m.framework.navVec3.md) |

#### Returns

`number`

#### Defined in

[framework/navmesh/MeshInfo.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L17)

___

### DotAZ

▸ `Static` **DotAZ**(`start`, `end`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `start` | [`navVec3`](m4m.framework.navVec3.md) |
| `end` | [`navVec3`](m4m.framework.navVec3.md) |

#### Returns

`number`

#### Defined in

[framework/navmesh/MeshInfo.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L39)

___

### NormalAZ

▸ `Static` **NormalAZ**(`start`, `end`): [`navVec3`](m4m.framework.navVec3.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `start` | [`navVec3`](m4m.framework.navVec3.md) |
| `end` | [`navVec3`](m4m.framework.navVec3.md) |

#### Returns

[`navVec3`](m4m.framework.navVec3.md)

#### Defined in

[framework/navmesh/MeshInfo.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L22)

___

### lerp

▸ `Static` **lerp**(`from`, `to`, `lerp`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | [`navVec3`](m4m.framework.navVec3.md) |
| `to` | [`navVec3`](m4m.framework.navVec3.md) |
| `lerp` | `number` |
| `out` | [`navVec3`](m4m.framework.navVec3.md) |

#### Returns

`void`

#### Defined in

[framework/navmesh/MeshInfo.ts:69](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L69)

## Constructors

### constructor

• **new navVec3**()

## Properties

### realy

• **realy**: `number` = `0`

#### Defined in

[framework/navmesh/MeshInfo.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L7)

___

### x

• **x**: `number` = `0`

#### Defined in

[framework/navmesh/MeshInfo.ts:3](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L3)

___

### y

• **y**: `number` = `0`

#### Defined in

[framework/navmesh/MeshInfo.ts:4](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L4)

___

### z

• **z**: `number` = `0`

#### Defined in

[framework/navmesh/MeshInfo.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/MeshInfo.ts#L5)
