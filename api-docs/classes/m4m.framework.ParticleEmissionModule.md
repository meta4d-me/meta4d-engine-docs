[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleEmissionModule

# Class: ParticleEmissionModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleEmissionModule

粒子系统发射模块。

**`author`** feng3d

## Hierarchy

- [`ParticleModule`](m4m.framework.ParticleModule.md)

  ↳ **`ParticleEmissionModule`**

## Table of contents

### Properties

- [\_\_class\_\_](m4m.framework.ParticleEmissionModule.md#__class__)
- [bursts](m4m.framework.ParticleEmissionModule.md#bursts)
- [enabled](m4m.framework.ParticleEmissionModule.md#enabled)
- [particleSystem](m4m.framework.ParticleEmissionModule.md#particlesystem)
- [rateOverDistance](m4m.framework.ParticleEmissionModule.md#rateoverdistance)
- [rateOverTime](m4m.framework.ParticleEmissionModule.md#rateovertime)

### Accessors

- [burstCount](m4m.framework.ParticleEmissionModule.md#burstcount)
- [rateOverDistanceMultiplier](m4m.framework.ParticleEmissionModule.md#rateoverdistancemultiplier)
- [rateOverTimeMultiplier](m4m.framework.ParticleEmissionModule.md#rateovertimemultiplier)

### Constructors

- [constructor](m4m.framework.ParticleEmissionModule.md#constructor)

### Methods

- [getBursts](m4m.framework.ParticleEmissionModule.md#getbursts)
- [initParticleState](m4m.framework.ParticleEmissionModule.md#initparticlestate)
- [setBursts](m4m.framework.ParticleEmissionModule.md#setbursts)
- [updateParticleState](m4m.framework.ParticleEmissionModule.md#updateparticlestate)

## Properties

### \_\_class\_\_

• **\_\_class\_\_**: ``"m4m.framework.ParticleEmissionModule"``

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L10)

___

### bursts

• **bursts**: [`ParticleEmissionBurst`](m4m.framework.ParticleEmissionBurst.md)[] = `[]`

爆发数组

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L68)

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

### rateOverDistance

• **rateOverDistance**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The rate at which new particles are spawned, over distance.
New particles will only be emitted when the emitter moves.

产生新粒子的速度，通过距离。
新粒子只有在发射器移动时才会被发射出来。

**`todo`**

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L45)

___

### rateOverTime

• **rateOverTime**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

随着时间的推移，新粒子产生的速度。

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L16)

## Accessors

### burstCount

• `get` **burstCount**(): `number`

The current number of bursts.

当前的爆发次数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L75)

___

### rateOverDistanceMultiplier

• `get` **rateOverDistanceMultiplier**(): `number`

Change the rate over distance multiplier.
This is more efficient than accessing the whole curve, if you only want to change the overall rate multiplier.

改变速率随距离变化的乘数。
如果您只想更改整体的速率乘数，那么这比访问整个曲线更有效。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L54)

• `set` **rateOverDistanceMultiplier**(`v`): `void`

Change the rate over distance multiplier.
This is more efficient than accessing the whole curve, if you only want to change the overall rate multiplier.

改变速率随距离变化的乘数。
如果您只想更改整体的速率乘数，那么这比访问整个曲线更有效。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L59)

___

### rateOverTimeMultiplier

• `get` **rateOverTimeMultiplier**(): `number`

Change the rate over time multiplier.
This is more efficient than accessing the whole curve, if you only want to change the overall rate multiplier.

改变率随时间的乘数。
如果您只想更改整体的速率乘数，那么这比访问整个曲线更有效。
只在

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L26)

• `set` **rateOverTimeMultiplier**(`v`): `void`

Change the rate over time multiplier.
This is more efficient than accessing the whole curve, if you only want to change the overall rate multiplier.

改变率随时间的乘数。
如果您只想更改整体的速率乘数，那么这比访问整个曲线更有效。
只在

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L31)

## Constructors

### constructor

• **new ParticleEmissionModule**()

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[constructor](m4m.framework.ParticleModule.md#constructor)

## Methods

### getBursts

▸ **getBursts**(`bursts`): `number`

Get the burst array.
获取爆发数组。

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `bursts` | [`ParticleEmissionBurst`](m4m.framework.ParticleEmissionBurst.md)[] | Array of bursts to be filled in.要填充的爆发数组。 |

#### Returns

`number`

The number of bursts in the array.数组中的爆发次数。

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:87](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L87)

___

### initParticleState

▸ **initParticleState**(`particle`): `void`

初始化粒子状态

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) | 粒子 |

#### Returns

`void`

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[initParticleState](m4m.framework.ParticleModule.md#initparticlestate)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L25)

___

### setBursts

▸ **setBursts**(`bursts`, `size?`): `void`

Set the burst array.
设置爆发数组。

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `bursts` | [`ParticleEmissionBurst`](m4m.framework.ParticleEmissionBurst.md)[] | `undefined` | Array of bursts.爆发的数组。 |
| `size` | `number` | `Number.MAX_SAFE_INTEGER` | Optional array size, if burst count is less than array size.可选的数组大小，如果爆发计数小于数组大小。 |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleEmissionModule.ts:104](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleEmissionModule.ts#L104)

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

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[updateParticleState](m4m.framework.ParticleModule.md#updateparticlestate)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L34)
