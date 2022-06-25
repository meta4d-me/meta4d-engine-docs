[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IAttributeData

# Interface: IAttributeData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IAttributeData

## Implemented by

- [`NumberAttributeData`](../classes/m4m.framework.NumberAttributeData.md)
- [`Vector2AttributeData`](../classes/m4m.framework.Vector2AttributeData.md)
- [`Vector3AttributeData`](../classes/m4m.framework.Vector3AttributeData.md)

## Table of contents

### Properties

- [actions](m4m.framework.IAttributeData.md#actions)
- [attributeType](m4m.framework.IAttributeData.md#attributetype)
- [attributeValType](m4m.framework.IAttributeData.md#attributevaltype)
- [data](m4m.framework.IAttributeData.md#data)
- [frameIndexs](m4m.framework.IAttributeData.md#frameindexs)
- [uiState](m4m.framework.IAttributeData.md#uistate)

### Methods

- [init](m4m.framework.IAttributeData.md#init)

## Properties

### actions

• **actions**: `Object`

#### Index signature

▪ [frameIndex: `number`]: `IEffectAction`[]

#### Defined in

[framework/particle/new/attribute.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L10)

___

### attributeType

• **attributeType**: [`AttributeType`](../enums/m4m.framework.AttributeType.md)

#### Defined in

[framework/particle/new/attribute.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L9)

___

### attributeValType

• **attributeValType**: [`AttributeValType`](../enums/m4m.framework.AttributeValType.md)

#### Defined in

[framework/particle/new/attribute.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L8)

___

### data

• **data**: `Object`

#### Index signature

▪ [frameIndex: `number`]: [`FrameKeyPointData`](../classes/m4m.framework.FrameKeyPointData.md)

#### Defined in

[framework/particle/new/attribute.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L6)

___

### frameIndexs

• **frameIndexs**: `number`[]

#### Defined in

[framework/particle/new/attribute.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L7)

___

### uiState

• **uiState**: [`AttributeUIState`](../enums/m4m.framework.AttributeUIState.md)

#### Defined in

[framework/particle/new/attribute.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L5)

## Methods

### init

▸ **init**(): `any`

#### Returns

`any`

#### Defined in

[framework/particle/new/attribute.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L11)
