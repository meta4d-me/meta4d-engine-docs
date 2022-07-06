# m4m.framework.Noise

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / Noise

## Class: Noise

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).Noise

柏林噪音

用于生产随机的噪音贴图

**`see`** http://staffwww.itn.liu.se/\~stegu/simplexnoise/simplexnoise.pdf

**`see`** https://mrl.nyu.edu/\~perlin/noise/

**`see`** https://gitee.com/feng3d\_admin/noise

### Table of contents

#### Constructors

* [constructor](m4m.framework.Noise.md#constructor)

#### Methods

* [perlin1](m4m.framework.Noise.md#perlin1)
* [perlin2](m4m.framework.Noise.md#perlin2)
* [perlin3](m4m.framework.Noise.md#perlin3)
* [perlinN](m4m.framework.Noise.md#perlinn)

#### Accessors

* [seed](m4m.framework.Noise.md#seed)

### Constructors

#### constructor

• **new Noise**(`seed?`)

构建柏林噪音

**Parameters**

| Name   | Type     | Default value | Description |
| ------ | -------- | ------------- | ----------- |
| `seed` | `number` | `0`           | 随机种子        |

**Defined in**

[framework/math/Noise.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/Noise.ts#L24)

### Methods

#### perlin1

▸ **perlin1**(`x`): `number`

1D 经典噪音

**Parameters**

| Name | Type     | Description |
| ---- | -------- | ----------- |
| `x`  | `number` | X轴数值        |

**Returns**

`number`

**Defined in**

[framework/math/Noise.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/Noise.ts#L34)

***

#### perlin2

▸ **perlin2**(`x`, `y`): `number`

2D 经典噪音

**Parameters**

| Name | Type     | Description |
| ---- | -------- | ----------- |
| `x`  | `number` | X轴数值        |
| `y`  | `number` | Y轴数值        |

**Returns**

`number`

**Defined in**

[framework/math/Noise.ts:67](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/Noise.ts#L67)

***

#### perlin3

▸ **perlin3**(`x`, `y`, `z`): `number`

3D 经典噪音

**Parameters**

| Name | Type     | Description |
| ---- | -------- | ----------- |
| `x`  | `number` | X轴数值        |
| `y`  | `number` | Y轴数值        |
| `z`  | `number` | Z轴数值        |

**Returns**

`number`

**Defined in**

[framework/math/Noise.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/Noise.ts#L112)

***

#### perlinN

▸ **perlinN**(...`ps`): `number`

N阶经典噪音

如果是1D，2D，3D噪音，最好选用对于函数，perlinN中存在for循环因此效率比perlin3等性能差3到5（8）倍！

满足以下运算 perlinN(x) == perlin1(x) perlinN(x,y) == perlin2(x,y) perlinN(x,y,z) == perlin3(x,y,z)

**Parameters**

| Name    | Type        | Description |
| ------- | ----------- | ----------- |
| `...ps` | `number`\[] | 每个轴的数值      |

**Returns**

`number`

**Defined in**

[framework/math/Noise.ts:179](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/Noise.ts#L179)

### Accessors

#### seed

• `get` **seed**(): `number`

This isn't a very good seeding function, but it works ok. It supports 2^16 different seed values. Write something better if you need more seeds.

**Returns**

`number`

**Defined in**

[framework/math/Noise.ts:268](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/Noise.ts#L268)

• `set` **seed**(`v`): `void`

This isn't a very good seeding function, but it works ok. It supports 2^16 different seed values. Write something better if you need more seeds.

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/math/Noise.ts:272](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/Noise.ts#L272)
