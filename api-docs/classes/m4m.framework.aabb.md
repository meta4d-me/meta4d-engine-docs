[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / aabb

# Class: aabb

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).aabb

**`language`** zh_CN

**`classdesc`**
表示轴对称包围盒

**`version`** m4m 1.0

## Table of contents

### Methods

- [addAABB](m4m.framework.aabb.md#addaabb)
- [addVector3](m4m.framework.aabb.md#addvector3)
- [clear](m4m.framework.aabb.md#clear)
- [clone](m4m.framework.aabb.md#clone)
- [cloneTo](m4m.framework.aabb.md#cloneto)
- [containsVector3](m4m.framework.aabb.md#containsvector3)
- [getVec3](m4m.framework.aabb.md#getvec3)
- [intersectAABB](m4m.framework.aabb.md#intersectaabb)
- [update](m4m.framework.aabb.md#update)

### Accessors

- [center](m4m.framework.aabb.md#center)

### Constructors

- [constructor](m4m.framework.aabb.md#constructor)

### Properties

- [maximum](m4m.framework.aabb.md#maximum)
- [minimum](m4m.framework.aabb.md#minimum)

## Methods

### addAABB

▸ **addAABB**(`aabb`): `void`

**`language`** zh_CN
包含一个aabb

**`version`** m4m 1.0

**`platform`** Web,Native

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `aabb` | [`aabb`](m4m.framework.aabb.md) | 轴对称包围盒 |

#### Returns

`void`

#### Defined in

[framework/tool/aabb.ts:230](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L230)

___

### addVector3

▸ **addVector3**(`vec`): `void`

**`language`** zh_CN
包含一个点

**`version`** m4m 1.0

**`platform`** Web,Native

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `vec` | `vector3` | 世界坐标 |

#### Returns

`void`

#### Defined in

[framework/tool/aabb.ts:182](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L182)

___

### clear

▸ **clear**(): `void`

**`language`** zh_CN
清空

**`version`** m4m 1.0

**`platform`** Web,Native

#### Returns

`void`

#### Defined in

[framework/tool/aabb.ts:260](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L260)

___

### clone

▸ **clone**(): [`aabb`](m4m.framework.aabb.md)

**`language`** zh_CN
克隆

**`version`** m4m 1.0

**`platform`** Web,Native

#### Returns

[`aabb`](m4m.framework.aabb.md)

#### Defined in

[framework/tool/aabb.ts:273](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L273)

___

### cloneTo

▸ **cloneTo**(`to`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `to` | [`aabb`](m4m.framework.aabb.md) |

#### Returns

`void`

#### Defined in

[framework/tool/aabb.ts:281](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L281)

___

### containsVector3

▸ **containsVector3**(`vec`): `boolean`

**`language`** zh_CN
检查是否包含点

**`version`** m4m 1.0

**`platform`** Web,Native

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `vec` | `vector3` | 世界坐标 |

#### Returns

`boolean`

#### Defined in

[framework/tool/aabb.ts:196](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L196)

___

### getVec3

▸ **getVec3**(`vecs`): `void`

**`language`** zh_CN
获取包围盒顶点数据

**`version`** m4m 1.0

**`platform`** Web,Native

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `vecs` | `vector3`[] | 引用数组 |

#### Returns

`void`

#### Defined in

[framework/tool/aabb.ts:298](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L298)

___

### intersectAABB

▸ **intersectAABB**(`aabb`): `boolean`

**`language`** zh_CN
检查是否与aabb相交

**`version`** m4m 1.0

**`platform`** Web,Native

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `aabb` | [`aabb`](m4m.framework.aabb.md) | 轴对称包围盒 |

#### Returns

`boolean`

#### Defined in

[framework/tool/aabb.ts:211](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L211)

___

### update

▸ **update**(`worldmatrix`): `void`

**`language`** zh_CN
刷新轴对称包围盒

**`version`** m4m 1.0

**`platform`** Web,Native

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `worldmatrix` | `matrix` | 物体的世界矩阵 |

#### Returns

`void`

#### Defined in

[framework/tool/aabb.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L61)

## Accessors

### center

• `get` **center**(): `vector3`

**`language`** zh_CN
计算包围盒的中心位置

**`version`** m4m 1.0

**`platform`** Web,Native

#### Returns

`vector3`

#### Defined in

[framework/tool/aabb.ts:246](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L246)

## Constructors

### constructor

• **new aabb**(`_minimum`, `_maximum`)

**`language`** zh_CN
构建轴对称包围盒

**`version`** m4m 1.0

**`platform`** Web,Native

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `_minimum` | `vector3` | 最小点 |
| `_maximum` | `vector3` | 最大点 |

#### Defined in

[framework/tool/aabb.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L44)

## Properties

### maximum

• **maximum**: `vector3`

**`language`** zh_CN
最大点

**`version`** m4m 1.0

**`platform`** Web,Native

#### Defined in

[framework/tool/aabb.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L28)

___

### minimum

• **minimum**: `vector3`

**`language`** zh_CN
最小点

**`version`** m4m 1.0

**`platform`** Web,Native

#### Defined in

[framework/tool/aabb.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/aabb.ts#L19)
