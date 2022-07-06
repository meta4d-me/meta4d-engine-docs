# m4m.framework.ICollider2d

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ICollider2d

## Interface: ICollider2d

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ICollider2d

**`language`** zh\_CN

**`classdesc`** 2d碰撞器接口

**`version`** m4m 1.0

### Implemented by

* [`boxcollider2d`](../classes/m4m.framework.boxcollider2d.md)

### Table of contents

#### Methods

* [getBound](m4m.framework.ICollider2d.md#getbound)
* [intersectsTransform](m4m.framework.ICollider2d.md#intersectstransform)

#### Properties

* [transform](m4m.framework.ICollider2d.md#transform)

### Methods

#### getBound

▸ **getBound**(): [`obb2d`](../classes/m4m.framework.obb2d.md)

**Returns**

[`obb2d`](../classes/m4m.framework.obb2d.md)

**Defined in**

[framework/interfaces.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L48)

***

#### intersectsTransform

▸ **intersectsTransform**(`tran`): `boolean`

**Parameters**

| Name   | Type                                                     |
| ------ | -------------------------------------------------------- |
| `tran` | [`transform2D`](../classes/m4m.framework.transform2D.md) |

**Returns**

`boolean`

**Defined in**

[framework/interfaces.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L49)

### Properties

#### transform

• **transform**: [`transform2D`](../classes/m4m.framework.transform2D.md)

**Defined in**

[framework/interfaces.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L47)
