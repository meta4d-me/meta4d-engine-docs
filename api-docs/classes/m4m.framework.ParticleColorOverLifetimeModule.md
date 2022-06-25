[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleColorOverLifetimeModule

# Class: ParticleColorOverLifetimeModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleColorOverLifetimeModule

粒子系统 颜色随时间变化模块

**`author`** feng3d

## Hierarchy

- [`ParticleModule`](m4m.framework.ParticleModule.md)

  ↳ **`ParticleColorOverLifetimeModule`**

## Table of contents

### Properties

- [color](m4m.framework.ParticleColorOverLifetimeModule.md#color)
- [enabled](m4m.framework.ParticleColorOverLifetimeModule.md#enabled)
- [particleSystem](m4m.framework.ParticleColorOverLifetimeModule.md#particlesystem)

### Constructors

- [constructor](m4m.framework.ParticleColorOverLifetimeModule.md#constructor)

### Methods

- [initParticleState](m4m.framework.ParticleColorOverLifetimeModule.md#initparticlestate)
- [updateParticleState](m4m.framework.ParticleColorOverLifetimeModule.md#updateparticlestate)

## Properties

### color

• **color**: [`MinMaxGradient`](m4m.framework.MinMaxGradient.md)

The gradient controlling the particle colors.
控制粒子颜色的梯度。

#### Defined in

[framework/particlesystem/modules/ParticleColorOverLifetimeModule.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleColorOverLifetimeModule.ts#L17)

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

## Constructors

### constructor

• **new ParticleColorOverLifetimeModule**()

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

[framework/particlesystem/modules/ParticleColorOverLifetimeModule.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleColorOverLifetimeModule.ts#L23)

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

[framework/particlesystem/modules/ParticleColorOverLifetimeModule.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleColorOverLifetimeModule.ts#L32)
