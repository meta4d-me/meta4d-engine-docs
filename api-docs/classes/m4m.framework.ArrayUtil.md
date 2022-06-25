[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ArrayUtil

# Class: ArrayUtil

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ArrayUtil

数组工具

## Table of contents

### Constructors

- [constructor](m4m.framework.ArrayUtil.md#constructor)

### Methods

- [concatToSelf](m4m.framework.ArrayUtil.md#concattoself)
- [replace](m4m.framework.ArrayUtil.md#replace)
- [unique](m4m.framework.ArrayUtil.md#unique)

## Constructors

### constructor

• **new ArrayUtil**()

## Methods

### concatToSelf

▸ `Static` **concatToSelf**<`T`\>(`self`, ...`items`): `T`[]

连接一个或多个数组到自身

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `self` | `T`[] | 被操作数组 |
| `...items` | (`T` \| `ConcatArray`<`T`\>)[] | 要添加到数组末尾的其他项。 |

#### Returns

`T`[]

返回自身

#### Defined in

[framework/util/arrayutil.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/arrayutil.ts#L39)

___

### replace

▸ `Static` **replace**<`T`\>(`arr`, `a`, `b`, `isAdd?`): `T`[]

使用b元素替换数组中第一个a元素。

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `arr` | `T`[] | `undefined` | 被操作数组 |
| `a` | `T` | `undefined` | 被替换的元素 |
| `b` | `T` | `undefined` | 用于替换的元素 |
| `isAdd` | `boolean` | `true` | 当数组中没有找到a元素时，是否需要把b元素添加到数组尾部。默认值为true。 |

#### Returns

`T`[]

#### Defined in

[framework/util/arrayutil.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/arrayutil.ts#L16)

___

### unique

▸ `Static` **unique**<`T`\>(`arr`, `compare?`): `T`[]

使数组变得唯一，不存在两个相等的元素

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `arr` | `T`[] | 被操作数组 |
| `compare?` | (`a`: `T`, `b`: `T`) => `boolean` | 比较函数 |

#### Returns

`T`[]

#### Defined in

[framework/util/arrayutil.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/arrayutil.ts#L53)
