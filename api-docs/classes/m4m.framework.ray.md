# m4m.framework.ray

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ray

## Class: ray

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ray

**`language`** zh\_CN

**`classdesc`** 射线

**`version`** m4m 1.0

### Table of contents

#### Properties

* [direction](m4m.framework.ray.md#direction)
* [origin](m4m.framework.ray.md#origin)

#### Methods

* [intersectPlane](m4m.framework.ray.md#intersectplane)

### Properties

#### direction

• **direction**: `vector3`

**Defined in**

[framework/tool/ray.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/ray.ts#L13)

***

#### origin

• **origin**: `vector3`

**Defined in**

[framework/tool/ray.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/ray.ts#L12)

### Methods

#### intersectPlane

▸ **intersectPlane**(`planePoint`, `planeNormal`, `outHitPoint`): `boolean`

**Parameters**

| Name          | Type      |
| ------------- | --------- |
| `planePoint`  | `vector3` |
| `planeNormal` | `vector3` |
| `outHitPoint` | `vector3` |

**Returns**

`boolean`

**Defined in**

[framework/tool/ray.ts:87](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/ray.ts#L87)
