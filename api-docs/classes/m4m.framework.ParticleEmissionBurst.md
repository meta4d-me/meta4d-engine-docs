# m4m.framework.ParticleEmissionBurst

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleEmissionBurst

## Class: ParticleEmissionBurst

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleEmissionBurst

**`author`** feng3d

### Table of contents

#### Properties

* [\_\_class\_\_](m4m.framework.ParticleEmissionBurst.md#\_\_class\_\_)
* [count](m4m.framework.ParticleEmissionBurst.md#count)
* [cycleCount](m4m.framework.ParticleEmissionBurst.md#cyclecount)
* [probability](m4m.framework.ParticleEmissionBurst.md#probability)
* [repeatInterval](m4m.framework.ParticleEmissionBurst.md#repeatinterval)
* [time](m4m.framework.ParticleEmissionBurst.md#time)

#### Methods

* [calculateProbability](m4m.framework.ParticleEmissionBurst.md#calculateprobability)

#### Constructors

* [constructor](m4m.framework.ParticleEmissionBurst.md#constructor)

#### Accessors

* [isProbability](m4m.framework.ParticleEmissionBurst.md#isprobability)
* [maxCount](m4m.framework.ParticleEmissionBurst.md#maxcount)
* [minCount](m4m.framework.ParticleEmissionBurst.md#mincount)

### Properties

#### \_\_class\_\_

• **\_\_class\_\_**: `"m4m.framework.ParticleEmissionBurst"`

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L8)

***

#### count

• **count**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

要发射的粒子数。

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L21)

***

#### cycleCount

• **cycleCount**: `number` = `1`

How many times to play the burst. (0 means infinitely). 爆发次数。(0意味着无限)。

**`todo`**

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L59)

***

#### probability

• **probability**: `number` = `1.0`

喷发被触发的几率。

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L75)

***

#### repeatInterval

• **repeatInterval**: `number` = `0.01`

How often to repeat the burst, in seconds.

多久重复一次，以秒为单位。

**`todo`**

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:69](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L69)

***

#### time

• **time**: `number` = `0`

The time that each burst occurs. 每次爆炸发生的时间。

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L15)

### Methods

#### calculateProbability

▸ **calculateProbability**(): `boolean`

通过触发的几率计算是否喷发。

**Returns**

`boolean`

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L90)

### Constructors

#### constructor

• **new ParticleEmissionBurst**()

### Accessors

#### isProbability

• `get` **isProbability**(): `boolean`

是否喷发

**Returns**

`boolean`

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L80)

***

#### maxCount

• `get` **maxCount**(): `number`

Maximum number of bursts to be emitted.

要发射的最大爆发数量。

**Returns**

`number`

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L42)

• `set` **maxCount**(`v`): `void`

Maximum number of bursts to be emitted.

要发射的最大爆发数量。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L47)

***

#### minCount

• `get` **minCount**(): `number`

Minimum number of bursts to be emitted. 要发射的最小爆发数量。

**Returns**

`number`

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L27)

• `set` **minCount**(`v`): `void`

Minimum number of bursts to be emitted. 要发射的最小爆发数量。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/others/ParticleEmissionBurst.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/others/ParticleEmissionBurst.ts#L32)
