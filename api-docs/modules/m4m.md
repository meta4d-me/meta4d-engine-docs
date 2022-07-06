# m4m

[@meta4d/engine](../) / [Exports](./) / m4m

## Namespace: m4m

### Table of contents

#### Classes

* [AEvent](../classes/m4m.AEvent.md)
* [version](../classes/m4m.version.md)

#### Namespaces

* [event](m4m.event.md)
* [framework](m4m.framework.md)
* [io](m4m.io.md)
* [math](m4m.math.md)
* [reflect](m4m.reflect.md)
* [render](m4m.render.md)
* [threading](m4m.threading.md)

#### Variables

* [m4m\_reflect\_root](m4m.md#m4m\_reflect\_root)

#### Functions

* [poolcolor](m4m.md#poolcolor)
* [poolcolor\_del](m4m.md#poolcolor\_del)
* [poolmtx](m4m.md#poolmtx)
* [poolmtx3x2](m4m.md#poolmtx3x2)
* [poolmtx3x2\_del](m4m.md#poolmtx3x2\_del)
* [poolmtx\_del](m4m.md#poolmtx\_del)
* [poolquat](m4m.md#poolquat)
* [poolquat\_del](m4m.md#poolquat\_del)
* [poolrect](m4m.md#poolrect)
* [poolrect\_del](m4m.md#poolrect\_del)
* [poolv2](m4m.md#poolv2)
* [poolv2\_del](m4m.md#poolv2\_del)
* [poolv3](m4m.md#poolv3)
* [poolv3\_del](m4m.md#poolv3\_del)
* [poolv4](m4m.md#poolv4)
* [poolv4\_del](m4m.md#poolv4\_del)

### Variables

#### m4m\_reflect\_root

• **m4m\_reflect\_root**: `any` = `{}`

**Defined in**

[io/reflect.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/reflect.ts#L6)

### Functions

#### poolcolor

▸ **poolcolor**(`clone?`): `math.color`

从池中取一个 color

**Parameters**

| Name     | Type    |
| -------- | ------- |
| `clone?` | `color` |

**Returns**

`math.color`

**Defined in**

[render/pool.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L39)

***

#### poolcolor\_del

▸ **poolcolor\_del**(`data`): `void`

删除释放一个 color

**Parameters**

| Name   | Type    |
| ------ | ------- |
| `data` | `color` |

**Returns**

`void`

**Defined in**

[render/pool.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L41)

***

#### poolmtx

▸ **poolmtx**(`clone?`): `math.matrix`

从池中取一个 matrix

**Parameters**

| Name     | Type     |
| -------- | -------- |
| `clone?` | `matrix` |

**Returns**

`math.matrix`

**Defined in**

[render/pool.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L24)

***

#### poolmtx3x2

▸ **poolmtx3x2**(`clone?`): `math.matrix3x2`

从池中取一个 matrix3x2

**Parameters**

| Name     | Type        |
| -------- | ----------- |
| `clone?` | `matrix3x2` |

**Returns**

`math.matrix3x2`

**Defined in**

[render/pool.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L29)

***

#### poolmtx3x2\_del

▸ **poolmtx3x2\_del**(`data`): `void`

删除释放一个 matrix3x2

**Parameters**

| Name   | Type        |
| ------ | ----------- |
| `data` | `matrix3x2` |

**Returns**

`void`

**Defined in**

[render/pool.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L31)

***

#### poolmtx\_del

▸ **poolmtx\_del**(`data`): `void`

删除释放一个 matrix

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `data` | `matrix` |

**Returns**

`void`

**Defined in**

[render/pool.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L26)

***

#### poolquat

▸ **poolquat**(`clone?`): `math.quaternion`

从池中取一个 quaternion

**Parameters**

| Name     | Type         |
| -------- | ------------ |
| `clone?` | `quaternion` |

**Returns**

`math.quaternion`

**Defined in**

[render/pool.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L19)

***

#### poolquat\_del

▸ **poolquat\_del**(`data`): `void`

删除释放一个 quaternion

**Parameters**

| Name   | Type         |
| ------ | ------------ |
| `data` | `quaternion` |

**Returns**

`void`

**Defined in**

[render/pool.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L21)

***

#### poolrect

▸ **poolrect**(`clone?`): `math.rect`

从池中取一个 rect

**Parameters**

| Name     | Type   |
| -------- | ------ |
| `clone?` | `rect` |

**Returns**

`math.rect`

**Defined in**

[render/pool.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L34)

***

#### poolrect\_del

▸ **poolrect\_del**(`data`): `void`

删除释放一个 rect

**Parameters**

| Name   | Type   |
| ------ | ------ |
| `data` | `rect` |

**Returns**

`void`

**Defined in**

[render/pool.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L36)

***

#### poolv2

▸ **poolv2**(`clone?`): `math.vector2`

从池中取一个 vector2

**Parameters**

| Name     | Type      |
| -------- | --------- |
| `clone?` | `vector2` |

**Returns**

`math.vector2`

**Defined in**

[render/pool.ts:4](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L4)

***

#### poolv2\_del

▸ **poolv2\_del**(`data`): `void`

删除释放一个 vector2

**Parameters**

| Name   | Type      |
| ------ | --------- |
| `data` | `vector2` |

**Returns**

`void`

**Defined in**

[render/pool.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L6)

***

#### poolv3

▸ **poolv3**(`clone?`): `math.vector3`

从池中取一个 vector3

**Parameters**

| Name     | Type      |
| -------- | --------- |
| `clone?` | `vector3` |

**Returns**

`math.vector3`

**Defined in**

[render/pool.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L9)

***

#### poolv3\_del

▸ **poolv3\_del**(`data`): `void`

删除释放一个 vector3

**Parameters**

| Name   | Type      |
| ------ | --------- |
| `data` | `vector3` |

**Returns**

`void`

**Defined in**

[render/pool.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L11)

***

#### poolv4

▸ **poolv4**(`clone?`): `math.vector4`

从池中取一个 vector4

**Parameters**

| Name     | Type      |
| -------- | --------- |
| `clone?` | `vector4` |

**Returns**

`math.vector4`

**Defined in**

[render/pool.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L14)

***

#### poolv4\_del

▸ **poolv4\_del**(`data`): `void`

删除释放一个 vector4

**Parameters**

| Name   | Type      |
| ------ | --------- |
| `data` | `vector4` |

**Returns**

`void`

**Defined in**

[render/pool.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L16)
