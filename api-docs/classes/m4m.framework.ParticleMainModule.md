[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleMainModule

# Class: ParticleMainModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleMainModule

粒子主模块

**`author`** feng3d

## Hierarchy

- [`ParticleModule`](m4m.framework.ParticleModule.md)

  ↳ **`ParticleMainModule`**

## Table of contents

### Properties

- [\_\_class\_\_](m4m.framework.ParticleMainModule.md#__class__)
- [customSimulationSpace](m4m.framework.ParticleMainModule.md#customsimulationspace)
- [duration](m4m.framework.ParticleMainModule.md#duration)
- [enabled](m4m.framework.ParticleMainModule.md#enabled)
- [gravityModifier](m4m.framework.ParticleMainModule.md#gravitymodifier)
- [loop](m4m.framework.ParticleMainModule.md#loop)
- [maxParticles](m4m.framework.ParticleMainModule.md#maxparticles)
- [particleSystem](m4m.framework.ParticleMainModule.md#particlesystem)
- [playOnAwake](m4m.framework.ParticleMainModule.md#playonawake)
- [prewarm](m4m.framework.ParticleMainModule.md#prewarm)
- [randomizeRotationDirection](m4m.framework.ParticleMainModule.md#randomizerotationdirection)
- [scalingMode](m4m.framework.ParticleMainModule.md#scalingmode)
- [simulationSpeed](m4m.framework.ParticleMainModule.md#simulationspeed)
- [startColor](m4m.framework.ParticleMainModule.md#startcolor)
- [startDelay](m4m.framework.ParticleMainModule.md#startdelay)
- [startLifetime](m4m.framework.ParticleMainModule.md#startlifetime)
- [startRotation3D](m4m.framework.ParticleMainModule.md#startrotation3d)
- [startSize3D](m4m.framework.ParticleMainModule.md#startsize3d)
- [startSpeed](m4m.framework.ParticleMainModule.md#startspeed)
- [useStartRotation3D](m4m.framework.ParticleMainModule.md#usestartrotation3d)
- [useStartSize3D](m4m.framework.ParticleMainModule.md#usestartsize3d)

### Constructors

- [constructor](m4m.framework.ParticleMainModule.md#constructor)

### Methods

- [initParticleState](m4m.framework.ParticleMainModule.md#initparticlestate)
- [updateParticleState](m4m.framework.ParticleMainModule.md#updateparticlestate)

### Accessors

- [simulationSpace](m4m.framework.ParticleMainModule.md#simulationspace)
- [startDelayMultiplier](m4m.framework.ParticleMainModule.md#startdelaymultiplier)
- [startLifetimeMultiplier](m4m.framework.ParticleMainModule.md#startlifetimemultiplier)
- [startRotation](m4m.framework.ParticleMainModule.md#startrotation)
- [startRotationMultiplier](m4m.framework.ParticleMainModule.md#startrotationmultiplier)
- [startRotationX](m4m.framework.ParticleMainModule.md#startrotationx)
- [startRotationXMultiplier](m4m.framework.ParticleMainModule.md#startrotationxmultiplier)
- [startRotationY](m4m.framework.ParticleMainModule.md#startrotationy)
- [startRotationYMultiplier](m4m.framework.ParticleMainModule.md#startrotationymultiplier)
- [startRotationZ](m4m.framework.ParticleMainModule.md#startrotationz)
- [startRotationZMultiplier](m4m.framework.ParticleMainModule.md#startrotationzmultiplier)
- [startSize](m4m.framework.ParticleMainModule.md#startsize)
- [startSizeMultiplier](m4m.framework.ParticleMainModule.md#startsizemultiplier)
- [startSizeX](m4m.framework.ParticleMainModule.md#startsizex)
- [startSizeXMultiplier](m4m.framework.ParticleMainModule.md#startsizexmultiplier)
- [startSizeY](m4m.framework.ParticleMainModule.md#startsizey)
- [startSizeYMultiplier](m4m.framework.ParticleMainModule.md#startsizeymultiplier)
- [startSizeZ](m4m.framework.ParticleMainModule.md#startsizez)
- [startSizeZMultiplier](m4m.framework.ParticleMainModule.md#startsizezmultiplier)
- [startSpeedMultiplier](m4m.framework.ParticleMainModule.md#startspeedmultiplier)

## Properties

### \_\_class\_\_

• **\_\_class\_\_**: ``"m4m.framework.ParticleMainModule"``

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L10)

___

### customSimulationSpace

• **customSimulationSpace**: [`transform`](m4m.framework.transform.md)

Simulate particles relative to a custom transform component.

模拟相对于自定义转换组件的粒子。

**`todo`**

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:442](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L442)

___

### duration

• **duration**: `number` = `5`

粒子系统的持续时间(秒)。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L18)

___

### enabled

• **enabled**: `boolean` = `true`

是否开启

#### Overrides

[ParticleModule](m4m.framework.ParticleModule.md).[enabled](m4m.framework.ParticleModule.md#enabled)

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L12)

___

### gravityModifier

• **gravityModifier**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Scale applied to the gravity.

应用于重力加速度的缩放。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:411](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L411)

___

### loop

• **loop**: `boolean` = `true`

粒子系统在循环吗?

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L24)

___

### maxParticles

• **maxParticles**: `number` = `1000`

The maximum number of particles to emit.

发射粒子的最大数量。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:474](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L474)

___

### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

粒子系统

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[particleSystem](m4m.framework.ParticleModule.md#particlesystem)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L19)

___

### playOnAwake

• **playOnAwake**: `boolean` = `true`

If set to true, the particle system will automatically start playing on startup.

如果设置为真，粒子系统将自动开始播放启动。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:466](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L466)

___

### prewarm

• **prewarm**: `boolean` = `false`

When looping is enabled, this controls whether this particle system will look like it has already simulated for one loop when first becoming visible.

当循环被激活时，它控制这个粒子系统在第一次出现时是否看起来像已经模拟了一个循环。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L32)

___

### randomizeRotationDirection

• **randomizeRotationDirection**: `number` = `0`

Cause some particles to spin in the opposite direction. Set between 0 and 1, where higher values will cause a higher proportion of particles to spin in the opposite direction.

导致一些粒子向相反的方向旋转。设置在0和1之间，数值越大，粒子朝相反方向旋转的比例越大。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:395](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L395)

___

### scalingMode

• **scalingMode**: [`ParticleSystemScalingMode`](../enums/m4m.framework.ParticleSystemScalingMode.md) = `ParticleSystemScalingMode.Local`

Control how the particle system's Transform Component is applied to the particle system.

控制粒子系统的变换组件如何应用于粒子系统。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:458](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L458)

___

### simulationSpeed

• **simulationSpeed**: `number` = `1`

Override the default playback speed of the Particle System.

重写粒子系统的默认播放速度。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:450](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L450)

___

### startColor

• **startColor**: [`MinMaxGradient`](m4m.framework.MinMaxGradient.md)

The initial color of particles when emitted.

粒子发射时的初始颜色。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:403](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L403)

___

### startDelay

• **startDelay**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Start delay in seconds.

启动延迟(以秒为单位)。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L40)

___

### startLifetime

• **startLifetime**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The total lifetime in seconds that each new particle will have.

每个新粒子的总寿命(以秒计)。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L58)

___

### startRotation3D

• **startRotation3D**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

The initial rotation of particles when emitted.

粒子发射时的初始旋转。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:291](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L291)

___

### startSize3D

• **startSize3D**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

The initial size of particles when emitted.

发射时粒子的初始大小。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L149)

___

### startSpeed

• **startSpeed**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The initial speed of particles when emitted.

粒子发射时的初始速度。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L83)

___

### useStartRotation3D

• **useStartRotation3D**: `boolean` = `false`

A flag to enable 3D particle rotation.
一个启用粒子3D旋转的标记。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:252](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L252)

___

### useStartSize3D

• **useStartSize3D**: `boolean` = `false`

A flag to enable specifying particle size individually for each axis.

允许为每个轴分别指定粒度大小的标志。

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:108](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L108)

## Constructors

### constructor

• **new ParticleMainModule**()

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

[framework/particlesystem/modules/ParticleMainModule.ts:480](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L480)

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

[framework/particlesystem/modules/ParticleMainModule.ts:526](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L526)

## Accessors

### simulationSpace

• `get` **simulationSpace**(): [`ParticleSystemSimulationSpace`](../enums/m4m.framework.ParticleSystemSimulationSpace.md)

This selects the space in which to simulate particles. It can be either world or local space.

模拟空间，使粒子位置模拟在世界，本地或自定义空间。在本地空间中，它们相对于自己的转换而存在，在自定义空间中，它们相对于自定义转换。

**`todo`**

#### Returns

[`ParticleSystemSimulationSpace`](../enums/m4m.framework.ParticleSystemSimulationSpace.md)

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:420](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L420)

• `set` **simulationSpace**(`v`): `void`

This selects the space in which to simulate particles. It can be either world or local space.

模拟空间，使粒子位置模拟在世界，本地或自定义空间。在本地空间中，它们相对于自己的转换而存在，在自定义空间中，它们相对于自定义转换。

**`todo`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`ParticleSystemSimulationSpace`](../enums/m4m.framework.ParticleSystemSimulationSpace.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:424](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L424)

___

### startDelayMultiplier

• `get` **startDelayMultiplier**(): `number`

Start delay multiplier in seconds.

启动延迟乘数(以秒为单位)。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L47)

___

### startLifetimeMultiplier

• `get` **startLifetimeMultiplier**(): `number`

Start lifetime multiplier.
This method is more efficient than accessing the whole curve, if you only want to change the overall lifetime multiplier.

起始寿命乘数。
如果您只想更改总体寿命乘数，则此方法比访问整个曲线更有效。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:67](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L67)

• `set` **startLifetimeMultiplier**(`v`): `void`

Start lifetime multiplier.
This method is more efficient than accessing the whole curve, if you only want to change the overall lifetime multiplier.

起始寿命乘数。
如果您只想更改总体寿命乘数，则此方法比访问整个曲线更有效。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L72)

___

### startRotation

• `get` **startRotation**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The initial rotation of particles when emitted.
粒子发射时的初始旋转。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:258](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L258)

• `set` **startRotation**(`v`): `void`

The initial rotation of particles when emitted.
粒子发射时的初始旋转。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:263](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L263)

___

### startRotationMultiplier

• `get` **startRotationMultiplier**(): `number`

Start rotation multiplier.
This method is more efficient than accessing the whole curve, if you only want to change the overall rotation multiplier.

开始旋转乘数。
这种方法比访问整个曲线更有效，如果你只想改变整体旋转乘数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:275](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L275)

• `set` **startRotationMultiplier**(`v`): `void`

Start rotation multiplier.
This method is more efficient than accessing the whole curve, if you only want to change the overall rotation multiplier.

开始旋转乘数。
这种方法比访问整个曲线更有效，如果你只想改变整体旋转乘数。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:280](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L280)

___

### startRotationX

• `get` **startRotationX**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The initial rotation of particles around the X axis when emitted.

发射时粒子围绕X轴的初始旋转。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:298](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L298)

• `set` **startRotationX**(`v`): `void`

The initial rotation of particles around the X axis when emitted.

发射时粒子围绕X轴的初始旋转。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:303](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L303)

___

### startRotationXMultiplier

• `get` **startRotationXMultiplier**(): `number`

Start rotation multiplier around the X axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall rotation multiplier.

开始绕X轴旋转乘法器。
这种方法比访问整个曲线更有效，如果你只想改变整体旋转乘数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:315](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L315)

• `set` **startRotationXMultiplier**(`v`): `void`

Start rotation multiplier around the X axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall rotation multiplier.

开始绕X轴旋转乘法器。
这种方法比访问整个曲线更有效，如果你只想改变整体旋转乘数。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:320](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L320)

___

### startRotationY

• `get` **startRotationY**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The initial rotation of particles around the Y axis when emitted.

发射时粒子围绕Y轴的初始旋转。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:330](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L330)

• `set` **startRotationY**(`v`): `void`

The initial rotation of particles around the Y axis when emitted.

发射时粒子围绕Y轴的初始旋转。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:335](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L335)

___

### startRotationYMultiplier

• `get` **startRotationYMultiplier**(): `number`

Start rotation multiplier around the Y axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall rotation multiplier.

开始绕Y轴旋转乘法器。
这种方法比访问整个曲线更有效，如果你只想改变整体旋转乘数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:347](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L347)

• `set` **startRotationYMultiplier**(`v`): `void`

Start rotation multiplier around the Y axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall rotation multiplier.

开始绕Y轴旋转乘法器。
这种方法比访问整个曲线更有效，如果你只想改变整体旋转乘数。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:352](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L352)

___

### startRotationZ

• `get` **startRotationZ**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The initial rotation of particles around the Z axis when emitted.

发射时粒子围绕Z轴的初始旋转。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:362](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L362)

• `set` **startRotationZ**(`v`): `void`

The initial rotation of particles around the Z axis when emitted.

发射时粒子围绕Z轴的初始旋转。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:367](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L367)

___

### startRotationZMultiplier

• `get` **startRotationZMultiplier**(): `number`

Start rotation multiplier around the Z axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall rotation multiplier.

开始绕Z轴旋转乘法器。
这种方法比访问整个曲线更有效，如果你只想改变整体旋转乘数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:379](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L379)

• `set` **startRotationZMultiplier**(`v`): `void`

Start rotation multiplier around the Z axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall rotation multiplier.

开始绕Z轴旋转乘法器。
这种方法比访问整个曲线更有效，如果你只想改变整体旋转乘数。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:384](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L384)

___

### startSize

• `get` **startSize**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The initial size of particles when emitted.

粒子发射时的初始大小。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L116)

• `set` **startSize**(`v`): `void`

The initial size of particles when emitted.

粒子发射时的初始大小。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L121)

___

### startSizeMultiplier

• `get` **startSizeMultiplier**(): `number`

Start size multiplier.
This method is more efficient than accessing the whole curve, if you only want to change the overall size multiplier.

开始尺寸乘数。
如果您只想更改整体尺寸倍增器，则此方法比访问整个曲线更有效。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:133](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L133)

• `set` **startSizeMultiplier**(`v`): `void`

Start size multiplier.
This method is more efficient than accessing the whole curve, if you only want to change the overall size multiplier.

开始尺寸乘数。
如果您只想更改整体尺寸倍增器，则此方法比访问整个曲线更有效。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:138](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L138)

___

### startSizeX

• `get` **startSizeX**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The initial size of particles along the X axis when emitted.

发射时沿X轴的粒子的初始大小。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:156](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L156)

• `set` **startSizeX**(`v`): `void`

The initial size of particles along the X axis when emitted.

发射时沿X轴的粒子的初始大小。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:161](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L161)

