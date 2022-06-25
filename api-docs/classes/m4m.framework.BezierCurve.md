[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / BezierCurve

# Class: BezierCurve

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).BezierCurve

Bézier曲线

**`see`** https://en.wikipedia.org/wiki/B%C3%A9zier_curve

**`author`** feng3d

## Table of contents

### Constructors

- [constructor](m4m.framework.BezierCurve.md#constructor)

### Methods

- [bn](m4m.framework.BezierCurve.md#bn)
- [bnDerivative](m4m.framework.BezierCurve.md#bnderivative)
- [bnND](m4m.framework.BezierCurve.md#bnnd)
- [bnSecondDerivative](m4m.framework.BezierCurve.md#bnsecondderivative)
- [cubic](m4m.framework.BezierCurve.md#cubic)
- [cubicDerivative](m4m.framework.BezierCurve.md#cubicderivative)
- [cubicSecondDerivative](m4m.framework.BezierCurve.md#cubicsecondderivative)
- [getDerivative](m4m.framework.BezierCurve.md#getderivative)
- [getExtremums](m4m.framework.BezierCurve.md#getextremums)
- [getMonotoneIntervals](m4m.framework.BezierCurve.md#getmonotoneintervals)
- [getSamples](m4m.framework.BezierCurve.md#getsamples)
- [getSecondDerivative](m4m.framework.BezierCurve.md#getsecondderivative)
- [getTFromValue](m4m.framework.BezierCurve.md#gettfromvalue)
- [getValue](m4m.framework.BezierCurve.md#getvalue)
- [linear](m4m.framework.BezierCurve.md#linear)
- [linearDerivative](m4m.framework.BezierCurve.md#linearderivative)
- [linearSecondDerivative](m4m.framework.BezierCurve.md#linearsecondderivative)
- [merge](m4m.framework.BezierCurve.md#merge)
- [quadratic](m4m.framework.BezierCurve.md#quadratic)
- [quadraticDerivative](m4m.framework.BezierCurve.md#quadraticderivative)
- [quadraticSecondDerivative](m4m.framework.BezierCurve.md#quadraticsecondderivative)
- [split](m4m.framework.BezierCurve.md#split)

## Constructors

### constructor

• **new BezierCurve**()

## Methods

### bn

▸ `Static` **bn**(`t`, `ps`, `processs?`): `number`

n次Bézier曲线

一般定义

Bézier曲线可以定义为任意度n。

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `t` | `number` | `undefined` | 插值度 |
| `ps` | `number`[] | `undefined` | 点列表 ps.length == n+1 |
| `processs` | `number`[][] | `null` | 收集中间过程数据，可用作Bézier曲线动画数据 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:189](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L189)

___

### bnDerivative

▸ `Static` **bnDerivative**(`t`, `ps`): `number`

n次Bézier曲线关于t的导数

一般定义

Bézier曲线可以定义为任意度n。

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `ps` | `number`[] | 点列表 ps.length == n+1 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:220](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L220)

___

### bnND

▸ `Static` **bnND**(`t`, `dn`, `ps`): `number`

n次Bézier曲线关于t的dn阶导数

Bézier曲线可以定义为任意度n。

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `dn` | `number` | 求导次数 |
| `ps` | `number`[] | 点列表     ps.length == n+1 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:271](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L271)

___

### bnSecondDerivative

▸ `Static` **bnSecondDerivative**(`t`, `ps`): `number`

n次Bézier曲线关于t的二阶导数

一般定义

Bézier曲线可以定义为任意度n。

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `ps` | `number`[] | 点列表 ps.length == n+1 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:246](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L246)

___

### cubic

▸ `Static` **cubic**(`t`, `p0`, `p1`, `p2`, `p3`): `number`

立方Bézier曲线

平面中或高维空间中（其实一维也是成立的，这里就是使用一维计算）的四个点P0，P1，P2和P3定义了三次Bézier曲线。
曲线开始于P0朝向P1并且从P2的方向到达P3。通常不会通过P1或P2; 这些点只是为了提供方向信息。
P1和P2之间的距离在转向P2之前确定曲线向P1移动的“多远”和“多快” 。

对于由点Pi，Pj和Pk定义的二次Bézier曲线，可以将Bpipjpk(t)写成三次Bézier曲线，它可以定义为两条二次Bézier曲线的仿射组合：
```
B(t) = (1 - t) * Bp0p1p2(t) + t * Bp1p2p3(t) , 0 <= t && t <= 1
```
曲线的显式形式是：
```
B(t) = (1 - t) * (1 - t) * (1 - t) * p0 + 3 * (1 - t) * (1 - t) * t * p1 + 3 * (1 - t) * t * t * p2 + t * t * t * p3 , 0 <= t && t <= 1
```
对于P1和P2的一些选择，曲线可以相交，或者包含尖点。

三次Bézier曲线相对于t的导数是
```
B'(t) = 3 * (1 - t) * (1 - t) * (p1 - p0) + 6 * (1 - t) * t * (p2 - p1) + 3 * t * t * (p3 - p2);
```
三次Bézier曲线关于t的二阶导数是
```
6 * (1 - t) * (p2 - 2 * p1 + p0) + 6 * t * (p3 - 2 * p2 + p1);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `p0` | `number` | 点0 |
| `p1` | `number` | 点1 |
| `p2` | `number` | 点2 |
| `p3` | `number` | 点3 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:145](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L145)

___

### cubicDerivative

▸ `Static` **cubicDerivative**(`t`, `p0`, `p1`, `p2`, `p3`): `number`

三次Bézier曲线关于t的导数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `p0` | `number` | 点0 |
| `p1` | `number` | 点1 |
| `p2` | `number` | 点2 |
| `p3` | `number` | 点3 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:159](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L159)

___

### cubicSecondDerivative

▸ `Static` **cubicSecondDerivative**(`t`, `p0`, `p1`, `p2`, `p3`): `number`

三次Bézier曲线关于t的二阶导数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `p0` | `number` | 点0 |
| `p1` | `number` | 点1 |
| `p2` | `number` | 点2 |
| `p3` | `number` | - |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:172](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L172)

___

### getDerivative

▸ `Static` **getDerivative**(`t`, `ps`): `number`

获取曲线在指定插值度上的导数(斜率)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `ps` | `number`[] | 点列表 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:321](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L321)

___

### getExtremums

▸ `Static` **getExtremums**(`ps`, `numSamples?`, `precision?`): `Object`

查找区间内极值列表

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `ps` | `number`[] | `undefined` | 点列表 |
| `numSamples` | `number` | `10` | 采样次数，用于分段查找极值 |
| `precision` | `number` | `0.0000001` | 查找精度 |

#### Returns

`Object`

极值列表 {} {ts: 极值插值度列表,vs: 极值值列表}

| Name | Type |
| :------ | :------ |
| `ts` | `number`[] |
| `vs` | `number`[] |

#### Defined in

[framework/util/curve/BezierCurve.ts:371](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L371)

___

### getMonotoneIntervals

▸ `Static` **getMonotoneIntervals**(`ps`, `numSamples?`, `precision?`): `Object`

获取单调区间列表

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `ps` | `number`[] | `undefined` |
| `numSamples` | `number` | `10` |
| `precision` | `number` | `0.0000001` |

#### Returns

`Object`

{ts: 区间结点插值度列表,vs: 区间结点值列表}

| Name | Type |
| :------ | :------ |
| `ts` | `number`[] |
| `vs` | `number`[] |

#### Defined in

[framework/util/curve/BezierCurve.ts:398](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L398)

___

### getSamples

▸ `Static` **getSamples**(`ps`, `num?`): { `t`: `number` ; `v`: `number`  }[]

获取曲线样本数据

这些点可用于连线来拟合曲线。

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `ps` | `number`[] | `undefined` | 点列表 |
| `num` | `number` | `100` | 采样次数 ，采样点分别为[0,1/num,2/num,....,(num-1)/num,1] |

#### Returns

{ `t`: `number` ; `v`: `number`  }[]

#### Defined in

[framework/util/curve/BezierCurve.ts:578](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L578)

___

### getSecondDerivative

▸ `Static` **getSecondDerivative**(`t`, `ps`): `number`

获取曲线在指定插值度上的二阶导数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `ps` | `number`[] | 点列表 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:344](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L344)

___

### getTFromValue

▸ `Static` **getTFromValue**(`targetV`, `ps`, `numSamples?`, `precision?`): `number`[]

获取目标值所在的插值度T

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `targetV` | `number` | `undefined` | 目标值 |
| `ps` | `number`[] | `undefined` | 点列表 |
| `numSamples` | `number` | `10` | 分段数量，用于分段查找，用于解决寻找多个解、是否无解等问题；过少的分段可能会造成找不到存在的解决，过多的分段将会造成性能很差。 |
| `precision` | `number` | `0.0000001` | 查找精度 |

#### Returns

`number`[]

返回解数组

#### Defined in

[framework/util/curve/BezierCurve.ts:424](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L424)

___

### getValue

▸ `Static` **getValue**(`t`, `ps`): `number`

获取曲线在指定插值度上的值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `ps` | `number`[] | 点列表 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:297](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L297)

___

### linear

▸ `Static` **linear**(`t`, `p0`, `p1`): `number`

线性Bézier曲线
给定不同的点P0和P1，线性Bézier曲线就是这两个点之间的直线。曲线由下式给出
```
B(t) = p0 + t * (p1 - p0) = (1 - t) * p0 + t * p1 , 0 <= t && t <= 1
```
相当于线性插值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `p0` | `number` | 点0 |
| `p1` | `number` | 点1 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L24)

___

### linearDerivative

▸ `Static` **linearDerivative**(`t`, `p0`, `p1`): `number`

线性Bézier曲线关于t的导数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `p0` | `number` | 点0 |
| `p1` | `number` | 点1 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L36)

___

### linearSecondDerivative

▸ `Static` **linearSecondDerivative**(`t`, `p0`, `p1`): `number`

线性Bézier曲线关于t的二阶导数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `p0` | `number` | 点0 |
| `p1` | `number` | 点1 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L47)

___

### merge

▸ `Static` **merge**(`fps`, `sps`, `mergeType?`): `number`[]

合并曲线

合并两条连接的曲线为一条曲线并且可以还原为分割前的曲线

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `fps` | `number`[] | `undefined` | 第一条曲线点列表 |
| `sps` | `number`[] | `undefined` | 第二条曲线点列表 |
| `mergeType` | `number` | `0` | 合并方式。mergeType = 0时进行还原合并，还原拆分之前的曲线；mergeType = 1时进行拟合合并，合并后的曲线会经过两条曲线的连接点； |

#### Returns

`number`[]

#### Defined in

[framework/util/curve/BezierCurve.ts:494](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L494)

___

### quadratic

▸ `Static` **quadratic**(`t`, `p0`, `p1`, `p2`): `number`

二次Bézier曲线

二次Bézier曲线是由函数B（t）跟踪的路径，给定点P0，P1和P2，
```
B(t) = (1 - t) * ((1 - t) * p0 + t * p1) + t * ((1 - t) * p1 + t * p2) , 0 <= t && t <= 1
```
这可以解释为分别从P0到P1和从P1到P2的线性Bézier曲线上相应点的线性插值。重新排列前面的等式得出：
```
B(t) = (1 - t) * (1 - t) * p0 + 2 * (1 - t) * t * p1 + t * t * p2 , 0 <= t && t <= 1
```
Bézier曲线关于t的导数是
```
B'(t) = 2 * (1 - t) * (p1 - p0) + 2 * t * (p2 - p1)
```
从中可以得出结论：在P0和P2处曲线的切线在P 1处相交。随着t从0增加到1，曲线沿P1的方向从P0偏离，然后从P1的方向弯曲到P2。

Bézier曲线关于t的二阶导数是
```
B''(t) = 2 * (p2 - 2 * p1 + p0)
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `p0` | `number` | 点0 |
| `p1` | `number` | 点1 |
| `p2` | `number` | 点2 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L79)

___

### quadraticDerivative

▸ `Static` **quadraticDerivative**(`t`, `p0`, `p1`, `p2`): `number`

二次Bézier曲线关于t的导数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `p0` | `number` | 点0 |
| `p1` | `number` | 点1 |
| `p2` | `number` | 点2 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L93)

___

### quadraticSecondDerivative

▸ `Static` **quadraticSecondDerivative**(`t`, `p0`, `p1`, `p2`): `number`

二次Bézier曲线关于t的二阶导数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 插值度 |
| `p0` | `number` | 点0 |
| `p1` | `number` | 点1 |
| `p2` | `number` | 点2 |

#### Returns

`number`

#### Defined in

[framework/util/curve/BezierCurve.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L106)

___

### split

▸ `Static` **split**(`t`, `ps`): `number`[][]

分割曲线

在曲线插值度t位置分割为两条连接起来与原曲线完全重合的曲线

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `t` | `number` | 分割位置（插值度） |
| `ps` | `number`[] | 被分割曲线点列表 |

#### Returns

`number`[][]

返回两条曲线组成的数组

#### Defined in

[framework/util/curve/BezierCurve.ts:457](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/curve/BezierCurve.ts#L457)
