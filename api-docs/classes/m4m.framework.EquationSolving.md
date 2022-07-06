# m4m.framework.EquationSolving

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / EquationSolving

## Class: EquationSolving

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).EquationSolving

方程求解

求解方程 f(x) == 0 在\[a, b]上的解

参考：高等数学 第七版上册 第三章第八节 方程的近似解 当f(x)在区间 \[a, b] 上连续，且f(a) \* f(b) <= 0 时，f(x)在区间 \[a, b] 上至少存在一个解使得 f(x) == 0

当f(x)在区间 \[a, b] 上连续，且 (f(a) - y) \* (f(b) - y) < 0 时，f(x)在区间 \[a, b] 上至少存在一个解使得 f(x) == y

**`author`** feng / http://feng3d.com 05/06/2018

### Table of contents

#### Constructors

* [constructor](m4m.framework.EquationSolving.md#constructor)

#### Methods

* [getDerivative](m4m.framework.EquationSolving.md#getderivative)
* [line](m4m.framework.EquationSolving.md#line)

### Constructors

#### constructor

• **new EquationSolving**()

### Methods

#### getDerivative

▸ `Static` **getDerivative**(`f`, `delta?`): (`x`: `number`) => `number`

获取近似导函数 f'(x)

导函数定义 f'(x) = (f(x + Δx) - f(x)) / Δx , Δx → 0

注：通过测试Δx不能太小，由于方程内存在x的n次方问题（比如0.000000000000001的10次方为0），过小会导致计算机计算进度不够反而导致求导不准确！

另外一种办法是还原一元多次函数，然后求出导函数。

**Parameters**

| Name    | Type                        | Default value | Description                                  |
| ------- | --------------------------- | ------------- | -------------------------------------------- |
| `f`     | (`x`: `number`) => `number` | `undefined`   | 函数                                           |
| `delta` | `number`                    | `0.000000001` | Δx，进过测试该值太小或者过大都会导致求导准确率降低（个人猜测是计算机计算精度问题导致） |

**Returns**

`fn`

▸ (`x`): `number`

**Parameters**

| Name | Type     |
| ---- | -------- |
| `x`  | `number` |

**Returns**

`number`

**Defined in**

[framework/math/EquationSolving.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/EquationSolving.ts#L51)

***

#### line

▸ `Static` **line**(`f`, `a`, `b`, `precision?`, `errorcallback?`): `number`

连线法 求解 f(x) == 0

连线法是我自己想的方法，自己取的名字，目前没有找到相应的资料（这方法大家都能够想得到。）

用曲线弧两端的连线来代替曲线弧与X轴交点作为边界来逐步缩小求解区间，最终获得解

通过 A，B两点连线与x轴交点来缩小求解区间最终获得解

A，B两点直线方程 f(x) = f(a) + (f(b) - f(a)) / (b - a) \* (x-a) ,求 f(x) == 0 解得 x = a - fa \* (b - a)/ (fb - fa)

**Parameters**

| Name             | Type                        | Default value | Description |
| ---------------- | --------------------------- | ------------- | ----------- |
| `f`              | (`x`: `number`) => `number` | `undefined`   | 函数f(x)      |
| `a`              | `number`                    | `undefined`   | 区间起点        |
| `b`              | `number`                    | `undefined`   | 区间终点        |
| `precision`      | `number`                    | `0.0000001`   | 求解精度        |
| `errorcallback?` | (`err`: `Error`) => `void`  | `undefined`   | 错误回调函数      |

**Returns**

`number`

不存在解时返回 undefined ，存在时返回 解

**Defined in**

[framework/math/EquationSolving.ts:117](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/EquationSolving.ts#L117)
