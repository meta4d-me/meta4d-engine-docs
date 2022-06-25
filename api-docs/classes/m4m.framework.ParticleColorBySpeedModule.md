[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleColorBySpeedModule

# Class: ParticleColorBySpeedModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleColorBySpeedModule

the Color By Speed module.

颜色随速度变化模块。

## Hierarchy

- [`ParticleModule`](m4m.framework.ParticleModule.md)

  ↳ **`ParticleColorBySpeedModule`**

## Table of contents

### Properties

- [color](m4m.framework.ParticleColorBySpeedModule.md#color)
- [enabled](m4m.framework.ParticleColorBySpeedModule.md#enabled)
- [particleSystem](m4m.framework.ParticleColorBySpeedModule.md#particlesystem)
- [range](m4m.framework.ParticleColorBySpeedModule.md#range)

### Constructors

- [constructor](m4m.framework.ParticleColorBySpeedModule.md#constructor)

### Methods

- [initParticleState](m4m.framework.ParticleColorBySpeedModule.md#initparticlestate)
- [updateParticleState](m4m.framework.ParticleColorBySpeedModule.md#updateparticlestate)

## Properties

### color

• **color**: [`MinMaxGradient`](m4m.framework.MinMaxGradient.md)

The gradient controlling the particle colors.

控制粒子颜色的梯度。

#### Defined in

[framework/particlesystem/modules/ParticleColorBySpeedModule.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleColorBySpeedModule.ts#L17)

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

Apply the color gradient between these minimum and maximum speeds.

在这些最小和最大速度之间应用颜色渐变。

#### Defined in

[framework/particlesystem/modules/ParticleColorBySpeedModule.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleColorBySpeedModule.ts#L24)

## Constructors

### constructor

• **new ParticleColorBySpeedModule**()

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

[framework/particlesystem/modules/ParticleColorBySpeedModule.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleColorBySpeedModule.ts#L30)

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

[framework/particlesystem/modules/ParticleColorBySpeedModule.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleColorBySpeedModule.ts#L39)
