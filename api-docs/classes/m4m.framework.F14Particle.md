# m4m.framework.F14Particle

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14Particle

## Class: F14Particle

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14Particle

### Table of contents

#### Properties

* [StartPos](m4m.framework.F14Particle.md#startpos)
* [Starteuler](m4m.framework.F14Particle.md#starteuler)
* [actived](m4m.framework.F14Particle.md#actived)
* [alpha](m4m.framework.F14Particle.md#alpha)
* [color](m4m.framework.F14Particle.md#color)
* [colorRate](m4m.framework.F14Particle.md#colorrate)
* [enableColorOverLifetime](m4m.framework.F14Particle.md#enablecoloroverlifetime)
* [enableRotOverLifeTime](m4m.framework.F14Particle.md#enablerotoverlifetime)
* [enableSizeOverLifetime](m4m.framework.F14Particle.md#enablesizeoverlifetime)
* [enableTexAnimation](m4m.framework.F14Particle.md#enabletexanimation)
* [enableVelocityOverLifetime](m4m.framework.F14Particle.md#enablevelocityoverlifetime)
* [eulerSpeed](m4m.framework.F14Particle.md#eulerspeed)
* [localMatrix](m4m.framework.F14Particle.md#localmatrix)
* [localRotation](m4m.framework.F14Particle.md#localrotation)
* [localScale](m4m.framework.F14Particle.md#localscale)
* [localTranslate](m4m.framework.F14Particle.md#localtranslate)
* [rotAngle](m4m.framework.F14Particle.md#rotangle)
* [rotationByEuler](m4m.framework.F14Particle.md#rotationbyeuler)
* [rotationByShape](m4m.framework.F14Particle.md#rotationbyshape)
* [startAlpha](m4m.framework.F14Particle.md#startalpha)
* [startColor](m4m.framework.F14Particle.md#startcolor)
* [startRotation](m4m.framework.F14Particle.md#startrotation)
* [tex\_ST](m4m.framework.F14Particle.md#tex\_st)
* [uvType](m4m.framework.F14Particle.md#uvtype)

#### Constructors

* [constructor](m4m.framework.F14Particle.md#constructor)

#### Methods

* [dispose](m4m.framework.F14Particle.md#dispose)
* [getCurTex\_ST](m4m.framework.F14Particle.md#getcurtex\_st)
* [initByEmissionData](m4m.framework.F14Particle.md#initbyemissiondata)
* [update](m4m.framework.F14Particle.md#update)
* [uploadMeshdata](m4m.framework.F14Particle.md#uploadmeshdata)

### Properties

#### StartPos

• **StartPos**: `vector3`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L13)

***

#### Starteuler

• **Starteuler**: `vector3`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L12)

***

#### actived

• **actived**: `boolean` = `false`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L58)

***

#### alpha

• **alpha**: `number` = `1`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L52)

***

#### color

• **color**: `vector3`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L51)

***

#### colorRate

• **colorRate**: `number`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L16)

***

#### enableColorOverLifetime

• **enableColorOverLifetime**: `boolean`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L32)

***

#### enableRotOverLifeTime

• **enableRotOverLifeTime**: `boolean`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L29)

***

#### enableSizeOverLifetime

• **enableSizeOverLifetime**: `boolean`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L26)

***

#### enableTexAnimation

• **enableTexAnimation**: `boolean`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L36)

***

#### enableVelocityOverLifetime

• **enableVelocityOverLifetime**: `boolean`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L23)

***

#### eulerSpeed

• **eulerSpeed**: `number`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L30)

***

#### localMatrix

• **localMatrix**: `matrix`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L46)

***

#### localRotation

• **localRotation**: `quaternion`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L49)

***

#### localScale

• **localScale**: `vector3`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L50)

***

#### localTranslate

• **localTranslate**: `vector3`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L48)

***

#### rotAngle

• **rotAngle**: `number` = `0`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L44)

***

#### rotationByEuler

• **rotationByEuler**: `quaternion`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L41)

***

#### rotationByShape

• **rotationByShape**: `quaternion`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L42)

***

#### startAlpha

• **startAlpha**: `number`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L15)

***

#### startColor

• **startColor**: `vector3`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L14)

***

#### startRotation

• **startRotation**: `quaternion`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L43)

***

#### tex\_ST

• **tex\_ST**: `vector4`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L38)

***

#### uvType

• **uvType**: [`UVTypeEnum`](../enums/m4m.framework.UVTypeEnum.md)

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L37)

### Constructors

#### constructor

• **new F14Particle**(`element`, `data`)

**Parameters**

| Name      | Type                                                          |
| --------- | ------------------------------------------------------------- |
| `element` | [`F14Emission`](m4m.framework.F14Emission.md)                 |
| `data`    | [`F14EmissionBaseData`](m4m.framework.F14EmissionBaseData.md) |

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L86)

### Methods

#### dispose

▸ **dispose**(): `void`

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:448](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L448)

***

#### getCurTex\_ST

▸ **getCurTex\_ST**(`data`): `void`

**Parameters**

| Name   | Type                                                          |
| ------ | ------------------------------------------------------------- |
| `data` | [`F14EmissionBaseData`](m4m.framework.F14EmissionBaseData.md) |

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:429](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L429)

***

#### initByEmissionData

▸ **initByEmissionData**(`data`): `void`

**Parameters**

| Name   | Type                                                          |
| ------ | ------------------------------------------------------------- |
| `data` | [`F14EmissionBaseData`](m4m.framework.F14EmissionBaseData.md) |

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:92](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L92)

***

#### update

▸ **update**(`deltaTime`): `void`

**Parameters**

| Name        | Type     |
| ----------- | -------- |
| `deltaTime` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:150](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L150)

***

#### uploadMeshdata

▸ **uploadMeshdata**(): `void`

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/particles/f14particle.ts:180](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14particle.ts#L180)
