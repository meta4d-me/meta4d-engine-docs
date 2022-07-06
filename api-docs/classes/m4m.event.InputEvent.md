# m4m.event.InputEvent

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [event](../modules/m4m.event.md) / InputEvent

## Class: InputEvent

[m4m](../modules/m4m.md).[event](../modules/m4m.event.md).InputEvent

输入事件

### Hierarchy

*   [`AEvent`](m4m.AEvent.md)

    ↳ **`InputEvent`**

### Table of contents

#### Methods

* [Emit](m4m.event.InputEvent.md#emit)
* [EmitEnum\_key](m4m.event.InputEvent.md#emitenum\_key)
* [EmitEnum\_point](m4m.event.InputEvent.md#emitenum\_point)
* [On](m4m.event.InputEvent.md#on)
* [OnEnum\_key](m4m.event.InputEvent.md#onenum\_key)
* [OnEnum\_point](m4m.event.InputEvent.md#onenum\_point)
* [RemoveListener](m4m.event.InputEvent.md#removelistener)
* [RemoveListenerAll](m4m.event.InputEvent.md#removelistenerall)
* [listenerCount](m4m.event.InputEvent.md#listenercount)

#### Constructors

* [constructor](m4m.event.InputEvent.md#constructor)

### Methods

#### Emit

▸ **Emit**(`event`, ...`args`): `void`

发出事件

**Parameters**

| Name      | Type     | Description |
| --------- | -------- | ----------- |
| `event`   | `string` | 事件类型        |
| `...args` | `any`\[] | 传递参数        |

**Returns**

`void`

**Inherited from**

[AEvent](m4m.AEvent.md).[Emit](m4m.AEvent.md#emit)

**Defined in**

[framework/event/AEvent.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L40)

***

#### EmitEnum\_key

▸ **EmitEnum\_key**(`event`, ...`args`): `void`

**Parameters**

| Name      | Type                                                 |
| --------- | ---------------------------------------------------- |
| `event`   | [`KeyEventEnum`](../enums/m4m.event.KeyEventEnum.md) |
| `...args` | `any`\[]                                             |

**Returns**

`void`

**Defined in**

[framework/event/InputEvent.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/InputEvent.ts#L10)

***

#### EmitEnum\_point

▸ **EmitEnum\_point**(`event`, ...`args`): `void`

**Parameters**

| Name      | Type                                                     |
| --------- | -------------------------------------------------------- |
| `event`   | [`PointEventEnum`](../enums/m4m.event.PointEventEnum.md) |
| `...args` | `any`\[]                                                 |

**Returns**

`void`

**Defined in**

[framework/event/InputEvent.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/InputEvent.ts#L19)

***

#### On

▸ **On**(`event`, `func`, `thisArg`): `void`

监听事件添加

**Parameters**

| Name      | Type                            | Description                                    |
| --------- | ------------------------------- | ---------------------------------------------- |
| `event`   | `string`                        | 事件类型                                           |
| `func`    | (...`args`: `any`\[]) => `void` | 事件触发回调方法 (Warn: 不要使用 func.bind() , 它会导致相等判断失败) |
| `thisArg` | `any`                           | 回调方法执行者                                        |

**Returns**

`void`

**Inherited from**

[AEvent](m4m.AEvent.md).[On](m4m.AEvent.md#on)

**Defined in**

[framework/event/AEvent.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L12)

***

#### OnEnum\_key

▸ **OnEnum\_key**(`event`, `func`, `thisArg`): `void`

**Parameters**

| Name      | Type                                                 |
| --------- | ---------------------------------------------------- |
| `event`   | [`KeyEventEnum`](../enums/m4m.event.KeyEventEnum.md) |
| `func`    | (...`args`: `any`\[]) => `void`                      |
| `thisArg` | `any`                                                |

**Returns**

`void`

**Defined in**

[framework/event/InputEvent.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/InputEvent.ts#L6)

***

#### OnEnum\_point

▸ **OnEnum\_point**(`event`, `func`, `thisArg`): `void`

**Parameters**

| Name      | Type                                                     |
| --------- | -------------------------------------------------------- |
| `event`   | [`PointEventEnum`](../enums/m4m.event.PointEventEnum.md) |
| `func`    | (...`args`: `any`\[]) => `void`                          |
| `thisArg` | `any`                                                    |

**Returns**

`void`

**Defined in**

[framework/event/InputEvent.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/InputEvent.ts#L15)

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

• **new InputEvent**()

**Inherited from**

[AEvent](m4m.AEvent.md).[constructor](m4m.AEvent.md#constructor)
