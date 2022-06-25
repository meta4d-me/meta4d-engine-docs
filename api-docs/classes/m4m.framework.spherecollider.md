[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / spherecollider

# Class: spherecollider

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).spherecollider

**`language`** zh_CN

**`classdesc`**
球形碰撞盒组件

**`version`** m4m 1.0

## Implements

- [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)
- [`ICollider`](../interfaces/m4m.framework.ICollider.md)

## Table of contents

### Properties

- [center](m4m.framework.spherecollider.md#center)
- [gameObject](m4m.framework.spherecollider.md#gameobject)
- [radius](m4m.framework.spherecollider.md#radius)
- [spherestruct](m4m.framework.spherecollider.md#spherestruct)
- [subTran](m4m.framework.spherecollider.md#subtran)
- [ClassName](m4m.framework.spherecollider.md#classname)

### Accessors

- [colliderVisible](m4m.framework.spherecollider.md#collidervisible)
- [matrix](m4m.framework.spherecollider.md#matrix)
- [worldCenter](m4m.framework.spherecollider.md#worldcenter)

### Constructors

- [constructor](m4m.framework.spherecollider.md#constructor)

### Methods

- [getBound](m4m.framework.spherecollider.md#getbound)
- [intersectsTransform](m4m.framework.spherecollider.md#intersectstransform)
- [onPlay](m4m.framework.spherecollider.md#onplay)
- [start](m4m.framework.spherecollider.md#start)
- [update](m4m.framework.spherecollider.md#update)

## Properties

### center

• **center**: `vector3`

**`language`** zh_CN

**`classdesc`**
碰撞球中心点

**`version`** m4m 1.0

#### Defined in

[framework/component/spherecollider.ts:142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L142)

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

[framework/component/spherecollider.ts:113](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L113)

___

### radius

• **radius**: `number` = `0.5`

**`language`** zh_CN

**`classdesc`**
碰撞球大小

**`version`** m4m 1.0

#### Defined in

[framework/component/spherecollider.ts:151](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L151)

___

### spherestruct

• **spherestruct**: [`spherestruct`](m4m.framework.spherestruct.md)

**`language`** zh_CN

**`classdesc`**
碰撞球数据

**`version`** m4m 1.0

#### Defined in

[framework/component/spherecollider.ts:133](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L133)

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

[framework/component/spherecollider.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L121)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"spherecollider"`

#### Defined in

[framework/component/spherecollider.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L103)

## Accessors

### colliderVisible

• `get` **colliderVisible**(): `boolean`

**`language`** zh_CN

**`classdesc`**
返回碰撞盒可见性

**`version`** m4m 1.0

#### Returns

`boolean`

#### Defined in

[framework/component/spherecollider.ts:230](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L230)

• `set` **colliderVisible**(`value`): `void`

**`language`** zh_CN

**`classdesc`**
设置碰撞盒是否可见

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `boolean` |

#### Returns

`void`

#### Defined in

[framework/component/spherecollider.ts:241](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L241)

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

[framework/component/spherecollider.ts:187](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L187)

___

### worldCenter

• `get` **worldCenter**(): `vector3`

**`language`** zh_CN

**`classdesc`**
碰撞球中心点

**`version`** m4m 1.0

#### Returns

`vector3`

#### Defined in

[framework/component/spherecollider.ts:163](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L163)

## Constructors

### constructor

• **new spherecollider**()

## Methods

### getBound

▸ **getBound**(): [`spherestruct`](m4m.framework.spherestruct.md)

**`language`** zh_CN

**`classdesc`**
碰撞球数据

**`version`** m4m 1.0

#### Returns

[`spherestruct`](m4m.framework.spherestruct.md)

#### Implementation of

[ICollider](../interfaces/m4m.framework.ICollider.md).[getBound](../interfaces/m4m.framework.ICollider.md#getbound)

#### Defined in

[framework/component/spherecollider.ts:176](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L176)

___

### intersectsTransform

▸ **intersectsTransform**(`tran`): `boolean`

**`language`** zh_CN

**`classdesc`**
检测碰撞

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `tran` | [`transform`](m4m.framework.transform.md) | 目标transform |

#### Returns

`boolean`

#### Implementation of

[ICollider](../interfaces/m4m.framework.ICollider.md).[intersectsTransform](../interfaces/m4m.framework.ICollider.md#intersectstransform)

#### Defined in

[framework/component/spherecollider.ts:293](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L293)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

#### Defined in

[framework/component/spherecollider.ts:199](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L199)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

#### Defined in

[framework/component/spherecollider.ts:193](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L193)

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

[framework/component/spherecollider.ts:204](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L204)
