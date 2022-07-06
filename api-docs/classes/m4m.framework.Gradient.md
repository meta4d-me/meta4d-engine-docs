# m4m.framework.Gradient

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / Gradient

## Class: Gradient

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).Gradient

颜色渐变

**`author`** feng3d

### Table of contents

#### Properties

* [\_\_class\_\_](m4m.framework.Gradient.md#\_\_class\_\_)
* [alphaKeys](m4m.framework.Gradient.md#alphakeys)
* [colorKeys](m4m.framework.Gradient.md#colorkeys)
* [mode](m4m.framework.Gradient.md#mode)

#### Constructors

* [constructor](m4m.framework.Gradient.md#constructor)

#### Methods

* [getAlpha](m4m.framework.Gradient.md#getalpha)
* [getColor](m4m.framework.Gradient.md#getcolor)
* [getValue](m4m.framework.Gradient.md#getvalue)

### Properties

#### \_\_class\_\_

• **\_\_class\_\_**: `"m4m.framework.Gradient"`

**Defined in**

[framework/util/gradient/Gradient.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/Gradient.ts#L10)

***

#### alphaKeys

• **alphaKeys**: [`GradientAlphaKey`](../interfaces/m4m.framework.GradientAlphaKey.md)\[]

在渐变中定义的所有alpha键。

注： 该值已对时间排序，否则赋值前请使用 sort((a, b) => a.time - b.time) 进行排序

**Defined in**

[framework/util/gradient/Gradient.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/Gradient.ts#L24)

***

#### colorKeys

• **colorKeys**: [`GradientColorKey`](../interfaces/m4m.framework.GradientColorKey.md)\[]

在渐变中定义的所有color键。

注： 该值已对时间排序，否则赋值前请使用 sort((a, b) => a.time - b.time) 进行排序

**Defined in**

[framework/util/gradient/Gradient.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/Gradient.ts#L32)

***

#### mode

• **mode**: [`GradientMode`](../enums/m4m.framework.GradientMode.md) = `GradientMode.Blend`

渐变模式

**Defined in**

[framework/util/gradient/Gradient.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/Gradient.ts#L16)

### Constructors

#### constructor

• **new Gradient**()

### Methods

#### getAlpha

▸ **getAlpha**(`time`): `number`

获取透明度

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `time` | `number` | 时间          |

**Returns**

`number`

**Defined in**

[framework/util/gradient/Gradient.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/Gradient.ts#L49)

***

#### getColor

▸ **getColor**(`time`): `color`

获取透明度

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `time` | `number` | 时间          |

**Returns**

`color`

**Defined in**

[framework/util/gradient/Gradient.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/Gradient.ts#L74)

***

#### getValue

▸ **getValue**(`time`): `color`

获取值

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `time` | `number` | 时间          |

**Returns**

`color`

**Defined in**

[framework/util/gradient/Gradient.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/Gradient.ts#L38)
