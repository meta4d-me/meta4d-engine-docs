[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14Emission

# Class: F14Emission

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14Emission

## Implements

- [`F14Element`](../interfaces/m4m.framework.F14Element.md)

## Table of contents

### Methods

- [OnEndOnceLoop](m4m.framework.F14Emission.md#onendonceloop)
- [changeAlpha](m4m.framework.F14Emission.md#changealpha)
- [changeColor](m4m.framework.F14Emission.md#changecolor)
- [changeCurrentBaseData](m4m.framework.F14Emission.md#changecurrentbasedata)
- [dispose](m4m.framework.F14Emission.md#dispose)
- [getWorldMatrix](m4m.framework.F14Emission.md#getworldmatrix)
- [getWorldRotation](m4m.framework.F14Emission.md#getworldrotation)
- [reset](m4m.framework.F14Emission.md#reset)
- [update](m4m.framework.F14Emission.md#update)

### Properties

- [baseddata](m4m.framework.F14Emission.md#baseddata)
- [colorArr](m4m.framework.F14Emission.md#colorarr)
- [curTime](m4m.framework.F14Emission.md#curtime)
- [currentData](m4m.framework.F14Emission.md#currentdata)
- [dataforebo](m4m.framework.F14Emission.md#dataforebo)
- [dataforvboLen](m4m.framework.F14Emission.md#dataforvbolen)
- [deadParticles](m4m.framework.F14Emission.md#deadparticles)
- [drawActive](m4m.framework.F14Emission.md#drawactive)
- [effect](m4m.framework.F14Emission.md#effect)
- [layer](m4m.framework.F14Emission.md#layer)
- [localMatrix](m4m.framework.F14Emission.md#localmatrix)
- [particlelist](m4m.framework.F14Emission.md#particlelist)
- [posArr](m4m.framework.F14Emission.md#posarr)
- [type](m4m.framework.F14Emission.md#type)
- [uvArr](m4m.framework.F14Emission.md#uvarr)
- [vertexCount](m4m.framework.F14Emission.md#vertexcount)
- [vertexLength](m4m.framework.F14Emission.md#vertexlength)

### Constructors

- [constructor](m4m.framework.F14Emission.md#constructor)

## Methods

### OnEndOnceLoop

▸ **OnEndOnceLoop**(): `void`

#### Returns

`void`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[OnEndOnceLoop](../interfaces/m4m.framework.F14Element.md#onendonceloop)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:237](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L237)

___

### changeAlpha

▸ **changeAlpha**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[changeAlpha](../interfaces/m4m.framework.F14Element.md#changealpha)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:232](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L232)

___

### changeColor

▸ **changeColor**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `color` |

#### Returns

`void`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[changeColor](../interfaces/m4m.framework.F14Element.md#changecolor)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:226](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L226)

___

### changeCurrentBaseData

▸ **changeCurrentBaseData**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`F14EmissionBaseData`](m4m.framework.F14EmissionBaseData.md) |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L100)

___

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[dispose](../interfaces/m4m.framework.F14Element.md#dispose)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:241](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L241)

___

### getWorldMatrix

▸ **getWorldMatrix**(): `matrix`

#### Returns

`matrix`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L112)

___

### getWorldRotation

▸ **getWorldRotation**(): `quaternion`

#### Returns

`quaternion`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:117](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L117)

___

### reset

▸ **reset**(): `void`

#### Returns

`void`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[reset](../interfaces/m4m.framework.F14Element.md#reset)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:215](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L215)

___

### update

▸ **update**(`deltaTime`, `frame`, `fps`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `deltaTime` | `number` |
| `frame` | `number` |
| `fps` | `number` |

#### Returns

`void`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[update](../interfaces/m4m.framework.F14Element.md#update)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:69](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L69)

## Properties

### baseddata

• **baseddata**: [`F14EmissionBaseData`](m4m.framework.F14EmissionBaseData.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L8)

___

### colorArr

• **colorArr**: `color`[]

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L36)

___

### curTime

• **curTime**: `number` = `0`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L20)

___

### currentData

• **currentData**: [`F14EmissionBaseData`](m4m.framework.F14EmissionBaseData.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L9)

___

### dataforebo

• **dataforebo**: `Uint16Array`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L34)

___

### dataforvboLen

• **dataforvboLen**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L33)

___

### deadParticles

• **deadParticles**: [`F14Particle`](m4m.framework.F14Particle.md)[] = `[]`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L12)

___

### drawActive

• **drawActive**: `boolean`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[drawActive](../interfaces/m4m.framework.F14Element.md#drawactive)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L5)

___

### effect

• **effect**: [`f14EffectSystem`](m4m.framework.f14EffectSystem.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L6)

___

### layer

• **layer**: [`F14Layer`](m4m.framework.F14Layer.md)

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[layer](../interfaces/m4m.framework.F14Element.md#layer)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:4](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L4)

___

### localMatrix

• **localMatrix**: `matrix`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L26)

___

### particlelist

• **particlelist**: [`F14Particle`](m4m.framework.F14Particle.md)[] = `[]`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L11)

___

### posArr

• **posArr**: `vector3`[]

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L35)

___

### type

• **type**: [`F14TypeEnum`](../enums/m4m.framework.F14TypeEnum.md)

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[type](../interfaces/m4m.framework.F14Element.md#type)

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:3](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L3)

___

### uvArr

• **uvArr**: `vector2`[]

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L37)

___

### vertexCount

• **vertexCount**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L31)

___

### vertexLength

• **vertexLength**: `number`

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L32)

## Constructors

### constructor

• **new F14Emission**(`effect`, `layer`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `effect` | [`f14EffectSystem`](m4m.framework.f14EffectSystem.md) |
| `layer` | [`F14Layer`](m4m.framework.F14Layer.md) |

#### Defined in

[framework/component/f14effectsystem/particles/f14emission.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emission.ts#L41)
