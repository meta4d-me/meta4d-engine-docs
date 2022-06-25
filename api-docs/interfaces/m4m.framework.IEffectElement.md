[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IEffectElement

# Interface: IEffectElement

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IEffectElement

## Implemented by

- [`EffectElementEmission`](../classes/m4m.framework.EffectElementEmission.md)
- [`EffectElementSingleMesh`](../classes/m4m.framework.EffectElementSingleMesh.md)

## Table of contents

### Properties

- [beloop](m4m.framework.IEffectElement.md#beloop)
- [delayTime](m4m.framework.IEffectElement.md#delaytime)
- [elementType](m4m.framework.IEffectElement.md#elementtype)
- [mat](m4m.framework.IEffectElement.md#mat)
- [mesh](m4m.framework.IEffectElement.md#mesh)
- [name](m4m.framework.IEffectElement.md#name)

### Methods

- [dispose](m4m.framework.IEffectElement.md#dispose)
- [writeToJson](m4m.framework.IEffectElement.md#writetojson)

## Properties

### beloop

• **beloop**: `boolean`

#### Defined in

[framework/particle/new/element.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L8)

___

### delayTime

• **delayTime**: `number`

#### Defined in

[framework/particle/new/element.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L9)

___

### elementType

• **elementType**: `EffectElementTypeEnum`

#### Defined in

[framework/particle/new/element.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L7)

___

### mat

• **mat**: [`material`](../classes/m4m.framework.material.md)

#### Defined in

[framework/particle/new/element.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L10)

___

### mesh

• **mesh**: [`mesh`](../classes/m4m.framework.mesh.md)

#### Defined in

[framework/particle/new/element.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L11)

___

### name

• **name**: `string`

#### Defined in

[framework/particle/new/element.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L6)

## Methods

### dispose

▸ **dispose**(): `any`

#### Returns

`any`

#### Defined in

[framework/particle/new/element.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L13)

___

### writeToJson

▸ **writeToJson**(`obj`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`any`

#### Defined in

[framework/particle/new/element.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/element.ts#L12)
