# m4m.framework.slideArea

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / slideArea

## Class: slideArea

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).slideArea

**`language`** zh\_CN

**`classdesc`** 滑动区域

**`version`** m4m 1.0

### Implements

* [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)
* [`I2DPointListener`](../interfaces/m4m.framework.I2DPointListener.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.slideArea.md#constructor)

#### Properties

* [horizontal](m4m.framework.slideArea.md#horizontal)
* [onDownFun](m4m.framework.slideArea.md#ondownfun)
* [onMoveFun](m4m.framework.slideArea.md#onmovefun)
* [onUpFun](m4m.framework.slideArea.md#onupfun)
* [transform](m4m.framework.slideArea.md#transform)
* [vertical](m4m.framework.slideArea.md#vertical)
* [ClassName](m4m.framework.slideArea.md#classname)

#### Methods

* [onPlay](m4m.framework.slideArea.md#onplay)
* [onPointEvent](m4m.framework.slideArea.md#onpointevent)
* [remove](m4m.framework.slideArea.md#remove)
* [start](m4m.framework.slideArea.md#start)
* [update](m4m.framework.slideArea.md#update)

### Constructors

#### constructor

• **new slideArea**()

### Properties

#### horizontal

• **horizontal**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 水平滑动开启

**`version`** m4m 1.0

**Defined in**

[framework/2d/component/slideArea.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L23)

***

#### onDownFun

• **onDownFun**: (`x`: `number`, `y`: `number`) => {}

**Type declaration**

▸ (`x`, `y`): `Object`

**Parameters**

| Name | Type     |
| ---- | -------- |
| `x`  | `number` |
| `y`  | `number` |

**Returns**

`Object`

**Defined in**

[framework/2d/component/slideArea.ts:99](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L99)

***

#### onMoveFun

• **onMoveFun**: (`x`: `number`, `y`: `number`) => {}

**Type declaration**

▸ (`x`, `y`): `Object`

**Parameters**

| Name | Type     |
| ---- | -------- |
| `x`  | `number` |
| `y`  | `number` |

**Returns**

`Object`

**Defined in**

[framework/2d/component/slideArea.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L98)

***

#### onUpFun

• **onUpFun**: () => {}

**Type declaration**

▸ (): `Object`

**Returns**

`Object`

**Defined in**

[framework/2d/component/slideArea.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L100)

***

#### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

**Implementation of**

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[transform](../interfaces/m4m.framework.I2DComponent.md#transform)

**Defined in**

[framework/2d/component/slideArea.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L43)

***

#### vertical

• **vertical**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 垂直滑动开启

**`version`** m4m 1.0

**Defined in**

[framework/2d/component/slideArea.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L33)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"slideArea"`

**Defined in**

[framework/2d/component/slideArea.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L11)

### Methods

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[onPlay](../interfaces/m4m.framework.I2DComponent.md#onplay)

**Defined in**

[framework/2d/component/slideArea.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L38)

***

#### onPointEvent

▸ **onPointEvent**(`canvas`, `ev`, `oncap`): `void`

**Parameters**

| Name     | Type                                |
| -------- | ----------------------------------- |
| `canvas` | [`canvas`](m4m.framework.canvas.md) |
| `ev`     | `PointEvent`                        |
| `oncap`  | `boolean`                           |

**Returns**

`void`

**Implementation of**

[I2DPointListener](../interfaces/m4m.framework.I2DPointListener.md).[onPointEvent](../interfaces/m4m.framework.I2DPointListener.md#onpointevent)

**Defined in**

[framework/2d/component/slideArea.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L44)

***

#### remove

▸ **remove**(): `void`

**Returns**

`void`

**Implementation of**

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[remove](../interfaces/m4m.framework.I2DComponent.md#remove)

**Defined in**

[framework/2d/component/slideArea.ts:104](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L104)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[start](../interfaces/m4m.framework.I2DComponent.md#start)

**Defined in**

[framework/2d/component/slideArea.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L35)

***

#### update

▸ **update**(`delta`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Implementation of**

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[update](../interfaces/m4m.framework.I2DComponent.md#update)

**Defined in**

[framework/2d/component/slideArea.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/slideArea.ts#L41)
