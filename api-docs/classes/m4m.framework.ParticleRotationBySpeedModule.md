[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleRotationBySpeedModule

# Class: ParticleRotationBySpeedModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleRotationBySpeedModule

粒子系统 旋转角度随速度变化模块

## Hierarchy

- [`ParticleModule`](m4m.framework.ParticleModule.md)

  ↳ **`ParticleRotationBySpeedModule`**

## Table of contents

### Properties

- [angularVelocity](m4m.framework.ParticleRotationBySpeedModule.md#angularvelocity)
- [enabled](m4m.framework.ParticleRotationBySpeedModule.md#enabled)
- [particleSystem](m4m.framework.ParticleRotationBySpeedModule.md#particlesystem)
- [range](m4m.framework.ParticleRotationBySpeedModule.md#range)
- [separateAxes](m4m.framework.ParticleRotationBySpeedModule.md#separateaxes)

### Constructors

- [constructor](m4m.framework.ParticleRotationBySpeedModule.md#constructor)

### Methods

- [initParticleState](m4m.framework.ParticleRotationBySpeedModule.md#initparticlestate)
- [updateParticleState](m4m.framework.ParticleRotationBySpeedModule.md#updateparticlestate)

### Accessors

- [x](m4m.framework.ParticleRotationBySpeedModule.md#x)
- [xMultiplier](m4m.framework.ParticleRotationBySpeedModule.md#xmultiplier)
- [y](m4m.framework.ParticleRotationBySpeedModule.md#y)
- [yMultiplier](m4m.framework.ParticleRotationBySpeedModule.md#ymultiplier)
- [z](m4m.framework.ParticleRotationBySpeedModule.md#z)
- [zMultiplier](m4m.framework.ParticleRotationBySpeedModule.md#zmultiplier)

## Properties

### angularVelocity

• **angularVelocity**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

角速度，随速度变化的旋转。

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L19)

___

### enabled

• **enabled**: `boolean` = `false`

是否开启

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[enabled](m4m.framework.ParticleModule.md#enabled)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L14)

___

### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

粒子系统

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[particleSystem](m4m.framework.ParticleModule.md#particlesystem)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L19)

___

### range

• **range**: `vector2`

Apply the rotation curve between these minimum and maximum speeds.

在这些最小和最大速度之间应用旋转曲线。

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L26)

___

### separateAxes

• **separateAxes**: `boolean` = `false`

Set the rotation by speed on each axis separately.
在每个轴上分别设置随速度变化的旋转。

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L14)

## Constructors

### constructor

• **new ParticleRotationBySpeedModule**()

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[constructor](m4m.framework.ParticleModule.md#constructor)

## Methods

### initParticleState

▸ **initParticleState**(`particle`): `void`

初始化粒子状态

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) | 粒子 |

#### Returns

`void`

#### Overrides

[ParticleModule](m4m.framework.ParticleModule.md).[initParticleState](m4m.framework.ParticleModule.md#initparticlestate)

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L122)

___

### updateParticleState

▸ **updateParticleState**(`particle`): `void`

更新粒子状态

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) | 粒子 |

#### Returns

`void`

#### Overrides

[ParticleModule](m4m.framework.ParticleModule.md).[updateParticleState](m4m.framework.ParticleModule.md#updateparticlestate)

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:132](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L132)

## Accessors

### x

• `get` **x**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Rotation by speed curve for the X axis.

X轴的旋转随速度变化曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L33)

• `set` **x**(`v`): `void`

Rotation by speed curve for the X axis.

X轴的旋转随速度变化曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L38)

___

### xMultiplier

• `get` **xMultiplier**(): `number`

Rotation multiplier around the X axis.

绕X轴旋转乘法器

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L48)

• `set` **xMultiplier**(`v`): `void`

Rotation multiplier around the X axis.

绕X轴旋转乘法器

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L53)

___

### y

• `get` **y**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Rotation by speed curve for the Y axis.

Y轴的旋转随速度变化曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L63)

• `set` **y**(`v`): `void`

Rotation by speed curve for the Y axis.

Y轴的旋转随速度变化曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L68)

___

### yMultiplier

• `get` **yMultiplier**(): `number`

Rotation multiplier around the Y axis.

绕Y轴旋转乘法器

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L78)

• `set` **yMultiplier**(`v`): `void`

Rotation multiplier around the Y axis.

绕Y轴旋转乘法器

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L83)

___

### z

• `get` **z**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Rotation by speed curve for the Z axis.

Z轴的旋转随速度变化曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L93)

• `set` **z**(`v`): `void`

Rotation by speed curve for the Z axis.

Z轴的旋转随速度变化曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L98)

___

### zMultiplier

• `get` **zMultiplier**(): `number`

Rotation multiplier around the Z axis.

绕Z轴旋转乘法器

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:108](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L108)

• `set` **zMultiplier**(`v`): `void`

Rotation multiplier around the Z axis.

绕Z轴旋转乘法器

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleRotationBySpeedModule.ts:113](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationBySpeedModule.ts#L113)