___

### startSizeXMultiplier

• `get` **startSizeXMultiplier**(): `number`

Start rotation multiplier along the X axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall size multiplier.

启动旋转乘法器沿X轴。
如果您只想更改整体大小倍增器，则此方法比访问整个曲线更有效。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:173](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L173)

• `set` **startSizeXMultiplier**(`v`): `void`

Start rotation multiplier along the X axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall size multiplier.

启动旋转乘法器沿X轴。
如果您只想更改整体大小倍增器，则此方法比访问整个曲线更有效。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:178](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L178)

___

### startSizeY

• `get` **startSizeY**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The initial size of particles along the Y axis when emitted.

发射时沿Y轴的粒子的初始大小。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:188](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L188)

• `set` **startSizeY**(`v`): `void`

The initial size of particles along the Y axis when emitted.

发射时沿Y轴的粒子的初始大小。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:193](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L193)

___

### startSizeYMultiplier

• `get` **startSizeYMultiplier**(): `number`

Start rotation multiplier along the Y axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall size multiplier.

启动旋转乘法器沿Y轴。
如果您只想更改整体大小倍增器，则此方法比访问整个曲线更有效。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:205](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L205)

• `set` **startSizeYMultiplier**(`v`): `void`

Start rotation multiplier along the Y axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall size multiplier.

