[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleRotationOverLifetimeModule

# Class: ParticleRotationOverLifetimeModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleRotationOverLifetimeModule

粒子系统 旋转角度随时间变化模块

**`author`** feng3d

## Hierarchy

- [`ParticleModule`](m4m.framework.ParticleModule.md)

  ↳ **`ParticleRotationOverLifetimeModule`**

## Table of contents

### Properties

- [angularVelocity](m4m.framework.ParticleRotationOverLifetimeModule.md#angularvelocity)
- [enabled](m4m.framework.ParticleRotationOverLifetimeModule.md#enabled)
- [particleSystem](m4m.framework.ParticleRotationOverLifetimeModule.md#particlesystem)
- [separateAxes](m4m.framework.ParticleRotationOverLifetimeModule.md#separateaxes)

### Constructors

- [constructor](m4m.framework.ParticleRotationOverLifetimeModule.md#constructor)

### Methods

- [initParticleState](m4m.framework.ParticleRotationOverLifetimeModule.md#initparticlestate)
- [updateParticleState](m4m.framework.ParticleRotationOverLifetimeModule.md#updateparticlestate)

### Accessors

- [x](m4m.framework.ParticleRotationOverLifetimeModule.md#x)
- [xMultiplier](m4m.framework.ParticleRotationOverLifetimeModule.md#xmultiplier)
- [y](m4m.framework.ParticleRotationOverLifetimeModule.md#y)
- [yMultiplier](m4m.framework.ParticleRotationOverLifetimeModule.md#ymultiplier)
- [z](m4m.framework.ParticleRotationOverLifetimeModule.md#z)
- [zMultiplier](m4m.framework.ParticleRotationOverLifetimeModule.md#zmultiplier)

## Properties

### angularVelocity

• **angularVelocity**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

角速度，基于生命周期的旋转。

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L21)

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

### separateAxes

• **separateAxes**: `boolean` = `false`

Set the rotation over lifetime on each axis separately.
在每个轴上分别设置基于生命周期的旋转。

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L15)

## Constructors

### constructor

• **new ParticleRotationOverLifetimeModule**()

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

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:117](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L117)

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

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:127](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L127)

## Accessors

### x

• `get` **x**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Rotation over lifetime curve for the X axis.

X轴的旋转寿命曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L28)

• `set` **x**(`v`): `void`

Rotation over lifetime curve for the X axis.

X轴的旋转寿命曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L33)

___

### xMultiplier

• `get` **xMultiplier**(): `number`

Rotation multiplier around the X axis.

绕X轴旋转乘法器

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L43)

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

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L48)

___

### y

• `get` **y**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Rotation over lifetime curve for the Y axis.

Y轴的旋转寿命曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L58)

• `set` **y**(`v`): `void`

Rotation over lifetime curve for the Y axis.

Y轴的旋转寿命曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L63)

___

### yMultiplier

• `get` **yMultiplier**(): `number`

Rotation multiplier around the Y axis.

绕Y轴旋转乘法器

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:73](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L73)

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

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L78)

___

### z

• `get` **z**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Rotation over lifetime curve for the Z axis.

Z轴的旋转寿命曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L88)

• `set` **z**(`v`): `void`

Rotation over lifetime curve for the Z axis.

Z轴的旋转寿命曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L93)

___

### zMultiplier

• `get` **zMultiplier**(): `number`

Rotation multiplier around the Z axis.

绕Z轴旋转乘法器

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L103)

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

[framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts:108](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleRotationOverLifetimeModule.ts#L108)
