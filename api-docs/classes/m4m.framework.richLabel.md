[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / richLabel

# Class: richLabel

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).richLabel

富文本版 lable
支持表情字符，自定义样式段落

## Implements

- [`IRectRenderer`](../interfaces/m4m.framework.IRectRenderer.md)

## Table of contents

### Constructors

- [constructor](m4m.framework.richLabel.md#constructor)

### Methods

- [getDrawBounds](m4m.framework.richLabel.md#getdrawbounds)
- [getMaterial](m4m.framework.richLabel.md#getmaterial)
- [onPlay](m4m.framework.richLabel.md#onplay)
- [remove](m4m.framework.richLabel.md#remove)
- [render](m4m.framework.richLabel.md#render)
- [start](m4m.framework.richLabel.md#start)
- [update](m4m.framework.richLabel.md#update)
- [updateTran](m4m.framework.richLabel.md#updatetran)

### Properties

- [transform](m4m.framework.richLabel.md#transform)

## Constructors

### constructor

• **new richLabel**()

## Methods

### getDrawBounds

▸ **getDrawBounds**(): `rect`

#### Returns

`rect`

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[getDrawBounds](../interfaces/m4m.framework.IRectRenderer.md#getdrawbounds)

#### Defined in

[framework/2d/component/richLabel.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/richLabel.ts#L23)

___

### getMaterial

▸ **getMaterial**(): [`material`](m4m.framework.material.md)

#### Returns

[`material`](m4m.framework.material.md)

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[getMaterial](../interfaces/m4m.framework.IRectRenderer.md#getmaterial)

#### Defined in

[framework/2d/component/richLabel.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/richLabel.ts#L19)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[onPlay](../interfaces/m4m.framework.IRectRenderer.md#onplay)

#### Defined in

[framework/2d/component/richLabel.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/richLabel.ts#L27)

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[remove](../interfaces/m4m.framework.IRectRenderer.md#remove)

#### Defined in

[framework/2d/component/richLabel.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/richLabel.ts#L40)

___

### render

▸ **render**(`canvas`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `canvas` | [`canvas`](m4m.framework.canvas.md) |

#### Returns

`void`

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[render](../interfaces/m4m.framework.IRectRenderer.md#render)

#### Defined in

[framework/2d/component/richLabel.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/richLabel.ts#L11)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[start](../interfaces/m4m.framework.IRectRenderer.md#start)

#### Defined in

[framework/2d/component/richLabel.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/richLabel.ts#L31)

___

### update

▸ **update**(`delta`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`void`

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[update](../interfaces/m4m.framework.IRectRenderer.md#update)

#### Defined in

[framework/2d/component/richLabel.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/richLabel.ts#L35)

___

### updateTran

▸ **updateTran**(): `void`

#### Returns

`void`

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[updateTran](../interfaces/m4m.framework.IRectRenderer.md#updatetran)

#### Defined in

[framework/2d/component/richLabel.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/richLabel.ts#L15)

## Properties

### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[transform](../interfaces/m4m.framework.IRectRenderer.md#transform)

#### Defined in

[framework/2d/component/richLabel.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/richLabel.ts#L39)
