[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / TransformUtil

# Class: TransformUtil

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).TransformUtil

**`language`** zh_CN

**`classdesc`**
Transform工具类

**`version`** m4m 1.0

## Table of contents

### Constructors

- [constructor](m4m.framework.TransformUtil.md#constructor)

### Methods

- [Create2DPrimitive](m4m.framework.TransformUtil.md#create2dprimitive)
- [CreatePrimitive](m4m.framework.TransformUtil.md#createprimitive)

## Constructors

### constructor

• **new TransformUtil**()

## Methods

### Create2DPrimitive

▸ `Static` **Create2DPrimitive**(`type`, `app?`): [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh_CN

**`classdesc`**
创建默认的2d控件

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `type` | [`Primitive2DType`](../enums/m4m.framework.Primitive2DType.md) | `undefined` | 2d控件类型 |
| `app` | [`application`](m4m.framework.application.md) | `null` | application的实例 |

#### Returns

[`transform2D`](m4m.framework.transform2D.md)

#### Defined in

[framework/util/transformutil.ts:115](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/transformutil.ts#L115)

___

### CreatePrimitive

▸ `Static` **CreatePrimitive**(`type`, `app?`): [`transform`](m4m.framework.transform.md)

**`language`** zh_CN

**`classdesc`**
创建默认的3d对象

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `type` | [`PrimitiveType`](../enums/m4m.framework.PrimitiveType.md) | `undefined` | 原生3d对象类型 |
| `app` | [`application`](m4m.framework.application.md) | `null` | application的实例 |

#### Returns

[`transform`](m4m.framework.transform.md)

#### Defined in

[framework/util/transformutil.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/transformutil.ts#L86)
