[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleModule

# Class: ParticleModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleModule

粒子模块

**`author`** feng3d

## Hierarchy

- **`ParticleModule`**

  ↳ [`ParticleColorBySpeedModule`](m4m.framework.ParticleColorBySpeedModule.md)

  ↳ [`ParticleColorOverLifetimeModule`](m4m.framework.ParticleColorOverLifetimeModule.md)

  ↳ [`ParticleEmissionModule`](m4m.framework.ParticleEmissionModule.md)

  ↳ [`ParticleForceOverLifetimeModule`](m4m.framework.ParticleForceOverLifetimeModule.md)

  ↳ [`ParticleInheritVelocityModule`](m4m.framework.ParticleInheritVelocityModule.md)

  ↳ [`ParticleLimitVelocityOverLifetimeModule`](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md)

  ↳ [`ParticleMainModule`](m4m.framework.ParticleMainModule.md)

  ↳ [`ParticleNoiseModule`](m4m.framework.ParticleNoiseModule.md)

  ↳ [`ParticleRotationBySpeedModule`](m4m.framework.ParticleRotationBySpeedModule.md)

  ↳ [`ParticleRotationOverLifetimeModule`](m4m.framework.ParticleRotationOverLifetimeModule.md)

  ↳ [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md)

  ↳ [`ParticleSizeBySpeedModule`](m4m.framework.ParticleSizeBySpeedModule.md)

  ↳ [`ParticleSizeOverLifetimeModule`](m4m.framework.ParticleSizeOverLifetimeModule.md)

  ↳ [`ParticleTextureSheetAnimationModule`](m4m.framework.ParticleTextureSheetAnimationModule.md)

  ↳ [`ParticleVelocityOverLifetimeModule`](m4m.framework.ParticleVelocityOverLifetimeModule.md)

## Table of contents

### Constructors

- [constructor](m4m.framework.ParticleModule.md#constructor)

### Properties

- [enabled](m4m.framework.ParticleModule.md#enabled)
- [particleSystem](m4m.framework.ParticleModule.md#particlesystem)

### Methods

- [initParticleState](m4m.framework.ParticleModule.md#initparticlestate)
- [updateParticleState](m4m.framework.ParticleModule.md#updateparticlestate)

## Constructors

### constructor

• **new ParticleModule**()

## Properties

### enabled

• **enabled**: `boolean` = `false`

是否开启

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L14)

___

### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

粒子系统

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L19)

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

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L25)

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

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L34)
