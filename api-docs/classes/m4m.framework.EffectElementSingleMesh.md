[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / EffectElementSingleMesh

# Class: EffectElementSingleMesh

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).EffectElementSingleMesh

## Implements

- [`IEffectElement`](../interfaces/m4m.framework.IEffectElement.md)

## Table of contents

### Properties

- [actions](m4m.framework.EffectElementSingleMesh.md#actions)
- [active](m4m.framework.EffectElementSingleMesh.md#active)
- [alpha](m4m.framework.EffectElementSingleMesh.md#alpha)
- [beloop](m4m.framework.EffectElementSingleMesh.md#beloop)
- [color](m4m.framework.EffectElementSingleMesh.md#color)
- [colorRate](m4m.framework.EffectElementSingleMesh.md#colorrate)
- [curAttrData](m4m.framework.EffectElementSingleMesh.md#curattrdata)
- [delayTime](m4m.framework.EffectElementSingleMesh.md#delaytime)
- [elementType](m4m.framework.EffectElementSingleMesh.md#elementtype)
- [euler](m4m.framework.EffectElementSingleMesh.md#euler)
- [life](m4m.framework.EffectElementSingleMesh.md#life)
- [localRotation](m4m.framework.EffectElementSingleMesh.md#localrotation)
- [loopFrame](m4m.framework.EffectElementSingleMesh.md#loopframe)
- [mat](m4m.framework.EffectElementSingleMesh.md#mat)
- [mesh](m4m.framework.EffectElementSingleMesh.md#mesh)
- [name](m4m.framework.EffectElementSingleMesh.md#name)
- [position](m4m.framework.EffectElementSingleMesh.md#position)
- [renderModel](m4m.framework.EffectElementSingleMesh.md#rendermodel)
- [rotationByEuler](m4m.framework.EffectElementSingleMesh.md#rotationbyeuler)
- [scale](m4m.framework.EffectElementSingleMesh.md#scale)
- [tex\_ST](m4m.framework.EffectElementSingleMesh.md#tex_st)
- [transform](m4m.framework.EffectElementSingleMesh.md#transform)

### Constructors

- [constructor](m4m.framework.EffectElementSingleMesh.md#constructor)

### Methods

- [dispose](m4m.framework.EffectElementSingleMesh.md#dispose)
- [update](m4m.framework.EffectElementSingleMesh.md#update)
- [writeToJson](m4m.framework.EffectElementSingleMesh.md#writetojson)

## Properties

### actions

• **actions**: `IEffectAction`[]

#### Defined in

[framework/particle/new/element.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L47)

___

### active

• **active**: `boolean` = `true`

#### Defined in

[framework/particle/new/element.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L53)

___

### alpha

• **alpha**: [`NumberKey`](m4m.framework.NumberKey.md)[] = `[]`

#### Defined in

[framework/particle/new/element.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L45)

___

### beloop

• **beloop**: `boolean` = `false`

#### Implementation of

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[beloop](../interfaces/m4m.framework.IEffectElement.md#beloop)

#### Defined in

[framework/particle/new/element.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L31)

___

### color

• **color**: [`Vector3Key`](m4m.framework.Vector3Key.md)[] = `[]`

#### Defined in

[framework/particle/new/element.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L44)

___

### colorRate

• **colorRate**: `number` = `1`

#### Defined in

[framework/particle/new/element.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L37)

___

### curAttrData

• **curAttrData**: `EffectAttrsData`

#### Defined in

[framework/particle/new/element.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L49)

___

### delayTime

• **delayTime**: `number` = `0`

#### Implementation of

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[delayTime](../interfaces/m4m.framework.IEffectElement.md#delaytime)

#### Defined in

[framework/particle/new/element.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L32)

___

### elementType

• **elementType**: `EffectElementTypeEnum` = `m4m.framework.EffectElementTypeEnum.SingleMeshType`

#### Implementation of

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[elementType](../interfaces/m4m.framework.IEffectElement.md#elementtype)

#### Defined in

[framework/particle/new/element.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L30)

___

### euler

• **euler**: [`Vector3Key`](m4m.framework.Vector3Key.md)[] = `[]`

#### Defined in

[framework/particle/new/element.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L42)

___

### life

• **life**: `number` = `5`

#### Defined in

[framework/particle/new/element.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L33)

___

### localRotation

• **localRotation**: `quaternion`

#### Defined in

[framework/particle/new/element.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L59)

___

### loopFrame

• **loopFrame**: `number` = `Number.MAX_VALUE`

#### Defined in

[framework/particle/new/element.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L52)

___

### mat

• **mat**: [`material`](m4m.framework.material.md)

#### Implementation of

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[mat](../interfaces/m4m.framework.IEffectElement.md#mat)

#### Defined in

[framework/particle/new/element.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L34)

___

### mesh

• **mesh**: [`mesh`](m4m.framework.mesh.md)

#### Implementation of

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[mesh](../interfaces/m4m.framework.IEffectElement.md#mesh)

#### Defined in

[framework/particle/new/element.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L35)

___

### name

• **name**: `string`

#### Implementation of

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[name](../interfaces/m4m.framework.IEffectElement.md#name)

#### Defined in

[framework/particle/new/element.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L29)

___

### position

• **position**: [`Vector3Key`](m4m.framework.Vector3Key.md)[] = `[]`

#### Defined in

[framework/particle/new/element.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L41)

___

### renderModel

• **renderModel**: `RenderModel` = `m4m.framework.RenderModel.Mesh`

#### Defined in

[framework/particle/new/element.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L38)

___

### rotationByEuler

• **rotationByEuler**: `quaternion`

#### Defined in

[framework/particle/new/element.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L58)

___

### scale

• **scale**: [`Vector3Key`](m4m.framework.Vector3Key.md)[] = `[]`

#### Defined in

[framework/particle/new/element.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L43)

___

### tex\_ST

• **tex\_ST**: `vector4`

#### Defined in

[framework/particle/new/element.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L39)

___

### transform

• **transform**: [`transform`](m4m.framework.transform.md)

#### Defined in

[framework/particle/new/element.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L54)

## Constructors

### constructor

• **new EffectElementSingleMesh**(`sys`, `data?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `sys` | [`TestEffectSystem`](m4m.framework.TestEffectSystem.md) | `undefined` |
| `data` | `EffectElementData` | `null` |

#### Defined in

[framework/particle/new/element.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L61)

## Methods

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Implementation of

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[dispose](../interfaces/m4m.framework.IEffectElement.md#dispose)

#### Defined in

[framework/particle/new/element.ts:192](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L192)

___

### update

▸ **update**(): `void`

#### Returns

`void`

#### Defined in

[framework/particle/new/element.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L89)

___

### writeToJson

▸ **writeToJson**(`obj`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`any`

#### Implementation of

[IEffectElement](../interfaces/m4m.framework.IEffectElement.md).[writeToJson](../interfaces/m4m.framework.IEffectElement.md#writetojson)

#### Defined in

[framework/particle/new/element.ts:84](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L84)
