# m4m.framework.physicTool

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / physicTool

## Class: physicTool

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).physicTool

tool of physic

### Table of contents

#### Constructors

* [constructor](m4m.framework.physicTool.md#constructor)

#### Methods

* [IQuatCopy](m4m.framework.physicTool.md#iquatcopy)
* [IQuatEqual](m4m.framework.physicTool.md#iquatequal)
* [Ivec2Copy](m4m.framework.physicTool.md#ivec2copy)
* [Ivec2Equal](m4m.framework.physicTool.md#ivec2equal)
* [Ivec3Copy](m4m.framework.physicTool.md#ivec3copy)
* [Ivec3Equal](m4m.framework.physicTool.md#ivec3equal)
* [vec3AsArray](m4m.framework.physicTool.md#vec3asarray)

### Constructors

#### constructor

• **new physicTool**()

### Methods

#### IQuatCopy

▸ `Static` **IQuatCopy**(`from`, `to`): `void`

**Parameters**

| Name   | Type                                       |
| ------ | ------------------------------------------ |
| `from` | [`Iquat`](../interfaces/m4m.math.Iquat.md) |
| `to`   | [`Iquat`](../interfaces/m4m.math.Iquat.md) |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicTool.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicTool.ts#L36)

***

#### IQuatEqual

▸ `Static` **IQuatEqual**(`a`, `b`): `boolean`

**Parameters**

| Name | Type                                       |
| ---- | ------------------------------------------ |
| `a`  | [`Iquat`](../interfaces/m4m.math.Iquat.md) |
| `b`  | [`Iquat`](../interfaces/m4m.math.Iquat.md) |

**Returns**

`boolean`

**Defined in**

[framework/physics3d/physicTool.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicTool.ts#L18)

***

#### Ivec2Copy

▸ `Static` **Ivec2Copy**(`from`, `to`): `void`

**Parameters**

| Name   | Type                                       |
| ------ | ------------------------------------------ |
| `from` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md) |
| `to`   | [`Ivec2`](../interfaces/m4m.math.Ivec2.md) |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicTool.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicTool.ts#L30)

***

#### Ivec2Equal

▸ `Static` **Ivec2Equal**(`a`, `b`): `boolean`

**Parameters**

| Name | Type                                       |
| ---- | ------------------------------------------ |
| `a`  | [`Ivec2`](../interfaces/m4m.math.Ivec2.md) |
| `b`  | [`Ivec2`](../interfaces/m4m.math.Ivec2.md) |

**Returns**

`boolean`

**Defined in**

[framework/physics3d/physicTool.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicTool.ts#L13)

***

#### Ivec3Copy

▸ `Static` **Ivec3Copy**(`from`, `to`): `void`

**Parameters**

| Name   | Type                                       |
| ------ | ------------------------------------------ |
| `from` | [`Ivec3`](../interfaces/m4m.math.Ivec3.md) |
| `to`   | [`Ivec3`](../interfaces/m4m.math.Ivec3.md) |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicTool.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicTool.ts#L23)

***

#### Ivec3Equal

▸ `Static` **Ivec3Equal**(`a`, `b`): `boolean`

**Parameters**

| Name | Type                                       |
| ---- | ------------------------------------------ |
| `a`  | [`Ivec3`](../interfaces/m4m.math.Ivec3.md) |
| `b`  | [`Ivec3`](../interfaces/m4m.math.Ivec3.md) |

**Returns**

`boolean`

**Defined in**

[framework/physics3d/physicTool.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicTool.ts#L8)

***

#### vec3AsArray

▸ `Static` **vec3AsArray**(`vec3`): `any`\[]

**Parameters**

| Name   | Type      |
| ------ | --------- |
| `vec3` | `vector3` |

**Returns**

`any`\[]

**Defined in**

[framework/physics3d/physicTool.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicTool.ts#L44)
