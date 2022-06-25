[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / meshFilter

# Class: meshFilter

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).meshFilter

**`language`** zh_CN

**`classdesc`**
mesh组件

**`version`** m4m 1.0

## Implements

- [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

## Table of contents

### Constructors

- [constructor](m4m.framework.meshFilter.md#constructor)

### Properties

- [gameObject](m4m.framework.meshFilter.md#gameobject)
- [ClassName](m4m.framework.meshFilter.md#classname)

### Methods

- [getMeshOutput](m4m.framework.meshFilter.md#getmeshoutput)
- [onPlay](m4m.framework.meshFilter.md#onplay)
- [start](m4m.framework.meshFilter.md#start)
- [update](m4m.framework.meshFilter.md#update)

## Constructors

### constructor

• **new meshFilter**()

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

[framework/component/meshfilter.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshfilter.ts#L24)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"meshFilter"`

#### Defined in

[framework/component/meshfilter.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshfilter.ts#L15)

## Methods

### getMeshOutput

▸ **getMeshOutput**(): [`mesh`](m4m.framework.mesh.md)

**`language`** zh_CN

**`classdesc`**
返回mesh数据

**`version`** m4m 1.0

#### Returns

[`mesh`](m4m.framework.mesh.md)

#### Defined in

[framework/component/meshfilter.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshfilter.ts#L81)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

#### Defined in

[framework/component/meshfilter.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshfilter.ts#L30)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

#### Defined in

[framework/component/meshfilter.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshfilter.ts#L25)

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

[framework/component/meshfilter.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshfilter.ts#L36)
