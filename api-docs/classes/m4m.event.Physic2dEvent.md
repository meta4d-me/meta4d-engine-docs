[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [event](../modules/m4m.event.md) / Physic2dEvent

# Class: Physic2dEvent

[m4m](../modules/m4m.md).[event](../modules/m4m.event.md).Physic2dEvent

## Hierarchy

- [`AEvent`](m4m.AEvent.md)

  ↳ **`Physic2dEvent`**

## Table of contents

### Methods

- [Emit](m4m.event.Physic2dEvent.md#emit)
- [EmitEnum](m4m.event.Physic2dEvent.md#emitenum)
- [On](m4m.event.Physic2dEvent.md#on)
- [OnEnum](m4m.event.Physic2dEvent.md#onenum)
- [RemoveListener](m4m.event.Physic2dEvent.md#removelistener)
- [RemoveListenerAll](m4m.event.Physic2dEvent.md#removelistenerall)
- [listenerCount](m4m.event.Physic2dEvent.md#listenercount)

### Constructors

- [constructor](m4m.event.Physic2dEvent.md#constructor)

## Methods

### Emit

▸ **Emit**(`event`, ...`args`): `void`

发出事件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | `string` | 事件类型 |
| `...args` | `any`[] | 传递参数 |

#### Returns

`void`

#### Inherited from

[AEvent](m4m.AEvent.md).[Emit](m4m.AEvent.md#emit)

#### Defined in

[framework/event/AEvent.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L40)

___

### EmitEnum

▸ **EmitEnum**(`event`, ...`args`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`Physic2dEventEnum`](../enums/m4m.event.Physic2dEventEnum.md) |
| `...args` | `any`[] |

#### Returns

`void`

#### Defined in

[framework/event/Physic2dEvent.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/Physic2dEvent.ts#L8)

___

### On

▸ **On**(`event`, `func`, `thisArg`): `void`

监听事件添加

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | `string` | 事件类型 |
| `func` | (...`args`: `any`[]) => `void` | 事件触发回调方法 (Warn: 不要使用 func.bind() , 它会导致相等判断失败) |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Inherited from

[AEvent](m4m.AEvent.md).[On](m4m.AEvent.md#on)

#### Defined in

[framework/event/AEvent.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L12)

___

### OnEnum

▸ **OnEnum**(`event`, `func`, `thisArg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`Physic2dEventEnum`](../enums/m4m.event.Physic2dEventEnum.md) |
| `func` | (...`args`: `any`[]) => `void` |
| `thisArg` | `any` |

#### Returns

`void`

#### Defined in

[framework/event/Physic2dEvent.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/Physic2dEvent.ts#L5)

___

### RemoveListener

▸ **RemoveListener**(`event`, `func`, `thisArg`): `void`

移除事件监听者

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | `string` | 事件类型 |
| `func` | `Function` | 事件触发回调方法 |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Inherited from

[AEvent](m4m.AEvent.md).[RemoveListener](m4m.AEvent.md#removelistener)

#### Defined in

[framework/event/AEvent.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L58)

___

### RemoveListenerAll

▸ **RemoveListenerAll**(): `void`

移除所有监听者

#### Returns

`void`

#### Inherited from

[AEvent](m4m.AEvent.md).[RemoveListenerAll](m4m.AEvent.md#removelistenerall)

#### Defined in

[framework/event/AEvent.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L83)

___

### listenerCount

▸ **listenerCount**(`event`): `number`

指定事件监听者的数量

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `string` |

#### Returns

`number`

#### Inherited from

[AEvent](m4m.AEvent.md).[listenerCount](m4m.AEvent.md#listenercount)

#### Defined in

[framework/event/AEvent.ts:91](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L91)

## Constructors

### constructor

• **new Physic2dEvent**()

#### Inherited from

[AEvent](m4m.AEvent.md).[constructor](m4m.AEvent.md#constructor)
