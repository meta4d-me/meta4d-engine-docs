# m4m.framework.obb2d

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / obb2d

## Class: obb2d

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).obb2d

### Table of contents

#### Methods

* [buildByCenterSize](m4m.framework.obb2d.md#buildbycentersize)
* [clone](m4m.framework.obb2d.md#clone)
* [dispose](m4m.framework.obb2d.md#dispose)
* [intersects](m4m.framework.obb2d.md#intersects)
* [update](m4m.framework.obb2d.md#update)

#### Constructors

* [constructor](m4m.framework.obb2d.md#constructor)

#### Properties

* [offset](m4m.framework.obb2d.md#offset)

#### Accessors

* [size](m4m.framework.obb2d.md#size)

### Methods

#### buildByCenterSize

▸ **buildByCenterSize**(`center`, `width`, `height`): `void`

**`language`** zh\_CN

**`classdesc`** 由最大最小点构建定向包围盒

**`version`** m4m 1.0

**Parameters**

| Name     | Type      | Description |
| -------- | --------- | ----------- |
| `center` | `vector2` | 中心点坐标       |
| `width`  | `number`  | 包围盒宽度       |
| `height` | `number`  | 包围盒高度       |

**Returns**

`void`

**Defined in**

[framework/tool/obb2d.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb2d.ts#L53)

***

#### clone

▸ **clone**(): [`obb2d`](m4m.framework.obb2d.md)

**`language`** zh\_CN

**`classdesc`** 克隆一个obb

**`version`** m4m 1.0

**Returns**

[`obb2d`](m4m.framework.obb2d.md)

**Defined in**

[framework/tool/obb2d.ts:147](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb2d.ts#L147)

***

#### dispose

▸ **dispose**(): `void`

**`language`** zh\_CN

**`classdesc`** 释放

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/tool/obb2d.ts:170](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb2d.ts#L170)

***

#### intersects

▸ **intersects**(`_obb`): `boolean`

**`language`** zh\_CN

**`classdesc`** obb2d的碰撞检测

**`version`** m4m 1.0

**Parameters**

| Name   | Type                              | Description |
| ------ | --------------------------------- | ----------- |
| `_obb` | [`obb2d`](m4m.framework.obb2d.md) | 待检测obb2d    |

**Returns**

`boolean`

**Defined in**

[framework/tool/obb2d.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb2d.ts#L100)

***

#### update

▸ **update**(`canvasWorldMtx`): `void`

**`language`** zh\_CN

**`classdesc`** 刷新定向包围盒

**`version`** m4m 1.0

**Parameters**

| Name             | Type        | Description |
| ---------------- | ----------- | ----------- |
| `canvasWorldMtx` | `matrix3x2` | Canvas世界矩阵  |

**Returns**

`void`

**Defined in**

[framework/tool/obb2d.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb2d.ts#L72)

### Constructors

#### constructor

• **new obb2d**()

### Properties

#### offset

• **offset**: `vector2`

**`language`** zh\_CN

**`classdesc`** 中心点偏移量

**`version`** m4m 1.0

**Defined in**

[framework/tool/obb2d.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb2d.ts#L22)

### Accessors

#### size

• `get` **size**(): `vector2`

**`language`** zh\_CN

**`classdesc`** 包围盒大小

**`version`** m4m 1.0

**Returns**

`vector2`

**Defined in**

[framework/tool/obb2d.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb2d.ts#L35)

• `set` **size**(`size`): `void`

**`language`** zh\_CN

**`classdesc`** 包围盒大小

**`version`** m4m 1.0

**Parameters**

| Name   | Type      |
| ------ | --------- |
| `size` | `vector2` |

**Returns**

`void`

**Defined in**

[framework/tool/obb2d.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb2d.ts#L36)
