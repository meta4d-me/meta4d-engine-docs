[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / scrollRect

# Class: scrollRect

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).scrollRect

**`language`** zh_CN

**`classdesc`**
矩形卷轴

**`version`** m4m 1.0

## Implements

- [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)
- [`I2DPointListener`](../interfaces/m4m.framework.I2DPointListener.md)

## Table of contents

### Constructors

- [constructor](m4m.framework.scrollRect.md#constructor)

### Accessors

- [content](m4m.framework.scrollRect.md#content)

### Properties

- [decelerationRate](m4m.framework.scrollRect.md#decelerationrate)
- [horizontal](m4m.framework.scrollRect.md#horizontal)
- [inertia](m4m.framework.scrollRect.md#inertia)
- [onDownFun](m4m.framework.scrollRect.md#ondownfun)
- [onMoveFun](m4m.framework.scrollRect.md#onmovefun)
- [onSlideEndFun](m4m.framework.scrollRect.md#onslideendfun)
- [onUpFun](m4m.framework.scrollRect.md#onupfun)
- [pauseSlide](m4m.framework.scrollRect.md#pauseslide)
- [transform](m4m.framework.scrollRect.md#transform)
- [vertical](m4m.framework.scrollRect.md#vertical)
- [ClassName](m4m.framework.scrollRect.md#classname)

### Methods

- [onPlay](m4m.framework.scrollRect.md#onplay)
- [onPointEvent](m4m.framework.scrollRect.md#onpointevent)
- [remove](m4m.framework.scrollRect.md#remove)
- [start](m4m.framework.scrollRect.md#start)
- [update](m4m.framework.scrollRect.md#update)

## Constructors

### constructor

• **new scrollRect**()

## Accessors

### content

• `get` **content**(): [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh_CN

**`classdesc`**
输入内容label

**`version`** m4m 1.0

#### Returns

[`transform2D`](m4m.framework.transform2D.md)

#### Defined in

[framework/2d/component/scrollRect.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L28)

• `set` **content**(`content`): `void`

**`language`** zh_CN

**`classdesc`**
输入内容label

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `content` | [`transform2D`](m4m.framework.transform2D.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/scrollRect.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L32)

## Properties

### decelerationRate

• **decelerationRate**: `number` = `0.135`

**`language`** zh_CN

**`classdesc`**
惯性减速率

**`version`** m4m 1.0

#### Defined in

[framework/2d/component/scrollRect.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L75)

___

### horizontal

• **horizontal**: `boolean` = `true`

**`language`** zh_CN

**`classdesc`**
水平滑动开启

**`version`** m4m 1.0

#### Defined in

[framework/2d/component/scrollRect.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L45)

___

### inertia

• **inertia**: `boolean` = `true`

**`language`** zh_CN

**`classdesc`**
滑动惯性

**`version`** m4m 1.0

#### Defined in

[framework/2d/component/scrollRect.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L65)

___

### onDownFun

• **onDownFun**: (`x`: `number`, `y`: `number`) => {}

#### Type declaration

▸ (`x`, `y`): `Object`

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

##### Returns

`Object`

#### Defined in

[framework/2d/component/scrollRect.ts:271](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L271)

___

### onMoveFun

• **onMoveFun**: (`x`: `number`, `y`: `number`) => {}

#### Type declaration

▸ (`x`, `y`): `Object`

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

##### Returns

`Object`

#### Defined in

[framework/2d/component/scrollRect.ts:270](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L270)

___

### onSlideEndFun

• **onSlideEndFun**: () => {}

#### Type declaration

▸ (): `Object`

##### Returns

`Object`

#### Defined in

[framework/2d/component/scrollRect.ts:273](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L273)

___

### onUpFun

• **onUpFun**: () => {}

#### Type declaration

▸ (): `Object`

##### Returns

`Object`

#### Defined in

[framework/2d/component/scrollRect.ts:272](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L272)

___

### pauseSlide

• **pauseSlide**: `boolean` = `false`

#### Defined in

[framework/2d/component/scrollRect.ts:92](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L92)

___

### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[transform](../interfaces/m4m.framework.I2DComponent.md#transform)

#### Defined in

[framework/2d/component/scrollRect.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L90)

___

### vertical

• **vertical**: `boolean` = `true`

**`language`** zh_CN

**`classdesc`**
垂直滑动开启

**`version`** m4m 1.0

#### Defined in

[framework/2d/component/scrollRect.ts:55](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L55)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"scrollRect"`

#### Defined in

[framework/2d/component/scrollRect.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L14)

## Methods

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[onPlay](../interfaces/m4m.framework.I2DComponent.md#onplay)

#### Defined in

[framework/2d/component/scrollRect.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L81)

___

### onPointEvent

▸ **onPointEvent**(`canvas`, `ev`, `oncap`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `canvas` | [`canvas`](m4m.framework.canvas.md) |
| `ev` | `PointEvent` |
| `oncap` | `boolean` |

#### Returns

`void`

#### Implementation of

[I2DPointListener](../interfaces/m4m.framework.I2DPointListener.md).[onPointEvent](../interfaces/m4m.framework.I2DPointListener.md#onpointevent)

#### Defined in

[framework/2d/component/scrollRect.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L93)

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[remove](../interfaces/m4m.framework.I2DComponent.md#remove)

#### Defined in

[framework/2d/component/scrollRect.ts:274](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L274)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[start](../interfaces/m4m.framework.I2DComponent.md#start)

#### Defined in

[framework/2d/component/scrollRect.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L77)

___

### update

▸ **update**(`delta`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`void`

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[update](../interfaces/m4m.framework.I2DComponent.md#update)

#### Defined in

[framework/2d/component/scrollRect.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/scrollRect.ts#L86)
