[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / frustumculling

# Class: frustumculling

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).frustumculling

**`language`** zh_CN

**`classdesc`**
视锥剔除组件，作为标记存在

**`version`** m4m 1.0

## Implements

- [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

## Table of contents

### Methods

- [clone](m4m.framework.frustumculling.md#clone)
- [onPlay](m4m.framework.frustumculling.md#onplay)
- [remove](m4m.framework.frustumculling.md#remove)
- [start](m4m.framework.frustumculling.md#start)
- [update](m4m.framework.frustumculling.md#update)

### Constructors

- [constructor](m4m.framework.frustumculling.md#constructor)

### Properties

- [gameObject](m4m.framework.frustumculling.md#gameobject)
- [ClassName](m4m.framework.frustumculling.md#classname)

## Methods

### clone

▸ **clone**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[clone](../interfaces/m4m.framework.INodeComponent.md#clone)

#### Defined in

[framework/component/frustumculling.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/frustumculling.ts#L47)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

#### Defined in

[framework/component/frustumculling.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/frustumculling.ts#L33)

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[remove](../interfaces/m4m.framework.INodeComponent.md#remove)

#### Defined in

[framework/component/frustumculling.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/frustumculling.ts#L43)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

#### Defined in

[framework/component/frustumculling.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/frustumculling.ts#L28)

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

[framework/component/frustumculling.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/frustumculling.ts#L38)

## Constructors

### constructor

• **new frustumculling**()

#### Defined in

[framework/component/frustumculling.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/frustumculling.ts#L15)

## Properties

### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh_CN

**`classdesc`**
挂载的gameobject

**`version`** m4m 1.0

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[gameObject](../interfaces/m4m.framework.INodeComponent.md#gameobject)

#### Defined in

[framework/component/frustumculling.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/frustumculling.ts#L26)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"frustumculling"`

#### Defined in

[framework/component/frustumculling.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/frustumculling.ts#L13)
