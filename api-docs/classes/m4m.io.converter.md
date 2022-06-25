[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [io](../modules/m4m.io.md) / converter

# Class: converter

[m4m](../modules/m4m.md).[io](../modules/m4m.io.md).converter

## Table of contents

### Constructors

- [constructor](m4m.io.converter.md#constructor)

### Methods

- [ArrayToFloat32](m4m.io.converter.md#arraytofloat32)
- [ArrayToFloat64](m4m.io.converter.md#arraytofloat64)
- [ArrayToInt16](m4m.io.converter.md#arraytoint16)
- [ArrayToInt32](m4m.io.converter.md#arraytoint32)
- [ArrayToInt8](m4m.io.converter.md#arraytoint8)
- [ArrayToLong](m4m.io.converter.md#arraytolong)
- [ArrayToString](m4m.io.converter.md#arraytostring)
- [ArrayToULong](m4m.io.converter.md#arraytoulong)
- [ArrayToUint16](m4m.io.converter.md#arraytouint16)
- [ArrayToUint32](m4m.io.converter.md#arraytouint32)
- [Float32ToArray](m4m.io.converter.md#float32toarray)
- [Float64ToArray](m4m.io.converter.md#float64toarray)
- [Int16ToArray](m4m.io.converter.md#int16toarray)
- [Int32ToArray](m4m.io.converter.md#int32toarray)
- [LongToArray](m4m.io.converter.md#longtoarray)
- [StringToUtf8Array](m4m.io.converter.md#stringtoutf8array)
- [ULongToArray](m4m.io.converter.md#ulongtoarray)
- [Uint16ToArray](m4m.io.converter.md#uint16toarray)
- [Uint32toArray](m4m.io.converter.md#uint32toarray)
- [getApplyFun](m4m.io.converter.md#getapplyfun)

## Constructors

### constructor

• **new converter**()

## Methods

### ArrayToFloat32

▸ `Static` **ArrayToFloat32**(`buf`, `offset?`): `number`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `buf` | `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L122)

___

### ArrayToFloat64

▸ `Static` **ArrayToFloat64**(`buf`, `offset?`): `number`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `buf` | `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:117](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L117)

___

### ArrayToInt16

▸ `Static` **ArrayToInt16**(`buf`, `offset?`): `number`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `buf` | `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:137](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L137)

___

### ArrayToInt32

▸ `Static` **ArrayToInt32**(`buf`, `offset?`): `number`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `buf` | `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:127](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L127)

___

### ArrayToInt8

▸ `Static` **ArrayToInt8**(`buf`, `offset?`): `number`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `buf` | `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:147](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L147)

___

### ArrayToLong

▸ `Static` **ArrayToLong**(`buf`, `offset?`): `number`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `buf` | `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:96](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L96)

___

### ArrayToString

▸ `Static` **ArrayToString**(`buf`, `offset?`): `string`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `buf` | `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |

#### Returns

`string`

#### Defined in

[framework/io/binBuffer.ts:154](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L154)

___

### ArrayToULong

▸ `Static` **ArrayToULong**(`buf`, `offset?`): `number`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `buf` | `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L106)

___

### ArrayToUint16

▸ `Static` **ArrayToUint16**(`buf`, `offset?`): `number`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `buf` | `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L142)

___

### ArrayToUint32

▸ `Static` **ArrayToUint32**(`buf`, `offset?`): `number`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `buf` | `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:132](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L132)

___

### Float32ToArray

▸ `Static` **Float32ToArray**(`value`, `target?`, `offset?`): `number`[] \| `Uint8Array`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `value` | `number` | `undefined` |
| `target` | `number`[] \| `Uint8Array` | `null` |
| `offset` | `number` | `0` |

#### Returns

`number`[] \| `Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L36)

___

### Float64ToArray

▸ `Static` **Float64ToArray**(`value`, `target?`, `offset?`): `number`[] \| `Uint8Array`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `value` | `number` | `undefined` |
| `target` | `number`[] \| `Uint8Array` | `null` |
| `offset` | `number` | `0` |

#### Returns

`number`[] \| `Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L31)

___

### Int16ToArray

▸ `Static` **Int16ToArray**(`value`, `target?`, `offset?`): `number`[] \| `Uint8Array`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `value` | `number` | `undefined` |
| `target` | `number`[] \| `Uint8Array` | `null` |
| `offset` | `number` | `0` |

#### Returns

`number`[] \| `Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L46)

___

### Int32ToArray

▸ `Static` **Int32ToArray**(`value`, `target?`, `offset?`): `number`[] \| `Uint8Array`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `value` | `number` | `undefined` |
| `target` | `number`[] \| `Uint8Array` | `null` |
| `offset` | `number` | `0` |

#### Returns

`number`[] \| `Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L41)

___

### LongToArray

▸ `Static` **LongToArray**(`value`, `t?`, `offset?`): `number`[] \| `Uint8Array`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `value` | `number` | `undefined` |
| `t` | `number`[] \| `Uint8Array` | `null` |
| `offset` | `number` | `0` |

#### Returns

`number`[] \| `Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L20)

___

### StringToUtf8Array

▸ `Static` **StringToUtf8Array**(`str`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `str` | `string` |

#### Returns

`Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L62)

___

### ULongToArray

▸ `Static` **ULongToArray**(`value`, `target?`, `offset?`): `number`[] \| `Uint8Array`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `value` | `number` | `undefined` |
| `target` | `Uint8Array` | `null` |
| `offset` | `number` | `0` |

#### Returns

`number`[] \| `Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L11)

___

### Uint16ToArray

▸ `Static` **Uint16ToArray**(`value`, `target?`, `offset?`): `number`[] \| `Uint8Array`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `value` | `number` | `undefined` |
| `target` | `number`[] \| `Uint8Array` | `null` |
| `offset` | `number` | `0` |

#### Returns

`number`[] \| `Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L57)

___

### Uint32toArray

▸ `Static` **Uint32toArray**(`value`, `target?`, `offset?`): `number`[] \| `Uint8Array`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `value` | `number` | `undefined` |
| `target` | `number`[] \| `Uint8Array` | `null` |
| `offset` | `number` | `0` |

#### Returns

`number`[] \| `Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L51)

___

### getApplyFun

▸ `Static` **getApplyFun**(`value`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`any`

#### Defined in

[framework/io/binBuffer.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L5)
