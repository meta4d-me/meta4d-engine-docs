# m4m.event.inputHtmlNativeEvent

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [event](../modules/m4m.event.md) / inputHtmlNativeEvent

## Class: inputHtmlNativeEvent

[m4m](../modules/m4m.md).[event](../modules/m4m.event.md).inputHtmlNativeEvent

输入htmlElement 原生事件

### Hierarchy

*   [`AEvent`](m4m.AEvent.md)

    ↳ **`inputHtmlNativeEvent`**

### Table of contents

#### Methods

* [Emit](m4m.event.inputHtmlNativeEvent.md#emit)
* [On](m4m.event.inputHtmlNativeEvent.md#on)
* [RemoveListener](m4m.event.inputHtmlNativeEvent.md#removelistener)
* [RemoveListenerAll](m4m.event.inputHtmlNativeEvent.md#removelistenerall)
* [listenerCount](m4m.event.inputHtmlNativeEvent.md#listenercount)

#### Constructors

* [constructor](m4m.event.inputHtmlNativeEvent.md#constructor)

### Methods

#### Emit

▸ **Emit**<`K`>(`tagName`, `ev`): `void`

发出事件

**Type parameters**

| Name | Type                                                                                          |
| ---- | --------------------------------------------------------------------------------------------- |
| `K`  | extends keyof [`inputHtmlNativeEventMap`](../interfaces/m4m.event.inputHtmlNativeEventMap.md) |

**Parameters**

| Name      | Type  |
| --------- | ----- |
| `tagName` | `K`   |
| `ev`      | `any` |

**Returns**

`void`

**Overrides**

[AEvent](m4m.AEvent.md).[Emit](m4m.AEvent.md#emit)

**Defined in**

[framework/event/InputEvent.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/InputEvent.ts#L52)

***

#### On

▸ **On**<`K`>(`tagName`, `func`, `thisArg`): `void`

监听事件添加

**Type parameters**

| Name | Type                                                                                          |
| ---- | --------------------------------------------------------------------------------------------- |
| `K`  | extends keyof [`inputHtmlNativeEventMap`](../interfaces/m4m.event.inputHtmlNativeEventMap.md) |

**Parameters**

| Name      | Type                    |
| --------- | ----------------------- |
| `tagName` | `K`                     |
| `func`    | (`ev`: `any`) => `void` |
| `thisArg` | `any`                   |

**Returns**

`void`

**Overrides**

[AEvent](m4m.AEvent.md).[On](m4m.AEvent.md#on)

**Defined in**

[framework/event/InputEvent.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/InputEvent.ts#L48)

***

#### RemoveListener

▸ **RemoveListener**(`event`, `func`, `thisArg`): `void`

移除事件监听者

**Parameters**

| Name      | Type       | Description |
| --------- | ---------- | ----------- |
| `event`   | `string`   | 事件类型        |
| `func`    | `Function` | 事件触发回调方法    |
| `thisArg` | `any`      | 回调方法执行者     |

**Returns**

`void`

**Inherited from**

[AEvent](m4m.AEvent.md).[RemoveListener](m4m.AEvent.md#removelistener)

**Defined in**

[framework/event/AEvent.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L58)

***

#### RemoveListenerAll

▸ **RemoveListenerAll**(): `void`

移除所有监听者

**Returns**

`void`

**Inherited from**

[AEvent](m4m.AEvent.md).[RemoveListenerAll](m4m.AEvent.md#removelistenerall)

**Defined in**

[framework/event/AEvent.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L83)

***

#### listenerCount

▸ **listenerCount**(`event`): `number`

指定事件监听者的数量

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `event` | `string` |

**Returns**

`number`

**Inherited from**

[AEvent](m4m.AEvent.md).[listenerCount](m4m.AEvent.md#listenercount)

**Defined in**

[framework/event/AEvent.ts:91](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L91)

### Constructors

#### constructor

• **new inputHtmlNativeEvent**()

**Inherited from**

[AEvent](m4m.AEvent.md).[constructor](m4m.AEvent.md#constructor)
