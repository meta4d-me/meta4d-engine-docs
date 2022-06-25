[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSizeBySpeedModule

# Class: ParticleSizeBySpeedModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSizeBySpeedModule

Script interface for the Size By Speed module.

粒子系统 缩放随速度变化模块

## Hierarchy

- [`ParticleModule`](m4m.framework.ParticleModule.md)

  ↳ **`ParticleSizeBySpeedModule`**

## Table of contents

### Constructors

- [constructor](m4m.framework.ParticleSizeBySpeedModule.md#constructor)

### Properties

- [enabled](m4m.framework.ParticleSizeBySpeedModule.md#enabled)
- [particleSystem](m4m.framework.ParticleSizeBySpeedModule.md#particlesystem)
- [range](m4m.framework.ParticleSizeBySpeedModule.md#range)
- [separateAxes](m4m.framework.ParticleSizeBySpeedModule.md#separateaxes)
- [size3D](m4m.framework.ParticleSizeBySpeedModule.md#size3d)

### Methods

- [initParticleState](m4m.framework.ParticleSizeBySpeedModule.md#initparticlestate)
- [updateParticleState](m4m.framework.ParticleSizeBySpeedModule.md#updateparticlestate)

### Accessors

- [size](m4m.framework.ParticleSizeBySpeedModule.md#size)
- [sizeMultiplier](m4m.framework.ParticleSizeBySpeedModule.md#sizemultiplier)
- [x](m4m.framework.ParticleSizeBySpeedModule.md#x)
- [xMultiplier](m4m.framework.ParticleSizeBySpeedModule.md#xmultiplier)
- [y](m4m.framework.ParticleSizeBySpeedModule.md#y)
- [yMultiplier](m4m.framework.ParticleSizeBySpeedModule.md#ymultiplier)
- [z](m4m.framework.ParticleSizeBySpeedModule.md#z)
- [zMultiplier](m4m.framework.ParticleSizeBySpeedModule.md#zmultiplier)

## Constructors

### constructor

• **new ParticleSizeBySpeedModule**()

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[constructor](m4m.framework.ParticleModule.md#constructor)

## Properties

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

Apply the size curve between these minimum and maximum speeds.

在这些最小和最大速度之间应用尺寸变化。

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L47)

___

### separateAxes

• **separateAxes**: `boolean` = `false`

Set the size over speed on each axis separately.

在每个轴上分别设置生命周期内的大小。

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L18)

___

### size3D

• **size3D**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

Curve to control particle size based on speed.

基于寿命的粒度控制曲线。

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L40)

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

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:158](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L158)

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

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:167](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L167)

## Accessors

### size

• `get` **size**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Curve to control particle size based on speed.

基于速度的粒度控制曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L25)

• `set` **size**(`v`): `void`

Curve to control particle size based on speed.

基于速度的粒度控制曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L30)

___

### sizeMultiplier

• `get` **sizeMultiplier**(): `number`

Size multiplier.

尺寸的乘数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L54)

• `set` **sizeMultiplier**(`v`): `void`

Size multiplier.

尺寸的乘数。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L59)

___

### x

• `get` **x**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Size over speed curve for the X axis.

X轴的尺寸随生命周期变化曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:69](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L69)

• `set` **x**(`v`): `void`

Size over speed curve for the X axis.

X轴的尺寸随生命周期变化曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L74)

___

### xMultiplier

• `get` **xMultiplier**(): `number`

X axis size multiplier.

X轴尺寸的乘数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:84](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L84)

• `set` **xMultiplier**(`v`): `void`

X axis size multiplier.

X轴尺寸的乘数。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L89)

___

### y

• `get` **y**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Size over speed curve for the Y axis.

Y轴的尺寸随生命周期变化曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:99](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L99)

• `set` **y**(`v`): `void`

Size over speed curve for the Y axis.

Y轴的尺寸随生命周期变化曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:104](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L104)

___

### yMultiplier

• `get` **yMultiplier**(): `number`

Y axis size multiplier.

Y轴尺寸的乘数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:114](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L114)

• `set` **yMultiplier**(`v`): `void`

Y axis size multiplier.

Y轴尺寸的乘数。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:119](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L119)

___

### z

• `get` **z**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Size over speed curve for the Z axis.

Z轴的尺寸随生命周期变化曲线。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:129](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L129)

• `set` **z**(`v`): `void`

Size over speed curve for the Z axis.

Z轴的尺寸随生命周期变化曲线。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L134)

___

### zMultiplier

• `get` **zMultiplier**(): `number`

Z axis size multiplier.

Z轴尺寸的乘数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:144](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L144)

• `set` **zMultiplier**(`v`): `void`

Z axis size multiplier.

Z轴尺寸的乘数。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleSizeBySpeedModule.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleSizeBySpeedModule.ts#L149)
