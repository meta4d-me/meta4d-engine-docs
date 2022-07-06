# m4m.framework.ParticleSizeOverLifetimeModule

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSizeOverLifetimeModule

## Class: ParticleSizeOverLifetimeModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSizeOverLifetimeModule

粒子系统 缩放随时间变化模块

**`author`** feng3d

### Hierarchy

*   [`ParticleModule`](m4m.framework.ParticleModule.md)

    ↳ **`ParticleSizeOverLifetimeModule`**

### Table of contents

#### Constructors

* [constructor](m4m.framework.ParticleSizeOverLifetimeModule.md#constructor)

#### Properties

* [enabled](m4m.framework.ParticleSizeOverLifetimeModule.md#enabled)
* [particleSystem](m4m.framework.ParticleSizeOverLifetimeModule.md#particlesystem)
* [separateAxes](m4m.framework.ParticleSizeOverLifetimeModule.md#separateaxes)
* [size3D](m4m.framework.ParticleSizeOverLifetimeModule.md#size3d)

#### Methods

* [initParticleState](m4m.framework.ParticleSizeOverLifetimeModule.md#initparticlestate)
* [updateParticleState](m4m.framework.ParticleSizeOverLifetimeModule.md#updateparticlestate)

#### Accessors

* [size](m4m.framework.ParticleSizeOverLifetimeModule.md#size)
* [sizeMultiplier](m4m.framework.ParticleSizeOverLifetimeModule.md#sizemultiplier)
* [x](m4m.framework.ParticleSizeOverLifetimeModule.md#x)
* [xMultiplier](m4m.framework.ParticleSizeOverLifetimeModule.md#xmultiplier)
* [y](m4m.framework.ParticleSizeOverLifetimeModule.md#y)
* [yMultiplier](m4m.framework.ParticleSizeOverLifetimeModule.md#ymultiplier)
* [z](m4m.framework.ParticleSizeOverLifetimeModule.md#z)
* [zMultiplier](m4m.framework.ParticleSizeOverLifetimeModule.md#zmultiplier)

### Constructors

#### constructor

• **new ParticleSizeOverLifetimeModule**()

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

#### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

粒子系统

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[particleSystem](m4m.framework.ParticleModule.md#particlesystem)

**Defined in**

[framework/particlesystem/modules/ParticleModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L19)

***

#### separateAxes

• **separateAxes**: `boolean` = `false`

Set the size over lifetime on each axis separately.

在每个轴上分别设置生命周期内的大小。

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L17)

***

#### size3D

• **size3D**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

Curve to control particle size based on lifetime.

基于寿命的粒度控制曲线。

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:55](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L55)

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

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:151](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L151)

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

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:160](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L160)

### Accessors

#### size

• `get` **size**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Curve to control particle size based on lifetime.

基于寿命的粒度控制曲线。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L24)

• `set` **size**(`v`): `void`

Curve to control particle size based on lifetime.

基于寿命的粒度控制曲线。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L29)

***

#### sizeMultiplier

• `get` **sizeMultiplier**(): `number`

Size multiplier.

尺寸的乘数。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L39)

• `set` **sizeMultiplier**(`v`): `void`

Size multiplier.

尺寸的乘数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L44)

***

#### x

• `get` **x**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Size over lifetime curve for the X axis.

X轴的尺寸随生命周期变化曲线。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L62)

• `set` **x**(`v`): `void`

Size over lifetime curve for the X axis.

X轴的尺寸随生命周期变化曲线。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:67](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L67)

***

#### xMultiplier

• `get` **xMultiplier**(): `number`

X axis size multiplier.

X轴尺寸的乘数。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L77)

• `set` **xMultiplier**(`v`): `void`

X axis size multiplier.

X轴尺寸的乘数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L82)

***

#### y

• `get` **y**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Size over lifetime curve for the Y axis.

Y轴的尺寸随生命周期变化曲线。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:92](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L92)

• `set` **y**(`v`): `void`

Size over lifetime curve for the Y axis.

Y轴的尺寸随生命周期变化曲线。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:97](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L97)

***

#### yMultiplier

• `get` **yMultiplier**(): `number`

Y axis size multiplier.

Y轴尺寸的乘数。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:107](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L107)

• `set` **yMultiplier**(`v`): `void`

Y axis size multiplier.

Y轴尺寸的乘数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L112)

***

#### z

• `get` **z**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Size over lifetime curve for the Z axis.

Z轴的尺寸随生命周期变化曲线。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L122)

• `set` **z**(`v`): `void`

Size over lifetime curve for the Z axis.

Z轴的尺寸随生命周期变化曲线。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:127](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L127)

***

#### zMultiplier

• `get` **zMultiplier**(): `number`

Z axis size multiplier.

Z轴尺寸的乘数。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:137](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L137)

• `set` **zMultiplier**(`v`): `void`

Z axis size multiplier.

Z轴尺寸的乘数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts:142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeOverLifetimeModule.ts#L142)
