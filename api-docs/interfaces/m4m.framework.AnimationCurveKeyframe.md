# m4m.framework.AnimationCurveKeyframe

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AnimationCurveKeyframe

## Interface: AnimationCurveKeyframe

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AnimationCurveKeyframe

动画关键帧

**`author`** feng3d

### Table of contents

#### Properties

* [inTangent](m4m.framework.AnimationCurveKeyframe.md#intangent)
* [outTangent](m4m.framework.AnimationCurveKeyframe.md#outtangent)
* [time](m4m.framework.AnimationCurveKeyframe.md#time)
* [value](m4m.framework.AnimationCurveKeyframe.md#value)

### Properties

#### inTangent

• **inTangent**: `number`

Describes the tangent when approaching this point from the previous point in the curve.

描述从曲线上的前一点接近该点时的切线。

**Defined in**

[framework/util/curve/AnimationCurveKeyframe.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurveKeyframe.ts#L27)

***

#### outTangent

• **outTangent**: `number`

Describes the tangent when leaving this point towards the next point in the curve.

描述从这个点到曲线上下一个点的切线。

**Defined in**

[framework/util/curve/AnimationCurveKeyframe.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurveKeyframe.ts#L34)

***

#### time

• **time**: `number`

The time of the keyframe.

关键帧的时间。

**Defined in**

[framework/util/curve/AnimationCurveKeyframe.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurveKeyframe.ts#L15)

***

#### value

• **value**: `number`

曲线在关键帧处的值。

**Defined in**

[framework/util/curve/AnimationCurveKeyframe.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/AnimationCurveKeyframe.ts#L20)
