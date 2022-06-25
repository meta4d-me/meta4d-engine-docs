[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14Basebatch

# Interface: F14Basebatch

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14Basebatch

## Implemented by

- [`F14EmissionBatch`](../classes/m4m.framework.F14EmissionBatch.md)
- [`F14RefElementBatch`](../classes/m4m.framework.F14RefElementBatch.md)
- [`F14SingleMeshBath`](../classes/m4m.framework.F14SingleMeshBath.md)

## Table of contents

### Methods

- [dispose](m4m.framework.F14Basebatch.md#dispose)
- [getElementCount](m4m.framework.F14Basebatch.md#getelementcount)
- [render](m4m.framework.F14Basebatch.md#render)
- [unRender](m4m.framework.F14Basebatch.md#unrender)

### Properties

- [effect](m4m.framework.F14Basebatch.md#effect)
- [type](m4m.framework.F14Basebatch.md#type)

## Methods

### dispose

▸ **dispose**(): `any`

#### Returns

`any`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L11)

___

### getElementCount

▸ **getElementCount**(): `number`

#### Returns

`number`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L12)

___

### render

▸ **render**(`context`, `assetmgr`, `camera`, `Effqueue`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | `renderContext` |
| `assetmgr` | [`assetMgr`](../classes/m4m.framework.assetMgr.md) |
| `camera` | [`camera`](../classes/m4m.framework.camera.md) |
| `Effqueue` | `number` |

#### Returns

`any`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L8)

___

### unRender

▸ **unRender**(): `any`

#### Returns

`any`

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L9)

## Properties

### effect

• **effect**: [`f14EffectSystem`](../classes/m4m.framework.f14EffectSystem.md)

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L6)

___

### type

• **type**: [`F14TypeEnum`](../enums/m4m.framework.F14TypeEnum.md)

#### Defined in

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L5)
