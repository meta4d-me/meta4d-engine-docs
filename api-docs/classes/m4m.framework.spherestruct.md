# m4m.framework.spherestruct

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / spherestruct

## Class: spherestruct

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).spherestruct

**`language`** zh\_CN

**`classdesc`** 球形碰撞盒结构体

**`version`** m4m 1.0

### Table of contents

#### Properties

* [center](m4m.framework.spherestruct.md#center)
* [radius](m4m.framework.spherestruct.md#radius)
* [srcradius](m4m.framework.spherestruct.md#srcradius)

#### Methods

* [computeExtentsByAxis](m4m.framework.spherestruct.md#computeextentsbyaxis)
* [intersects](m4m.framework.spherestruct.md#intersects)
* [update](m4m.framework.spherestruct.md#update)

#### Constructors

* [constructor](m4m.framework.spherestruct.md#constructor)

### Properties

#### center

• **center**: `vector3`

**`language`** zh\_CN

**`classdesc`** 球形碰撞盒中心点

**`version`** m4m 1.0

**Defined in**

[framework/component/spherecollider.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L19)

***

#### radius

• **radius**: `number`

**`language`** zh\_CN

**`classdesc`** 球形碰撞盒半径（缩放处理过的半径）

**`version`** m4m 1.0

**Defined in**

[framework/component/spherecollider.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L27)

***

#### srcradius

• **srcradius**: `number`

**`language`** zh\_CN

**`classdesc`** 球形碰撞盒半径（collider定义的源半径）

**`version`** m4m 1.0

**Defined in**

[framework/component/spherecollider.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L35)

### Methods

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

[framework/component/spherecollider.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L86)

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

[framework/component/spherecollider.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L61)

***

#### update

▸ **update**(`worldmatrix`): `void`

**Parameters**

| Name          | Type     |
| ------------- | -------- |
| `worldmatrix` | `matrix` |

**Returns**

`void`

**Defined in**

[framework/component/spherecollider.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L44)

### Constructors

#### constructor

• **new spherestruct**(`_center`, `_r`)

**Parameters**

| Name      | Type      |
| --------- | --------- |
| `_center` | `vector3` |
| `_r`      | `number`  |

**Defined in**

[framework/component/spherecollider.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/spherecollider.ts#L38)
