[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14EmissionBatch

# Class: F14EmissionBatch

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14EmissionBatch

## Implements

- [`F14Basebatch`](../interfaces/m4m.framework.F14Basebatch.md)

## Table of contents

### Constructors

- [constructor](m4m.framework.F14EmissionBatch.md#constructor)

### Properties

- [curIndexCount](m4m.framework.F14EmissionBatch.md#curindexcount)
- [curRealVboCount](m4m.framework.F14EmissionBatch.md#currealvbocount)
- [curVertexcount](m4m.framework.F14EmissionBatch.md#curvertexcount)
- [dataForEbo](m4m.framework.F14EmissionBatch.md#dataforebo)
- [dataForVbo](m4m.framework.F14EmissionBatch.md#dataforvbo)
- [effect](m4m.framework.F14EmissionBatch.md#effect)
- [emission](m4m.framework.F14EmissionBatch.md#emission)
- [type](m4m.framework.F14EmissionBatch.md#type)
- [vertexLength](m4m.framework.F14EmissionBatch.md#vertexlength)

### Methods

- [dispose](m4m.framework.F14EmissionBatch.md#dispose)
- [getElementCount](m4m.framework.F14EmissionBatch.md#getelementcount)
- [render](m4m.framework.F14EmissionBatch.md#render)
- [unRender](m4m.framework.F14EmissionBatch.md#unrender)

## Constructors

### constructor

• **new F14EmissionBatch**(`effect`, `element`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `effect` | [`f14EffectSystem`](m4m.framework.f14EffectSystem.md) |
| `element` | [`F14Emission`](m4m.framework.F14Emission.md) |

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L26)

## Properties

### curIndexCount

• **curIndexCount**: `number` = `0`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L22)

___

### curRealVboCount

• **curRealVboCount**: `number` = `0`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L20)

___

### curVertexcount

• **curVertexcount**: `number` = `0`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L21)

___

### dataForEbo

• **dataForEbo**: `Uint16Array`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L16)

___

### dataForVbo

• **dataForVbo**: `Float32Array`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L15)

___

### effect

• **effect**: [`f14EffectSystem`](m4m.framework.f14EffectSystem.md)

#### Implementation of

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[effect](../interfaces/m4m.framework.F14Basebatch.md#effect)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L7)

___

### emission

• **emission**: [`F14Emission`](m4m.framework.F14Emission.md)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L10)

___

### type

• **type**: [`F14TypeEnum`](../enums/m4m.framework.F14TypeEnum.md)

#### Implementation of

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[type](../interfaces/m4m.framework.F14Basebatch.md#type)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L6)

___

### vertexLength

• **vertexLength**: `number` = `0`

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L24)

## Methods

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Implementation of

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[dispose](../interfaces/m4m.framework.F14Basebatch.md#dispose)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:147](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L147)

___

### getElementCount

▸ **getElementCount**(): `number`

#### Returns

`number`

#### Implementation of

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[getElementCount](../interfaces/m4m.framework.F14Basebatch.md#getelementcount)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:144](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L144)

___

### render

▸ **render**(`context`, `assetmgr`, `camera`, `Effqueue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | `renderContext` |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `camera` | [`camera`](m4m.framework.camera.md) |
| `Effqueue` | `number` |

#### Returns

`void`

#### Implementation of

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[render](../interfaces/m4m.framework.F14Basebatch.md#render)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L106)

___

### unRender

▸ **unRender**(): `void`

#### Returns

`void`

#### Implementation of

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[unRender](../interfaces/m4m.framework.F14Basebatch.md#unrender)

#### Defined in

[framework/component/f14effectsystem/particles/f14emissionbatch.ts:141](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/particles/f14emissionbatch.ts#L141)
