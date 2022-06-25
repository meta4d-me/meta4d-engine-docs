[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / button

# Class: button

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).button

**`language`** zh_CN

**`classdesc`**
2d按钮组件

**`version`** m4m 1.0

## Implements

- [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)
- [`IUIEventer`](../interfaces/m4m.event.IUIEventer.md)
- [`I2DPointListener`](../interfaces/m4m.framework.I2DPointListener.md)

## Table of contents

### Properties

- [UIEventer](m4m.framework.button.md#uieventer)
- [transform](m4m.framework.button.md#transform)
- [ClassName](m4m.framework.button.md#classname)
- [enablePathDispatch](m4m.framework.button.md#enablepathdispatch)
- [onPath](m4m.framework.button.md#onpath)

### Methods

- [addListener](m4m.framework.button.md#addlistener)
- [onPlay](m4m.framework.button.md#onplay)
- [removeListener](m4m.framework.button.md#removelistener)

### Constructors

- [constructor](m4m.framework.button.md#constructor)

### Accessors

- [fadeDuration](m4m.framework.button.md#fadeduration)
- [normalColor](m4m.framework.button.md#normalcolor)
- [pressedColor](m4m.framework.button.md#pressedcolor)
- [pressedGraphic](m4m.framework.button.md#pressedgraphic)
- [targetImage](m4m.framework.button.md#targetimage)
- [transition](m4m.framework.button.md#transition)

## Properties

### UIEventer

• **UIEventer**: [`UIEvent`](m4m.event.UIEvent.md)

**`language`** zh_CN

**`classdesc`**
点击事件

**`version`** m4m 1.0

#### Defined in

[framework/2d/component/button.ts:322](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L322)

___

### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[transform](../interfaces/m4m.framework.I2DComponent.md#transform)

#### Defined in

[framework/2d/component/button.ts:211](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L211)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"button"`

#### Defined in

[framework/2d/component/button.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L29)

___

### enablePathDispatch

▪ `Static` **enablePathDispatch**: `boolean` = `false`

开启 交互时 路径派发

#### Defined in

[framework/2d/component/button.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L32)

___

### onPath

▪ `Static` **onPath**: (`path`: `string`) => `any`

#### Type declaration

▸ (`path`): `any`

按钮交互时 调用路径返回（需要 enablePathDispatch == true）

##### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

##### Returns

`any`

#### Defined in

[framework/2d/component/button.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L37)

## Methods

### addListener

▸ **addListener**(`eventEnum`, `func`, `thisArg`): `void`

添加UI事件监听者

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventEnum` | [`UIEventEnum`](../enums/m4m.event.UIEventEnum.md) | 事件类型 |
| `func` | (...`args`: `any`[]) => `void` | 事件触发回调方法 (Warn: 不要使用 func.bind() , 它会导致相等判断失败) |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Implementation of

[IUIEventer](../interfaces/m4m.event.IUIEventer.md).[addListener](../interfaces/m4m.event.IUIEventer.md#addlistener)

#### Defined in

[framework/2d/component/button.ts:330](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L330)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[onPlay](../interfaces/m4m.framework.I2DComponent.md#onplay)

#### Defined in

[framework/2d/component/button.ts:200](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L200)

___

### removeListener

▸ **removeListener**(`eventEnum`, `func`, `thisArg`): `void`

移除事件监听者

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventEnum` | [`UIEventEnum`](../enums/m4m.event.UIEventEnum.md) | - |
| `func` | (...`args`: `any`[]) => `void` | 事件触发回调方法 |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Implementation of

[IUIEventer](../interfaces/m4m.event.IUIEventer.md).[removeListener](../interfaces/m4m.event.IUIEventer.md#removelistener)

#### Defined in

[framework/2d/component/button.ts:339](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L339)

## Constructors

### constructor

• **new button**()

## Accessors

### fadeDuration

• `get` **fadeDuration**(): `number`

**`language`** zh_CN

**`classdesc`**
颜色淡出持续时间

**`version`** m4m 1.0

#### Returns

`number`

#### Defined in

[framework/2d/component/button.ts:185](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L185)

• `set` **fadeDuration**(`duration`): `void`

**`language`** zh_CN

**`classdesc`**
颜色淡出持续时间

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `duration` | `number` |

#### Returns

`void`

#### Defined in

[framework/2d/component/button.ts:189](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L189)

___

### normalColor

• `get` **normalColor**(): `color`

**`language`** zh_CN

**`classdesc`**
正常的显示颜色

**`version`** m4m 1.0

#### Returns

`color`

#### Defined in

[framework/2d/component/button.ts:144](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L144)

• `set` **normalColor**(`color`): `void`

**`language`** zh_CN

**`classdesc`**
正常的显示颜色

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `color` | `color` |

#### Returns

`void`

#### Defined in

[framework/2d/component/button.ts:148](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L148)

___

### pressedColor

• `get` **pressedColor**(): `color`

**`language`** zh_CN

**`classdesc`**
按下后的颜色

**`version`** m4m 1.0

#### Returns

`color`

#### Defined in

[framework/2d/component/button.ts:167](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L167)

• `set` **pressedColor**(`color`): `void`

**`language`** zh_CN

**`classdesc`**
按下后的颜色

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `color` | `color` |

#### Returns

`void`

#### Defined in

[framework/2d/component/button.ts:171](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L171)

___

### pressedGraphic

• `get` **pressedGraphic**(): [`sprite`](m4m.framework.sprite.md)

**`language`** zh_CN

**`classdesc`**
按下时要显示的sprite

**`version`** m4m 1.0

#### Returns

[`sprite`](m4m.framework.sprite.md)

#### Defined in

[framework/2d/component/button.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L122)

• `set` **pressedGraphic**(`sprite`): `void`

**`language`** zh_CN

**`classdesc`**
按下时要显示的sprite

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `sprite` | [`sprite`](m4m.framework.sprite.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/button.ts:126](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L126)

___

### targetImage

• `get` **targetImage**(): [`image2D`](m4m.framework.image2D.md)

**`language`** zh_CN

**`classdesc`**
默认显示图像

**`version`** m4m 1.0

#### Returns

[`image2D`](m4m.framework.image2D.md)

#### Defined in

[framework/2d/component/button.ts:85](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L85)

• `set` **targetImage**(`graphic`): `void`

**`language`** zh_CN

**`classdesc`**
默认显示图像

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `graphic` | [`image2D`](m4m.framework.image2D.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/button.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L89)

___

### transition

• `get` **transition**(): [`TransitionType`](../enums/m4m.framework.TransitionType.md)

**`language`** zh_CN

**`classdesc`**
按钮变换类型

**`version`** m4m 1.0

#### Returns

[`TransitionType`](../enums/m4m.framework.TransitionType.md)

#### Defined in

[framework/2d/component/button.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L48)

• `set` **transition**(`transition`): `void`

**`language`** zh_CN

**`classdesc`**
按钮变换类型

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `transition` | [`TransitionType`](../enums/m4m.framework.TransitionType.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/button.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/button.ts#L52)
