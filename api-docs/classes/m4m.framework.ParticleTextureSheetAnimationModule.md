# m4m.framework.ParticleTextureSheetAnimationModule

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleTextureSheetAnimationModule

## Class: ParticleTextureSheetAnimationModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleTextureSheetAnimationModule

粒子系统纹理表动画模块。

**`author`** feng3d

### Hierarchy

*   [`ParticleModule`](m4m.framework.ParticleModule.md)

    ↳ **`ParticleTextureSheetAnimationModule`**

### Table of contents

#### Properties

* [animation](m4m.framework.ParticleTextureSheetAnimationModule.md#animation)
* [cycleCount](m4m.framework.ParticleTextureSheetAnimationModule.md#cyclecount)
* [enabled](m4m.framework.ParticleTextureSheetAnimationModule.md#enabled)
* [flipUV](m4m.framework.ParticleTextureSheetAnimationModule.md#flipuv)
* [frameOverTime](m4m.framework.ParticleTextureSheetAnimationModule.md#frameovertime)
* [particleSystem](m4m.framework.ParticleTextureSheetAnimationModule.md#particlesystem)
* [startFrame](m4m.framework.ParticleTextureSheetAnimationModule.md#startframe)
* [tiles](m4m.framework.ParticleTextureSheetAnimationModule.md#tiles)
* [useRandomRow](m4m.framework.ParticleTextureSheetAnimationModule.md#userandomrow)
* [uvChannelMask](m4m.framework.ParticleTextureSheetAnimationModule.md#uvchannelmask)

#### Constructors

* [constructor](m4m.framework.ParticleTextureSheetAnimationModule.md#constructor)

#### Accessors

* [flipU](m4m.framework.ParticleTextureSheetAnimationModule.md#flipu)
* [flipV](m4m.framework.ParticleTextureSheetAnimationModule.md#flipv)
* [frameOverTimeMultiplier](m4m.framework.ParticleTextureSheetAnimationModule.md#frameovertimemultiplier)
* [numTilesX](m4m.framework.ParticleTextureSheetAnimationModule.md#numtilesx)
* [numTilesY](m4m.framework.ParticleTextureSheetAnimationModule.md#numtilesy)
* [rowIndex](m4m.framework.ParticleTextureSheetAnimationModule.md#rowindex)
* [startFrameMultiplier](m4m.framework.ParticleTextureSheetAnimationModule.md#startframemultiplier)

#### Methods

* [initParticleState](m4m.framework.ParticleTextureSheetAnimationModule.md#initparticlestate)
* [updateParticleState](m4m.framework.ParticleTextureSheetAnimationModule.md#updateparticlestate)

### Properties

#### animation

• **animation**: [`ParticleSystemAnimationType`](../enums/m4m.framework.ParticleSystemAnimationType.md) = `ParticleSystemAnimationType.WholeSheet`

Specifies the animation type.

指定动画类型。

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L25)

***

#### cycleCount

• **cycleCount**: `number` = `1`

Specifies how many times the animation will loop during the lifetime of the particle.

指定在粒子的生命周期内动画将循环多少次。

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:70](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L70)

***

#### enabled

• **enabled**: `boolean` = `false`

是否开启

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[enabled](m4m.framework.ParticleModule.md#enabled)

**Defined in**

[framework/particlesystem/modules/ParticleModule.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L14)

***

#### flipUV

• **flipUV**: `vector2`

Flip the UV coordinate on particles, causing them to appear mirrored.

在粒子上翻转UV坐标，使它们呈现镜像翻转。

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L78)

***

#### frameOverTime

• **frameOverTime**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Curve to control which frame of the texture sheet animation to play.

曲线控制哪个帧的纹理表动画播放。

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L33)

***

#### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

粒子系统

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[particleSystem](m4m.framework.ParticleModule.md#particlesystem)

**Defined in**

[framework/particlesystem/modules/ParticleModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L19)

***

#### startFrame

• **startFrame**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

Define a random starting frame for the texture sheet animation.

为纹理表动画定义一个随机的起始帧。

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L62)

***

#### tiles

• **tiles**: `vector2`

Defines the tiling of the texture.

定义纹理的平铺。

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L17)

***

#### useRandomRow

• **useRandomRow**: `boolean` = `true`

Use a random row of the texture sheet for each particle emitted.

对每个发射的粒子使用纹理表的随机行。

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L41)

***

#### uvChannelMask

• **uvChannelMask**: [`UVChannelFlags`](../enums/m4m.framework.UVChannelFlags.md) = `UVChannelFlags.Everything`

Choose which UV channels will receive texture animation.

选择哪个UV通道将接收纹理动画。

todo 目前引擎中只有一套UV

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L88)

### Constructors

#### constructor

• **new ParticleTextureSheetAnimationModule**()

**Inherited from**

[ParticleModule](m4m.framework.ParticleModule.md).[constructor](m4m.framework.ParticleModule.md#constructor)

### Accessors

#### flipU

• `get` **flipU**(): `number`

Flip the U coordinate on particles, causing them to appear mirrored horizontally.

在粒子上翻转U坐标，使它们呈现水平镜像。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:95](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L95)

• `set` **flipU**(`v`): `void`

Flip the U coordinate on particles, causing them to appear mirrored horizontally.

在粒子上翻转U坐标，使它们呈现水平镜像。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L100)

***

#### flipV

• `get` **flipV**(): `number`

Flip the V coordinate on particles, causing them to appear mirrored vertically.

在粒子上翻转V坐标，使它们垂直镜像。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:110](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L110)

• `set` **flipV**(`v`): `void`

Flip the V coordinate on particles, causing them to appear mirrored vertically.

在粒子上翻转V坐标，使它们垂直镜像。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:115](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L115)

***

#### frameOverTimeMultiplier

• `get` **frameOverTimeMultiplier**(): `number`

Frame over time mutiplier.

帧随时间变化的乘数。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:125](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L125)

• `set` **frameOverTimeMultiplier**(`v`): `void`

Frame over time mutiplier.

帧随时间变化的乘数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:130](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L130)

***

#### numTilesX

• `get` **numTilesX**(): `number`

Defines the tiling of the texture in the X axis.

定义纹理在X轴上的平铺。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:140](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L140)

• `set` **numTilesX**(`v`): `void`

Defines the tiling of the texture in the X axis.

定义纹理在X轴上的平铺。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:145](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L145)

***

#### numTilesY

• `get` **numTilesY**(): `number`

Defines the tiling of the texture in the Y axis.

定义纹理在Y轴上的平铺。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:155](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L155)

• `set` **numTilesY**(`v`): `void`

Defines the tiling of the texture in the Y axis.

定义纹理在Y轴上的平铺。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:160](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L160)

***

#### rowIndex

• `get` **rowIndex**(): `number`

Explicitly select which row of the texture sheet is used, when useRandomRow is set to false.

当useRandomRow设置为false时，显式选择使用纹理表的哪一行。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L49)

• `set` **rowIndex**(`v`): `void`

Explicitly select which row of the texture sheet is used, when useRandomRow is set to false.

当useRandomRow设置为false时，显式选择使用纹理表的哪一行。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L50)

***

#### startFrameMultiplier

• `get` **startFrameMultiplier**(): `number`

Starting frame multiplier.

起始帧乘数。

**Returns**

`number`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:170](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L170)

• `set` **startFrameMultiplier**(`v`): `void`

Starting frame multiplier.

起始帧乘数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:175](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L175)

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

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:184](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L184)

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

[framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts:195](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleTextureSheetAnimationModule.ts#L195)