启动旋转乘法器沿Y轴。
如果您只想更改整体大小倍增器，则此方法比访问整个曲线更有效。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:210](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L210)

___

### startSizeZ

• `get` **startSizeZ**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

The initial size of particles along the Z axis when emitted.

发射时沿Z轴的粒子的初始大小。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:220](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L220)

• `set` **startSizeZ**(`v`): `void`

The initial size of particles along the Z axis when emitted.

发射时沿Z轴的粒子的初始大小。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:225](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L225)

___

### startSizeZMultiplier

• `get` **startSizeZMultiplier**(): `number`

Start rotation multiplier along the Z axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall size multiplier.

启动旋转乘法器沿Z轴。
如果您只想更改整体大小倍增器，则此方法比访问整个曲线更有效。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:237](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L237)

• `set` **startSizeZMultiplier**(`v`): `void`

Start rotation multiplier along the Z axis.
This method is more efficient than accessing the whole curve, if you only want to change the overall size multiplier.

启动旋转乘法器沿Z轴。
如果您只想更改整体大小倍增器，则此方法比访问整个曲线更有效。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:242](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L242)

___

### startSpeedMultiplier

• `get` **startSpeedMultiplier**(): `number`

A multiplier of the initial speed of particles when emitted.
This method is more efficient than accessing the whole curve, if you only want to change the overall speed multiplier.

粒子发射时的初始速度的乘子。
这种方法比访问整个曲线更有效，如果你只想改变整体速度乘数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:92](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L92)

• `set` **startSpeedMultiplier**(`v`): `void`

A multiplier of the initial speed of particles when emitted.
This method is more efficient than accessing the whole curve, if you only want to change the overall speed multiplier.

粒子发射时的初始速度的乘子。
这种方法比访问整个曲线更有效，如果你只想改变整体速度乘数。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleMainModule.ts:97](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleMainModule.ts#L97)
