# m4m.framework.MinMaxGradient

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / MinMaxGradient

## Class: MinMaxGradient

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).MinMaxGradient

最大最小颜色渐变

**`author`** feng3d

### Table of contents

#### Properties

* [\_\_class\_\_](m4m.framework.MinMaxGradient.md#\_\_class\_\_)
* [color](m4m.framework.MinMaxGradient.md#color)
* [colorMax](m4m.framework.MinMaxGradient.md#colormax)
* [colorMin](m4m.framework.MinMaxGradient.md#colormin)
* [gradient](m4m.framework.MinMaxGradient.md#gradient)
* [gradientMax](m4m.framework.MinMaxGradient.md#gradientmax)
* [gradientMin](m4m.framework.MinMaxGradient.md#gradientmin)
* [mode](m4m.framework.MinMaxGradient.md#mode)

#### Constructors

* [constructor](m4m.framework.MinMaxGradient.md#constructor)

#### Methods

* [getValue](m4m.framework.MinMaxGradient.md#getvalue)

### Properties

#### \_\_class\_\_

• **\_\_class\_\_**: `"m4m.framework.MinMaxGradient"`

**Defined in**

[framework/util/gradient/MinMaxGradient.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/MinMaxGradient.ts#L10)

***

#### color

• **color**: `color`

Set a constant color.

常量颜色值

**Defined in**

[framework/util/gradient/MinMaxGradient.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/MinMaxGradient.ts#L26)

***

#### colorMax

• **colorMax**: `color`

Set a constant color for the upper bound.

为上界设置一个常量颜色。

**Defined in**

[framework/util/gradient/MinMaxGradient.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/MinMaxGradient.ts#L42)

***

#### colorMin

• **colorMin**: `color`

Set a constant color for the lower bound.

为下界设置一个常量颜色。

**Defined in**

[framework/util/gradient/MinMaxGradient.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/MinMaxGradient.ts#L34)

***

#### gradient

• **gradient**: [`Gradient`](m4m.framework.Gradient.md)

Set the gradient.

设置渐变。

**Defined in**

[framework/util/gradient/MinMaxGradient.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/MinMaxGradient.ts#L50)

***

#### gradientMax

• **gradientMax**: [`Gradient`](m4m.framework.Gradient.md)

Set a gradient for the upper bound.

为上界设置一个渐变。

**Defined in**

[framework/util/gradient/MinMaxGradient.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/MinMaxGradient.ts#L66)

***

#### gradientMin

• **gradientMin**: [`Gradient`](m4m.framework.Gradient.md)

Set a gradient for the lower bound.

为下界设置一个渐变。

**Defined in**

[framework/util/gradient/MinMaxGradient.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/MinMaxGradient.ts#L58)

***

#### mode

• **mode**: [`MinMaxGradientMode`](../enums/m4m.framework.MinMaxGradientMode.md) = `MinMaxGradientMode.Color`

Set the mode that the min-max gradient will use to evaluate colors.

设置最小-最大梯度将用于评估颜色的模式。

**Defined in**

[framework/util/gradient/MinMaxGradient.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/MinMaxGradient.ts#L18)

### Constructors

#### constructor

• **new MinMaxGradient**()

### Methods

#### getValue

▸ **getValue**(`time`, `randomBetween?`, `out?`): `color`

获取值

**Parameters**

| Name            | Type     | Description |
| --------------- | -------- | ----------- |
| `time`          | `number` | 时间          |
| `randomBetween` | `number` | -           |
| `out`           | `color`  | -           |

**Returns**

`color`

**Defined in**

[framework/util/gradient/MinMaxGradient.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/gradient/MinMaxGradient.ts#L72)
