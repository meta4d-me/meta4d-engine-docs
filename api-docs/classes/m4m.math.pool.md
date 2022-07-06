# m4m.math.pool

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [math](../modules/m4m.math.md) / pool

## Class: pool

[m4m](../modules/m4m.md).[math](../modules/m4m.math.md).pool

**`language`** zh\_CN

**`classdesc`** 对常用结构类型数据进行池化处理， 在大量使用结构类型数据的逻辑中尽量使用该结构

**`version`** m4m 1.0

### Table of contents

#### Constructors

* [constructor](m4m.math.pool.md#constructor)

#### Methods

* [clone\_color](m4m.math.pool.md#clone\_color)
* [clone\_matrix](m4m.math.pool.md#clone\_matrix)
* [clone\_matrix3x2](m4m.math.pool.md#clone\_matrix3x2)
* [clone\_quaternion](m4m.math.pool.md#clone\_quaternion)
* [clone\_rect](m4m.math.pool.md#clone\_rect)
* [clone\_vector2](m4m.math.pool.md#clone\_vector2)
* [clone\_vector3](m4m.math.pool.md#clone\_vector3)
* [clone\_vector4](m4m.math.pool.md#clone\_vector4)
* [collect\_all](m4m.math.pool.md#collect\_all)
* [collect\_color](m4m.math.pool.md#collect\_color)
* [collect\_matrix](m4m.math.pool.md#collect\_matrix)
* [collect\_matrix3x2](m4m.math.pool.md#collect\_matrix3x2)
* [collect\_pickInfo](m4m.math.pool.md#collect\_pickinfo)
* [collect\_quaternion](m4m.math.pool.md#collect\_quaternion)
* [collect\_rect](m4m.math.pool.md#collect\_rect)
* [collect\_vector2](m4m.math.pool.md#collect\_vector2)
* [collect\_vector3](m4m.math.pool.md#collect\_vector3)
* [collect\_vector4](m4m.math.pool.md#collect\_vector4)
* [delete\_color](m4m.math.pool.md#delete\_color)
* [delete\_matrix](m4m.math.pool.md#delete\_matrix)
* [delete\_matrix3x2](m4m.math.pool.md#delete\_matrix3x2)
* [delete\_pickInfo](m4m.math.pool.md#delete\_pickinfo)
* [delete\_quaternion](m4m.math.pool.md#delete\_quaternion)
* [delete\_rect](m4m.math.pool.md#delete\_rect)
* [delete\_vector2](m4m.math.pool.md#delete\_vector2)
* [delete\_vector2Array](m4m.math.pool.md#delete\_vector2array)
* [delete\_vector3](m4m.math.pool.md#delete\_vector3)
* [delete\_vector3Array](m4m.math.pool.md#delete\_vector3array)
* [delete\_vector4](m4m.math.pool.md#delete\_vector4)
* [genHelpData](m4m.math.pool.md#genhelpdata)
* [new\_color](m4m.math.pool.md#new\_color)
* [new\_matrix](m4m.math.pool.md#new\_matrix)
* [new\_matrix3x2](m4m.math.pool.md#new\_matrix3x2)
* [new\_pickInfo](m4m.math.pool.md#new\_pickinfo)
* [new\_quaternion](m4m.math.pool.md#new\_quaternion)
* [new\_rect](m4m.math.pool.md#new\_rect)
* [new\_vector2](m4m.math.pool.md#new\_vector2)
* [new\_vector3](m4m.math.pool.md#new\_vector3)
* [new\_vector4](m4m.math.pool.md#new\_vector4)

#### Accessors

* [color\_one](m4m.math.pool.md#color\_one)
* [vector2\_right](m4m.math.pool.md#vector2\_right)
* [vector2\_up](m4m.math.pool.md#vector2\_up)
* [vector2\_zero](m4m.math.pool.md#vector2\_zero)
* [vector3\_forward](m4m.math.pool.md#vector3\_forward)
* [vector3\_one](m4m.math.pool.md#vector3\_one)
* [vector3\_right](m4m.math.pool.md#vector3\_right)
* [vector3\_up](m4m.math.pool.md#vector3\_up)
* [vector3\_zero](m4m.math.pool.md#vector3\_zero)
* [vector4\_one](m4m.math.pool.md#vector4\_one)

#### Properties

* [identityMat](m4m.math.pool.md#identitymat)

### Constructors

#### constructor

• **new pool**()

### Methods

#### clone\_color

▸ `Static` **clone\_color**(`col`): `color`

**`language`** zh\_CN

**`classdesc`** clone一个color

**`version`** m4m 1.0

**Parameters**

| Name  | Type    |
| ----- | ------- |
| `col` | `color` |

**Returns**

`color`

**Defined in**

[render/pool.ts:236](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L236)

***

#### clone\_matrix

▸ `Static` **clone\_matrix**(`src`): `matrix`

**`language`** zh\_CN

**`classdesc`** 带返回值的matrix克隆

**`version`** m4m 1.0

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `src` | `matrix` |

**Returns**

`matrix`

**Defined in**

[render/pool.ts:699](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L699)

***

#### clone\_matrix3x2

▸ `Static` **clone\_matrix3x2**(`src`): `matrix3x2`

**`language`** zh\_CN

**`classdesc`** 带返回值的3x2matrix克隆

**`version`** m4m 1.0

**Parameters**

| Name  | Type        |
| ----- | ----------- |
| `src` | `matrix3x2` |

**Returns**

`matrix3x2`

**Defined in**

[render/pool.ts:632](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L632)

***

#### clone\_quaternion

▸ `Static` **clone\_quaternion**(`src`): `quaternion`

**`language`** zh\_CN

**`classdesc`** 带返回值的quat克隆

**`version`** m4m 1.0

**Parameters**

| Name  | Type         |
| ----- | ------------ |
| `src` | `quaternion` |

**Returns**

`quaternion`

**Defined in**

[render/pool.ts:782](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L782)

***

#### clone\_rect

▸ `Static` **clone\_rect**(`src`): `rect`

**`language`** zh\_CN

**`classdesc`** 带返回值的rect克隆

**`version`** m4m 1.0

**Parameters**

| Name  | Type   |
| ----- | ------ |
| `src` | `rect` |

**Returns**

`rect`

**Defined in**

[render/pool.ts:911](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L911)

***

#### clone\_vector2

▸ `Static` **clone\_vector2**(`src`): `vector2`

**`language`** zh\_CN

**`classdesc`** 带返回值的v2克隆

**`version`** m4m 1.0

**Parameters**

| Name  | Type      |
| ----- | --------- |
| `src` | `vector2` |

**Returns**

`vector2`

**Defined in**

[render/pool.ts:541](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L541)

***

#### clone\_vector3

▸ `Static` **clone\_vector3**(`src`): `vector3`

**`language`** zh\_CN

**`classdesc`** 带返回值的v3克隆

**`version`** m4m 1.0

**Parameters**

| Name  | Type      |
| ----- | --------- |
| `src` | `vector3` |

**Returns**

`vector3`

**Defined in**

[render/pool.ts:398](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L398)

***

#### clone\_vector4

▸ `Static` **clone\_vector4**(`src`): `vector4`

**`language`** zh\_CN

**`classdesc`** 有返回值的v4克隆

**`version`** m4m 1.0

**Parameters**

| Name  | Type      |
| ----- | --------- |
| `src` | `vector4` |

**Returns**

`vector4`

**Defined in**

[render/pool.ts:146](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L146)

***

#### collect\_all

▸ `Static` **collect\_all**(): `void`

**`language`** zh\_CN

**`classdesc`** 释放所有池

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[render/pool.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L90)

***

#### collect\_color

▸ `Static` **collect\_color**(): `void`

**`language`** zh\_CN

**`classdesc`** 清除color池

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[render/pool.ts:277](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L277)

***

#### collect\_matrix

▸ `Static` **collect\_matrix**(): `void`

**`language`** zh\_CN

**`classdesc`** 清除matrix池

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[render/pool.ts:751](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L751)

***

#### collect\_matrix3x2

▸ `Static` **collect\_matrix3x2**(): `void`

**`language`** zh\_CN

**`classdesc`** 清除3x2matrix池

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[render/pool.ts:671](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L671)

***

#### collect\_pickInfo

▸ `Static` **collect\_pickInfo**(): `void`

**`language`** zh\_CN

**`classdesc`** 清除pickInfo池

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[render/pool.ts:879](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L879)

***

#### collect\_quaternion

▸ `Static` **collect\_quaternion**(): `void`

**`language`** zh\_CN

**`classdesc`** 清除quat池

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[render/pool.ts:823](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L823)

***

#### collect\_rect

▸ `Static` **collect\_rect**(): `void`

**`language`** zh\_CN

**`classdesc`** 清除rect池

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[render/pool.ts:949](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L949)

***

#### collect\_vector2

▸ `Static` **collect\_vector2**(): `void`

**`language`** zh\_CN

**`classdesc`** 清除v2池

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[render/pool.ts:603](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L603)

***

#### collect\_vector3

▸ `Static` **collect\_vector3**(): `void`

**`language`** zh\_CN

**`classdesc`** 清除v3池

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[render/pool.ts:457](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L457)

***

#### collect\_vector4

▸ `Static` **collect\_vector4**(): `void`

**`language`** zh\_CN

**`classdesc`** 清除v4池

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[render/pool.ts:187](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L187)

***

#### delete\_color

▸ `Static` **delete\_color**(`v`): `void`

**`language`** zh\_CN

**`classdesc`** 回收color

**`version`** m4m 1.0

**Parameters**

| Name | Type    |
| ---- | ------- |
| `v`  | `color` |

**Returns**

`void`

**Defined in**

[render/pool.ts:258](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L258)

***

#### delete\_matrix

▸ `Static` **delete\_matrix**(`v`): `void`

**`language`** zh\_CN

**`classdesc`** 回收一个matrix

**`version`** m4m 1.0

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `matrix` |

**Returns**

`void`

**Defined in**

[render/pool.ts:715](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L715)

***

#### delete\_matrix3x2

▸ `Static` **delete\_matrix3x2**(`v`): `void`

**`language`** zh\_CN

**`classdesc`** 回收一个3x2matrix

**`version`** m4m 1.0

**Parameters**

| Name | Type        |
| ---- | ----------- |
| `v`  | `matrix3x2` |

**Returns**

`void`

**Defined in**

[render/pool.ts:647](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L647)

***

#### delete\_pickInfo

▸ `Static` **delete\_pickInfo**(`v`): `void`

**`language`** zh\_CN

**`classdesc`** 回收一个pickInfo

**`version`** m4m 1.0

**Parameters**

| Name | Type       |
| ---- | ---------- |
| `v`  | `pickinfo` |

**Returns**

`void`

**Defined in**

[render/pool.ts:860](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L860)

***

#### delete\_quaternion

▸ `Static` **delete\_quaternion**(`v`): `void`

**`language`** zh\_CN

**`classdesc`** 回收一个quat

**`version`** m4m 1.0

**Parameters**

| Name | Type         |
| ---- | ------------ |
| `v`  | `quaternion` |

**Returns**

`void`

**Defined in**

[render/pool.ts:804](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L804)

***

#### delete\_rect

▸ `Static` **delete\_rect**(`v`): `void`

**`language`** zh\_CN

**`classdesc`** 回收一个rect

**`version`** m4m 1.0

**Parameters**

| Name | Type   |
| ---- | ------ |
| `v`  | `rect` |

**Returns**

`void`

**Defined in**

[render/pool.ts:930](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L930)

***

#### delete\_vector2

▸ `Static` **delete\_vector2**(`v`): `void`

**`language`** zh\_CN

**`classdesc`** 回收一个v2

**`version`** m4m 1.0

**Parameters**

| Name | Type      |
| ---- | --------- |
| `v`  | `vector2` |

**Returns**

`void`

**Defined in**

[render/pool.ts:567](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L567)

***

#### delete\_vector2Array

▸ `Static` **delete\_vector2Array**(`vs`): `void`

**`language`** zh\_CN

**`classdesc`** 回收一个v2数组

**`version`** m4m 1.0

**Parameters**

| Name | Type         |
| ---- | ------------ |
| `vs` | `vector2`\[] |

**Returns**

`void`

**Defined in**

[render/pool.ts:585](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L585)

***

#### delete\_vector3

▸ `Static` **delete\_vector3**(`v`): `void`

**`language`** zh\_CN

**`classdesc`** 回收一个v3

**`version`** m4m 1.0

**Parameters**

| Name | Type      |
| ---- | --------- |
| `v`  | `vector3` |

**Returns**

`void`

**Defined in**

[render/pool.ts:419](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L419)

***

#### delete\_vector3Array

▸ `Static` **delete\_vector3Array**(`vs`): `void`

**`language`** zh\_CN

**`classdesc`** 回收一个v3数组

**`version`** m4m 1.0

**Parameters**

| Name | Type         |
| ---- | ------------ |
| `vs` | `vector3`\[] |

**Returns**

`void`

**Defined in**

[render/pool.ts:438](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L438)

***

#### delete\_vector4

▸ `Static` **delete\_vector4**(`v`): `void`

**`language`** zh\_CN

**`classdesc`** 回收一个v4

**`version`** m4m 1.0

**Parameters**

| Name | Type      |
| ---- | --------- |
| `v`  | `vector4` |

**Returns**

`void`

**Defined in**

[render/pool.ts:168](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L168)

***

#### genHelpData

▸ `Static` **genHelpData**(`type`, `id`): `any`

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `type` | `string` |
| `id`   | `number` |

**Returns**

`any`

**Defined in**

[render/pool.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L57)

***

#### new\_color

▸ `Static` **new\_color**(`r?`, `g?`, `b?`, `a?`): `color`

**`language`** zh\_CN

**`classdesc`** 获取一个color

**`version`** m4m 1.0

**Parameters**

| Name | Type     | Default value |
| ---- | -------- | ------------- |
| `r`  | `number` | `0`           |
| `g`  | `number` | `0`           |
| `b`  | `number` | `0`           |
| `a`  | `number` | `0`           |

**Returns**

`color`

**Defined in**

[render/pool.ts:218](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L218)

***

#### new\_matrix

▸ `Static` **new\_matrix**(): `matrix`

**`language`** zh\_CN

**`classdesc`** 获取一个matrix

**`version`** m4m 1.0

**Returns**

`matrix`

**Defined in**

[render/pool.ts:685](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L685)

***

#### new\_matrix3x2

▸ `Static` **new\_matrix3x2**(): `matrix3x2`

**`language`** zh\_CN

**`classdesc`** 获取一个3x2matrix

**`version`** m4m 1.0

**Returns**

`matrix3x2`

**Defined in**

[render/pool.ts:618](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L618)

***

#### new\_pickInfo

▸ `Static` **new\_pickInfo**(`bu?`, `bv?`, `distance?`): `pickinfo`

**`language`** zh\_CN

**`classdesc`** 获取一个pickInfo

**`version`** m4m 1.0

**Parameters**

| Name       | Type     | Default value |
| ---------- | -------- | ------------- |
| `bu`       | `number` | `0`           |
| `bv`       | `number` | `0`           |
| `distance` | `number` | `0`           |

**Returns**

`pickinfo`

**Defined in**

[render/pool.ts:839](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L839)

***

#### new\_quaternion

▸ `Static` **new\_quaternion**(`x?`, `y?`, `z?`, `w?`): `quaternion`

**`language`** zh\_CN

**`classdesc`** 获取一个quat

**`version`** m4m 1.0

**Parameters**

| Name | Type     | Default value |
| ---- | -------- | ------------- |
| `x`  | `number` | `0`           |
| `y`  | `number` | `0`           |
| `z`  | `number` | `0`           |
| `w`  | `number` | `1`           |

**Returns**

`quaternion`

**Defined in**

[render/pool.ts:765](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L765)

***

#### new\_rect

▸ `Static` **new\_rect**(`x?`, `y?`, `w?`, `h?`): `rect`

**`language`** zh\_CN

**`classdesc`** 获取一个rect

**`version`** m4m 1.0

**Parameters**

| Name | Type     | Default value |
| ---- | -------- | ------------- |
| `x`  | `number` | `0`           |
| `y`  | `number` | `0`           |
| `w`  | `number` | `0`           |
| `h`  | `number` | `0`           |

**Returns**

`rect`

**Defined in**

[render/pool.ts:893](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L893)

***

#### new\_vector2

▸ `Static` **new\_vector2**(`x?`, `y?`): `vector2`

**`language`** zh\_CN

**`classdesc`** 获取一个v2

**`version`** m4m 1.0

**Parameters**

| Name | Type     | Default value |
| ---- | -------- | ------------- |
| `x`  | `number` | `0`           |
| `y`  | `number` | `0`           |

**Returns**

`vector2`

**Defined in**

[render/pool.ts:523](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L523)

***

#### new\_vector3

▸ `Static` **new\_vector3**(`x?`, `y?`, `z?`): `vector3`

**`language`** zh\_CN

**`classdesc`** 获取一个v3

**`version`** m4m 1.0

**Parameters**

| Name | Type     | Default value |
| ---- | -------- | ------------- |
| `x`  | `number` | `0`           |
| `y`  | `number` | `0`           |
| `z`  | `number` | `0`           |

**Returns**

`vector3`

**Defined in**

[render/pool.ts:380](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L380)

***

#### new\_vector4

▸ `Static` **new\_vector4**(`x?`, `y?`, `z?`, `w?`): `vector4`

**`language`** zh\_CN

**`classdesc`** 获取一个v4

**`version`** m4m 1.0

**Parameters**

| Name | Type     | Default value |
| ---- | -------- | ------------- |
| `x`  | `number` | `0`           |
| `y`  | `number` | `0`           |
| `z`  | `number` | `0`           |
| `w`  | `number` | `0`           |

**Returns**

`vector4`

**Defined in**

[render/pool.ts:128](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L128)

### Accessors

#### color\_one

• `Static` `get` **color\_one**(): `color`

**`language`** zh\_CN

**`classdesc`** 获取1填充的color

**`version`** m4m 1.0

**Returns**

`color`

**Defined in**

[render/pool.ts:201](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L201)

***

#### vector2\_right

• `Static` `get` **vector2\_right**(): `vector2`

**`language`** zh\_CN

**`classdesc`** 获取v2朝x轴正向

**`version`** m4m 1.0

**Returns**

`vector2`

**Defined in**

[render/pool.ts:506](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L506)

***

#### vector2\_up

• `Static` `get` **vector2\_up**(): `vector2`

**`language`** zh\_CN

**`classdesc`** 获取v2朝y轴正向

**`version`** m4m 1.0

**Returns**

`vector2`

**Defined in**

[render/pool.ts:489](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L489)

***

#### vector2\_zero

• `Static` `get` **vector2\_zero**(): `vector2`

**`language`** zh\_CN

**`classdesc`** 获取v2 zero

**`version`** m4m 1.0

**Returns**

`vector2`

**Defined in**

[render/pool.ts:471](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L471)

***

#### vector3\_forward

• `Static` `get` **vector3\_forward**(): `vector3`

**`language`** zh\_CN

**`classdesc`** 获取v3朝z轴正向

**`version`** m4m 1.0

**Returns**

`vector3`

**Defined in**

[render/pool.ts:327](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L327)

***

#### vector3\_one

• `Static` `get` **vector3\_one**(): `vector3`

**`language`** zh\_CN

**`classdesc`** 获取1填充的v3

**`version`** m4m 1.0

**Returns**

`vector3`

**Defined in**

[render/pool.ts:362](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L362)

***

#### vector3\_right

• `Static` `get` **vector3\_right**(): `vector3`

**`language`** zh\_CN

**`classdesc`** 获取v3朝x轴正向

**`version`** m4m 1.0

**Returns**

`vector3`

**Defined in**

[render/pool.ts:309](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L309)

***

#### vector3\_up

• `Static` `get` **vector3\_up**(): `vector3`

**`language`** zh\_CN

**`classdesc`** 获取v3朝y轴正向

**`version`** m4m 1.0

**Returns**

`vector3`

**Defined in**

[render/pool.ts:291](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L291)

***

#### vector3\_zero

• `Static` `get` **vector3\_zero**(): `vector3`

**`language`** zh\_CN

**`classdesc`** 获取0填充的v3

**`version`** m4m 1.0

**Returns**

`vector3`

**Defined in**

[render/pool.ts:345](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L345)

***

#### vector4\_one

• `Static` `get` **vector4\_one**(): `vector4`

**`language`** zh\_CN

**`classdesc`** 获取1填充的v4

**`version`** m4m 1.0

**Returns**

`vector4`

**Defined in**

[render/pool.ts:110](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L110)

### Properties

#### identityMat

▪ `Static` `Readonly` **identityMat**: `matrix`

**Defined in**

[render/pool.ts:707](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/pool.ts#L707)
