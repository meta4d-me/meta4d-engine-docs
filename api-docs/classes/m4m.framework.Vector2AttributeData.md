[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / Vector2AttributeData

# Class: Vector2AttributeData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).Vector2AttributeData

## Implements

- [`IAttributeData`](../interfaces/m4m.framework.IAttributeData.md)
- [`ILerpAttributeInterface`](../interfaces/m4m.framework.ILerpAttributeInterface.md)

## Table of contents

### Properties

- [actions](m4m.framework.Vector2AttributeData.md#actions)
- [attributeType](m4m.framework.Vector2AttributeData.md#attributetype)
- [attributeValType](m4m.framework.Vector2AttributeData.md#attributevaltype)
- [data](m4m.framework.Vector2AttributeData.md#data)
- [frameIndexs](m4m.framework.Vector2AttributeData.md#frameindexs)
- [uiState](m4m.framework.Vector2AttributeData.md#uistate)

### Methods

- [addFramePoint](m4m.framework.Vector2AttributeData.md#addframepoint)
- [init](m4m.framework.Vector2AttributeData.md#init)
- [removeFramePoint](m4m.framework.Vector2AttributeData.md#removeframepoint)
- [updateFramePoint](m4m.framework.Vector2AttributeData.md#updateframepoint)

### Constructors

- [constructor](m4m.framework.Vector2AttributeData.md#constructor)

## Properties

### actions

• **actions**: `Object`

#### Index signature

▪ [frameIndex: `number`]: `IEffectAction`[]

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[actions](../interfaces/m4m.framework.IAttributeData.md#actions)

#### Defined in

[framework/particle/new/attribute.ts:85](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L85)

___

### attributeType

• **attributeType**: [`AttributeType`](../enums/m4m.framework.AttributeType.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[attributeType](../interfaces/m4m.framework.IAttributeData.md#attributetype)

#### Defined in

[framework/particle/new/attribute.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L82)

___

### attributeValType

• **attributeValType**: [`AttributeValType`](../enums/m4m.framework.AttributeValType.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[attributeValType](../interfaces/m4m.framework.IAttributeData.md#attributevaltype)

#### Defined in

[framework/particle/new/attribute.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L81)

___

### data

• **data**: `Object`

#### Index signature

▪ [frameIndex: `number`]: [`FrameKeyPointData`](m4m.framework.FrameKeyPointData.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[data](../interfaces/m4m.framework.IAttributeData.md#data)

#### Defined in

[framework/particle/new/attribute.ts:84](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L84)

___

### frameIndexs

• **frameIndexs**: `number`[]

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[frameIndexs](../interfaces/m4m.framework.IAttributeData.md#frameindexs)

#### Defined in

[framework/particle/new/attribute.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L83)

___

### uiState

• **uiState**: [`AttributeUIState`](../enums/m4m.framework.AttributeUIState.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[uiState](../interfaces/m4m.framework.IAttributeData.md#uistate)

#### Defined in

[framework/particle/new/attribute.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L80)

## Methods

### addFramePoint

▸ **addFramePoint**(`data`, `func?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`FrameKeyPointData`](m4m.framework.FrameKeyPointData.md) |
| `func?` | `Function` |

#### Returns

`void`

#### Implementation of

[ILerpAttributeInterface](../interfaces/m4m.framework.ILerpAttributeInterface.md).[addFramePoint](../interfaces/m4m.framework.ILerpAttributeInterface.md#addframepoint)

#### Defined in

[framework/particle/new/attribute.ts:97](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L97)

___

### init

▸ **init**(): `void`

#### Returns

`void`

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[init](../interfaces/m4m.framework.IAttributeData.md#init)

#### Defined in

[framework/particle/new/attribute.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L90)

___

### removeFramePoint

▸ **removeFramePoint**(`frameId`, `data`, `func?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `frameId` | `number` |
| `data` | `vector2` |
| `func?` | `Function` |

#### Returns

`void`

#### Implementation of

[ILerpAttributeInterface](../interfaces/m4m.framework.ILerpAttributeInterface.md).[removeFramePoint](../interfaces/m4m.framework.ILerpAttributeInterface.md#removeframepoint)

#### Defined in

[framework/particle/new/attribute.ts:110](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L110)

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

[framework/particle/new/attribute.ts:125](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L125)

## Constructors

### constructor

• **new Vector2AttributeData**()

#### Defined in

[framework/particle/new/attribute.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L86)
