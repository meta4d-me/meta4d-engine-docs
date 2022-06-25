[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [event](../modules/m4m.event.md) / UIEvent

# Class: UIEvent

[m4m](../modules/m4m.md).[event](../modules/m4m.event.md).UIEvent

**`language`** zh_CN

**`classdesc`**
ui事件

**`version`** m4m 1.0

## Hierarchy

- [`AEvent`](m4m.AEvent.md)

  ↳ **`UIEvent`**

## Table of contents

### Methods

- [Emit](m4m.event.UIEvent.md#emit)
- [EmitEnum](m4m.event.UIEvent.md#emitenum)
- [On](m4m.event.UIEvent.md#on)
- [OnEnum](m4m.event.UIEvent.md#onenum)
- [RemoveListener](m4m.event.UIEvent.md#removelistener)
- [RemoveListenerAll](m4m.event.UIEvent.md#removelistenerall)
- [listenerCount](m4m.event.UIEvent.md#listenercount)

### Constructors

- [constructor](m4m.event.UIEvent.md#constructor)

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
| `event` | [`UIEventEnum`](../enums/m4m.event.UIEventEnum.md) |
| `...args` | `any`[] |

#### Returns

`void`

#### Defined in

[framework/event/UIEvent.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/UIEvent.ts#L34)

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
| `event` | [`UIEventEnum`](../enums/m4m.event.UIEventEnum.md) |
| `func` | (...`args`: `any`[]) => `void` |
| `thisArg` | `any` |

#### Returns

`void`

#### Defined in

[framework/event/UIEvent.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/UIEvent.ts#L31)

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

• **new UIEvent**()

#### Inherited from

[AEvent](m4m.AEvent.md).[constructor](m4m.AEvent.md#constructor)
