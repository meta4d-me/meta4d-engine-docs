[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleLimitVelocityOverLifetimeModule

# Class: ParticleLimitVelocityOverLifetimeModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleLimitVelocityOverLifetimeModule

Limit Velocity Over Lifetime module.

基于时间轴限制速度模块。

**`author`** feng3d

## Hierarchy

- [`ParticleModule`](m4m.framework.ParticleModule.md)

  ↳ **`ParticleLimitVelocityOverLifetimeModule`**

## Table of contents

### Properties

- [\_\_class\_\_](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#__class__)
- [dampen](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#dampen)
- [enabled](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#enabled)
- [limit](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#limit)
- [limit3D](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#limit3d)
- [particleSystem](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#particlesystem)
- [separateAxes](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#separateaxes)
- [space](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#space)

### Constructors

- [constructor](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#constructor)

### Methods

- [initParticleState](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#initparticlestate)
- [updateParticleState](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#updateparticlestate)

### Accessors

- [limitMultiplier](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#limitmultiplier)
- [limitX](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#limitx)
- [limitXMultiplier](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#limitxmultiplier)
- [limitY](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#limity)
- [limitYMultiplier](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#limitymultiplier)
- [limitZ](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#limitz)
- [limitZMultiplier](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md#limitzmultiplier)

## Properties

### \_\_class\_\_

• **\_\_class\_\_**: ``"m4m.framework.ParticleLimitVelocityOverLifetimeModule"``

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L12)

___

### dampen

• **dampen**: `number` = `1`

Controls how much the velocity that exceeds the velocity limit should be dampened.

控制多少速度，超过速度限制应该被抑制。

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L52)

___

### enabled

• **enabled**: `boolean` = `false`

是否开启

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[enabled](m4m.framework.ParticleModule.md#enabled)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L14)

___

### limit

• **limit**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Maximum velocity curve, when not using one curve per axis.

最大速度曲线，当不使用每轴一个曲线时。

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L28)

___

### limit3D

• **limit3D**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

Maximum velocity.

最高速度。

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L36)

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

Set the size over lifetime on each axis separately.

在每个轴上分别设置生命周期内的大小。

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L20)

___

### space

• **space**: [`ParticleSystemSimulationSpace`](../enums/m4m.framework.ParticleSystemSimulationSpace.md) = `ParticleSystemSimulationSpace.Local`

Specifies if the velocities are in local space (rotated with the transform) or world space.

指定速度是在局部空间(与变换一起旋转)还是在世界空间。

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L44)

## Constructors

### constructor

• **new ParticleLimitVelocityOverLifetimeModule**()

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

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:164](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L164)

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

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:174](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L174)

## Accessors

### limitMultiplier

• `get` **limitMultiplier**(): `number`

Change the limit multiplier.

改变限制乘法因子。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L59)

• `set` **limitMultiplier**(`v`): `void`

Change the limit multiplier.

改变限制乘法因子。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L64)

___

### limitX

• `get` **limitX**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Maximum velocity curve for the X axis.

X轴的最大速度曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L74)

• `set` **limitX**(`v`): `void`

Maximum velocity curve for the X axis.

X轴的最大速度曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L79)

___

### limitXMultiplier

• `get` **limitXMultiplier**(): `number`

Change the limit multiplier on the X axis.

改变X轴上的极限乘法器。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L89)

• `set` **limitXMultiplier**(`v`): `void`

Change the limit multiplier on the X axis.

改变X轴上的极限乘法器。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:94](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L94)

___

### limitY

• `get` **limitY**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Maximum velocity curve for the Y axis.

Y轴的最大速度曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:104](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L104)

• `set` **limitY**(`v`): `void`

Maximum velocity curve for the Y axis.

Y轴的最大速度曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:109](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L109)

___

### limitYMultiplier

• `get` **limitYMultiplier**(): `number`

Change the limit multiplier on the Y axis.

改变Y轴上的极限乘法器。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:119](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L119)

• `set` **limitYMultiplier**(`v`): `void`

Change the limit multiplier on the Y axis.

改变Y轴上的极限乘法器。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:124](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L124)

___

### limitZ

• `get` **limitZ**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Maximum velocity curve for the Z axis.

Z轴的最大速度曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L134)

• `set` **limitZ**(`v`): `void`

Maximum velocity curve for the Z axis.

Z轴的最大速度曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:139](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L139)

___

### limitZMultiplier

• `get` **limitZMultiplier**(): `number`

Change the limit multiplier on the Z axis.

更改Z轴上的极限乘法器。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L149)

• `set` **limitZMultiplier**(`v`): `void`

Change the limit multiplier on the Z axis.

更改Z轴上的极限乘法器。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts:154](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleLimitVelocityOverLifetimeModule.ts#L154)
