[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ICollider

# Interface: ICollider

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ICollider

## Implemented by

- [`boxcollider`](../classes/m4m.framework.boxcollider.md)
- [`canvasRenderer`](../classes/m4m.framework.canvasRenderer.md)
- [`meshcollider`](../classes/m4m.framework.meshcollider.md)
- [`spherecollider`](../classes/m4m.framework.spherecollider.md)

## Table of contents

### Properties

- [gameObject](m4m.framework.ICollider.md#gameobject)
- [subTran](m4m.framework.ICollider.md#subtran)

### Methods

- [getBound](m4m.framework.ICollider.md#getbound)
- [intersectsTransform](m4m.framework.ICollider.md#intersectstransform)

## Properties

### gameObject

• **gameObject**: [`gameObject`](../classes/m4m.framework.gameObject.md)

#### Defined in

[framework/component/boxcollider.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L7)

___

### subTran

• **subTran**: [`transform`](../classes/m4m.framework.transform.md)

#### Defined in

[framework/component/boxcollider.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L8)

## Methods

### getBound

▸ **getBound**(): `any`

#### Returns

`any`

#### Defined in

[framework/component/boxcollider.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L9)

___

### intersectsTransform

▸ **intersectsTransform**(`tran`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tran` | [`transform`](../classes/m4m.framework.transform.md) |

#### Returns

`boolean`

#### Defined in

[framework/component/boxcollider.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L10)
