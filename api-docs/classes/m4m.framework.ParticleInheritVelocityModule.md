# m4m.framework.ParticleInheritVelocityModule

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleInheritVelocityModule

## Class: ParticleInheritVelocityModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleInheritVelocityModule

The Inherit Velocity Module controls how the velocity of the emitter is transferred to the particles as they are emitted.

遗传速度模块控制发射体的速度在粒子发射时如何传递到粒子上。（只有粒子系统在世界空间中模拟时生效）

### Hierarchy

*   [`ParticleModule`](m4m.framework.ParticleModule.md)

    ↳ **`ParticleInheritVelocityModule`**

### Table of contents

#### Properties

* [\_\_class\_\_](m4m.framework.ParticleInheritVelocityModule.md#\_\_class\_\_)
* [enabled](m4m.framework.ParticleInheritVelocityModule.md#enabled)
* [mode](m4m.framework.ParticleInheritVelocityModule.md#mode)
* [multiplier](m4m.framework.ParticleInheritVelocityModule.md#multiplier)
* [particleSystem](m4m.framework.ParticleInheritVelocityModule.md#particlesystem)

#### Constructors

* [constructor](m4m.framework.ParticleInheritVelocityModule.md#constructor)

#### Accessors

* [curve](m4m.framework.ParticleInheritVelocityModule.md#curve)
* [curveMultiplier](m4m.framework.ParticleInheritVelocityModule.md#curvemultiplier)

#### Methods

* [initParticleState](m4m.framework.ParticleInheritVelocityModule.md#initparticlestate)
* [updateParticleState](m4m.framework.ParticleInheritVelocityModule.md#updateparticlestate)

### Properties

#### \_\_class\_\_

• **\_\_class\_\_**: `"m4m.framework.ParticleInheritVelocityModule"`

**Defined in**

[framework/particlesystem/modules/ParticleInheritVelocityModule.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleInheritVelocityModule.ts#L10)

***

#### enabled

• **enabled**: `boolean` = `false`

是否开启

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[enabled](m4m.framework.ParticleModule.md#enabled)

**Defined in**

[framework/particlesystem/modules/ParticleModule.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L14)

***

#### mode

• **mode**: [`ParticleSystemInheritVelocityMode`](../enums/m4m.framework.ParticleSystemInheritVelocityMode.md) = `ParticleSystemInheritVelocityMode.Initial`

How to apply emitter velocity to particles.

如何将发射体速度应用于粒子。

**Defined in**

[framework/particlesystem/modules/ParticleInheritVelocityModule.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleInheritVelocityModule.ts#L17)

***

#### multiplier

• **multiplier**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Curve to define how much emitter velocity is applied during the lifetime of a particle.

曲线，用来定义在粒子的生命周期内应用了多少发射速度。

**Defined in**

[framework/particlesystem/modules/ParticleInheritVelocityModule.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleInheritVelocityModule.ts#L24)

***

#### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

粒子系统

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[particleSystem](m4m.framework.ParticleModule.md#particlesystem)

**Defined in**

[framework/particlesystem/modules/ParticleModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L19)

### Constructors

#### constructor

• **new ParticleInheritVelocityModule**()

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[constructor](m4m.framework.ParticleModule.md#constructor)

### Accessors

#### curve

• `get` **curve**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Curve to define how much emitter velocity is applied during the lifetime of a particle.

曲线，用来定义在粒子的生命周期内应用了多少发射速度。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleInheritVelocityModule.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleInheritVelocityModule.ts#L31)

• `set` **curve**(`v`): `void`

Curve to define how much emitter velocity is applied during the lifetime of a particle.

曲线，用来定义在粒子的生命周期内应用了多少发射速度。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleInheritVelocityModule.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleInheritVelocityModule.ts#L36)

***

#### curveMultiplier

• `get` **curveMultiplier**(): `number`

Change the curve multiplier.

改变曲线的乘数。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleInheritVelocityModule.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleInheritVelocityModule.ts#L46)

• `set` **curveMultiplier**(`v`): `void`

Change the curve multiplier.

改变曲线的乘数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleInheritVelocityModule.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleInheritVelocityModule.ts#L51)

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

[framework/particlesystem/modules/ParticleInheritVelocityModule.ts:60](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleInheritVelocityModule.ts#L60)

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

[framework/particlesystem/modules/ParticleInheritVelocityModule.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleInheritVelocityModule.ts#L78)
