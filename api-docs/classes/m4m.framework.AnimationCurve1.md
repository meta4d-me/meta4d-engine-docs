[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AnimationCurve1

# Class: AnimationCurve1

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AnimationCurve1

动画曲线

基于时间轴的连续三阶Bézier曲线

**`author`** feng3d

## Table of contents

### Properties

- [\_\_class\_\_](m4m.framework.AnimationCurve1.md#__class__)
- [keys](m4m.framework.AnimationCurve1.md#keys)
- [maxtan](m4m.framework.AnimationCurve1.md#maxtan)
- [postWrapMode](m4m.framework.AnimationCurve1.md#postwrapmode)
- [preWrapMode](m4m.framework.AnimationCurve1.md#prewrapmode)

### Methods

- [addKey](m4m.framework.AnimationCurve1.md#addkey)
- [addKeyAtCurve](m4m.framework.AnimationCurve1.md#addkeyatcurve)
- [deleteKey](m4m.framework.AnimationCurve1.md#deletekey)
- [findKey](m4m.framework.AnimationCurve1.md#findkey)
- [getKey](m4m.framework.AnimationCurve1.md#getkey)
- [getPoint](m4m.framework.AnimationCurve1.md#getpoint)
- [getSamples](m4m.framework.AnimationCurve1.md#getsamples)
- [getValue](m4m.framework.AnimationCurve1.md#getvalue)
- [indexOfKeys](m4m.framework.AnimationCurve1.md#indexofkeys)
- [sort](m4m.framework.AnimationCurve1.md#sort)

### Constructors

- [constructor](m4m.framework.AnimationCurve1.md#constructor)

### Accessors

- [numKeys](m4m.framework.AnimationCurve1.md#numkeys)

## Properties

### \_\_class\_\_

• **\_\_class\_\_**: ``"m4m.framework.AnimationCurve1"``

#### Defined in

[framework/util/curve/AnimationCurve.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L13)

___

### keys

• **keys**: [`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)[]

All keys defined in the animation curve.

动画曲线上所有关键字定义。

注： 该值已对时间排序，否则赋值前请使用 sort((a, b) => a.time - b.time) 进行排序

#### Defined in

[framework/util/curve/AnimationCurve.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L44)

___

### maxtan

• **maxtan**: `number` = `1000`

最大tan值，超出该值后将会变成分段

#### Defined in

[framework/util/curve/AnimationCurve.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L18)

___

### postWrapMode

• **postWrapMode**: [`AnimationCurveWrapMode`](../enums/m4m.framework.AnimationCurveWrapMode.md) = `AnimationCurveWrapMode.Clamp`

The behaviour of the animation after the last keyframe.

动画在最后一个关键帧之后的行为。

#### Defined in

[framework/util/curve/AnimationCurve.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L34)

___

### preWrapMode

• **preWrapMode**: [`AnimationCurveWrapMode`](../enums/m4m.framework.AnimationCurveWrapMode.md) = `AnimationCurveWrapMode.Clamp`

The behaviour of the animation before the first keyframe.

在第一个关键帧之前的动画行为。

#### Defined in

[framework/util/curve/AnimationCurve.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L26)

## Methods

### addKey

▸ **addKey**(`key`): `void`

添加关键点

添加关键点后将会执行按t进行排序

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | [`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md) | 关键点 |

#### Returns

`void`

#### Defined in

[framework/util/curve/AnimationCurve.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L61)

___

### addKeyAtCurve

▸ **addKeyAtCurve**(`time`, `value`, `precision`): [`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)

添加曲线上的关键点

如果该点在曲线上，则添加关键点

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `time` | `number` | 时间轴的位置 [0,1] |
| `value` | `number` | 值 |
| `precision` | `number` | 查找进度 |

#### Returns

[`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)

#### Defined in

[framework/util/curve/AnimationCurve.ts:226](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L226)

___

### deleteKey

▸ **deleteKey**(`key`): `void`

删除关键点

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | [`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md) | 关键点 |

#### Returns

`void`

#### Defined in

[framework/util/curve/AnimationCurve.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L81)

___

### findKey

▸ **findKey**(`t`, `y`, `precision`): [`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)

查找关键点

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 时间轴的位置 [0,1] |
| `y` | `number` | 值 |
| `precision` | `number` | 查找精度 |

#### Returns

[`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)

#### Defined in

[framework/util/curve/AnimationCurve.ts:204](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L204)

___

### getKey

▸ **getKey**(`index`): [`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)

获取关键点

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `number` | 索引 |

#### Returns

[`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)

#### Defined in

[framework/util/curve/AnimationCurve.ts:92](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L92)

___

### getPoint

▸ **getPoint**(`t`): [`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)

获取曲线上点信息

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 时间轴的位置 [0,1] |

#### Returns

[`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)

#### Defined in

[framework/util/curve/AnimationCurve.ts:110](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L110)

___

### getSamples

▸ **getSamples**(`num?`): [`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)[]

获取曲线样本数据

这些点可用于连线来拟合曲线。

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `num` | `number` | `100` | 采样次数 ，采样点分别为[0,1/num,2/num,....,(num-1)/num,1] |

#### Returns

[`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md)[]

#### Defined in

[framework/util/curve/AnimationCurve.ts:245](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L245)

___

### getValue

▸ **getValue**(`t`): `number`

获取值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 时间轴的位置 [0,1] |

#### Returns

`number`

#### Defined in

[framework/util/curve/AnimationCurve.ts:191](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L191)

___

### indexOfKeys

▸ **indexOfKeys**(`key`): `number`

获取关键点索引

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | [`AnimationCurveKeyframe`](../interfaces/m4m.framework.AnimationCurveKeyframe.md) | 关键点 |

#### Returns

`number`

#### Defined in

[framework/util/curve/AnimationCurve.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L101)

___

### sort

▸ **sort**(): `void`

关键点排序

当移动关键点或者新增关键点时需要再次排序

#### Returns

`void`

#### Defined in

[framework/util/curve/AnimationCurve.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L72)

## Constructors

### constructor

• **new AnimationCurve1**()

## Accessors

### numKeys

• `get` **numKeys**(): `number`

关键点数量

#### Returns

`number`

#### Defined in

[framework/util/curve/AnimationCurve.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurve.ts#L49)
