[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / NumberAttributeData

# Class: NumberAttributeData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).NumberAttributeData

## Implements

- [`IAttributeData`](../interfaces/m4m.framework.IAttributeData.md)
- [`ILerpAttributeInterface`](../interfaces/m4m.framework.ILerpAttributeInterface.md)

## Table of contents

### Properties

- [actions](m4m.framework.NumberAttributeData.md#actions)
- [attributeType](m4m.framework.NumberAttributeData.md#attributetype)
- [attributeValType](m4m.framework.NumberAttributeData.md#attributevaltype)
- [data](m4m.framework.NumberAttributeData.md#data)
- [frameIndexs](m4m.framework.NumberAttributeData.md#frameindexs)
- [timeLine](m4m.framework.NumberAttributeData.md#timeline)
- [uiState](m4m.framework.NumberAttributeData.md#uistate)

### Methods

- [addFramePoint](m4m.framework.NumberAttributeData.md#addframepoint)
- [init](m4m.framework.NumberAttributeData.md#init)
- [removeFramePoint](m4m.framework.NumberAttributeData.md#removeframepoint)
- [updateFramePoint](m4m.framework.NumberAttributeData.md#updateframepoint)

### Constructors

- [constructor](m4m.framework.NumberAttributeData.md#constructor)

## Properties

### actions

• **actions**: `Object`

#### Index signature

▪ [frameIndex: `number`]: `IEffectAction`[]

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[actions](../interfaces/m4m.framework.IAttributeData.md#actions)

#### Defined in

[framework/particle/new/attribute.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L149)

___

### attributeType

• **attributeType**: [`AttributeType`](../enums/m4m.framework.AttributeType.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[attributeType](../interfaces/m4m.framework.IAttributeData.md#attributetype)

#### Defined in

[framework/particle/new/attribute.ts:145](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L145)

___

### attributeValType

• **attributeValType**: [`AttributeValType`](../enums/m4m.framework.AttributeValType.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[attributeValType](../interfaces/m4m.framework.IAttributeData.md#attributevaltype)

#### Defined in

[framework/particle/new/attribute.ts:144](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L144)

___

### data

• **data**: `Object`

#### Index signature

▪ [frameIndex: `number`]: [`FrameKeyPointData`](m4m.framework.FrameKeyPointData.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[data](../interfaces/m4m.framework.IAttributeData.md#data)

#### Defined in

[framework/particle/new/attribute.ts:146](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L146)

___

### frameIndexs

• **frameIndexs**: `number`[]

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[frameIndexs](../interfaces/m4m.framework.IAttributeData.md#frameindexs)

#### Defined in

[framework/particle/new/attribute.ts:147](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L147)

___

### timeLine

• **timeLine**: `Object`

#### Index signature

▪ [frameIndex: `number`]: `number`

#### Defined in

[framework/particle/new/attribute.ts:148](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L148)

___

### uiState

• **uiState**: [`AttributeUIState`](../enums/m4m.framework.AttributeUIState.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[uiState](../interfaces/m4m.framework.IAttributeData.md#uistate)

#### Defined in

[framework/particle/new/attribute.ts:143](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L143)

## Methods

### addFramePoint

▸ **addFramePoint**(`data`, `func?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |
| `func?` | `Function` |

#### Returns

`void`

#### Implementation of

[ILerpAttributeInterface](../interfaces/m4m.framework.ILerpAttributeInterface.md).[addFramePoint](../interfaces/m4m.framework.ILerpAttributeInterface.md#addframepoint)

#### Defined in

[framework/particle/new/attribute.ts:161](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L161)

___

### init

▸ **init**(): `void`

#### Returns

`void`

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[init](../interfaces/m4m.framework.IAttributeData.md#init)

#### Defined in

[framework/particle/new/attribute.ts:154](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L154)

___

### removeFramePoint

▸ **removeFramePoint**(`frameId`, `data`, `func?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `frameId` | `number` |
| `data` | `number` |
| `func?` | `Function` |

#### Returns

`void`

#### Implementation of

[ILerpAttributeInterface](../interfaces/m4m.framework.ILerpAttributeInterface.md).[removeFramePoint](../interfaces/m4m.framework.ILerpAttributeInterface.md#removeframepoint)

#### Defined in

[framework/particle/new/attribute.ts:174](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L174)

___

### updateFramePoint

▸ **updateFramePoint**(`data`, `func?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |
| `func?` | `Function` |

#### Returns

`void`

#### Implementation of

[ILerpAttributeInterface](../interfaces/m4m.framework.ILerpAttributeInterface.md).[updateFramePoint](../interfaces/m4m.framework.ILerpAttributeInterface.md#updateframepoint)

#### Defined in

[framework/particle/new/attribute.ts:189](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L189)

## Constructors

### constructor

• **new NumberAttributeData**()

#### Defined in

[framework/particle/new/attribute.ts:150](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L150)
