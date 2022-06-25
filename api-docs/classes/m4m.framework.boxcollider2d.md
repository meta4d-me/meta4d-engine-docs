[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / boxcollider2d

# Class: boxcollider2d

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).boxcollider2d

**`language`** zh_CN

**`classdesc`**
2d矩形碰撞盒

**`version`** m4m 1.0

## Implements

- [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)
- [`ICollider2d`](../interfaces/m4m.framework.ICollider2d.md)

## Table of contents

### Constructors

- [constructor](m4m.framework.boxcollider2d.md#constructor)

### Methods

- [getBound](m4m.framework.boxcollider2d.md#getbound)
- [intersectsTransform](m4m.framework.boxcollider2d.md#intersectstransform)
- [onPlay](m4m.framework.boxcollider2d.md#onplay)
- [remove](m4m.framework.boxcollider2d.md#remove)
- [start](m4m.framework.boxcollider2d.md#start)
- [update](m4m.framework.boxcollider2d.md#update)

### Properties

- [transform](m4m.framework.boxcollider2d.md#transform)
- [ClassName](m4m.framework.boxcollider2d.md#classname)

## Constructors

### constructor

• **new boxcollider2d**()

## Methods

### getBound

▸ **getBound**(): [`obb2d`](m4m.framework.obb2d.md)

**`language`** zh_CN

**`classdesc`**
获取obb2d

**`version`** m4m 1.0

#### Returns

[`obb2d`](m4m.framework.obb2d.md)

#### Implementation of

[ICollider2d](../interfaces/m4m.framework.ICollider2d.md).[getBound](../interfaces/m4m.framework.ICollider2d.md#getbound)

#### Defined in

[framework/2d/component/boxcollider2d.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/boxcollider2d.ts#L29)

___

### intersectsTransform

▸ **intersectsTransform**(`tran`): `boolean`

**`language`** zh_CN

**`classdesc`**
检测碰撞

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `tran` | [`transform2D`](m4m.framework.transform2D.md) |

#### Returns

`boolean`

#### Implementation of

[ICollider2d](../interfaces/m4m.framework.ICollider2d.md).[intersectsTransform](../interfaces/m4m.framework.ICollider2d.md#intersectstransform)

#### Defined in

[framework/2d/component/boxcollider2d.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/boxcollider2d.ts#L41)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[onPlay](../interfaces/m4m.framework.I2DComponent.md#onplay)

#### Defined in

[framework/2d/component/boxcollider2d.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/boxcollider2d.ts#L83)

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[remove](../interfaces/m4m.framework.I2DComponent.md#remove)

#### Defined in

[framework/2d/component/boxcollider2d.ts:92](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/boxcollider2d.ts#L92)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[start](../interfaces/m4m.framework.I2DComponent.md#start)

#### Defined in

[framework/2d/component/boxcollider2d.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/boxcollider2d.ts#L80)

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

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[update](../interfaces/m4m.framework.I2DComponent.md#update)

#### Defined in

[framework/2d/component/boxcollider2d.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/boxcollider2d.ts#L86)

## Properties

### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

#### Implementation of

[ICollider2d](../interfaces/m4m.framework.ICollider2d.md).[transform](../interfaces/m4m.framework.ICollider2d.md#transform)

#### Defined in

[framework/2d/component/boxcollider2d.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/boxcollider2d.ts#L18)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"boxcollider2d"`

#### Defined in

[framework/2d/component/boxcollider2d.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/boxcollider2d.ts#L16)
