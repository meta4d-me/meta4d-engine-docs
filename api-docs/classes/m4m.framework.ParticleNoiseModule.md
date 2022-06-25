[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleNoiseModule

# Class: ParticleNoiseModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleNoiseModule

Script interface for the Noise Module.

The Noise Module allows you to apply turbulence to the movement of your particles. Use the low quality settings to create computationally efficient Noise, or simulate smoother, richer Noise with the higher quality settings. You can also choose to define the behavior of the Noise individually for each axis.

噪声模块

噪声模块允许你将湍流应用到粒子的运动中。使用低质量设置来创建计算效率高的噪声，或者使用高质量设置来模拟更平滑、更丰富的噪声。您还可以选择为每个轴分别定义噪声的行为。

## Hierarchy

- [`ParticleModule`](m4m.framework.ParticleModule.md)

  ↳ **`ParticleNoiseModule`**

## Table of contents

### Constructors

- [constructor](m4m.framework.ParticleNoiseModule.md#constructor)

### Properties

- [damping](m4m.framework.ParticleNoiseModule.md#damping)
- [enabled](m4m.framework.ParticleNoiseModule.md#enabled)
- [frequency](m4m.framework.ParticleNoiseModule.md#frequency)
- [octaveCount](m4m.framework.ParticleNoiseModule.md#octavecount)
- [octaveMultiplier](m4m.framework.ParticleNoiseModule.md#octavemultiplier)
- [octaveScale](m4m.framework.ParticleNoiseModule.md#octavescale)
- [particleSystem](m4m.framework.ParticleNoiseModule.md#particlesystem)
- [quality](m4m.framework.ParticleNoiseModule.md#quality)
- [remap3D](m4m.framework.ParticleNoiseModule.md#remap3d)
- [remapEnabled](m4m.framework.ParticleNoiseModule.md#remapenabled)
- [scrollSpeed](m4m.framework.ParticleNoiseModule.md#scrollspeed)
- [separateAxes](m4m.framework.ParticleNoiseModule.md#separateaxes)
- [strength3D](m4m.framework.ParticleNoiseModule.md#strength3d)
- [\_frequencyScale](m4m.framework.ParticleNoiseModule.md#_frequencyscale)
- [\_strengthScale](m4m.framework.ParticleNoiseModule.md#_strengthscale)
- [\_timeScale](m4m.framework.ParticleNoiseModule.md#_timescale)

### Methods

- [drawImage](m4m.framework.ParticleNoiseModule.md#drawimage)
- [initParticleState](m4m.framework.ParticleNoiseModule.md#initparticlestate)
- [update](m4m.framework.ParticleNoiseModule.md#update)
- [updateParticleState](m4m.framework.ParticleNoiseModule.md#updateparticlestate)

### Accessors

- [remap](m4m.framework.ParticleNoiseModule.md#remap)
- [remapX](m4m.framework.ParticleNoiseModule.md#remapx)
- [remapY](m4m.framework.ParticleNoiseModule.md#remapy)
- [remapZ](m4m.framework.ParticleNoiseModule.md#remapz)
- [strength](m4m.framework.ParticleNoiseModule.md#strength)
- [strengthX](m4m.framework.ParticleNoiseModule.md#strengthx)
- [strengthY](m4m.framework.ParticleNoiseModule.md#strengthy)
- [strengthZ](m4m.framework.ParticleNoiseModule.md#strengthz)

## Constructors

### constructor

• **new ParticleNoiseModule**()

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[constructor](m4m.framework.ParticleModule.md#constructor)

## Properties

### damping

• **damping**: `boolean` = `true`

Higher frequency noise will reduce the strength by a proportional amount, if enabled.

如果启用高频率噪音，将按比例减少强度。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:107](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L107)

___

### enabled

• **enabled**: `boolean` = `false`

是否开启

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[enabled](m4m.framework.ParticleModule.md#enabled)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L14)

___

### frequency

• **frequency**: `number` = `0.5`

Low values create soft, smooth noise, and high values create rapidly changing noise.

低值产生柔和、平滑的噪声，高值产生快速变化的噪声。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L93)

___

### octaveCount

• **octaveCount**: `number` = `1`

Layers of noise that combine to produce final noise.

一层一层的噪声组合在一起产生最终的噪声。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:114](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L114)

___

### octaveMultiplier

• **octaveMultiplier**: `number` = `0.5`

When combining each octave, scale the intensity by this amount.

当组合每个八度时，按这个比例调整强度。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L121)

___

### octaveScale

• **octaveScale**: `number` = `2`

When combining each octave, zoom in by this amount.

当组合每个八度时，放大这个数字。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:128](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L128)

___

### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

粒子系统

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[particleSystem](m4m.framework.ParticleModule.md#particlesystem)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L19)

___

### quality

• **quality**: [`ParticleSystemNoiseQuality`](../enums/m4m.framework.ParticleSystemNoiseQuality.md) = `ParticleSystemNoiseQuality.High`

Generate 1D, 2D or 3D noise.

生成一维、二维或三维噪声。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:135](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L135)

___

### remap3D

• **remap3D**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

Define how the noise values are remapped.

定义如何重新映射噪声值。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:164](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L164)

___

### remapEnabled

• **remapEnabled**: `boolean` = `false`

Enable remapping of the final noise values, allowing for noise values to be translated into different values.

允许重新映射最终的噪声值，允许将噪声值转换为不同的值。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L142)

___

### scrollSpeed

• **scrollSpeed**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Scroll the noise map over the particle system.

在粒子系统上滚动噪声图。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L100)

___

### separateAxes

• **separateAxes**: `boolean` = `false`

Control the noise separately for each axis.

分别控制每个轴的噪声。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L19)

___

### strength3D

• **strength3D**: [`MinMaxCurveVector3`](m4m.framework.MinMaxCurveVector3.md)

How strong the overall noise effect is.

整体噪音效应有多强。

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L41)

___

### \_frequencyScale

▪ `Static` **\_frequencyScale**: `number` = `5`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:272](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L272)

___

### \_strengthScale

▪ `Static` **\_strengthScale**: `number` = `0.3`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:273](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L273)

___

### \_timeScale

▪ `Static` **\_timeScale**: `number` = `5`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:274](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L274)

## Methods

### drawImage

▸ **drawImage**(`image`): `void`

绘制噪音到图片

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `image` | `ImageData` | 图片数据 |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:281](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L281)

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

#### Overrides

[ParticleModule](m4m.framework.ParticleModule.md).[initParticleState](m4m.framework.ParticleModule.md#initparticlestate)

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:219](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L219)

___

### update

▸ **update**(`interval`): `void`

更新

#### Parameters

| Name | Type |
| :------ | :------ |
| `interval` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:421](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L421)

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

[framework/particlesystem/modules/ParticleNoiseModule.ts:229](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L229)

## Accessors

### remap

• `get` **remap**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Define how the noise values are remapped.

定义如何重新映射噪声值。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L149)

• `set` **remap**(`v`): `void`

Define how the noise values are remapped.

定义如何重新映射噪声值。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:154](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L154)

___

### remapX

• `get` **remapX**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Define how the noise values are remapped on the X axis, when using the ParticleSystem.NoiseModule.separateAxes option.

在使用分别控制每个轴时，如何在X轴上重新映射噪声值。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:175](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L175)

• `set` **remapX**(`v`): `void`

Define how the noise values are remapped on the X axis, when using the ParticleSystem.NoiseModule.separateAxes option.

在使用分别控制每个轴时，如何在X轴上重新映射噪声值。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:180](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L180)

___

### remapY

• `get` **remapY**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Define how the noise values are remapped on the Y axis, when using the ParticleSystem.NoiseModule.separateAxes option.

在使用分别控制每个轴时，如何在Y轴上重新映射噪声值。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:190](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L190)

• `set` **remapY**(`v`): `void`

Define how the noise values are remapped on the Y axis, when using the ParticleSystem.NoiseModule.separateAxes option.

在使用分别控制每个轴时，如何在Y轴上重新映射噪声值。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:195](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L195)

___

### remapZ

• `get` **remapZ**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Define how the noise values are remapped on the Z axis, when using the ParticleSystem.NoiseModule.separateAxes option.

在使用分别控制每个轴时，如何在Z轴上重新映射噪声值。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:205](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L205)

• `set` **remapZ**(`v`): `void`

Define how the noise values are remapped on the Z axis, when using the ParticleSystem.NoiseModule.separateAxes option.

在使用分别控制每个轴时，如何在Z轴上重新映射噪声值。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:210](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L210)

___

### strength

• `get` **strength**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

How strong the overall noise effect is.

整体噪音效应有多强。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L26)

• `set` **strength**(`v`): `void`

How strong the overall noise effect is.

整体噪音效应有多强。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L31)

___

### strengthX

• `get` **strengthX**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Define the strength of the effect on the X axis, when using separateAxes option.

在使用分别控制每个轴时，在X轴上定义效果的强度。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L48)

• `set` **strengthX**(`v`): `void`

Define the strength of the effect on the X axis, when using separateAxes option.

在使用分别控制每个轴时，在X轴上定义效果的强度。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L53)

___

### strengthY

• `get` **strengthY**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Define the strength of the effect on the Y axis, when using separateAxes option.

在使用分别控制每个轴时，在Y轴上定义效果的强度。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L63)

• `set` **strengthY**(`v`): `void`

Define the strength of the effect on the Y axis, when using separateAxes option.

在使用分别控制每个轴时，在Y轴上定义效果的强度。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L68)

___

### strengthZ

• `get` **strengthZ**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Define the strength of the effect on the Z axis, when using separateAxes option.

在使用分别控制每个轴时，在Z轴上定义效果的强度。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L78)

• `set` **strengthZ**(`v`): `void`

Define the strength of the effect on the Z axis, when using separateAxes option.

在使用分别控制每个轴时，在Z轴上定义效果的强度。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleNoiseModule.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleNoiseModule.ts#L83)
