[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14SingleMesh

# Class: F14SingleMesh

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14SingleMesh

## Implements

- [`F14Element`](../interfaces/m4m.framework.F14Element.md)

## Table of contents

### Methods

- [OnEndOnceLoop](m4m.framework.F14SingleMesh.md#onendonceloop)
- [changeAlpha](m4m.framework.F14SingleMesh.md#changealpha)
- [changeColor](m4m.framework.F14SingleMesh.md#changecolor)
- [dispose](m4m.framework.F14SingleMesh.md#dispose)
- [refreshCurTex\_ST](m4m.framework.F14SingleMesh.md#refreshcurtex_st)
- [refreshStartEndFrame](m4m.framework.F14SingleMesh.md#refreshstartendframe)
- [refreshTargetMatrix](m4m.framework.F14SingleMesh.md#refreshtargetmatrix)
- [reset](m4m.framework.F14SingleMesh.md#reset)
- [update](m4m.framework.F14SingleMesh.md#update)
- [updateRotByBillboard](m4m.framework.F14SingleMesh.md#updaterotbybillboard)
- [uploadMeshdata](m4m.framework.F14SingleMesh.md#uploadmeshdata)

### Properties

- [RenderBatch](m4m.framework.F14SingleMesh.md#renderbatch)
- [baseddata](m4m.framework.F14SingleMesh.md#baseddata)
- [color](m4m.framework.F14SingleMesh.md#color)
- [dataforebo](m4m.framework.F14SingleMesh.md#dataforebo)
- [dataforvbo](m4m.framework.F14SingleMesh.md#dataforvbo)
- [drawActive](m4m.framework.F14SingleMesh.md#drawactive)
- [endFrame](m4m.framework.F14SingleMesh.md#endframe)
- [euler](m4m.framework.F14SingleMesh.md#euler)
- [layer](m4m.framework.F14SingleMesh.md#layer)
- [position](m4m.framework.F14SingleMesh.md#position)
- [scale](m4m.framework.F14SingleMesh.md#scale)
- [settedAlpha](m4m.framework.F14SingleMesh.md#settedalpha)
- [startFrame](m4m.framework.F14SingleMesh.md#startframe)
- [targetMat](m4m.framework.F14SingleMesh.md#targetmat)
- [tex\_ST](m4m.framework.F14SingleMesh.md#tex_st)
- [type](m4m.framework.F14SingleMesh.md#type)

### Constructors

- [constructor](m4m.framework.F14SingleMesh.md#constructor)

## Methods

### OnEndOnceLoop

▸ **OnEndOnceLoop**(): `void`

#### Returns

`void`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[OnEndOnceLoop](../interfaces/m4m.framework.F14Element.md#onendonceloop)

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L121)

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

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:275](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L275)

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

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:270](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L270)

___

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[dispose](../interfaces/m4m.framework.F14Element.md#dispose)

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:280](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L280)

___

### refreshCurTex\_ST

▸ **refreshCurTex_ST**(`curframe`, `detalTime`, `fps`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `curframe` | `number` |
| `detalTime` | `number` |
| `fps` | `number` |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:177](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L177)

___

### refreshStartEndFrame

▸ **refreshStartEndFrame**(): `void`

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L56)

___

### refreshTargetMatrix

▸ **refreshTargetMatrix**(): `void`

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:127](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L127)

___

### reset

▸ **reset**(): `void`

#### Returns

`void`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[reset](../interfaces/m4m.framework.F14Element.md#reset)

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:257](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L257)

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

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L75)

___

### updateRotByBillboard

▸ **updateRotByBillboard**(): `void`

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:200](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L200)

___

### uploadMeshdata

▸ **uploadMeshdata**(): `void`

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:137](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L137)

## Properties

### RenderBatch

• **RenderBatch**: [`F14SingleMeshBath`](m4m.framework.F14SingleMeshBath.md)

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L10)

___

### baseddata

• **baseddata**: [`F14SingleMeshBaseData`](m4m.framework.F14SingleMeshBaseData.md)

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L17)

___

### color

• **color**: `color`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L15)

___

### dataforebo

• **dataforebo**: `Uint16Array`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L29)

___

### dataforvbo

• **dataforvbo**: `Float32Array`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L28)

___

### drawActive

• **drawActive**: `boolean`

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[drawActive](../interfaces/m4m.framework.F14Element.md#drawactive)

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L5)

___

### endFrame

• **endFrame**: `number`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L22)

___

### euler

• **euler**: `vector3`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L14)

___

### layer

• **layer**: [`F14Layer`](m4m.framework.F14Layer.md)

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[layer](../interfaces/m4m.framework.F14Element.md#layer)

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L7)

___

### position

• **position**: `vector3`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L12)

___

### scale

• **scale**: `vector3`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L13)

___

### settedAlpha

• **settedAlpha**: `number`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:274](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L274)

___

### startFrame

• **startFrame**: `number`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L21)

___

### targetMat

• **targetMat**: `matrix`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:126](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L126)

___

### tex\_ST

• **tex\_ST**: `vector4`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L16)

___

### type

• **type**: [`F14TypeEnum`](../enums/m4m.framework.F14TypeEnum.md)

#### Implementation of

[F14Element](../interfaces/m4m.framework.F14Element.md).[type](../interfaces/m4m.framework.F14Element.md#type)

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L6)

## Constructors

### constructor

• **new F14SingleMesh**(`effect`, `layer`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `effect` | [`f14EffectSystem`](m4m.framework.f14EffectSystem.md) |
| `layer` | [`F14Layer`](m4m.framework.F14Layer.md) |

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemesh.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemesh.ts#L31)
