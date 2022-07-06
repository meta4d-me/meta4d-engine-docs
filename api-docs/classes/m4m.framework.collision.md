# m4m.framework.collision

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / collision

## Class: collision

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).collision

**`language`** zh\_CN

**`classdesc`** 碰撞检测Tool

**`version`** m4m 1.0

### Table of contents

#### Constructors

* [constructor](m4m.framework.collision.md#constructor)

#### Methods

* [obbVsObb](m4m.framework.collision.md#obbvsobb)
* [obbVsSphere](m4m.framework.collision.md#obbvssphere)
* [sphereVsSphere](m4m.framework.collision.md#spherevssphere)

### Constructors

#### constructor

• **new collision**()

### Methods

#### obbVsObb

▸ `Static` **obbVsObb**(`a`, `b`): `boolean`

**`language`** zh\_CN

**`classdesc`** obb 碰 obb

**`version`** m4m 1.0

**Parameters**

| Name | Type                          |
| ---- | ----------------------------- |
| `a`  | [`obb`](m4m.framework.obb.md) |
| `b`  | [`obb`](m4m.framework.obb.md) |

**Returns**

`boolean`

**Defined in**

[framework/tool/collision.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/collision.ts#L23)

***

#### obbVsSphere

▸ `Static` **obbVsSphere**(`a`, `b`): `boolean`

**`language`** zh\_CN

**`classdesc`** obb 碰 sphere

**`version`** m4m 1.0

**Parameters**

| Name | Type                                            |
| ---- | ----------------------------------------------- |
| `a`  | [`obb`](m4m.framework.obb.md)                   |
| `b`  | [`spherestruct`](m4m.framework.spherestruct.md) |

**Returns**

`boolean`

**Defined in**

[framework/tool/collision.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/collision.ts#L81)

***

#### sphereVsSphere

▸ `Static` **sphereVsSphere**(`a`, `b`): `boolean`

**`language`** zh\_CN

**`classdesc`** sphere 碰 sphere

**`version`** m4m 1.0

**Parameters**

| Name | Type                                            |
| ---- | ----------------------------------------------- |
| `a`  | [`spherestruct`](m4m.framework.spherestruct.md) |
| `b`  | [`spherestruct`](m4m.framework.spherestruct.md) |

**Returns**

`boolean`

**Defined in**

[framework/tool/collision.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/collision.ts#L68)
