[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [threading](../modules/m4m.threading.md) / thread

# Class: thread

[m4m](../modules/m4m.md).[threading](../modules/m4m.threading.md).thread

## Table of contents

### Methods

- [Call](m4m.threading.thread.md#call)
- [OnMessage](m4m.threading.thread.md#onmessage)

### Constructors

- [constructor](m4m.threading.thread.md#constructor)

### Accessors

- [Instance](m4m.threading.thread.md#instance)

### Properties

- [workerInstance](m4m.threading.thread.md#workerinstance)

## Methods

### Call

▸ **Call**(`name`, `data`, `callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `data` | `any` |
| `callback` | (`result`: `any`) => `void` |

#### Returns

`void`

#### Defined in

[framework/threading/thread.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/threading/thread.ts#L48)

___

### OnMessage

▸ **OnMessage**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MessageEvent`<`any`\> |

#### Returns

`void`

#### Defined in

[framework/threading/thread.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/threading/thread.ts#L40)

## Constructors

### constructor

• **new thread**()

#### Defined in

[framework/threading/thread.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/threading/thread.ts#L19)

## Accessors

### Instance

• `Static` `get` **Instance**(): [`thread`](m4m.threading.thread.md)

#### Returns

[`thread`](m4m.threading.thread.md)

#### Defined in

[framework/threading/thread.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/threading/thread.ts#L9)

## Properties

### workerInstance

▪ `Static` **workerInstance**: `Worker`

#### Defined in

[framework/threading/thread.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/threading/thread.ts#L5)
