[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14EmissionBaseData

# Class: F14EmissionBaseData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14EmissionBaseData

## Implements

- [`F14ElementData`](../interfaces/m4m.framework.F14ElementData.md)

## Table of contents

### Properties

- [alphaNodes](m4m.framework.F14EmissionBaseData.md#alphanodes)
- [angle](m4m.framework.F14EmissionBaseData.md#angle)
- [angleSpeed](m4m.framework.F14EmissionBaseData.md#anglespeed)
- [beloop](m4m.framework.F14EmissionBaseData.md#beloop)
- [bursts](m4m.framework.F14EmissionBaseData.md#bursts)
- [colorNodes](m4m.framework.F14EmissionBaseData.md#colornodes)
- [colorRate](m4m.framework.F14EmissionBaseData.md#colorrate)
- [column](m4m.framework.F14EmissionBaseData.md#column)
- [count](m4m.framework.F14EmissionBaseData.md#count)
- [delayTime](m4m.framework.F14EmissionBaseData.md#delaytime)
- [depth](m4m.framework.F14EmissionBaseData.md#depth)
- [duration](m4m.framework.F14EmissionBaseData.md#duration)
- [emitFrom](m4m.framework.F14EmissionBaseData.md#emitfrom)
- [enableColorOverLifetime](m4m.framework.F14EmissionBaseData.md#enablecoloroverlifetime)
- [enableRotOverLifeTime](m4m.framework.F14EmissionBaseData.md#enablerotoverlifetime)
- [enableSizeOverLifetime](m4m.framework.F14EmissionBaseData.md#enablesizeoverlifetime)
- [enableTexAnimation](m4m.framework.F14EmissionBaseData.md#enabletexanimation)
- [enableVelocityOverLifetime](m4m.framework.F14EmissionBaseData.md#enablevelocityoverlifetime)
- [height](m4m.framework.F14EmissionBaseData.md#height)
- [lifeTime](m4m.framework.F14EmissionBaseData.md#lifetime)
- [loopenum](m4m.framework.F14EmissionBaseData.md#loopenum)
- [material](m4m.framework.F14EmissionBaseData.md#material)
- [mesh](m4m.framework.F14EmissionBaseData.md#mesh)
- [moveSpeed](m4m.framework.F14EmissionBaseData.md#movespeed)
- [radius](m4m.framework.F14EmissionBaseData.md#radius)
- [rateOverTime](m4m.framework.F14EmissionBaseData.md#rateovertime)
- [rendermodel](m4m.framework.F14EmissionBaseData.md#rendermodel)
- [rotEuler](m4m.framework.F14EmissionBaseData.md#roteuler)
- [rotPosition](m4m.framework.F14EmissionBaseData.md#rotposition)
- [rotScale](m4m.framework.F14EmissionBaseData.md#rotscale)
- [row](m4m.framework.F14EmissionBaseData.md#row)
- [shapeType](m4m.framework.F14EmissionBaseData.md#shapetype)
- [simulateInLocalSpace](m4m.framework.F14EmissionBaseData.md#simulateinlocalspace)
- [simulationSpeed](m4m.framework.F14EmissionBaseData.md#simulationspeed)
- [sizeNodes](m4m.framework.F14EmissionBaseData.md#sizenodes)
- [startAlpha](m4m.framework.F14EmissionBaseData.md#startalpha)
- [startColor](m4m.framework.F14EmissionBaseData.md#startcolor)
- [startEuler](m4m.framework.F14EmissionBaseData.md#starteuler)
- [startScale](m4m.framework.F14EmissionBaseData.md#startscale)
- [startScaleRate](m4m.framework.F14EmissionBaseData.md#startscalerate)
- [start\_tex\_st](m4m.framework.F14EmissionBaseData.md#start_tex_st)
- [uSpeed](m4m.framework.F14EmissionBaseData.md#uspeed)
- [uvType](m4m.framework.F14EmissionBaseData.md#uvtype)
- [vSpeed](m4m.framework.F14EmissionBaseData.md#vspeed)
- [width](m4m.framework.F14EmissionBaseData.md#width)

### Constructors

- [constructor](m4m.framework.F14EmissionBaseData.md#constructor)

### Methods

- [parse](m4m.framework.F14EmissionBaseData.md#parse)
- [getRandomDirAndPosByZEmission](m4m.framework.F14EmissionBaseData.md#getrandomdirandposbyzemission)

## Properties

### alphaNodes

• **alphaNodes**: [`NumberKey`](m4m.framework.NumberKey.md)[] = `[]`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:84](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L84)

___

### angle

• **angle**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L64)

___

### angleSpeed

• **angleSpeed**: [`NumberData`](m4m.framework.NumberData.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L79)

___

### beloop

• **beloop**: `boolean` = `true`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L31)

___

### bursts

• **bursts**: [`busrtInfo`](m4m.framework.busrtInfo.md)[] = `[]`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L51)

___

### colorNodes

• **colorNodes**: [`Vector3Key`](m4m.framework.Vector3Key.md)[] = `[]`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L83)

___

### colorRate

• **colorRate**: `number` = `1`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L40)

___

### column

• **column**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:94](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L94)

___

### count

• **count**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:95](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L95)

___

### delayTime

• **delayTime**: `number` = `0`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L45)

___

### depth

• **depth**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L59)

___

### duration

• **duration**: `number` = `10`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L46)

___

### emitFrom

• **emitFrom**: `emitfromenum` = `emitfromenum.base`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L65)

___

### enableColorOverLifetime

• **enableColorOverLifetime**: `boolean` = `false`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L82)

___

### enableRotOverLifeTime

• **enableRotOverLifeTime**: `boolean` = `false`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L78)

___

### enableSizeOverLifetime

• **enableSizeOverLifetime**: `boolean` = `false`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L74)

___

### enableTexAnimation

• **enableTexAnimation**: `boolean` = `false`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:87](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L87)

___

### enableVelocityOverLifetime

• **enableVelocityOverLifetime**: `boolean` = `false`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:70](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L70)

___

### height

• **height**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L58)

___

### lifeTime

• **lifeTime**: [`NumberData`](m4m.framework.NumberData.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L32)

___

### loopenum

• **loopenum**: [`LoopEnum`](../enums/m4m.framework.LoopEnum.md) = `LoopEnum.Restart`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L17)

___

### material

• **material**: [`material`](m4m.framework.material.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L21)

___

### mesh

• **mesh**: [`mesh`](m4m.framework.mesh.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L20)

___

### moveSpeed

• **moveSpeed**: [`Vector3Data`](m4m.framework.Vector3Data.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L71)

___

### radius

• **radius**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L61)

___

### rateOverTime

• **rateOverTime**: [`NumberData`](m4m.framework.NumberData.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L49)

___

### rendermodel

• **rendermodel**: [`RenderModelEnum`](../enums/m4m.framework.RenderModelEnum.md) = `RenderModelEnum.Mesh`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L28)

___

### rotEuler

• **rotEuler**: `vector3`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L25)

___

### rotPosition

• **rotPosition**: `vector3`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L23)

___

### rotScale

• **rotScale**: `vector3`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L24)

___

### row

• **row**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L93)

___

### shapeType

• **shapeType**: `ParticleSystemShape` = `ParticleSystemShape.NORMAL`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:55](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L55)

___

### simulateInLocalSpace

• **simulateInLocalSpace**: `boolean` = `true`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L33)

___

### simulationSpeed

• **simulationSpeed**: [`NumberData`](m4m.framework.NumberData.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L41)

___

### sizeNodes

• **sizeNodes**: [`NumberKey`](m4m.framework.NumberKey.md)[] = `[]`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L75)

___

### startAlpha

• **startAlpha**: [`NumberData`](m4m.framework.NumberData.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L39)

___

### startColor

• **startColor**: [`Vector3Data`](m4m.framework.Vector3Data.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L38)

___

### startEuler

• **startEuler**: [`Vector3Data`](m4m.framework.Vector3Data.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L36)

___

### startScale

• **startScale**: [`Vector3Data`](m4m.framework.Vector3Data.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L35)

___

### startScaleRate

• **startScaleRate**: [`NumberData`](m4m.framework.NumberData.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L34)

___

### start\_tex\_st

• **start\_tex\_st**: `vector4`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L43)

___

### uSpeed

• **uSpeed**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L90)

___

### uvType

• **uvType**: [`UVTypeEnum`](../enums/m4m.framework.UVTypeEnum.md) = `UVTypeEnum.NONE`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L88)

___

### vSpeed

• **vSpeed**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:91](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L91)

___

### width

• **width**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L57)

## Constructors

### constructor

• **new F14EmissionBaseData**()

## Methods

### parse

▸ **parse**(`json`, `assetmgr`, `assetbundle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `json` | `any` |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `assetbundle` | `string` |

#### Returns

`void`

#### Implementation of

[F14ElementData](../interfaces/m4m.framework.F14ElementData.md).[parse](../interfaces/m4m.framework.F14ElementData.md#parse)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L98)

___

### getRandomDirAndPosByZEmission

▸ `Static` **getRandomDirAndPosByZEmission**(`emission`, `outDir`, `outPos`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `emission` | [`F14EmissionBaseData`](m4m.framework.F14EmissionBaseData.md) |
| `outDir` | `vector3` |
| `outPos` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbasedata.ts:259](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbasedata.ts#L259)
