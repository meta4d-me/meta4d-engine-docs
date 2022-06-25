[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ObjectUtil

# Class: ObjectUtil

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ObjectUtil

Object 工具

## Table of contents

### Constructors

- [constructor](m4m.framework.ObjectUtil.md#constructor)

### Methods

- [isBaseType](m4m.framework.ObjectUtil.md#isbasetype)
- [isObject](m4m.framework.ObjectUtil.md#isobject)

## Constructors

### constructor

• **new ObjectUtil**()

## Methods

### isBaseType

▸ `Static` **isBaseType**(`object`): `boolean`

判断是否为基础类型 undefined,null,boolean,string,number

#### Parameters

| Name | Type |
| :------ | :------ |
| `object` | `any` |

#### Returns

`boolean`

#### Defined in

[framework/util/objectutil.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/objectutil.ts#L13)

___

### isObject

▸ `Static` **isObject**(`obj`): `boolean`

判断是否为Object对象，构造函数是否为Object， 检测 object.constructor == Object

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 用于判断的对象 |

#### Returns

`boolean`

#### Defined in

[framework/util/objectutil.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/objectutil.ts#L31)
