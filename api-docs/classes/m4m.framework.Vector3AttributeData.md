[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / Vector3AttributeData

# Class: Vector3AttributeData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).Vector3AttributeData

## Implements

- [`IAttributeData`](../interfaces/m4m.framework.IAttributeData.md)
- [`ILerpAttributeInterface`](../interfaces/m4m.framework.ILerpAttributeInterface.md)

## Table of contents

### Properties

- [actions](m4m.framework.Vector3AttributeData.md#actions)
- [attributeType](m4m.framework.Vector3AttributeData.md#attributetype)
- [attributeValType](m4m.framework.Vector3AttributeData.md#attributevaltype)
- [data](m4m.framework.Vector3AttributeData.md#data)
- [frameIndexs](m4m.framework.Vector3AttributeData.md#frameindexs)
- [uiState](m4m.framework.Vector3AttributeData.md#uistate)

### Methods

- [addFramePoint](m4m.framework.Vector3AttributeData.md#addframepoint)
- [init](m4m.framework.Vector3AttributeData.md#init)
- [removeFramePoint](m4m.framework.Vector3AttributeData.md#removeframepoint)
- [updateFramePoint](m4m.framework.Vector3AttributeData.md#updateframepoint)

### Constructors

- [constructor](m4m.framework.Vector3AttributeData.md#constructor)

## Properties

### actions

• **actions**: `Object`

#### Index signature

▪ [frameIndex: `number`]: `IEffectAction`[]

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[actions](../interfaces/m4m.framework.IAttributeData.md#actions)

#### Defined in

[framework/particle/new/attribute.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L21)

___

### attributeType

• **attributeType**: [`AttributeType`](../enums/m4m.framework.AttributeType.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[attributeType](../interfaces/m4m.framework.IAttributeData.md#attributetype)

#### Defined in

[framework/particle/new/attribute.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L18)

___

### attributeValType

• **attributeValType**: [`AttributeValType`](../enums/m4m.framework.AttributeValType.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[attributeValType](../interfaces/m4m.framework.IAttributeData.md#attributevaltype)

#### Defined in

[framework/particle/new/attribute.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L17)

___

### data

• **data**: `Object`

#### Index signature

▪ [frameIndex: `number`]: [`FrameKeyPointData`](m4m.framework.FrameKeyPointData.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[data](../interfaces/m4m.framework.IAttributeData.md#data)

#### Defined in

[framework/particle/new/attribute.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L19)

___

### frameIndexs

• **frameIndexs**: `number`[]

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[frameIndexs](../interfaces/m4m.framework.IAttributeData.md#frameindexs)

#### Defined in

[framework/particle/new/attribute.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L20)

___

### uiState

• **uiState**: [`AttributeUIState`](../enums/m4m.framework.AttributeUIState.md)

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[uiState](../interfaces/m4m.framework.IAttributeData.md#uistate)

#### Defined in

[framework/particle/new/attribute.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L16)

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

[framework/particle/new/attribute.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L33)

___

### init

▸ **init**(): `void`

#### Returns

`void`

#### Implementation of

[IAttributeData](../interfaces/m4m.framework.IAttributeData.md).[init](../interfaces/m4m.framework.IAttributeData.md#init)

#### Defined in

[framework/particle/new/attribute.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L26)

___

### removeFramePoint

▸ **removeFramePoint**(`frameId`, `data`, `func?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `frameId` | `number` |
| `data` | `any` |
| `func?` | `Function` |

#### Returns

`void`

#### Implementation of

[ILerpAttributeInterface](../interfaces/m4m.framework.ILerpAttributeInterface.md).[removeFramePoint](../interfaces/m4m.framework.ILerpAttributeInterface.md#removeframepoint)

#### Defined in

[framework/particle/new/attribute.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L47)

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

[framework/particle/new/attribute.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L62)

## Constructors

### constructor

• **new Vector3AttributeData**()

#### Defined in

[framework/particle/new/attribute.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particle/new/attribute.ts#L22)
