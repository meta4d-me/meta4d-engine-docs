# m4m.framework.tweenUtil

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / tweenUtil

## Class: tweenUtil

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).tweenUtil

tween 工具

### Table of contents

#### Constructors

* [constructor](m4m.framework.tweenUtil.md#constructor)

#### Methods

* [BackEaseIn](m4m.framework.tweenUtil.md#backeasein)
* [BackEaseInOut](m4m.framework.tweenUtil.md#backeaseinout)
* [BackEaseOut](m4m.framework.tweenUtil.md#backeaseout)
* [BackEaseOutIn](m4m.framework.tweenUtil.md#backeaseoutin)
* [BounceEaseIn](m4m.framework.tweenUtil.md#bounceeasein)
* [BounceEaseInOut](m4m.framework.tweenUtil.md#bounceeaseinout)
* [BounceEaseOut](m4m.framework.tweenUtil.md#bounceeaseout)
* [BounceEaseOutIn](m4m.framework.tweenUtil.md#bounceeaseoutin)
* [CircEaseIn](m4m.framework.tweenUtil.md#circeasein)
* [CircEaseInOut](m4m.framework.tweenUtil.md#circeaseinout)
* [CircEaseOut](m4m.framework.tweenUtil.md#circeaseout)
* [CircEaseOutIn](m4m.framework.tweenUtil.md#circeaseoutin)
* [CubicEaseIn](m4m.framework.tweenUtil.md#cubiceasein)
* [CubicEaseInOut](m4m.framework.tweenUtil.md#cubiceaseinout)
* [CubicEaseOut](m4m.framework.tweenUtil.md#cubiceaseout)
* [CubicEaseOutIn](m4m.framework.tweenUtil.md#cubiceaseoutin)
* [ElasticEaseIn](m4m.framework.tweenUtil.md#elasticeasein)
* [ElasticEaseInOut](m4m.framework.tweenUtil.md#elasticeaseinout)
* [ElasticEaseOut](m4m.framework.tweenUtil.md#elasticeaseout)
* [ElasticEaseOutIn](m4m.framework.tweenUtil.md#elasticeaseoutin)
* [ExpoEaseIn](m4m.framework.tweenUtil.md#expoeasein)
* [ExpoEaseInOut](m4m.framework.tweenUtil.md#expoeaseinout)
* [ExpoEaseOut](m4m.framework.tweenUtil.md#expoeaseout)
* [ExpoEaseOutIn](m4m.framework.tweenUtil.md#expoeaseoutin)
* [GetEaseProgress](m4m.framework.tweenUtil.md#geteaseprogress)
* [Linear](m4m.framework.tweenUtil.md#linear)
* [QuadEaseIn](m4m.framework.tweenUtil.md#quadeasein)
* [QuadEaseInOut](m4m.framework.tweenUtil.md#quadeaseinout)
* [QuadEaseOut](m4m.framework.tweenUtil.md#quadeaseout)
* [QuadEaseOutIn](m4m.framework.tweenUtil.md#quadeaseoutin)
* [QuartEaseIn](m4m.framework.tweenUtil.md#quarteasein)
* [QuartEaseInOut](m4m.framework.tweenUtil.md#quarteaseinout)
* [QuartEaseOut](m4m.framework.tweenUtil.md#quarteaseout)
* [QuartEaseOutIn](m4m.framework.tweenUtil.md#quarteaseoutin)
* [QuintEaseIn](m4m.framework.tweenUtil.md#quinteasein)
* [QuintEaseInOut](m4m.framework.tweenUtil.md#quinteaseinout)
* [QuintEaseOut](m4m.framework.tweenUtil.md#quinteaseout)
* [QuintEaseOutIn](m4m.framework.tweenUtil.md#quinteaseoutin)
* [SineEaseIn](m4m.framework.tweenUtil.md#sineeasein)
* [SineEaseInOut](m4m.framework.tweenUtil.md#sineeaseinout)
* [SineEaseOut](m4m.framework.tweenUtil.md#sineeaseout)
* [SineEaseOutIn](m4m.framework.tweenUtil.md#sineeaseoutin)

### Constructors

#### constructor

• **new tweenUtil**()

### Methods

#### BackEaseIn

▸ `Static` **BackEaseIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a back (overshooting cubic easing: (s+1)_t^3 - s_t^2) easing in: accelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:506](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L506)

***

#### BackEaseInOut

▸ `Static` **BackEaseInOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a back (overshooting cubic easing: (s+1)_t^3 - s_t^2) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:514](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L514)

***

#### BackEaseOut

▸ `Static` **BackEaseOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a back (overshooting cubic easing: (s+1)_t^3 - s_t^2) easing out: decelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:498](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L498)

***

#### BackEaseOutIn

▸ `Static` **BackEaseOutIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a back (overshooting cubic easing: (s+1)_t^3 - s_t^2) easing out/in: deceleration until halfway, then acceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:525](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L525)

***

#### BounceEaseIn

▸ `Static` **BounceEaseIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a bounce (exponentially decaying parabolic bounce) easing in: accelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:469](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L469)

***

#### BounceEaseInOut

▸ `Static` **BounceEaseInOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a bounce (exponentially decaying parabolic bounce) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:477](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L477)

***

#### BounceEaseOut

▸ `Static` **BounceEaseOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a bounce (exponentially decaying parabolic bounce) easing out: decelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:454](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L454)

***

#### BounceEaseOutIn

▸ `Static` **BounceEaseOutIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a bounce (exponentially decaying parabolic bounce) easing out/in: deceleration until halfway, then acceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:488](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L488)

***

#### CircEaseIn

▸ `Static` **CircEaseIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a circular (sqrt(1-t^2)) easing in: accelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:181](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L181)

***

#### CircEaseInOut

▸ `Static` **CircEaseInOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a circular (sqrt(1-t^2)) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:189](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L189)

***

#### CircEaseOut

▸ `Static` **CircEaseOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a circular (sqrt(1-t^2)) easing out: decelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:173](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L173)

***

#### CircEaseOutIn

▸ `Static` **CircEaseOutIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a circular (sqrt(1-t^2)) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:200](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L200)

***

#### CubicEaseIn

▸ `Static` **CubicEaseIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a cubic (t^3) easing in: accelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:296](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L296)

***

#### CubicEaseInOut

▸ `Static` **CubicEaseInOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a cubic (t^3) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:304](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L304)

***

#### CubicEaseOut

▸ `Static` **CubicEaseOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a cubic (t^3) easing out: decelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:288](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L288)

***

#### CubicEaseOutIn

▸ `Static` **CubicEaseOutIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a cubic (t^3) easing out/in: deceleration until halfway, then acceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:315](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L315)

***

#### ElasticEaseIn

▸ `Static` **ElasticEaseIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for an elastic (exponentially decaying sine wave) easing in: accelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:414](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L414)

***

#### ElasticEaseInOut

▸ `Static` **ElasticEaseInOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for an elastic (exponentially decaying sine wave) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:428](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L428)

***

#### ElasticEaseOut

▸ `Static` **ElasticEaseOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for an elastic (exponentially decaying sine wave) easing out: decelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:400](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L400)

***

#### ElasticEaseOutIn

▸ `Static` **ElasticEaseOutIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for an elastic (exponentially decaying sine wave) easing out/in: deceleration until halfway, then acceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:444](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L444)

***

#### ExpoEaseIn

▸ `Static` **ExpoEaseIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for an exponential (2^t) easing in: accelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:137](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L137)

***

#### ExpoEaseInOut

▸ `Static` **ExpoEaseInOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for an exponential (2^t) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:145](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L145)

***

#### ExpoEaseOut

▸ `Static` **ExpoEaseOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for an exponential (2^t) easing out: decelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:129](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L129)

***

#### ExpoEaseOutIn

▸ `Static` **ExpoEaseOutIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for an exponential (2^t) easing out/in: deceleration until halfway, then acceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:162](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L162)

***

#### GetEaseProgress

▸ `Static` **GetEaseProgress**(`ease_type`, `linear_progress`): `number`

获取缓动计算后的进度值

**Parameters**

| Name              | Type                                                   | Description      |
| ----------------- | ------------------------------------------------------ | ---------------- |
| `ease_type`       | [`tweenMethod`](../enums/m4m.framework.tweenMethod.md) | 缓动类型             |
| `linear_progress` | `number`                                               | 当前进度值(范围: 0 - 1) |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L14)

***

#### Linear

▸ `Static` **Linear**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a simple linear tweening, with no easing.

**Parameters**

| Name | Type     | Description              |
| ---- | -------- | ------------------------ |
| `t`  | `number` | Current time in seconds. |
| `b`  | `number` | Starting value.          |
| `c`  | `number` | Final value.             |
| `d`  | `number` | Duration of              |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L121)

***

#### QuadEaseIn

▸ `Static` **QuadEaseIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quadratic (t^2) easing in: accelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:219](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L219)

***

#### QuadEaseInOut

▸ `Static` **QuadEaseInOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quadratic (t^2) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:227](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L227)

***

#### QuadEaseOut

▸ `Static` **QuadEaseOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quadratic (t^2) easing out: decelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:211](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L211)

***

#### QuadEaseOutIn

▸ `Static` **QuadEaseOutIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quadratic (t^2) easing out/in: deceleration until halfway, then acceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:238](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L238)

***

#### QuartEaseIn

▸ `Static` **QuartEaseIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quartic (t^4) easing in: accelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:334](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L334)

***

#### QuartEaseInOut

▸ `Static` **QuartEaseInOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quartic (t^4) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:342](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L342)

***

#### QuartEaseOut

▸ `Static` **QuartEaseOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quartic (t^4) easing out: decelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:326](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L326)

***

#### QuartEaseOutIn

▸ `Static` **QuartEaseOutIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quartic (t^4) easing out/in: deceleration until halfway, then acceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:353](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L353)

***

#### QuintEaseIn

▸ `Static` **QuintEaseIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quintic (t^5) easing in: accelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:372](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L372)

***

#### QuintEaseInOut

▸ `Static` **QuintEaseInOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quintic (t^5) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:380](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L380)

***

#### QuintEaseOut

▸ `Static` **QuintEaseOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quintic (t^5) easing out: decelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:364](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L364)

***

#### QuintEaseOutIn

▸ `Static` **QuintEaseOutIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a quintic (t^5) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:390](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L390)

***

#### SineEaseIn

▸ `Static` **SineEaseIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a sinusoidal (sin(t)) easing in: accelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:258](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L258)

***

#### SineEaseInOut

▸ `Static` **SineEaseInOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a sinusoidal (sin(t)) easing in/out: acceleration until halfway, then deceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:266](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L266)

***

#### SineEaseOut

▸ `Static` **SineEaseOut**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a sinusoidal (sin(t)) easing out: decelerating from zero velocity.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:249](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L249)

***

#### SineEaseOutIn

▸ `Static` **SineEaseOutIn**(`t`, `b`, `c`, `d`): `number`

Easing equation function for a sinusoidal (sin(t)) easing in/out: deceleration until halfway, then acceleration.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `t`  | `number` |
| `b`  | `number` |
| `c`  | `number` |
| `d`  | `number` |

**Returns**

`number`

**Defined in**

[framework/util/TweenUtil.ts:277](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/TweenUtil.ts#L277)
