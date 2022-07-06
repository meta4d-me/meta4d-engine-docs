# m4m.framework.obb

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / obb

## Class: obb

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).obb

**`language`** zh\_CN

**`classdesc`** 表示定向包围盒

**`version`** m4m 1.0

### Table of contents

#### Methods

* [buildByCenterSize](m4m.framework.obb.md#buildbycentersize)
* [buildByMaxMin](m4m.framework.obb.md#buildbymaxmin)
* [clone](m4m.framework.obb.md#clone)
* [computeExtentsByAxis](m4m.framework.obb.md#computeextentsbyaxis)
* [dispose](m4m.framework.obb.md#dispose)
* [getWorldMatrix](m4m.framework.obb.md#getworldmatrix)
* [intersects](m4m.framework.obb.md#intersects)
* [update](m4m.framework.obb.md#update)

#### Properties

* [center](m4m.framework.obb.md#center)
* [halfsize](m4m.framework.obb.md#halfsize)
* [vectors](m4m.framework.obb.md#vectors)

#### Constructors

* [constructor](m4m.framework.obb.md#constructor)

#### Accessors

* [directions](m4m.framework.obb.md#directions)
* [halfSizeWorld](m4m.framework.obb.md#halfsizeworld)
* [vectorsWorld](m4m.framework.obb.md#vectorsworld)
* [worldCenter](m4m.framework.obb.md#worldcenter)

### Methods

#### buildByCenterSize

▸ **buildByCenterSize**(`center`, `size`): `void`

**`language`** zh\_CN

**`classdesc`** 由中心点和各轴向长度构建定向包围盒

**`version`** m4m 1.0

**Parameters**

| Name     | Type      | Description |
| -------- | --------- | ----------- |
| `center` | `vector3` | 中心点坐标       |
| `size`   | `vector3` | 各轴向长度       |

**Returns**

`void`

**Defined in**

[framework/tool/obb.ts:206](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L206)

***

#### buildByMaxMin

▸ **buildByMaxMin**(`minimum`, `maximum`): `void`

**`language`** zh\_CN

**`classdesc`** 由最大最小点构建定向包围盒

**`version`** m4m 1.0

**Parameters**

| Name      | Type      | Description |
| --------- | --------- | ----------- |
| `minimum` | `vector3` | 最小点坐标       |
| `maximum` | `vector3` | 最大点坐标       |

**Returns**

`void`

**Defined in**

[framework/tool/obb.ts:170](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L170)

***

#### clone

▸ **clone**(): [`obb`](m4m.framework.obb.md)

**`language`** zh\_CN

**`classdesc`** 克隆一个obb

**`version`** m4m 1.0

**Returns**

[`obb`](m4m.framework.obb.md)

**Defined in**

[framework/tool/obb.ts:301](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L301)

***

#### computeExtentsByAxis

▸ **computeExtentsByAxis**(`axis`, `out`): `void`

**`language`** zh\_CN

**`classdesc`** 计算到指定轴上投影的长度

**`version`** m4m 1.0

**Parameters**

| Name   | Type      | Description |
| ------ | --------- | ----------- |
| `axis` | `vector3` | 指定轴         |
| `out`  | `vector2` | 长度范围        |

**Returns**

`void`

**Defined in**

[framework/tool/obb.ts:281](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L281)

***

#### dispose

▸ **dispose**(): `void`

**`language`** zh\_CN

**`classdesc`** 释放

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/tool/obb.ts:335](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L335)

***

#### getWorldMatrix

▸ **getWorldMatrix**(): `matrix`

**`language`** zh\_CN

**`classdesc`** 获取obb世界矩阵

**`version`** m4m 1.0

**Returns**

`matrix`

**Defined in**

[framework/tool/obb.ts:157](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L157)

***

#### intersects

▸ **intersects**(`bound`): `boolean`

**`language`** zh\_CN

**`classdesc`** 碰撞体检测碰撞

**`version`** m4m 1.0

**Parameters**

| Name    | Type  | Description |
| ------- | ----- | ----------- |
| `bound` | `any` | 碰撞体         |

**Returns**

`boolean`

**Defined in**

[framework/tool/obb.ts:259](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L259)

***

#### update

▸ **update**(`worldmatrix`): `void`

**`language`** zh\_CN

**`classdesc`** 刷新定向包围盒

**`version`** m4m 1.0

**Parameters**

| Name          | Type     | Description |
| ------------- | -------- | ----------- |
| `worldmatrix` | `matrix` | 物体的世界矩阵     |

**Returns**

`void`

**Defined in**

[framework/tool/obb.ts:236](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L236)

### Properties

#### center

• **center**: `vector3`

**`language`** zh\_CN

**`classdesc`** 包围盒中心坐标

**`version`** m4m 1.0

**Defined in**

[framework/tool/obb.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L31)

***

#### halfsize

• **halfsize**: `vector3`

**`language`** zh\_CN

**`classdesc`** 包围盒各轴向半长

**`version`** m4m 1.0

**Defined in**

[framework/tool/obb.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L39)

***

#### vectors

• **vectors**: `vector3`\[]

**`language`** zh\_CN

**`classdesc`** 包围盒世界空间下各个点坐标

**`version`** m4m 1.0

**Defined in**

[framework/tool/obb.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L48)

### Constructors

#### constructor

• **new obb**()

### Accessors

#### directions

• `get` **directions**(): `vector3`\[]

**`language`** zh\_CN

**`classdesc`** x,y,z 轴方向

**`version`** m4m 1.0

**Returns**

`vector3`\[]

**Defined in**

[framework/tool/obb.ts:140](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L140)

***

#### halfSizeWorld

• `get` **halfSizeWorld**(): `vector3`

**`language`** zh\_CN

**`classdesc`** 包围盒在世界坐标中各轴向半长

**`version`** m4m 1.0

**Returns**

`vector3`

**Defined in**

[framework/tool/obb.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L106)

***

#### vectorsWorld

• `get` **vectorsWorld**(): `vector3`\[]

**`language`** zh\_CN

**`classdesc`** 包围盒世界空间下各个点坐标

**`version`** m4m 1.0

**Returns**

`vector3`\[]

**Defined in**

[framework/tool/obb.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L64)

***

#### worldCenter

• `get` **worldCenter**(): `vector3`

**`language`** zh\_CN

**`classdesc`** 在世界空间的中心点

**`version`** m4m 1.0

**Returns**

`vector3`

**Defined in**

[framework/tool/obb.ts:91](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/obb.ts#L91)
