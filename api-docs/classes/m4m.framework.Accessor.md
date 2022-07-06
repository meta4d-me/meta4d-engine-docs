# m4m.framework.Accessor

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / Accessor

## Class: Accessor

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).Accessor

### Table of contents

#### Properties

* [attribute](m4m.framework.Accessor.md#attribute)
* [bufferView](m4m.framework.Accessor.md#bufferview)
* [byteOffset](m4m.framework.Accessor.md#byteoffset)
* [componentType](m4m.framework.Accessor.md#componenttype)
* [count](m4m.framework.Accessor.md#count)
* [max](m4m.framework.Accessor.md#max)
* [min](m4m.framework.Accessor.md#min)
* [normalized](m4m.framework.Accessor.md#normalized)
* [size](m4m.framework.Accessor.md#size)
* [types](m4m.framework.Accessor.md#types)

#### Constructors

* [constructor](m4m.framework.Accessor.md#constructor)

#### Accessors

* [data](m4m.framework.Accessor.md#data)

#### Methods

* [getData](m4m.framework.Accessor.md#getdata)
* [getFloat32Blocks](m4m.framework.Accessor.md#getfloat32blocks)
* [getSubChunks](m4m.framework.Accessor.md#getsubchunks)
* [newFloat32Array](m4m.framework.Accessor.md#newfloat32array)
* [newTypedArray](m4m.framework.Accessor.md#newtypedarray)

### Properties

#### attribute

• **attribute**: `string`

**Defined in**

[framework/asset/resource/gltf.ts:494](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L494)

***

#### bufferView

• **bufferView**: `any`

**Defined in**

[framework/asset/resource/gltf.ts:495](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L495)

***

#### byteOffset

• **byteOffset**: `number`

**Defined in**

[framework/asset/resource/gltf.ts:496](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L496)

***

#### componentType

• **componentType**: `number`

**Defined in**

[framework/asset/resource/gltf.ts:497](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L497)

***

#### count

• **count**: `number`

**Defined in**

[framework/asset/resource/gltf.ts:499](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L499)

***

#### max

• **max**: `number`\[]

**Defined in**

[framework/asset/resource/gltf.ts:500](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L500)

***

#### min

• **min**: `number`\[]

**Defined in**

[framework/asset/resource/gltf.ts:501](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L501)

***

#### normalized

• **normalized**: `boolean`

**Defined in**

[framework/asset/resource/gltf.ts:498](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L498)

***

#### size

• **size**: `number`

**Defined in**

[framework/asset/resource/gltf.ts:502](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L502)

***

#### types

▪ `Static` **types**: `Object`

**Type declaration**

| Name     | Type     |
| -------- | -------- |
| `MAT2`   | `number` |
| `MAT3`   | `number` |
| `MAT4`   | `number` |
| `SCALAR` | `number` |
| `VEC1`   | `number` |
| `VEC2`   | `number` |
| `VEC3`   | `number` |
| `VEC4`   | `number` |

**Defined in**

[framework/asset/resource/gltf.ts:484](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L484)

### Constructors

#### constructor

• **new Accessor**(`__namedParameters`, `name?`)

**Parameters**

| Name                | Type     | Default value |
| ------------------- | -------- | ------------- |
| `__namedParameters` | `Object` | `undefined`   |
| `name`              | `string` | `''`          |

**Defined in**

[framework/asset/resource/gltf.ts:504](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L504)

### Accessors

#### data

• `get` **data**(): `any`

**Returns**

`any`

**Defined in**

[framework/asset/resource/gltf.ts:515](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L515)

### Methods

#### getData

▸ `Static` **getData**(`acc`): `any`\[] | `Int8Array` | `Uint8Array` | `Int16Array` | `Uint16Array` | `Uint32Array` | `Float32Array`

**Parameters**

| Name  | Type                                    |
| ----- | --------------------------------------- |
| `acc` | [`Accessor`](m4m.framework.Accessor.md) |

**Returns**

`any`\[] | `Int8Array` | `Uint8Array` | `Int16Array` | `Uint16Array` | `Uint32Array` | `Float32Array`

**Defined in**

[framework/asset/resource/gltf.ts:551](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L551)

***

#### getFloat32Blocks

▸ `Static` **getFloat32Blocks**(`acc`): `any`\[]

**Parameters**

| Name  | Type                                    |
| ----- | --------------------------------------- |
| `acc` | [`Accessor`](m4m.framework.Accessor.md) |

**Returns**

`any`\[]

**Defined in**

[framework/asset/resource/gltf.ts:531](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L531)

***

#### getSubChunks

▸ `Static` **getSubChunks**(`acc`, `data`): `any`\[]

**Parameters**

| Name   | Type  |
| ------ | ----- |
| `acc`  | `any` |
| `data` | `any` |

**Returns**

`any`\[]

**Defined in**

[framework/asset/resource/gltf.ts:523](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L523)

***

#### newFloat32Array

▸ `Static` **newFloat32Array**(`acc`): `Float32Array`

**Parameters**

| Name  | Type                                    |
| ----- | --------------------------------------- |
| `acc` | [`Accessor`](m4m.framework.Accessor.md) |

**Returns**

`Float32Array`

**Defined in**

[framework/asset/resource/gltf.ts:520](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L520)

***

#### newTypedArray

▸ `Static` **newTypedArray**(`acc`): `Int8Array` | `Uint8Array` | `Int16Array` | `Uint16Array` | `Uint32Array` | `Float32Array`

**Parameters**

| Name  | Type                                    |
| ----- | --------------------------------------- |
| `acc` | [`Accessor`](m4m.framework.Accessor.md) |

**Returns**

`Int8Array` | `Uint8Array` | `Int16Array` | `Uint16Array` | `Uint32Array` | `Float32Array`

**Defined in**

[framework/asset/resource/gltf.ts:535](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/gltf.ts#L535)
