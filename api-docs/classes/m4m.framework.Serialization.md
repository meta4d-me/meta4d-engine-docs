[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / Serialization

# Class: Serialization

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).Serialization

序列化

**`author`** feng3d

## Table of contents

### Methods

- [clone](m4m.framework.Serialization.md#clone)
- [deserialize](m4m.framework.Serialization.md#deserialize)
- [different](m4m.framework.Serialization.md#different)
- [serialize](m4m.framework.Serialization.md#serialize)
- [setValue](m4m.framework.Serialization.md#setvalue)

### Constructors

- [constructor](m4m.framework.Serialization.md#constructor)

### Properties

- [deserializeHandlers](m4m.framework.Serialization.md#deserializehandlers)
- [differentHandlers](m4m.framework.Serialization.md#differenthandlers)
- [serializeHandlers](m4m.framework.Serialization.md#serializehandlers)
- [setValueHandlers](m4m.framework.Serialization.md#setvaluehandlers)

## Methods

### clone

▸ **clone**<`T`\>(`target`): `T`

克隆

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `target` | `T` | 被克隆对象 |

#### Returns

`T`

#### Defined in

[framework/util/serialization.ts:186](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/serialization.ts#L186)

___

### deserialize

▸ **deserialize**<`T`\>(`object`): `T`

反序列化对象为基础对象数据（由Object与Array组合）

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `object` | [`gPartial`](../modules/m4m.framework.md#gpartial)<`T`\> | 换为Json的对象 |

#### Returns

`T`

反序列化后的数据

#### Defined in

[framework/util/serialization.ts:143](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/serialization.ts#L143)

___

### different

▸ **different**<`T`\>(`target`, `source`): [`gPartial`](../modules/m4m.framework.md#gpartial)<`T`\>

比较两个对象的不同，提取出不同的数据(可能会经过反序列化处理)

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `target` | `T` | 用于检测不同的数据 |
| `source` | `T` | 模板（默认）数据 |

#### Returns

[`gPartial`](../modules/m4m.framework.md#gpartial)<`T`\>

比较得出的不同数据（由Object与Array组合可 JSON.stringify 的简单结构）

#### Defined in

[framework/util/serialization.ts:161](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/serialization.ts#L161)

___

### serialize

▸ **serialize**<`T`\>(`target`): [`gPartial`](../modules/m4m.framework.md#gpartial)<`T`\>

序列化对象

过程中使用 different与默认值作比较减少结果中的数据。

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `target` | `T` | 被序列化的对象 |

#### Returns

[`gPartial`](../modules/m4m.framework.md#gpartial)<`T`\>

序列化后简单数据对象（由Object与Array组合可 JSON.stringify 的简单结构）

#### Defined in

[framework/util/serialization.ts:128](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/serialization.ts#L128)

___

### setValue

▸ **setValue**<`T`\>(`target`, `source`): `T`

从数据对象中提取数据给目标对象赋值（可能会经过序列化处理）

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `target` | `T` | 目标对象 |
| `source` | [`gPartial`](../modules/m4m.framework.md#gpartial)<`T`\> | 数据对象 可由Object与Array以及自定义类型组合 |

#### Returns

`T`

#### Defined in

[framework/util/serialization.ts:175](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/serialization.ts#L175)

## Constructors

### constructor

• **new Serialization**()

## Properties

### deserializeHandlers

• **deserializeHandlers**: { `handler`: [`PropertyHandler`](../interfaces/m4m.framework.PropertyHandler.md) ; `priority`: `number`  }[] = `[]`

反序列化函数列表

#### Defined in

[framework/util/serialization.ts:107](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/serialization.ts#L107)

___

### differentHandlers

• **differentHandlers**: { `handler`: [`DifferentPropertyHandler`](../interfaces/m4m.framework.DifferentPropertyHandler.md) ; `priority`: `number`  }[] = `[]`

比较差异函数列表

#### Defined in

[framework/util/serialization.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/serialization.ts#L112)

___

### serializeHandlers

• **serializeHandlers**: { `handler`: [`PropertyHandler`](../interfaces/m4m.framework.PropertyHandler.md) ; `priority`: `number`  }[] = `[]`

序列化函数列表

#### Defined in

[framework/util/serialization.ts:102](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/serialization.ts#L102)

___

### setValueHandlers

• **setValueHandlers**: { `handler`: [`PropertyHandler`](../interfaces/m4m.framework.PropertyHandler.md) ; `priority`: `number`  }[] = `[]`

设置函数列表

#### Defined in

[framework/util/serialization.ts:117](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/serialization.ts#L117)
