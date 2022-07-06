# m4m.framework.EffectElementEmission

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / EffectElementEmission

## Class: EffectElementEmission

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).EffectElementEmission

### Implements

* [`IEffectElement`](../interfaces/m4m.framework.IEffectElement.md)

### Table of contents

#### Properties

* [active](m4m.framework.EffectElementEmission.md#active)
* [alphaNodes](m4m.framework.EffectElementEmission.md#alphanodes)
* [angle](m4m.framework.EffectElementEmission.md#angle)
* [angleSpeed](m4m.framework.EffectElementEmission.md#anglespeed)
* [beloop](m4m.framework.EffectElementEmission.md#beloop)
* [colorNodes](m4m.framework.EffectElementEmission.md#colornodes)
* [colorRate](m4m.framework.EffectElementEmission.md#colorrate)
* [column](m4m.framework.EffectElementEmission.md#column)
* [count](m4m.framework.EffectElementEmission.md#count)
* [deadParticles](m4m.framework.EffectElementEmission.md#deadparticles)
* [delayTime](m4m.framework.EffectElementEmission.md#delaytime)
* [depth](m4m.framework.EffectElementEmission.md#depth)
* [duration](m4m.framework.EffectElementEmission.md#duration)
* [effectSys](m4m.framework.EffectElementEmission.md#effectsys)
* [elementType](m4m.framework.EffectElementEmission.md#elementtype)
* [emissionBatchers](m4m.framework.EffectElementEmission.md#emissionbatchers)
* [emissionCount](m4m.framework.EffectElementEmission.md#emissioncount)
* [emissionType](m4m.framework.EffectElementEmission.md#emissiontype)
* [emitFrom](m4m.framework.EffectElementEmission.md#emitfrom)
* [enableColorOverLifetime](m4m.framework.EffectElementEmission.md#enablecoloroverlifetime)
* [enableRotOverLifeTime](m4m.framework.EffectElementEmission.md#enablerotoverlifetime)
* [enableSizeOverLifetime](m4m.framework.EffectElementEmission.md#enablesizeoverlifetime)
* [enableTexAnimation](m4m.framework.EffectElementEmission.md#enabletexanimation)
* [enableVelocityOverLifetime](m4m.framework.EffectElementEmission.md#enablevelocityoverlifetime)
* [gameObject](m4m.framework.EffectElementEmission.md#gameobject)
* [height](m4m.framework.EffectElementEmission.md#height)
* [lifeTime](m4m.framework.EffectElementEmission.md#lifetime)
* [mat](m4m.framework.EffectElementEmission.md#mat)
* [matToObj](m4m.framework.EffectElementEmission.md#mattoobj)
* [mesh](m4m.framework.EffectElementEmission.md#mesh)
* [moveSpeed](m4m.framework.EffectElementEmission.md#movespeed)
* [name](m4m.framework.EffectElementEmission.md#name)
* [perIndexxCount](m4m.framework.EffectElementEmission.md#perindexxcount)
* [perVertexCount](m4m.framework.EffectElementEmission.md#pervertexcount)
* [radius](m4m.framework.EffectElementEmission.md#radius)
* [rendermodel](m4m.framework.EffectElementEmission.md#rendermodel)
* [rotRotation](m4m.framework.EffectElementEmission.md#rotrotation)
* [rotScale](m4m.framework.EffectElementEmission.md#rotscale)
* [rotTranslate](m4m.framework.EffectElementEmission.md#rottranslate)
* [row](m4m.framework.EffectElementEmission.md#row)
* [shapeType](m4m.framework.EffectElementEmission.md#shapetype)
* [simulateInLocalSpace](m4m.framework.EffectElementEmission.md#simulateinlocalspace)
* [simulationSpeed](m4m.framework.EffectElementEmission.md#simulationspeed)
* [sizeNodes](m4m.framework.EffectElementEmission.md#sizenodes)
* [startColor](m4m.framework.EffectElementEmission.md#startcolor)
* [startEuler](m4m.framework.EffectElementEmission.md#starteuler)
* [startScale](m4m.framework.EffectElementEmission.md#startscale)
* [uSpeed](m4m.framework.EffectElementEmission.md#uspeed)
* [uvType](m4m.framework.EffectElementEmission.md#uvtype)
* [vSpeed](m4m.framework.EffectElementEmission.md#vspeed)
* [vbo](m4m.framework.EffectElementEmission.md#vbo)
* [vertexSize](m4m.framework.EffectElementEmission.md#vertexsize)
* [vf](m4m.framework.EffectElementEmission.md#vf)
* [webgl](m4m.framework.EffectElementEmission.md#webgl)
* [width](m4m.framework.EffectElementEmission.md#width)

#### Methods

* [cloneMeshEBO](m4m.framework.EffectElementEmission.md#clonemeshebo)
* [cloneMeshVBO](m4m.framework.EffectElementEmission.md#clonemeshvbo)
* [dispose](m4m.framework.EffectElementEmission.md#dispose)
* [getWorldRotation](m4m.framework.EffectElementEmission.md#getworldrotation)
* [getmatrixToObj](m4m.framework.EffectElementEmission.md#getmatrixtoobj)
* [getmatrixToWorld](m4m.framework.EffectElementEmission.md#getmatrixtoworld)
* [render](m4m.framework.EffectElementEmission.md#render)
* [update](m4m.framework.EffectElementEmission.md#update)
* [writeToJson](m4m.framework.EffectElementEmission.md#writetojson)

#### Constructors

* [constructor](m4m.framework.EffectElementEmission.md#constructor)

#### Accessors

* [renderCamera](m4m.framework.EffectElementEmission.md#rendercamera)

### Properties

#### active

• **active**: `boolean` = `true`

**Defined in**

[framework/particle/new/elementEmission.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L10)

***

#### alphaNodes

• **alphaNodes**: [`NumberKey`](m4m.framework.NumberKey.md)\[]

**Defined in**

[framework/particle/new/elementEmission.ts:73](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L73)

***

#### angle

• **angle**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L51)

***

#### angleSpeed

• **angleSpeed**: [`NumberData`](m4m.framework.NumberData.md)

**Defined in**

[framework/particle/new/elementEmission.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L68)

***

#### beloop

• **beloop**: `boolean` = `true`

**Implementation of**

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[beloop](../interfaces/m4m.framework.IEffectElement.md#beloop)

**Defined in**

[framework/particle/new/elementEmission.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L25)

***

#### colorNodes

• **colorNodes**: [`Vector3Key`](m4m.framework.Vector3Key.md)\[]

**Defined in**

[framework/particle/new/elementEmission.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L71)

***

#### colorRate

• **colorRate**: `number` = `1`

**Defined in**

[framework/particle/new/elementEmission.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L32)

***

#### column

• **column**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L82)

***

#### count

• **count**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L83)

***

#### deadParticles

• **deadParticles**: `Particle_new`\[]

**Defined in**

[framework/particle/new/elementEmission.ts:95](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L95)

***

#### delayTime

• **delayTime**: `number` = `0`

**Implementation of**

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[delayTime](../interfaces/m4m.framework.IEffectElement.md#delaytime)

**Defined in**

[framework/particle/new/elementEmission.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L24)

***

#### depth

• **depth**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L46)

***

#### duration

• **duration**: [`NumberData`](m4m.framework.NumberData.md)

**Defined in**

[framework/particle/new/elementEmission.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L34)

***

#### effectSys

• **effectSys**: [`TestEffectSystem`](m4m.framework.TestEffectSystem.md)

**Defined in**

[framework/particle/new/elementEmission.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L9)

***

#### elementType

• **elementType**: `EffectElementTypeEnum` = `EffectElementTypeEnum.EmissionType`

**Implementation of**

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[elementType](../interfaces/m4m.framework.IEffectElement.md#elementtype)

**Defined in**

[framework/particle/new/elementEmission.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L23)

***

#### emissionBatchers

• **emissionBatchers**: `EmissionBatcher_new`\[]

**Defined in**

[framework/particle/new/elementEmission.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L93)

***

#### emissionCount

• **emissionCount**: [`NumberData`](m4m.framework.NumberData.md)

**Defined in**

[framework/particle/new/elementEmission.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L35)

***

#### emissionType

• **emissionType**: `ParticleEmissionType` = `ParticleEmissionType.burst`

**Defined in**

[framework/particle/new/elementEmission.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L38)

***

#### emitFrom

• **emitFrom**: `emitfromenum` = `emitfromenum.base`

**Defined in**

[framework/particle/new/elementEmission.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L52)

***

#### enableColorOverLifetime

• **enableColorOverLifetime**: `boolean` = `false`

**Defined in**

[framework/particle/new/elementEmission.ts:70](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L70)

***

#### enableRotOverLifeTime

• **enableRotOverLifeTime**: `boolean` = `false`

**Defined in**

[framework/particle/new/elementEmission.ts:67](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L67)

***

#### enableSizeOverLifetime

• **enableSizeOverLifetime**: `boolean` = `false`

**Defined in**

[framework/particle/new/elementEmission.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L64)

***

#### enableTexAnimation

• **enableTexAnimation**: `boolean` = `false`

**Defined in**

[framework/particle/new/elementEmission.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L75)

***

#### enableVelocityOverLifetime

• **enableVelocityOverLifetime**: `boolean` = `false`

**Defined in**

[framework/particle/new/elementEmission.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L61)

***

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**Defined in**

[framework/particle/new/elementEmission.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L8)

***

#### height

• **height**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L45)

***

#### lifeTime

• **lifeTime**: [`NumberData`](m4m.framework.NumberData.md)

**Defined in**

[framework/particle/new/elementEmission.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L27)

***

#### mat

• **mat**: [`material`](m4m.framework.material.md)

**Implementation of**

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[mat](../interfaces/m4m.framework.IEffectElement.md#mat)

**Defined in**

[framework/particle/new/elementEmission.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L56)

***

#### matToObj

• **matToObj**: `matrix`

**Defined in**

[framework/particle/new/elementEmission.ts:162](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L162)

***

#### mesh

• **mesh**: [`mesh`](m4m.framework.mesh.md)

**Implementation of**

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[mesh](../interfaces/m4m.framework.IEffectElement.md#mesh)

**Defined in**

[framework/particle/new/elementEmission.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L57)

***

#### moveSpeed

• **moveSpeed**: [`Vector3Data`](m4m.framework.Vector3Data.md)

**Defined in**

[framework/particle/new/elementEmission.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L62)

***

#### name

• **name**: `string`

**Implementation of**

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[name](../interfaces/m4m.framework.IEffectElement.md#name)

**Defined in**

[framework/particle/new/elementEmission.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L22)

***

#### perIndexxCount

• **perIndexxCount**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L89)

***

#### perVertexCount

• **perVertexCount**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L88)

***

#### radius

• **radius**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L48)

***

#### rendermodel

• **rendermodel**: `RenderModel` = `RenderModel.BillBoard`

**Defined in**

[framework/particle/new/elementEmission.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L54)

***

#### rotRotation

• **rotRotation**: `vector3`

**Defined in**

[framework/particle/new/elementEmission.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L19)

***

#### rotScale

• **rotScale**: `vector3`

**Defined in**

[framework/particle/new/elementEmission.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L18)

***

#### rotTranslate

• **rotTranslate**: `vector3`

**Defined in**

[framework/particle/new/elementEmission.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L17)

***

#### row

• **row**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L81)

***

#### shapeType

• **shapeType**: `ParticleSystemShape` = `ParticleSystemShape.NORMAL`

**Defined in**

[framework/particle/new/elementEmission.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L41)

***

#### simulateInLocalSpace

• **simulateInLocalSpace**: `boolean` = `true`

**Defined in**

[framework/particle/new/elementEmission.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L28)

***

#### simulationSpeed

• **simulationSpeed**: [`NumberData`](m4m.framework.NumberData.md)

**Defined in**

[framework/particle/new/elementEmission.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L42)

***

#### sizeNodes

• **sizeNodes**: [`NumberKey`](m4m.framework.NumberKey.md)\[]

**Defined in**

[framework/particle/new/elementEmission.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L65)

***

#### startColor

• **startColor**: `color`

**Defined in**

[framework/particle/new/elementEmission.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L31)

***

#### startEuler

• **startEuler**: [`Vector3Data`](m4m.framework.Vector3Data.md)

**Defined in**

[framework/particle/new/elementEmission.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L30)

***

#### startScale

• **startScale**: [`Vector3Data`](m4m.framework.Vector3Data.md)

**Defined in**

[framework/particle/new/elementEmission.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L29)

***

#### uSpeed

• **uSpeed**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L78)

***

#### uvType

• **uvType**: [`UVTypeEnum`](../enums/m4m.framework.UVTypeEnum.md) = `UVTypeEnum.NONE`

**Defined in**

[framework/particle/new/elementEmission.ts:76](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L76)

***

#### vSpeed

• **vSpeed**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L79)

***

#### vbo

• **vbo**: `Float32Array`

**Defined in**

[framework/particle/new/elementEmission.ts:307](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L307)

***

#### vertexSize

• **vertexSize**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L90)

***

#### vf

• **vf**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L12)

***

#### webgl

• **webgl**: `WebGLRenderingContext`

**Defined in**

[framework/particle/new/elementEmission.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L7)

***

#### width

• **width**: `number`

**Defined in**

[framework/particle/new/elementEmission.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L44)

### Methods

#### cloneMeshEBO

▸ **cloneMeshEBO**(): `Uint16Array`

**Returns**

`Uint16Array`

**Defined in**

[framework/particle/new/elementEmission.ts:330](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L330)

***

#### cloneMeshVBO

▸ **cloneMeshVBO**(): `Float32Array`

**Returns**

`Float32Array`

**Defined in**

[framework/particle/new/elementEmission.ts:322](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L322)

***

#### dispose

▸ **dispose**(): `void`

**Returns**

`void`

**Implementation of**

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[dispose](../interfaces/m4m.framework.IEffectElement.md#dispose)

**Defined in**

[framework/particle/new/elementEmission.ts:298](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L298)

***

#### getWorldRotation

▸ **getWorldRotation**(): `quaternion`

**Returns**

`quaternion`

**Defined in**

[framework/particle/new/elementEmission.ts:155](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L155)

***

#### getmatrixToObj

▸ **getmatrixToObj**(): `void`

**Returns**

`void`

**Defined in**

[framework/particle/new/elementEmission.ts:164](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L164)

***

#### getmatrixToWorld

▸ **getmatrixToWorld**(): `matrix`

**Returns**

`matrix`

**Defined in**

[framework/particle/new/elementEmission.ts:170](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L170)

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

**Defined in**

[framework/particle/new/elementEmission.ts:282](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L282)

***

#### update

▸ **update**(`delta`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Defined in**

[framework/particle/new/elementEmission.ts:177](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L177)

***

#### writeToJson

▸ **writeToJson**(`obj`): `void`

**Parameters**

| Name  | Type  |
| ----- | ----- |
| `obj` | `any` |

**Returns**

`void`

**Implementation of**

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[writeToJson](../interfaces/m4m.framework.IEffectElement.md#writetojson)

**Defined in**

[framework/particle/new/elementEmission.ts:339](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L339)

### Constructors

#### constructor

• **new EffectElementEmission**(`sys`, `data?`)

**Parameters**

| Name   | Type                                                    | Default value |
| ------ | ------------------------------------------------------- | ------------- |
| `sys`  | [`TestEffectSystem`](m4m.framework.TestEffectSystem.md) | `undefined`   |
| `data` | `EffectElementData`                                     | `null`        |

**Defined in**

[framework/particle/new/elementEmission.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L103)

### Accessors

#### renderCamera

• `get` **renderCamera**(): [`camera`](m4m.framework.camera.md)

**Returns**

[`camera`](m4m.framework.camera.md)

**Defined in**

[framework/particle/new/elementEmission.ts:272](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/elementEmission.ts#L272)
