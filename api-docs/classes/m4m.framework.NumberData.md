[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / NumberData

# Class: NumberData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).NumberData

## Table of contents

### Properties

- [\_value](m4m.framework.NumberData.md#_value)
- [\_valueLimitMax](m4m.framework.NumberData.md#_valuelimitmax)
- [\_valueLimitMin](m4m.framework.NumberData.md#_valuelimitmin)
- [beInited](m4m.framework.NumberData.md#beinited)
- [isRandom](m4m.framework.NumberData.md#israndom)
- [key](m4m.framework.NumberData.md#key)

### Constructors

- [constructor](m4m.framework.NumberData.md#constructor)

### Methods

- [getValue](m4m.framework.NumberData.md#getvalue)
- [setRandomValue](m4m.framework.NumberData.md#setrandomvalue)
- [setValue](m4m.framework.NumberData.md#setvalue)
- [FormJson](m4m.framework.NumberData.md#formjson)
- [copyto](m4m.framework.NumberData.md#copyto)

## Properties

### \_value

• **\_value**: `number` = `0`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L6)

___

### \_valueLimitMax

• **\_valueLimitMax**: `number` = `0`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L8)

___

### \_valueLimitMin

• **\_valueLimitMin**: `number` = `0`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L7)

___

### beInited

• **beInited**: `boolean` = `false`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L9)

___

### isRandom

• **isRandom**: `boolean` = `false`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L5)

___

### key

• **key**: `number`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L10)

## Constructors

### constructor

• **new NumberData**(`value?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `value` | `number` | `0` |

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L38)

## Methods

### getValue

▸ **getValue**(`reRandom?`): `number`

针对随机类型，只要随机过一次就返回值不变（rerandom=false），返回新的随机值（rerandom=true）

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `reRandom` | `boolean` | `false` |

#### Returns

`number`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L24)

___

### setRandomValue

▸ **setRandomValue**(`max`, `min`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `max` | `number` |
| `min` | `number` |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L15)

___

### setValue

▸ **setValue**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L11)

___

### FormJson

▸ `Static` **FormJson**(`json`, `data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `json` | `string` |
| `data` | [`NumberData`](m4m.framework.NumberData.md) |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L51)

___

### copyto

▸ `Static` **copyto**(`from`, `to`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | [`NumberData`](m4m.framework.NumberData.md) |
| `to` | [`NumberData`](m4m.framework.NumberData.md) |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/data/numberdata.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/numberdata.ts#L43)
