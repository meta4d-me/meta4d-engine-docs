# m4m.math.RotationOrder

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [math](../modules/m4m.math.md) / RotationOrder

## Enumeration: RotationOrder

[m4m](../modules/m4m.md).[math](../modules/m4m.math.md).RotationOrder

用于表示欧拉角的旋转顺序

如果顺序为XYZ，则依次按 ZYZ 轴旋转。为什么循序与定义相反？因为three.js中都这么定义，他们为什么这么定义就不清楚了。

### Table of contents

#### Enumeration Members

* [XYZ](m4m.math.RotationOrder.md#xyz)
* [XZY](m4m.math.RotationOrder.md#xzy)
* [YXZ](m4m.math.RotationOrder.md#yxz)
* [YZX](m4m.math.RotationOrder.md#yzx)
* [ZXY](m4m.math.RotationOrder.md#zxy)
* [ZYX](m4m.math.RotationOrder.md#zyx)

### Enumeration Members

#### XYZ

• **XYZ**

依次按 ZYX 轴旋转。

three.js默认旋转顺序。

**Defined in**

[framework/math/RotationOrder.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/RotationOrder.ts#L16)

***

#### XZY

• **XZY**

依次按 YZX 轴旋转。

**Defined in**

[framework/math/RotationOrder.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/RotationOrder.ts#L40)

***

#### YXZ

• **YXZ**

依次按 ZXY 轴旋转。

unity默认旋转顺序。

**Defined in**

[framework/math/RotationOrder.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/RotationOrder.ts#L32)

***

#### YZX

• **YZX**

依次按 XZY 轴旋转。

**Defined in**

[framework/math/RotationOrder.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/RotationOrder.ts#L36)

***

#### ZXY

• **ZXY**

依次按 YXZ 轴旋转。

**Defined in**

[framework/math/RotationOrder.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/RotationOrder.ts#L20)

***

#### ZYX

• **ZYX**

依次按 XYZ 轴旋转。

playcanvas默认旋转顺序。

**Defined in**

[framework/math/RotationOrder.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/RotationOrder.ts#L26)
