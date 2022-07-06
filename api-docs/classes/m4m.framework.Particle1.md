# m4m.framework.Particle1

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / Particle1

## Class: Particle1

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).Particle1

粒子

**`author`** feng3d

### Table of contents

#### Properties

* [acceleration](m4m.framework.Particle1.md#acceleration)
* [angularVelocity](m4m.framework.Particle1.md#angularvelocity)
* [birthRateAtDuration](m4m.framework.Particle1.md#birthrateatduration)
* [birthTime](m4m.framework.Particle1.md#birthtime)
* [cache](m4m.framework.Particle1.md#cache)
* [color](m4m.framework.Particle1.md#color)
* [flipUV](m4m.framework.Particle1.md#flipuv)
* [lifetime](m4m.framework.Particle1.md#lifetime)
* [position](m4m.framework.Particle1.md#position)
* [rateAtLifeTime](m4m.framework.Particle1.md#rateatlifetime)
* [rotation](m4m.framework.Particle1.md#rotation)
* [size](m4m.framework.Particle1.md#size)
* [startColor](m4m.framework.Particle1.md#startcolor)
* [startSize](m4m.framework.Particle1.md#startsize)
* [tilingOffset](m4m.framework.Particle1.md#tilingoffset)
* [velocity](m4m.framework.Particle1.md#velocity)

#### Constructors

* [constructor](m4m.framework.Particle1.md#constructor)

#### Methods

* [updateState](m4m.framework.Particle1.md#updatestate)

### Properties

#### acceleration

• **acceleration**: `vector3`

加速度

**Defined in**

[framework/particlesystem/Particle1.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L34)

***

#### angularVelocity

• **angularVelocity**: `vector3`

角速度

**Defined in**

[framework/particlesystem/Particle1.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L44)

***

#### birthRateAtDuration

• **birthRateAtDuration**: `number`

出生时在周期的位置（在发射时被更新）

**Defined in**

[framework/particlesystem/Particle1.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L79)

***

#### birthTime

• **birthTime**: `number` = `0`

出生时间

**Defined in**

[framework/particlesystem/Particle1.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L14)

***

#### cache

• **cache**: `Object` = `{}`

缓存，用于存储计算时临时数据

**Defined in**

[framework/particlesystem/Particle1.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L89)

***

#### color

• **color**: `color`

颜色

**Defined in**

[framework/particlesystem/Particle1.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L59)

***

#### flipUV

• **flipUV**: `vector2`

在粒子上翻转UV坐标，使它们呈现水平镜像。

**Defined in**

[framework/particlesystem/Particle1.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L74)

***

#### lifetime

• **lifetime**: `number` = `5`

寿命

**Defined in**

[framework/particlesystem/Particle1.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L19)

***

#### position

• **position**: `vector3`

位置

**Defined in**

[framework/particlesystem/Particle1.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L24)

***

#### rateAtLifeTime

• **rateAtLifeTime**: `number`

此时粒子在生命周期的位置（在更新状态前被更新）

**Defined in**

[framework/particlesystem/Particle1.ts:84](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L84)

***

#### rotation

• **rotation**: `vector3`

旋转角度

**Defined in**

[framework/particlesystem/Particle1.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L39)

***

#### size

• **size**: `vector3`

尺寸

**Defined in**

[framework/particlesystem/Particle1.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L49)

***

#### startColor

• **startColor**: `color`

起始颜色

**Defined in**

[framework/particlesystem/Particle1.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L64)

***

#### startSize

• **startSize**: `vector3`

起始尺寸

**Defined in**

[framework/particlesystem/Particle1.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L54)

***

#### tilingOffset

• **tilingOffset**: `vector4`

纹理UV缩放和偏移。

**Defined in**

[framework/particlesystem/Particle1.ts:69](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L69)

***

#### velocity

• **velocity**: `vector3`

速度

**Defined in**

[framework/particlesystem/Particle1.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L29)

### Constructors

#### constructor

• **new Particle1**()

### Methods

#### updateState

▸ **updateState**(`preTime`, `time`): `void`

更新状态

**Parameters**

| Name      | Type     |
| --------- | -------- |
| `preTime` | `number` |
| `time`    | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/Particle1.ts:94](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/Particle1.ts#L94)
