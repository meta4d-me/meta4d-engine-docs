# m4m.threading.gdPromise

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [threading](../modules/m4m.threading.md) / gdPromise

## Class: gdPromise\<T>

[m4m](../modules/m4m.md).[threading](../modules/m4m.threading.md).gdPromise

### Type parameters

| Name |
| ---- |
| `T`  |

### Table of contents

#### Methods

* [catch](m4m.threading.gdPromise.md#catch)
* [reject](m4m.threading.gdPromise.md#reject)
* [resolve](m4m.threading.gdPromise.md#resolve)
* [then](m4m.threading.gdPromise.md#then)

#### Constructors

* [constructor](m4m.threading.gdPromise.md#constructor)

### Methods

#### catch

▸ **catch**(`callbcack`): [`gdPromise`](m4m.threading.gdPromise.md)<`T`>

**Parameters**

| Name        | Type                     |
| ----------- | ------------------------ |
| `callbcack` | (`val`: `any`) => `void` |

**Returns**

[`gdPromise`](m4m.threading.gdPromise.md)<`T`>

**Defined in**

[framework/threading/gdPromise.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/threading/gdPromise.ts#L48)

***

#### reject

▸ **reject**(`reason?`): `void`

**Parameters**

| Name      | Type  |
| --------- | ----- |
| `reason?` | `any` |

**Returns**

`void`

**Defined in**

[framework/threading/gdPromise.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/threading/gdPromise.ts#L33)

***

#### resolve

▸ **resolve**(`value?`): `void`

**Parameters**

| Name     | Type |
| -------- | ---- |
| `value?` | `T`  |

**Returns**

`void`

**Defined in**

[framework/threading/gdPromise.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/threading/gdPromise.ts#L17)

***

#### then

▸ **then**(`thenCall`): [`gdPromise`](m4m.threading.gdPromise.md)<`T`>

**Parameters**

| Name       | Type                      |
| ---------- | ------------------------- |
| `thenCall` | (`value?`: `T`) => `void` |

**Returns**

[`gdPromise`](m4m.threading.gdPromise.md)<`T`>

**Defined in**

[framework/threading/gdPromise.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/threading/gdPromise.ts#L41)

### Constructors

#### constructor

• **new gdPromise**<`T`>(`executor`)

**Type parameters**

| Name |
| ---- |
| `T`  |

**Parameters**

| Name       | Type                                                                                     |
| ---------- | ---------------------------------------------------------------------------------------- |
| `executor` | (`resolve`: (`value?`: `T`) => `void`, `reject`: (`reason?`: `any`) => `void`) => `void` |

**Defined in**

[framework/threading/gdPromise.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/threading/gdPromise.ts#L9)
