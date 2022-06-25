[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [event](../modules/m4m.event.md) / IUIEventer

# Interface: IUIEventer

[m4m](../modules/m4m.md).[event](../modules/m4m.event.md).IUIEventer

## Implemented by

- [`button`](../classes/m4m.framework.button.md)

## Table of contents

### Methods

- [addListener](m4m.event.IUIEventer.md#addlistener)
- [removeListener](m4m.event.IUIEventer.md#removelistener)

## Methods

### addListener

▸ **addListener**(`eventEnum`, `func`, `thisArg`): `any`

添加事件监听者

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventEnum` | [`UIEventEnum`](../enums/m4m.event.UIEventEnum.md) | 事件类型 |
| `func` | (...`args`: `any`[]) => `void` | 事件触发回调方法 (Warn: 不要使用 func.bind() , 它会导致相等判断失败) |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`any`

#### Defined in

[framework/event/UIEvent.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/UIEvent.ts#L10)

___

### removeListener

▸ **removeListener**(`eventEnum`, `func`, `thisArg`): `any`

移除事件监听者

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventEnum` | [`UIEventEnum`](../enums/m4m.event.UIEventEnum.md) | 事件类型 |
| `func` | (...`args`: `any`[]) => `void` | 事件触发回调方法 |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`any`

#### Defined in

[framework/event/UIEvent.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/UIEvent.ts#L17)
