[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / inputMgr

# Class: inputMgr

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).inputMgr

**`language`** zh_CN

**`classdesc`**
键盘、鼠标(触屏)事件管理类 应用状态机区分状态

**`version`** m4m 1.0

## Table of contents

### Methods

- [CalcuPoint](m4m.framework.inputMgr.md#calcupoint)
- [GetKeyDown](m4m.framework.inputMgr.md#getkeydown)
- [GetKeyUP](m4m.framework.inputMgr.md#getkeyup)
- [KeyDownCount](m4m.framework.inputMgr.md#keydowncount)
- [addHTMLElementListener](m4m.framework.inputMgr.md#addhtmlelementlistener)
- [addKeyListener](m4m.framework.inputMgr.md#addkeylistener)
- [addPointListener](m4m.framework.inputMgr.md#addpointlistener)
- [anyKey](m4m.framework.inputMgr.md#anykey)
- [disableContextMenu](m4m.framework.inputMgr.md#disablecontextmenu)
- [enableContextMenu](m4m.framework.inputMgr.md#enablecontextmenu)
- [isPressed](m4m.framework.inputMgr.md#ispressed)
- [pointCk](m4m.framework.inputMgr.md#pointck)
- [removeHTMLElementListener](m4m.framework.inputMgr.md#removehtmlelementlistener)
- [removeKeyListener](m4m.framework.inputMgr.md#removekeylistener)
- [removePointListener](m4m.framework.inputMgr.md#removepointlistener)
- [update](m4m.framework.inputMgr.md#update)
- [wasPressed](m4m.framework.inputMgr.md#waspressed)

### Constructors

- [constructor](m4m.framework.inputMgr.md#constructor)

### Accessors

- [point](m4m.framework.inputMgr.md#point)
- [touches](m4m.framework.inputMgr.md#touches)
- [wheel](m4m.framework.inputMgr.md#wheel)

## Methods

### CalcuPoint

▸ **CalcuPoint**(`clientX`, `clientY`, `out`): `void`

计算校准html 输入坐标点

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `clientX` | `number` | 输入x |
| `clientY` | `number` | 输入y |
| `out` | [`pointinfo`](m4m.framework.pointinfo.md) | 返回pointinfo |

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:520](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L520)

___

### GetKeyDown

▸ **GetKeyDown**(`name`): `any`

**`language`** zh_CN

**`classdesc`**
获取 指定按键是否Down

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`any`

#### Defined in

[framework/input/inputmgr.ts:463](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L463)

▸ **GetKeyDown**(`key`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | [`KeyCode`](../enums/m4m.event.KeyCode.md) |

#### Returns

`any`

#### Defined in

[framework/input/inputmgr.ts:464](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L464)

___

### GetKeyUP

▸ **GetKeyUP**(`name`): `any`

**`language`** zh_CN

**`classdesc`**
获取 指定按键是否UP

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`any`

#### Defined in

[framework/input/inputmgr.ts:484](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L484)

▸ **GetKeyUP**(`key`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | [`KeyCode`](../enums/m4m.event.KeyCode.md) |

#### Returns

`any`

#### Defined in

[framework/input/inputmgr.ts:485](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L485)

___

### KeyDownCount

▸ **KeyDownCount**(): `number`

按键按下的数量

#### Returns

`number`

#### Defined in

[framework/input/inputmgr.ts:500](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L500)

___

### addHTMLElementListener

▸ **addHTMLElementListener**<`K`\>(`tagName`, `func`, `thisArg`): `void`

添加HTMLElement原生事件监听者

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`inputHtmlNativeEventMap`](../interfaces/m4m.event.inputHtmlNativeEventMap.md) |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `tagName` | `K` | 事件类型名字 |
| `func` | (`ev`: `any`) => `void` | 事件触发回调方法 (Warn: 不要使用 func.bind() , 它会导致相等判断失败) |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:427](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L427)

___

### addKeyListener

▸ **addKeyListener**(`eventEnum`, `func`, `thisArg`): `void`

添加按键事件监听者

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventEnum` | [`KeyEventEnum`](../enums/m4m.event.KeyEventEnum.md) | 事件类型 |
| `func` | (...`args`: `any`[]) => `void` | 事件触发回调方法 (Warn: 不要使用 func.bind() , 它会导致相等判断失败) |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:408](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L408)

___

### addPointListener

▸ **addPointListener**(`eventEnum`, `func`, `thisArg`): `void`

添加point事件监听者

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventEnum` | [`PointEventEnum`](../enums/m4m.event.PointEventEnum.md) | 事件类型 |
| `func` | (...`args`: `any`[]) => `void` | 事件触发回调方法 (Warn: 不要使用 func.bind() , 它会导致相等判断失败) |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:389](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L389)

___

### anyKey

▸ **anyKey**(): `boolean`

任意一按键被按下

#### Returns

`boolean`

#### Defined in

[framework/input/inputmgr.ts:444](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L444)

___

### disableContextMenu

▸ **disableContextMenu**(): `void`

禁用右键菜单

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:371](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L371)

___

### enableContextMenu

▸ **enableContextMenu**(): `void`

启用右键菜单

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:378](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L378)

___

### isPressed

▸ **isPressed**(`button`): `boolean`

按键是否在按下状态

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `button` | `number` | 按键, 0: 左键；1: 中键；2: 右键 |

#### Returns

`boolean`

#### Defined in

[framework/input/inputmgr.ts:355](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L355)

___

### pointCk

▸ **pointCk**(): `void`

point 刷新检查

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:288](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L288)

___

### removeHTMLElementListener

▸ **removeHTMLElementListener**<`K`\>(`tagName`, `func`, `thisArg`): `void`

移除HTMLElement原生事件监听者

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`inputHtmlNativeEventMap`](../interfaces/m4m.event.inputHtmlNativeEventMap.md) |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `tagName` | `K` | 事件类型名字 |
| `func` | (`ev`: `any`) => `void` | 事件触发回调方法 |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:436](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L436)

___

### removeKeyListener

▸ **removeKeyListener**(`eventEnum`, `func`, `thisArg`): `void`

移除按键事件监听者

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventEnum` | [`KeyEventEnum`](../enums/m4m.event.KeyEventEnum.md) | 事件类型 |
| `func` | (...`args`: `any`[]) => `void` | 事件触发回调方法 |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:417](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L417)

___

### removePointListener

▸ **removePointListener**(`eventEnum`, `func`, `thisArg`): `void`

移除point事件监听者

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventEnum` | [`PointEventEnum`](../enums/m4m.event.PointEventEnum.md) | 事件类型 |
| `func` | (...`args`: `any`[]) => `void` | 事件触发回调方法 |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:398](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L398)

___

### update

▸ **update**(`delta`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `any` |

#### Returns

`void`

#### Defined in

[framework/input/inputmgr.ts:274](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L274)

___

### wasPressed

▸ **wasPressed**(`button`): `boolean`

按键被按下一次

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `button` | `number` | 按键, 0: 左键；1: 中键；2: 右键 |

#### Returns

`boolean`

#### Defined in

[framework/input/inputmgr.ts:363](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L363)

## Constructors

### constructor

• **new inputMgr**(`app`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `app` | [`application`](m4m.framework.application.md) |

#### Defined in

[framework/input/inputmgr.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L45)

## Accessors

### point

• `get` **point**(): [`pointinfo`](m4m.framework.pointinfo.md)

#### Returns

[`pointinfo`](m4m.framework.pointinfo.md)

#### Defined in

[framework/input/inputmgr.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L38)

___

### touches

• `get` **touches**(): `Object`

#### Returns

`Object`

#### Defined in

[framework/input/inputmgr.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L40)

___

### wheel

• `get` **wheel**(): `number`

#### Returns

`number`

#### Defined in

[framework/input/inputmgr.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/input/inputmgr.ts#L36)
