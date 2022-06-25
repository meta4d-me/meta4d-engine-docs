[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / behaviour

# Class: behaviour

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).behaviour

**`language`** zh_CN

**`classdesc`**
脚本行文类

**`version`** m4m 1.0

## Implements

- [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)
- [`IEnabled`](../interfaces/m4m.framework.IEnabled.md)

## Table of contents

### Constructors

- [constructor](m4m.framework.behaviour.md#constructor)

### Properties

- [enabled](m4m.framework.behaviour.md#enabled)
- [gameObject](m4m.framework.behaviour.md#gameobject)

### Methods

- [onPlay](m4m.framework.behaviour.md#onplay)
- [start](m4m.framework.behaviour.md#start)
- [update](m4m.framework.behaviour.md#update)

## Constructors

### constructor

• **new behaviour**()

## Properties

### enabled

• **enabled**: `boolean` = `true`

**`language`** zh_CN

**`classdesc`**
组件启用

**`version`** m4m 1.0

#### Implementation of

[IEnabled](../interfaces/m4m.framework.IEnabled.md).[enabled](../interfaces/m4m.framework.IEnabled.md#enabled)

#### Defined in

[framework/component/behaviour.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/behaviour.ts#L20)

___

### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh_CN

**`classdesc`**
挂载的gameobject

**`version`** m4m 1.0

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[gameObject](../interfaces/m4m.framework.INodeComponent.md#gameobject)

#### Defined in

[framework/component/behaviour.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/behaviour.ts#L29)

## Methods

### onPlay

▸ **onPlay**(): `void`

初始化使用 在start 之后

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

#### Defined in

[framework/component/behaviour.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/behaviour.ts#L38)

___

### start

▸ **start**(): `void`

初始化使用

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

#### Defined in

[framework/component/behaviour.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/behaviour.ts#L32)

___

### update

▸ **update**(`delta`): `void`

每帧调用一次

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[update](../interfaces/m4m.framework.INodeComponent.md#update)

#### Defined in

[framework/component/behaviour.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/behaviour.ts#L44)
