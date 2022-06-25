[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / boxcollider

# Class: boxcollider

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).boxcollider

**`language`** zh_CN

**`classdesc`**
表示矩形碰撞盒

**`version`** m4m 1.0

## Implements

- [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)
- [`ICollider`](../interfaces/m4m.framework.ICollider.md)

## Table of contents

### Properties

- [center](m4m.framework.boxcollider.md#center)
- [gameObject](m4m.framework.boxcollider.md#gameobject)
- [size](m4m.framework.boxcollider.md#size)
- [subTran](m4m.framework.boxcollider.md#subtran)
- [ClassName](m4m.framework.boxcollider.md#classname)

### Accessors

- [colliderVisible](m4m.framework.boxcollider.md#collidervisible)
- [matrix](m4m.framework.boxcollider.md#matrix)

### Constructors

- [constructor](m4m.framework.boxcollider.md#constructor)

### Methods

- [intersectsTransform](m4m.framework.boxcollider.md#intersectstransform)
- [onPlay](m4m.framework.boxcollider.md#onplay)
- [start](m4m.framework.boxcollider.md#start)
- [update](m4m.framework.boxcollider.md#update)

## Properties

### center

• **center**: `vector3`

**`language`** zh_CN

**`classdesc`**
碰撞盒中心点

**`version`** m4m 1.0

#### Defined in

[framework/component/boxcollider.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L57)

___

### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh_CN

**`classdesc`**
挂载的gameobject

**`version`** m4m 1.0

#### Implementation of

[ICollider](../interfaces/m4m.framework.ICollider.md).[gameObject](../interfaces/m4m.framework.ICollider.md#gameobject)

#### Defined in

[framework/component/boxcollider.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L32)

___

### size

• **size**: `vector3`

**`language`** zh_CN

**`classdesc`**
碰撞盒大小

**`version`** m4m 1.0

#### Defined in

[framework/component/boxcollider.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L66)

___

### subTran

• **subTran**: [`transform`](m4m.framework.transform.md)

**`language`** zh_CN

**`classdesc`**
子transform

**`version`** m4m 1.0

#### Implementation of

[ICollider](../interfaces/m4m.framework.ICollider.md).[subTran](../interfaces/m4m.framework.ICollider.md#subtran)

#### Defined in

[framework/component/boxcollider.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L40)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"boxcollider"`

#### Defined in

[framework/component/boxcollider.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L23)

## Accessors

### colliderVisible

• `get` **colliderVisible**(): `boolean`

**`language`** zh_CN

**`classdesc`**
碰撞盒的可见性

**`version`** m4m 1.0

#### Returns

`boolean`

#### Defined in

[framework/component/boxcollider.ts:124](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L124)

• `set` **colliderVisible**(`value`): `void`

**`language`** zh_CN

**`classdesc`**
设置碰撞盒的可见性

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `boolean` |

#### Returns

`void`

#### Defined in

[framework/component/boxcollider.ts:135](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L135)

___

### matrix

• `get` **matrix**(): `matrix`

**`language`** zh_CN

**`classdesc`**
获取该碰撞盒物体的世界矩阵

**`version`** m4m 1.0

#### Returns

`matrix`

#### Defined in

[framework/component/boxcollider.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L83)

## Constructors

### constructor

• **new boxcollider**()

## Methods

### intersectsTransform

▸ **intersectsTransform**(`tran`): `boolean`

**`language`** zh_CN

**`classdesc`**
检测碰撞

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `tran` | [`transform`](m4m.framework.transform.md) |

#### Returns

`boolean`

#### Implementation of

[ICollider](../interfaces/m4m.framework.ICollider.md).[intersectsTransform](../interfaces/m4m.framework.ICollider.md#intersectstransform)

#### Defined in

[framework/component/boxcollider.ts:163](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L163)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

#### Defined in

[framework/component/boxcollider.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L101)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

#### Defined in

[framework/component/boxcollider.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L93)

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

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[update](../interfaces/m4m.framework.INodeComponent.md#update)

#### Defined in

[framework/component/boxcollider.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/boxcollider.ts#L106)
