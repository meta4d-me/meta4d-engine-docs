[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / MinMaxCurve

# Class: MinMaxCurve

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).MinMaxCurve

最大最小曲线

**`author`** feng3d

## Table of contents

### Properties

- [\_\_class\_\_](m4m.framework.MinMaxCurve.md#__class__)
- [between0And1](m4m.framework.MinMaxCurve.md#between0and1)
- [constant](m4m.framework.MinMaxCurve.md#constant)
- [constantMax](m4m.framework.MinMaxCurve.md#constantmax)
- [constantMin](m4m.framework.MinMaxCurve.md#constantmin)
- [curve](m4m.framework.MinMaxCurve.md#curve)
- [curveMax](m4m.framework.MinMaxCurve.md#curvemax)
- [curveMin](m4m.framework.MinMaxCurve.md#curvemin)
- [curveMultiplier](m4m.framework.MinMaxCurve.md#curvemultiplier)
- [mode](m4m.framework.MinMaxCurve.md#mode)

### Constructors

- [constructor](m4m.framework.MinMaxCurve.md#constructor)

### Methods

- [getValue](m4m.framework.MinMaxCurve.md#getvalue)

## Properties

### \_\_class\_\_

• **\_\_class\_\_**: ``"m4m.framework.MinMaxCurve"``

#### Defined in

[framework/util/curve/MinMaxCurve.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L10)

___

### between0And1

• **between0And1**: `boolean` = `false`

是否在编辑器中只显示Y轴 0-1 区域，例如 lifetime 为非负，需要设置为true

#### Defined in

[framework/util/curve/MinMaxCurve.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L77)

___

### constant

• **constant**: `number` = `0`

Set the constant value.

设置常数值。

#### Defined in

[framework/util/curve/MinMaxCurve.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L24)

___

### constantMax

• **constantMax**: `number` = `0`

Set a constant for the upper bound.

为上界设置一个常数。

#### Defined in

[framework/util/curve/MinMaxCurve.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L40)

___

### constantMin

• **constantMin**: `number` = `0`

Set a constant for the lower bound.

为下界设置一个常数。

#### Defined in

[framework/util/curve/MinMaxCurve.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L32)

___

### curve

• **curve**: [`AnimationCurve1`](m4m.framework.AnimationCurve1.md)

Set the curve.

设置曲线。

#### Defined in

[framework/util/curve/MinMaxCurve.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L48)

___

### curveMax

• **curveMax**: [`AnimationCurve1`](m4m.framework.AnimationCurve1.md)

Set a curve for the upper bound.

为上界设置一条曲线。

#### Defined in

[framework/util/curve/MinMaxCurve.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L64)

___

### curveMin

• **curveMin**: [`AnimationCurve1`](m4m.framework.AnimationCurve1.md)

Set a curve for the lower bound.

为下界设置一条曲线。

#### Defined in

[framework/util/curve/MinMaxCurve.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L56)

___

### curveMultiplier

• **curveMultiplier**: `number` = `1`

Set a multiplier to be applied to the curves.

设置一个乘数应用于曲线。

#### Defined in

[framework/util/curve/MinMaxCurve.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L72)

___

### mode

• **mode**: [`MinMaxCurveMode`](../enums/m4m.framework.MinMaxCurveMode.md) = `MinMaxCurveMode.Constant`

模式

#### Defined in

[framework/util/curve/MinMaxCurve.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L16)

## Constructors

### constructor

• **new MinMaxCurve**()

## Methods

### getValue

▸ **getValue**(`time`, `randomBetween?`): `number`

获取值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `time` | `number` | 时间 |
| `randomBetween` | `number` | - |

#### Returns

`number`

#### Defined in

[framework/util/curve/MinMaxCurve.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/MinMaxCurve.ts#L83)
