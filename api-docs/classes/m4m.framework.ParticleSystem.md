# m4m.framework.ParticleSystem

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystem

## Class: ParticleSystem

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystem

粒子系统

**`author`** feng3d

### Implements

* [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)

### Table of contents

#### Properties

* [\_\_class\_\_](m4m.framework.ParticleSystem.md#\_\_class\_\_)
* [gameObject](m4m.framework.ParticleSystem.md#gameobject)
* [layer](m4m.framework.ParticleSystem.md#layer)
* [localToWorldMatrix](m4m.framework.ParticleSystem.md#localtoworldmatrix)
* [material](m4m.framework.ParticleSystem.md#material)
* [moveVec](m4m.framework.ParticleSystem.md#movevec)
* [pivot](m4m.framework.ParticleSystem.md#pivot)
* [queue](m4m.framework.ParticleSystem.md#queue)
* [sortingFudge](m4m.framework.ParticleSystem.md#sortingfudge)
* [speed](m4m.framework.ParticleSystem.md#speed)
* [startDelay](m4m.framework.ParticleSystem.md#startdelay)
* [time](m4m.framework.ParticleSystem.md#time)
* [worldPos](m4m.framework.ParticleSystem.md#worldpos)
* [worldToLocalMatrix](m4m.framework.ParticleSystem.md#worldtolocalmatrix)
* [ClassName](m4m.framework.ParticleSystem.md#classname)

#### Methods

* [\_simulationSpaceChanged](m4m.framework.ParticleSystem.md#\_simulationspacechanged)
* [addListener](m4m.framework.ParticleSystem.md#addlistener)
* [addParticleAcceleration](m4m.framework.ParticleSystem.md#addparticleacceleration)
* [addParticlePosition](m4m.framework.ParticleSystem.md#addparticleposition)
* [addParticleVelocity](m4m.framework.ParticleSystem.md#addparticlevelocity)
* [clone](m4m.framework.ParticleSystem.md#clone)
* [continue](m4m.framework.ParticleSystem.md#continue)
* [onPlay](m4m.framework.ParticleSystem.md#onplay)
* [pause](m4m.framework.ParticleSystem.md#pause)
* [play](m4m.framework.ParticleSystem.md#play)
* [remove](m4m.framework.ParticleSystem.md#remove)
* [removeListener](m4m.framework.ParticleSystem.md#removelistener)
* [removeParticleAcceleration](m4m.framework.ParticleSystem.md#removeparticleacceleration)
* [removeParticlePosition](m4m.framework.ParticleSystem.md#removeparticleposition)
* [removeParticleVelocity](m4m.framework.ParticleSystem.md#removeparticlevelocity)
* [render](m4m.framework.ParticleSystem.md#render)
* [start](m4m.framework.ParticleSystem.md#start)
* [stop](m4m.framework.ParticleSystem.md#stop)
* [update](m4m.framework.ParticleSystem.md#update)

#### Accessors

* [colorBySpeed](m4m.framework.ParticleSystem.md#colorbyspeed)
* [colorOverLifetime](m4m.framework.ParticleSystem.md#coloroverlifetime)
* [emission](m4m.framework.ParticleSystem.md#emission)
* [forceOverLifetime](m4m.framework.ParticleSystem.md#forceoverlifetime)
* [inheritVelocity](m4m.framework.ParticleSystem.md#inheritvelocity)
* [isPaused](m4m.framework.ParticleSystem.md#ispaused)
* [isPlaying](m4m.framework.ParticleSystem.md#isplaying)
* [isStopped](m4m.framework.ParticleSystem.md#isstopped)
* [limitVelocityOverLifetime](m4m.framework.ParticleSystem.md#limitvelocityoverlifetime)
* [main](m4m.framework.ParticleSystem.md#main)
* [noise](m4m.framework.ParticleSystem.md#noise)
* [particleCount](m4m.framework.ParticleSystem.md#particlecount)
* [particleSystemData](m4m.framework.ParticleSystem.md#particlesystemdata)
* [rateAtDuration](m4m.framework.ParticleSystem.md#rateatduration)
* [renderLayer](m4m.framework.ParticleSystem.md#renderlayer)
* [rotationBySpeed](m4m.framework.ParticleSystem.md#rotationbyspeed)
* [rotationOverLifetime](m4m.framework.ParticleSystem.md#rotationoverlifetime)
* [shape](m4m.framework.ParticleSystem.md#shape)
* [single](m4m.framework.ParticleSystem.md#single)
* [sizeBySpeed](m4m.framework.ParticleSystem.md#sizebyspeed)
* [sizeOverLifetime](m4m.framework.ParticleSystem.md#sizeoverlifetime)
* [textureSheetAnimation](m4m.framework.ParticleSystem.md#texturesheetanimation)
* [transform](m4m.framework.ParticleSystem.md#transform)
* [velocityOverLifetime](m4m.framework.ParticleSystem.md#velocityoverlifetime)

#### Constructors

* [constructor](m4m.framework.ParticleSystem.md#constructor)

### Properties

#### \_\_class\_\_

• **\_\_class\_\_**: `"m4m.framework.ParticleSystem"`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L49)

***

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[gameObject](../interfaces/m4m.framework.IRenderer.md#gameobject)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:430](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L430)

***

#### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Transparent`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[layer](../interfaces/m4m.framework.IRenderer.md#layer)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L51)

***

#### localToWorldMatrix

• **localToWorldMatrix**: `matrix`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1210](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1210)

***

#### material

• **material**: [`material`](m4m.framework.material.md)

**`language`** zh\_CN

**`classdesc`** mesh的材质数组

**`version`** m4m 1.0

**Defined in**

[framework/particlesystem/ParticleSystem.ts:342](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L342)

***

#### moveVec

• **moveVec**: `vector3`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1206](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1206)

***

#### pivot

• **pivot**: `vector3`

参考Unity ParticleSystemRenderer.pivot

Modify the pivot point used for rotating particles.

The units are expressed as a multiplier of the particle sizes, relative to their diameters. For example, a value of 0.5 adjusts the pivot by the particle radius, allowing particles to rotate around their edges.

**Defined in**

[framework/particlesystem/ParticleSystem.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L88)

***

#### queue

• **queue**: `number` = `0`

**`language`** zh\_CN

**`classdesc`** 同场景渲染层级时候先后排序依据

**`version`** m4m 1.0

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[queue](../interfaces/m4m.framework.IRenderer.md#queue)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L72)

***

#### sortingFudge

• **sortingFudge**: `number` = `0`

Biases Particle System sorting amongst other transparencies.

Use lower (negative) numbers to prioritize the Particle System to draw closer to the front, and use higher numbers to prioritize other transparent objects.

**Defined in**

[framework/particlesystem/ParticleSystem.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L79)

***

#### speed

• **speed**: `vector3`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1207](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1207)

***

#### startDelay

• **startDelay**: `number` = `0`

Start delay in seconds. 启动延迟(以秒为单位)。在调用.play()时初始化值。

**Defined in**

[framework/particlesystem/ParticleSystem.ts:350](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L350)

***

#### time

• **time**: `number` = `0`

Playback position in seconds.

回放位置(秒)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:141](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L141)

***

#### worldPos

• **worldPos**: `vector3`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1205](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1205)

***

#### worldToLocalMatrix

• **worldToLocalMatrix**: `matrix`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1211](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1211)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"particlesystem"`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L47)

### Methods

#### \_simulationSpaceChanged

▸ **\_simulationSpaceChanged**(): `void`

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:980](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L980)

***

#### addListener

▸ **addListener**<`K`>(`event`, `func`, `thisArg`): `void`

添加UI事件监听者

**Type parameters**

| Name | Type                          |
| ---- | ----------------------------- |
| `K`  | extends `"particleCompleted"` |

**Parameters**

| Name      | Type                                                                                                | Description                                    |
| --------- | --------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| `event`   | `K`                                                                                                 | -                                              |
| `func`    | (`args`: [`GameObjectEventMap`](../interfaces/m4m.framework.GameObjectEventMap.md)\[`K`]) => `void` | 事件触发回调方法 (Warn: 不要使用 func.bind() , 它会导致相等判断失败) |
| `thisArg` | `any`                                                                                               | 回调方法执行者                                        |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:383](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L383)

***

#### addParticleAcceleration

▸ **addParticleAcceleration**(`particle`, `acceleration`, `space`, `name?`): `void`

给指定粒子添加指定空间的速度。

**Parameters**

| Name           | Type                                                                                       | Description                                                   |
| -------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------- |
| `particle`     | [`Particle1`](m4m.framework.Particle1.md)                                                  | 粒子。                                                           |
| `acceleration` | `vector3`                                                                                  | 加速度。                                                          |
| `space`        | [`ParticleSystemSimulationSpace`](../enums/m4m.framework.ParticleSystemSimulationSpace.md) | 加速度所在空间。                                                      |
| `name?`        | `string`                                                                                   | 加速度名称。如果不为 undefined 时保存，调用 removeParticleVelocity 可以移除该部分速度。 |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1142)

***

#### addParticlePosition

▸ **addParticlePosition**(`particle`, `position`, `space`, `name?`): `void`

给指定粒子添加指定空间的位移。

**Parameters**

| Name       | Type                                                                                       | Description                                                  |
| ---------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| `particle` | [`Particle1`](m4m.framework.Particle1.md)                                                  | 粒子。                                                          |
| `position` | `vector3`                                                                                  | 速度。                                                          |
| `space`    | [`ParticleSystemSimulationSpace`](../enums/m4m.framework.ParticleSystemSimulationSpace.md) | 速度所在空间。                                                      |
| `name?`    | `string`                                                                                   | 速度名称。如果不为 undefined 时保存，调用 removeParticleVelocity 可以移除该部分速度。 |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1014](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1014)

***

#### addParticleVelocity

▸ **addParticleVelocity**(`particle`, `velocity`, `space`, `name?`): `void`

给指定粒子添加指定空间的速度。

**Parameters**

| Name       | Type                                                                                       | Description                                                  |
| ---------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| `particle` | [`Particle1`](m4m.framework.Particle1.md)                                                  | 粒子。                                                          |
| `velocity` | `vector3`                                                                                  | 速度。                                                          |
| `space`    | [`ParticleSystemSimulationSpace`](../enums/m4m.framework.ParticleSystemSimulationSpace.md) | 速度所在空间。                                                      |
| `name?`    | `string`                                                                                   | 速度名称。如果不为 undefined 时保存，调用 removeParticleVelocity 可以移除该部分速度。 |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1078](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1078)

***

#### clone

▸ **clone**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[clone](../interfaces/m4m.framework.IRenderer.md#clone)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:424](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L424)

***

#### continue

▸ **continue**(): `void`

继续

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:563](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L563)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[onPlay](../interfaces/m4m.framework.IRenderer.md#onplay)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:399](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L399)

***

#### pause

▸ **pause**(): `void`

暂停

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:555](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L555)

***

#### play

▸ **play**(): `void`

播放

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:517](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L517)

***

#### remove

▸ **remove**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[remove](../interfaces/m4m.framework.IRenderer.md#remove)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:418](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L418)

***

#### removeListener

▸ **removeListener**<`K`>(`event`, `func`, `thisArg`): `void`

移除事件监听者

**Type parameters**

| Name | Type                          |
| ---- | ----------------------------- |
| `K`  | extends `"particleCompleted"` |

**Parameters**

| Name      | Type                                                                                                | Description |
| --------- | --------------------------------------------------------------------------------------------------- | ----------- |
| `event`   | `K`                                                                                                 | 事件类型        |
| `func`    | (`args`: [`GameObjectEventMap`](../interfaces/m4m.framework.GameObjectEventMap.md)\[`K`]) => `void` | 事件触发回调方法    |
| `thisArg` | `any`                                                                                               | 回调方法执行者     |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:394](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L394)

***

#### removeParticleAcceleration

▸ **removeParticleAcceleration**(`particle`, `name`): `void`

移除指定粒子上的加速度

**Parameters**

| Name       | Type                                      | Description |
| ---------- | ----------------------------------------- | ----------- |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) | 粒子。         |
| `name`     | `string`                                  | 加速度名称。      |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1172](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1172)

***

#### removeParticlePosition

▸ **removeParticlePosition**(`particle`, `name`): `void`

移除指定粒子上的位移

**Parameters**

| Name       | Type                                      | Description |
| ---------- | ----------------------------------------- | ----------- |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) | 粒子。         |
| `name`     | `string`                                  | 位移名称。       |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1044](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1044)

***

#### removeParticleVelocity

▸ **removeParticleVelocity**(`particle`, `name`): `void`

移除指定粒子上的速度

**Parameters**

| Name       | Type                                      | Description |
| ---------- | ----------------------------------------- | ----------- |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) | 粒子。         |
| `name`     | `string`                                  | 速度名称。       |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:1108](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L1108)

***

#### render

▸ **render**(`context`, `assetmgr`, `camera`): `void`

**Parameters**

| Name       | Type                                    |
| ---------- | --------------------------------------- |
| `context`  | `renderContext`                         |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `camera`   | [`camera`](m4m.framework.camera.md)     |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[render](../interfaces/m4m.framework.IRenderer.md#render)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:575](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L575)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[start](../interfaces/m4m.framework.IRenderer.md#start)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:404](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L404)

***

#### stop

▸ **stop**(): `void`

停止

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:505](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L505)

***

#### update

▸ **update**(`interval`): `void`

**Parameters**

| Name       | Type     |
| ---------- | -------- |
| `interval` | `number` |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[update](../interfaces/m4m.framework.IRenderer.md#update)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:455](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L455)

### Accessors

#### colorBySpeed

• `get` **colorBySpeed**(): [`ParticleColorBySpeedModule`](m4m.framework.ParticleColorBySpeedModule.md)

颜色随速度变化模块。

**Returns**

[`ParticleColorBySpeedModule`](m4m.framework.ParticleColorBySpeedModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:223](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L223)

• `set` **colorBySpeed**(`v`): `void`

颜色随速度变化模块。

**Parameters**

| Name | Type                                                                        |
| ---- | --------------------------------------------------------------------------- |
| `v`  | [`ParticleColorBySpeedModule`](m4m.framework.ParticleColorBySpeedModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:224](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L224)

***

#### colorOverLifetime

• `get` **colorOverLifetime**(): [`ParticleColorOverLifetimeModule`](m4m.framework.ParticleColorOverLifetimeModule.md)

**Returns**

[`ParticleColorOverLifetimeModule`](m4m.framework.ParticleColorOverLifetimeModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:211](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L211)

• `set` **colorOverLifetime**(`v`): `void`

**Parameters**

| Name | Type                                                                                  |
| ---- | ------------------------------------------------------------------------------------- |
| `v`  | [`ParticleColorOverLifetimeModule`](m4m.framework.ParticleColorOverLifetimeModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:212](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L212)

***

#### emission

• `get` **emission**(): [`ParticleEmissionModule`](m4m.framework.ParticleEmissionModule.md)

**Returns**

[`ParticleEmissionModule`](m4m.framework.ParticleEmissionModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:152](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L152)

• `set` **emission**(`v`): `void`

**Parameters**

| Name | Type                                                                |
| ---- | ------------------------------------------------------------------- |
| `v`  | [`ParticleEmissionModule`](m4m.framework.ParticleEmissionModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:153](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L153)

***

#### forceOverLifetime

• `get` **forceOverLifetime**(): [`ParticleForceOverLifetimeModule`](m4m.framework.ParticleForceOverLifetimeModule.md)

**Returns**

[`ParticleForceOverLifetimeModule`](m4m.framework.ParticleForceOverLifetimeModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:202](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L202)

• `set` **forceOverLifetime**(`v`): `void`

**Parameters**

| Name | Type                                                                                  |
| ---- | ------------------------------------------------------------------------------------- |
| `v`  | [`ParticleForceOverLifetimeModule`](m4m.framework.ParticleForceOverLifetimeModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:203](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L203)

***

#### inheritVelocity

• `get` **inheritVelocity**(): [`ParticleInheritVelocityModule`](m4m.framework.ParticleInheritVelocityModule.md)

Script interface for the Particle System velocity inheritance module.

粒子系统速度继承模块。

**Returns**

[`ParticleInheritVelocityModule`](m4m.framework.ParticleInheritVelocityModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:193](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L193)

• `set` **inheritVelocity**(`v`): `void`

Script interface for the Particle System velocity inheritance module.

粒子系统速度继承模块。

**Parameters**

| Name | Type                                                                              |
| ---- | --------------------------------------------------------------------------------- |
| `v`  | [`ParticleInheritVelocityModule`](m4m.framework.ParticleInheritVelocityModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:194](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L194)

***

#### isPaused

• `get` **isPaused**(): `boolean`

Is the particle system paused right now ?

粒子系统现在暂停了吗?

**Returns**

`boolean`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L121)

***

#### isPlaying

• `get` **isPlaying**(): `boolean`

Is the particle system playing right now ?

粒子系统正在运行吗?

**Returns**

`boolean`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L100)

***

#### isStopped

• `get` **isStopped**(): `boolean`

Is the particle system stopped right now ?

粒子系统现在停止了吗?

**Returns**

`boolean`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:111](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L111)

***

#### limitVelocityOverLifetime

• `get` **limitVelocityOverLifetime**(): [`ParticleLimitVelocityOverLifetimeModule`](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md)

**Returns**

[`ParticleLimitVelocityOverLifetimeModule`](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:179](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L179)

• `set` **limitVelocityOverLifetime**(`v`): `void`

**Parameters**

| Name | Type                                                                                                  |
| ---- | ----------------------------------------------------------------------------------------------------- |
| `v`  | [`ParticleLimitVelocityOverLifetimeModule`](m4m.framework.ParticleLimitVelocityOverLifetimeModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:180](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L180)

***

#### main

• `get` **main**(): [`ParticleMainModule`](m4m.framework.ParticleMainModule.md)

**Returns**

[`ParticleMainModule`](m4m.framework.ParticleMainModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:143](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L143)

• `set` **main**(`v`): `void`

**Parameters**

| Name | Type                                                        |
| ---- | ----------------------------------------------------------- |
| `v`  | [`ParticleMainModule`](m4m.framework.ParticleMainModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:144](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L144)

***

#### noise

• `get` **noise**(): [`ParticleNoiseModule`](m4m.framework.ParticleNoiseModule.md)

旋转角度随速度变化模块

**Returns**

[`ParticleNoiseModule`](m4m.framework.ParticleNoiseModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:277](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L277)

• `set` **noise**(`v`): `void`

旋转角度随速度变化模块

**Parameters**

| Name | Type                                                          |
| ---- | ------------------------------------------------------------- |
| `v`  | [`ParticleNoiseModule`](m4m.framework.ParticleNoiseModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:278](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L278)

***

#### particleCount

• `get` **particleCount**(): `number`

The current number of particles (Read Only).

当前粒子数(只读)。

**Returns**

`number`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:131](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L131)

***

#### particleSystemData

• `get` **particleSystemData**(): [`ParticleSystemData`](m4m.framework.ParticleSystemData.md)

**Returns**

[`ParticleSystemData`](m4m.framework.ParticleSystemData.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:353](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L353)

• `set` **particleSystemData**(`v`): `void`

**Parameters**

| Name | Type                                                        |
| ---- | ----------------------------------------------------------- |
| `v`  | [`ParticleSystemData`](m4m.framework.ParticleSystemData.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:358](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L358)

***

#### rateAtDuration

• `get` **rateAtDuration**(): `number`

此时在周期中的位置

**Returns**

`number`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:772](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L772)

***

#### renderLayer

• `get` **renderLayer**(): `number`

**`language`** zh\_CN

**`classdesc`** 渲染层级

**`version`** m4m 1.0

**Returns**

`number`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:60](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L60)

• `set` **renderLayer**(`layer`): `void`

**`language`** zh\_CN

**`classdesc`** 渲染层级

**`version`** m4m 1.0

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `layer` | `number` |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L61)

***

#### rotationBySpeed

• `get` **rotationBySpeed**(): [`ParticleRotationBySpeedModule`](m4m.framework.ParticleRotationBySpeedModule.md)

旋转角度随速度变化模块

**Returns**

[`ParticleRotationBySpeedModule`](m4m.framework.ParticleRotationBySpeedModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:265](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L265)

• `set` **rotationBySpeed**(`v`): `void`

旋转角度随速度变化模块

**Parameters**

| Name | Type                                                                              |
| ---- | --------------------------------------------------------------------------------- |
| `v`  | [`ParticleRotationBySpeedModule`](m4m.framework.ParticleRotationBySpeedModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:266](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L266)

***

#### rotationOverLifetime

• `get` **rotationOverLifetime**(): [`ParticleRotationOverLifetimeModule`](m4m.framework.ParticleRotationOverLifetimeModule.md)

**Returns**

[`ParticleRotationOverLifetimeModule`](m4m.framework.ParticleRotationOverLifetimeModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:253](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L253)

• `set` **rotationOverLifetime**(`v`): `void`

**Parameters**

| Name | Type                                                                                        |
| ---- | ------------------------------------------------------------------------------------------- |
| `v`  | [`ParticleRotationOverLifetimeModule`](m4m.framework.ParticleRotationOverLifetimeModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:254](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L254)

***

#### shape

• `get` **shape**(): [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md)

**Returns**

[`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:161](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L161)

• `set` **shape**(`v`): `void`

**Parameters**

| Name | Type                                                          |
| ---- | ------------------------------------------------------------- |
| `v`  | [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:162](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L162)

***

#### single

• `get` **single**(): `boolean`

**Returns**

`boolean`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:344](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L344)

***

#### sizeBySpeed

• `get` **sizeBySpeed**(): [`ParticleSizeBySpeedModule`](m4m.framework.ParticleSizeBySpeedModule.md)

缩放随速度变化模块

**Returns**

[`ParticleSizeBySpeedModule`](m4m.framework.ParticleSizeBySpeedModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:244](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L244)

• `set` **sizeBySpeed**(`v`): `void`

缩放随速度变化模块

**Parameters**

| Name | Type                                                                      |
| ---- | ------------------------------------------------------------------------- |
| `v`  | [`ParticleSizeBySpeedModule`](m4m.framework.ParticleSizeBySpeedModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:245](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L245)

***

#### sizeOverLifetime

• `get` **sizeOverLifetime**(): [`ParticleSizeOverLifetimeModule`](m4m.framework.ParticleSizeOverLifetimeModule.md)

**Returns**

[`ParticleSizeOverLifetimeModule`](m4m.framework.ParticleSizeOverLifetimeModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:232](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L232)

• `set` **sizeOverLifetime**(`v`): `void`

**Parameters**

| Name | Type                                                                                |
| ---- | ----------------------------------------------------------------------------------- |
| `v`  | [`ParticleSizeOverLifetimeModule`](m4m.framework.ParticleSizeOverLifetimeModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:233](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L233)

***

#### textureSheetAnimation

• `get` **textureSheetAnimation**(): [`ParticleTextureSheetAnimationModule`](m4m.framework.ParticleTextureSheetAnimationModule.md)

粒子系统纹理表动画模块。

**Returns**

[`ParticleTextureSheetAnimationModule`](m4m.framework.ParticleTextureSheetAnimationModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:289](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L289)

• `set` **textureSheetAnimation**(`v`): `void`

粒子系统纹理表动画模块。

**Parameters**

| Name | Type                                                                                          |
| ---- | --------------------------------------------------------------------------------------------- |
| `v`  | [`ParticleTextureSheetAnimationModule`](m4m.framework.ParticleTextureSheetAnimationModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:290](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L290)

***

#### transform

• `get` **transform**(): [`transform`](m4m.framework.transform.md)

**Returns**

[`transform`](m4m.framework.transform.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L90)

***

#### velocityOverLifetime

• `get` **velocityOverLifetime**(): [`ParticleVelocityOverLifetimeModule`](m4m.framework.ParticleVelocityOverLifetimeModule.md)

**Returns**

[`ParticleVelocityOverLifetimeModule`](m4m.framework.ParticleVelocityOverLifetimeModule.md)

**Defined in**

[framework/particlesystem/ParticleSystem.ts:170](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L170)

• `set` **velocityOverLifetime**(`v`): `void`

**Parameters**

| Name | Type                                                                                        |
| ---- | ------------------------------------------------------------------------------------------- |
| `v`  | [`ParticleVelocityOverLifetimeModule`](m4m.framework.ParticleVelocityOverLifetimeModule.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/ParticleSystem.ts:171](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L171)

### Constructors

#### constructor

• **new ParticleSystem**()

**Defined in**

[framework/particlesystem/ParticleSystem.ts:432](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L432)
