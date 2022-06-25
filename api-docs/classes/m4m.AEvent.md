[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / AEvent

# Class: AEvent

[m4m](../modules/m4m.md).AEvent

## Hierarchy

- **`AEvent`**

  ↳ [`ParticleSystemEvent`](m4m.framework.ParticleSystemEvent.md)

  ↳ [`InputEvent`](m4m.event.InputEvent.md)

  ↳ [`inputHtmlNativeEvent`](m4m.event.inputHtmlNativeEvent.md)

  ↳ [`Physic2dEvent`](m4m.event.Physic2dEvent.md)

  ↳ [`UIEvent`](m4m.event.UIEvent.md)

## Table of contents

### Methods

- [Emit](m4m.AEvent.md#emit)
- [On](m4m.AEvent.md#on)
- [RemoveListener](m4m.AEvent.md#removelistener)
- [RemoveListenerAll](m4m.AEvent.md#removelistenerall)
- [listenerCount](m4m.AEvent.md#listenercount)

### Constructors

- [constructor](m4m.AEvent.md#constructor)

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

#### Defined in

[framework/event/AEvent.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L40)

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

#### Defined in

[framework/event/AEvent.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L12)

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

#### Defined in

[framework/event/AEvent.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L58)

___

### RemoveListenerAll

▸ **RemoveListenerAll**(): `void`

移除所有监听者

#### Returns

`void`

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

#### Defined in

[framework/event/AEvent.ts:91](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L91)

## Constructors

### constructor

• **new AEvent**()
