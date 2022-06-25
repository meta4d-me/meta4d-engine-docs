[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IRectRenderer

# Interface: IRectRenderer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IRectRenderer

**`language`** zh_CN

**`classdesc`**
2D渲染组件的接口

**`version`** m4m 1.0

## Hierarchy

- [`I2DComponent`](m4m.framework.I2DComponent.md)

  ↳ **`IRectRenderer`**

## Implemented by

- [`image2D`](../classes/m4m.framework.image2D.md)
- [`label`](../classes/m4m.framework.label.md)
- [`rawImage2D`](../classes/m4m.framework.rawImage2D.md)
- [`richLabel`](../classes/m4m.framework.richLabel.md)

## Table of contents

### Methods

- [getDrawBounds](m4m.framework.IRectRenderer.md#getdrawbounds)
- [getMaterial](m4m.framework.IRectRenderer.md#getmaterial)
- [onPlay](m4m.framework.IRectRenderer.md#onplay)
- [remove](m4m.framework.IRectRenderer.md#remove)
- [render](m4m.framework.IRectRenderer.md#render)
- [start](m4m.framework.IRectRenderer.md#start)
- [update](m4m.framework.IRectRenderer.md#update)
- [updateTran](m4m.framework.IRectRenderer.md#updatetran)

### Properties

- [transform](m4m.framework.IRectRenderer.md#transform)

## Methods

### getDrawBounds

▸ **getDrawBounds**(): `rect`

#### Returns

`rect`

#### Defined in

[framework/interfaces.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L66)

___

### getMaterial

▸ **getMaterial**(): [`material`](../classes/m4m.framework.material.md)

#### Returns

[`material`](../classes/m4m.framework.material.md)

#### Defined in

[framework/interfaces.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L64)

___

### onPlay

▸ **onPlay**(): `any`

#### Returns

`any`

#### Inherited from

[I2DComponent](m4m.framework.I2DComponent.md).[onPlay](m4m.framework.I2DComponent.md#onplay)

#### Defined in

[framework/interfaces.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L32)

___

### remove

▸ **remove**(): `any`

#### Returns

`any`

#### Inherited from

[I2DComponent](m4m.framework.I2DComponent.md).[remove](m4m.framework.I2DComponent.md#remove)

#### Defined in

[framework/interfaces.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L36)

___

### render

▸ **render**(`canvas`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `canvas` | [`canvas`](../classes/m4m.framework.canvas.md) |

#### Returns

`any`

#### Defined in

[framework/interfaces.ts:60](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L60)

___

### start

▸ **start**(): `any`

#### Returns

`any`

#### Inherited from

[I2DComponent](m4m.framework.I2DComponent.md).[start](m4m.framework.I2DComponent.md#start)

#### Defined in

[framework/interfaces.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L33)

___

### update

▸ **update**(`delta`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`any`

#### Inherited from

[I2DComponent](m4m.framework.I2DComponent.md).[update](m4m.framework.I2DComponent.md#update)

#### Defined in

[framework/interfaces.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L34)

___

### updateTran

▸ **updateTran**(): `any`

#### Returns

`any`

#### Defined in

[framework/interfaces.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L62)

## Properties

### transform

• **transform**: [`transform2D`](../classes/m4m.framework.transform2D.md)

#### Inherited from

[I2DComponent](m4m.framework.I2DComponent.md).[transform](m4m.framework.I2DComponent.md#transform)

#### Defined in

[framework/interfaces.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L35)
