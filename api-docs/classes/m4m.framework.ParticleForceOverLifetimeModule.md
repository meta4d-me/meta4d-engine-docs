# m4m.framework.ParticleForceOverLifetimeModule

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleForceOverLifetimeModule

## Class: ParticleForceOverLifetimeModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleForceOverLifetimeModule

粒子系统 作用在粒子上的力随时间变化模块

控制每个粒子在其生命周期内的力。 Script interface for the Force Over Lifetime module.

**`author`** feng3d

### Hierarchy

*   [`ParticleModule`](m4m.framework.ParticleModule.md)

    ↳ **`ParticleForceOverLifetimeModule`**

### Table of contents

#### Constructors

* [constructor](m4m.framework.ParticleForceOverLifetimeModule.md#constructor)

#### Properties

* [enabled](m4m.framework.ParticleForceOverLifetimeModule.md#enabled)
* [force](m4m.framework.ParticleForceOverLifetimeModule.md#force)
* [particleSystem](m4m.framework.ParticleForceOverLifetimeModule.md#particlesystem)
* [randomized](m4m.framework.ParticleForceOverLifetimeModule.md#randomized)
* [space](m4m.framework.ParticleForceOverLifetimeModule.md#space)

#### Methods

* [initParticleState](m4m.framework.ParticleForceOverLifetimeModule.md#initparticlestate)
* [updateParticleState](m4m.framework.ParticleForceOverLifetimeModule.md#updateparticlestate)

#### Accessors

* [x](m4m.framework.ParticleForceOverLifetimeModule.md#x)
* [xMultiplier](m4m.framework.ParticleForceOverLifetimeModule.md#xmultiplier)
* [y](m4m.framework.ParticleForceOverLifetimeModule.md#y)
* [yMultiplier](m4m.framework.ParticleForceOverLifetimeModule.md#ymultiplier)
* [z](m4m.framework.ParticleForceOverLifetimeModule.md#z)
* [zMultiplier](m4m.framework.ParticleForceOverLifetimeModule.md#zmultiplier)

### Constructors

#### constructor

• **new ParticleForceOverLifetimeModule**()

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[constructor](m4m.framework.ParticleModule.md#constructor)

### Properties

#### enabled

• **enabled**: `boolean` = `false`

是否开启

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[enabled](m4m.framework.ParticleModule.md#enabled)

**Defined in**

[framework/particlesystem/modules/ParticleModule.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L14)

***

#### force

• **force**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

作用在粒子上的力

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L17)

***

#### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

粒子系统

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[particleSystem](m4m.framework.ParticleModule.md#particlesystem)

**Defined in**

[framework/particlesystem/modules/ParticleModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L19)

***

#### randomized

• **randomized**: `boolean` = `false`

When randomly selecting values between two curves or constants, this flag will cause a new random force to be chosen on each frame.

当在两条曲线或常数之间随机选择值时，此标志将导致在每一帧上选择一个新的随机力。

**`todo`**

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L34)

***

#### space

• **space**: [`ParticleSystemSimulationSpace`](../enums/m4m.framework.ParticleSystemSimulationSpace.md) = `ParticleSystemSimulationSpace.Local`

Are the forces being applied in local or world space?

这些力是作用于局部空间还是世界空间

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L24)

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

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:130](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L130)

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

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:139](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L139)

### Accessors

#### x

• `get` **x**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The curve defining particle forces in the X axis.

在X轴上定义粒子力的曲线。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L41)

• `set` **x**(`v`): `void`

The curve defining particle forces in the X axis.

在X轴上定义粒子力的曲线。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L46)

***

#### xMultiplier

• `get` **xMultiplier**(): `number`

Change the X axis mulutiplier.

改变X轴的乘数。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L56)

• `set` **xMultiplier**(`v`): `void`

Change the X axis mulutiplier.

改变X轴的乘数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L61)

***

#### y

• `get` **y**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The curve defining particle forces in the Y axis.

在Y轴上定义粒子力的曲线。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L71)

• `set` **y**(`v`): `void`

The curve defining particle forces in the Y axis.

在Y轴上定义粒子力的曲线。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:76](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L76)

***

#### yMultiplier

• `get` **yMultiplier**(): `number`

Change the Y axis mulutiplier.

改变Y轴的乘数。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L86)

• `set` **yMultiplier**(`v`): `void`

Change the Y axis mulutiplier.

改变Y轴的乘数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:91](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L91)

***

#### z

• `get` **z**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The curve defining particle forces in the Z axis.

在Z轴上定义粒子力的曲线。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L101)

• `set` **z**(`v`): `void`

The curve defining particle forces in the Z axis.

在Z轴上定义粒子力的曲线。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L106)

***

#### zMultiplier

• `get` **zMultiplier**(): `number`

Change the Z axis mulutiplier.

改变Z轴的乘数。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L116)

• `set` **zMultiplier**(`v`): `void`

Change the Z axis mulutiplier.

改变Z轴的乘数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleForceOverLifetimeModule.ts#L121)
