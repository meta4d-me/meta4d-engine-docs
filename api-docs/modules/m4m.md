[@meta4d/engine](../README.md) / [Exports](../modules.md) / m4m

# Namespace: m4m

## Table of contents

### Classes

- [AEvent](../classes/m4m.AEvent.md)
- [version](../classes/m4m.version.md)

### Namespaces

- [event](m4m.event.md)
- [framework](m4m.framework.md)
- [io](m4m.io.md)
- [math](m4m.math.md)
- [reflect](m4m.reflect.md)
- [render](m4m.render.md)
- [threading](m4m.threading.md)

### Variables

- [m4m\_reflect\_root](m4m.md#m4m_reflect_root)

### Functions

- [poolcolor](m4m.md#poolcolor)
- [poolcolor\_del](m4m.md#poolcolor_del)
- [poolmtx](m4m.md#poolmtx)
- [poolmtx3x2](m4m.md#poolmtx3x2)
- [poolmtx3x2\_del](m4m.md#poolmtx3x2_del)
- [poolmtx\_del](m4m.md#poolmtx_del)
- [poolquat](m4m.md#poolquat)
- [poolquat\_del](m4m.md#poolquat_del)
- [poolrect](m4m.md#poolrect)
- [poolrect\_del](m4m.md#poolrect_del)
- [poolv2](m4m.md#poolv2)
- [poolv2\_del](m4m.md#poolv2_del)
- [poolv3](m4m.md#poolv3)
- [poolv3\_del](m4m.md#poolv3_del)
- [poolv4](m4m.md#poolv4)
- [poolv4\_del](m4m.md#poolv4_del)

## Variables

### m4m\_reflect\_root

• **m4m\_reflect\_root**: `any` = `{}`

#### Defined in

[io/reflect.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/reflect.ts#L6)

## Functions

### poolcolor

▸ **poolcolor**(`clone?`): `math.color`

从池中取一个 color

#### Parameters

| Name | Type |
| :------ | :------ |
| `clone?` | `color` |

#### Returns

`math.color`

#### Defined in

[render/pool.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L39)

___

### poolcolor\_del

▸ **poolcolor_del**(`data`): `void`

删除释放一个 color

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `color` |

#### Returns

`void`

#### Defined in

[render/pool.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L41)

___

### poolmtx

▸ **poolmtx**(`clone?`): `math.matrix`

从池中取一个 matrix

#### Parameters

| Name | Type |
| :------ | :------ |
| `clone?` | `matrix` |

#### Returns

`math.matrix`

#### Defined in

[render/pool.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L24)

___

### poolmtx3x2

▸ **poolmtx3x2**(`clone?`): `math.matrix3x2`

从池中取一个 matrix3x2

#### Parameters

| Name | Type |
| :------ | :------ |
| `clone?` | `matrix3x2` |

#### Returns

`math.matrix3x2`

#### Defined in

[render/pool.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L29)

___

### poolmtx3x2\_del

▸ **poolmtx3x2_del**(`data`): `void`

删除释放一个 matrix3x2

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `matrix3x2` |

#### Returns

`void`

#### Defined in

[render/pool.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L31)

___

### poolmtx\_del

▸ **poolmtx_del**(`data`): `void`

删除释放一个 matrix

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `matrix` |

#### Returns

`void`

#### Defined in

[render/pool.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L26)

___

### poolquat

▸ **poolquat**(`clone?`): `math.quaternion`

从池中取一个 quaternion

#### Parameters

| Name | Type |
| :------ | :------ |
| `clone?` | `quaternion` |

#### Returns

`math.quaternion`

#### Defined in

[render/pool.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L19)

___

### poolquat\_del

▸ **poolquat_del**(`data`): `void`

删除释放一个 quaternion

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `quaternion` |

#### Returns

`void`

#### Defined in

[render/pool.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L21)

___

### poolrect

▸ **poolrect**(`clone?`): `math.rect`

从池中取一个 rect

#### Parameters

| Name | Type |
| :------ | :------ |
| `clone?` | `rect` |

#### Returns

`math.rect`

#### Defined in

[render/pool.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L34)

___

### poolrect\_del

▸ **poolrect_del**(`data`): `void`

删除释放一个 rect

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `rect` |

#### Returns

`void`

#### Defined in

[render/pool.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L36)

___

### poolv2

▸ **poolv2**(`clone?`): `math.vector2`

从池中取一个 vector2

#### Parameters

| Name | Type |
| :------ | :------ |
| `clone?` | `vector2` |

#### Returns

`math.vector2`

#### Defined in

[render/pool.ts:4](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L4)

___

### poolv2\_del

▸ **poolv2_del**(`data`): `void`

删除释放一个 vector2

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `vector2` |

#### Returns

`void`

#### Defined in

[render/pool.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L6)

___

### poolv3

▸ **poolv3**(`clone?`): `math.vector3`

从池中取一个 vector3

#### Parameters

| Name | Type |
| :------ | :------ |
| `clone?` | `vector3` |

#### Returns

`math.vector3`

#### Defined in

[render/pool.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L9)

___

### poolv3\_del

▸ **poolv3_del**(`data`): `void`

删除释放一个 vector3

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `vector3` |

#### Returns

`void`

#### Defined in

[render/pool.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L11)

___

### poolv4

▸ **poolv4**(`clone?`): `math.vector4`

从池中取一个 vector4

#### Parameters

| Name | Type |
| :------ | :------ |
| `clone?` | `vector4` |

#### Returns

`math.vector4`

#### Defined in

[render/pool.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L14)

___

### poolv4\_del

▸ **poolv4_del**(`data`): `void`

删除释放一个 vector4

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `vector4` |

#### Returns

`void`

#### Defined in

[render/pool.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L16)
