[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / light

# Class: light

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).light

**`language`** zh_CN

**`classdesc`**
灯光组件

**`version`** m4m 1.0

## Implements

- [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

## Table of contents

### Properties

- [color](m4m.framework.light.md#color)
- [cullingMask](m4m.framework.light.md#cullingmask)
- [gameObject](m4m.framework.light.md#gameobject)
- [intensity](m4m.framework.light.md#intensity)
- [range](m4m.framework.light.md#range)
- [type](m4m.framework.light.md#type)
- [ClassName](m4m.framework.light.md#classname)

### Constructors

- [constructor](m4m.framework.light.md#constructor)

### Methods

- [onPlay](m4m.framework.light.md#onplay)
- [start](m4m.framework.light.md#start)
- [update](m4m.framework.light.md#update)

## Properties

### color

• **color**: `color`

**`language`** zh_CN

**`classdesc`**
光源颜色

**`version`** m4m 1.0

#### Defined in

[framework/component/light.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/light.ts#L71)

___

### cullingMask

• **cullingMask**: `number` = `CullingMask.everything`

**`language`** zh_CN

**`classdesc`**
光照剔除mask

**`version`** m4m 1.0

#### Defined in

[framework/component/light.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/light.ts#L80)

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

[framework/component/light.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/light.ts#L31)

___

### intensity

• **intensity**: `number` = `1`

**`language`** zh_CN

**`classdesc`**
光源强度

**`version`** m4m 1.0

#### Defined in

[framework/component/light.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/light.ts#L62)

___

### range

• **range**: `number` = `10`

**`language`** zh_CN

**`classdesc`**
光源范围

**`version`** m4m 1.0

#### Defined in

[framework/component/light.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/light.ts#L53)

___

### type

• **type**: [`LightTypeEnum`](../enums/m4m.framework.LightTypeEnum.md)

**`language`** zh_CN

**`classdesc`**
光源类型

**`version`** m4m 1.0

#### Defined in

[framework/component/light.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/light.ts#L40)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"light"`

#### Defined in

[framework/component/light.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/light.ts#L22)

## Constructors

### constructor

• **new light**()

## Methods

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

#### Defined in

[framework/component/light.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/light.ts#L86)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

#### Defined in

[framework/component/light.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/light.ts#L81)

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

[framework/component/light.ts:91](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/light.ts#L91)
