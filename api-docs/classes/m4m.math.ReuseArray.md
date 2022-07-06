# m4m.math.ReuseArray

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [math](../modules/m4m.math.md) / ReuseArray

## Class: ReuseArray\<T>

[m4m](../modules/m4m.md).[math](../modules/m4m.math.md).ReuseArray

复用数组 ，用于频繁重复创建数组容器的场景(减少GC消耗)

### Type parameters

| Name |
| ---- |
| `T`  |

### Table of contents

#### Methods

* [clear](m4m.math.ReuseArray.md#clear)
* [get](m4m.math.ReuseArray.md#get)
* [getArray](m4m.math.ReuseArray.md#getarray)
* [push](m4m.math.ReuseArray.md#push)

#### Constructors

* [constructor](m4m.math.ReuseArray.md#constructor)

#### Accessors

* [length](m4m.math.ReuseArray.md#length)

### Methods

#### clear

▸ **clear**(): `void`

数组所有值置为null

**Returns**

`void`

**Defined in**

[render/struct.ts:686](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L686)

***

#### get

▸ **get**(`index`): `T`

获取指定索引的值

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `index` | `number` |

**Returns**

`T`

**Defined in**

[render/struct.ts:680](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L680)

***

#### getArray

▸ **getArray**(): `T`\[]

获取 Array 对象

**Returns**

`T`\[]

**Defined in**

[render/struct.ts:666](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L666)

***

#### push

▸ **push**(`val`): `void`

**Parameters**

| Name  | Type |
| ----- | ---- |
| `val` | `T`  |

**Returns**

`void`

**Defined in**

[render/struct.ts:674](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L674)

### Constructors

#### constructor

• **new ReuseArray**<`T`>()

**Type parameters**

| Name |
| ---- |
| `T`  |

### Accessors

#### length

• `get` **length**(): `number`

获取当前长度

**Returns**

`number`

**Defined in**

[render/struct.ts:671](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L671)

• `set` **length**(`val`): `void`

获取当前长度

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[render/struct.ts:672](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L672)
