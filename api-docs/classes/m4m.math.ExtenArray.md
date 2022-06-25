[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [math](../modules/m4m.math.md) / ExtenArray

# Class: ExtenArray<T\>

[m4m](../modules/m4m.md).[math](../modules/m4m.math.md).ExtenArray

动态延长 Array

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `Uint8Array` \| `Uint16Array` \| `Uint32Array` \| `Int8Array` \| `Int16Array` \| `Int32Array` \| `Float32Array` \| `Float64Array` |

## Table of contents

### Accessors

- [buffer](m4m.math.ExtenArray.md#buffer)
- [count](m4m.math.ExtenArray.md#count)

### Constructors

- [constructor](m4m.math.ExtenArray.md#constructor)

### Methods

- [dispose](m4m.math.ExtenArray.md#dispose)
- [push](m4m.math.ExtenArray.md#push)

## Accessors

### buffer

• `get` **buffer**(): `T`

定长数组

#### Returns

`T`

#### Defined in

[render/struct.ts:602](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L602)

___

### count

• `get` **count**(): `number`

已经使用到数量

#### Returns

`number`

#### Defined in

[render/struct.ts:604](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L604)

• `set` **count**(`val`): `void`

已经使用到数量

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `number` |

#### Returns

`void`

#### Defined in

[render/struct.ts:605](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L605)

## Constructors

### constructor

• **new ExtenArray**<`T`\>(`bufferType`, `initSize?`)

动态延长 Array

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `Int8Array` \| `Uint8Array` \| `Int16Array` \| `Uint16Array` \| `Int32Array` \| `Uint32Array` \| `Float32Array` \| `Float64Array` |

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `bufferType` | (`size`: `number`) => `T` | `undefined` | buffer类型 |
| `initSize` | `number` | `32` | 初始array 长度 |

#### Defined in

[render/struct.ts:619](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L619)

## Methods

### dispose

▸ **dispose**(): `void`

对象清理

#### Returns

`void`

#### Defined in

[render/struct.ts:652](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L652)

___

### push

▸ **push**(`num`): `void`

push添加到array

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[render/struct.ts:627](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L627)
