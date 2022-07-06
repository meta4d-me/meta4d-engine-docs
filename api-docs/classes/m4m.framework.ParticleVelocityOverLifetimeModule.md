# m4m.framework.ParticleVelocityOverLifetimeModule

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleVelocityOverLifetimeModule

## Class: ParticleVelocityOverLifetimeModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleVelocityOverLifetimeModule

粒子系统 速度随时间变化模块

Controls the velocity of each particle during its lifetime. 控制每个粒子在其生命周期内的速度。

**`author`** feng3d

### Hierarchy

*   [`ParticleModule`](m4m.framework.ParticleModule.md)

    ↳ **`ParticleVelocityOverLifetimeModule`**

### Table of contents

#### Properties

* [\_\_class\_\_](m4m.framework.ParticleVelocityOverLifetimeModule.md#\_\_class\_\_)
* [enabled](m4m.framework.ParticleVelocityOverLifetimeModule.md#enabled)
* [particleSystem](m4m.framework.ParticleVelocityOverLifetimeModule.md#particlesystem)
* [space](m4m.framework.ParticleVelocityOverLifetimeModule.md#space)
* [velocity](m4m.framework.ParticleVelocityOverLifetimeModule.md#velocity)

#### Constructors

* [constructor](m4m.framework.ParticleVelocityOverLifetimeModule.md#constructor)

#### Methods

* [initParticleState](m4m.framework.ParticleVelocityOverLifetimeModule.md#initparticlestate)
* [updateParticleState](m4m.framework.ParticleVelocityOverLifetimeModule.md#updateparticlestate)

#### Accessors

* [x](m4m.framework.ParticleVelocityOverLifetimeModule.md#x)
* [xMultiplier](m4m.framework.ParticleVelocityOverLifetimeModule.md#xmultiplier)
* [y](m4m.framework.ParticleVelocityOverLifetimeModule.md#y)
* [yMultiplier](m4m.framework.ParticleVelocityOverLifetimeModule.md#ymultiplier)
* [z](m4m.framework.ParticleVelocityOverLifetimeModule.md#z)
* [zMultiplier](m4m.framework.ParticleVelocityOverLifetimeModule.md#zmultiplier)

### Properties

#### \_\_class\_\_

• **\_\_class\_\_**: `"m4m.framework.ParticleVelocityOverLifetimeModule"`

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L13)

***

#### enabled

• **enabled**: `boolean` = `false`

是否开启

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[enabled](m4m.framework.ParticleModule.md#enabled)

**Defined in**

[framework/particlesystem/modules/ParticleModule.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L14)

***

#### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

粒子系统

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[particleSystem](m4m.framework.ParticleModule.md#particlesystem)

**Defined in**

[framework/particlesystem/modules/ParticleModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L19)

***

#### space

• **space**: [`ParticleSystemSimulationSpace`](../enums/m4m.framework.ParticleSystemSimulationSpace.md) = `ParticleSystemSimulationSpace.Local`

Specifies if the velocities are in local space (rotated with the transform) or world space.

指定速度是在局部空间(与变换一起旋转)还是在世界空间。

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L29)

***

#### velocity

• **velocity**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

Curve to control particle speed based on lifetime.

基于寿命的粒子速度控制曲线。

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L21)

### Constructors

#### constructor

• **new ParticleVelocityOverLifetimeModule**()

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[constructor](m4m.framework.ParticleModule.md#constructor)

### Methods

#### initParticleState

▸ **initParticleState**(`particle`): `void`

初始化粒子状态

**Parameters**

| Name       | Type                                      | Description |
| ---------- | ----------------------------------------- | ----------- |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) | 粒子          |

**Returns**

`void`

**Overrides**

[ParticleModule](m4m.framework.ParticleModule.md).[initParticleState](m4m.framework.ParticleModule.md#initparticlestate)

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:125](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L125)

***

#### updateParticleState

▸ **updateParticleState**(`particle`): `void`

更新粒子状态

**Parameters**

| Name       | Type                                      | Description |
| ---------- | ----------------------------------------- | ----------- |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) | 粒子          |

**Returns**

`void`

**Overrides**

[ParticleModule](m4m.framework.ParticleModule.md).[updateParticleState](m4m.framework.ParticleModule.md#updateparticlestate)

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L134)

### Accessors

#### x

• `get` **x**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Curve to control particle speed based on lifetime, on the X axis.

曲线控制粒子速度基于寿命，在X轴上。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L36)

• `set` **x**(`v`): `void`

Curve to control particle speed based on lifetime, on the X axis.

曲线控制粒子速度基于寿命，在X轴上。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L41)

***

#### xMultiplier

• `get` **xMultiplier**(): `number`

X axis speed multiplier.

X轴速度倍增器。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L51)

• `set` **xMultiplier**(`v`): `void`

X axis speed multiplier.

X轴速度倍增器。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L56)

***

#### y

• `get` **y**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Curve to control particle speed based on lifetime, on the Y axis.

曲线控制粒子速度基于寿命，在Y轴上。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L66)

• `set` **y**(`v`): `void`

Curve to control particle speed based on lifetime, on the Y axis.

曲线控制粒子速度基于寿命，在Y轴上。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L71)

***

#### yMultiplier

• `get` **yMultiplier**(): `number`

Y axis speed multiplier.

Y轴速度倍增器。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L81)

• `set` **yMultiplier**(`v`): `void`

Y axis speed multiplier.

Y轴速度倍增器。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L86)

***

#### z

• `get` **z**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Curve to control particle speed based on lifetime, on the Z axis.

曲线控制粒子速度基于寿命，在Z轴上。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:96](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L96)

• `set` **z**(`v`): `void`

Curve to control particle speed based on lifetime, on the Z axis.

曲线控制粒子速度基于寿命，在Z轴上。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L101)

***

#### zMultiplier

• `get` **zMultiplier**(): `number`

Z axis speed multiplier.

Z轴速度倍增器。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:111](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L111)

• `set` **zMultiplier**(`v`): `void`

Z axis speed multiplier.

Z轴速度倍增器。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleVelocityOverLifetimeModule.ts#L116)
