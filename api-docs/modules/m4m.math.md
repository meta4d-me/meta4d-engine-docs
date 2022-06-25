[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](m4m.md) / math

# Namespace: math

[m4m](m4m.md).math

## Table of contents

### Functions

- [Byte](m4m.math.md#byte)
- [Double](m4m.math.md#double)
- [Float](m4m.math.md#float)
- [GetPointAlongCurve](m4m.math.md#getpointalongcurve)
- [Int16](m4m.math.md#int16)
- [Int32](m4m.math.md#int32)
- [Multiply](m4m.math.md#multiply)
- [UByte](m4m.math.md#ubyte)
- [UInt16](m4m.math.md#uint16)
- [UInt32](m4m.math.md#uint32)
- [caclStringByteLength](m4m.math.md#caclstringbytelength)
- [calPlaneLineIntersectPoint](m4m.math.md#calplanelineintersectpoint)
- [colorClone](m4m.math.md#colorclone)
- [colorFormJson](m4m.math.md#colorformjson)
- [colorLerp](m4m.math.md#colorlerp)
- [colorMultiply](m4m.math.md#colormultiply)
- [colorSet](m4m.math.md#colorset)
- [colorSet\_Black](m4m.math.md#colorset_black)
- [colorSet\_Gray](m4m.math.md#colorset_gray)
- [colorSet\_White](m4m.math.md#colorset_white)
- [colorToCSS](m4m.math.md#colortocss)
- [count](m4m.math.md#count)
- [countEnd](m4m.math.md#countend)
- [countStart](m4m.math.md#countstart)
- [degToRad](m4m.math.md#degtorad)
- [floatClamp](m4m.math.md#floatclamp)
- [floatFormat](m4m.math.md#floatformat)
- [getKeyCodeByAscii](m4m.math.md#getkeycodebyascii)
- [isContain](m4m.math.md#iscontain)
- [mapLinear](m4m.math.md#maplinear)
- [matrix2Quaternion](m4m.math.md#matrix2quaternion)
- [matrix3x2Clone](m4m.math.md#matrix3x2clone)
- [matrix3x2Decompose](m4m.math.md#matrix3x2decompose)
- [matrix3x2Equal](m4m.math.md#matrix3x2equal)
- [matrix3x2Inverse](m4m.math.md#matrix3x2inverse)
- [matrix3x2MakeIdentity](m4m.math.md#matrix3x2makeidentity)
- [matrix3x2MakeRotate](m4m.math.md#matrix3x2makerotate)
- [matrix3x2MakeScale](m4m.math.md#matrix3x2makescale)
- [matrix3x2MakeTransformRTS](m4m.math.md#matrix3x2maketransformrts)
- [matrix3x2MakeTranslate](m4m.math.md#matrix3x2maketranslate)
- [matrix3x2Multiply](m4m.math.md#matrix3x2multiply)
- [matrix3x2TransformNormal](m4m.math.md#matrix3x2transformnormal)
- [matrix3x2TransformVector2](m4m.math.md#matrix3x2transformvector2)
- [matrixAdd](m4m.math.md#matrixadd)
- [matrixClone](m4m.math.md#matrixclone)
- [matrixDecompose](m4m.math.md#matrixdecompose)
- [matrixEqual](m4m.math.md#matrixequal)
- [matrixGetEuler](m4m.math.md#matrixgeteuler)
- [matrixGetRotation](m4m.math.md#matrixgetrotation)
- [matrixGetScale](m4m.math.md#matrixgetscale)
- [matrixGetTranslation](m4m.math.md#matrixgettranslation)
- [matrixGetVector3ByOffset](m4m.math.md#matrixgetvector3byoffset)
- [matrixInverse](m4m.math.md#matrixinverse)
- [matrixIsIdentity](m4m.math.md#matrixisidentity)
- [matrixLerp](m4m.math.md#matrixlerp)
- [matrixLookat](m4m.math.md#matrixlookat)
- [matrixLookatLH](m4m.math.md#matrixlookatlh)
- [matrixMakeEuler](m4m.math.md#matrixmakeeuler)
- [matrixMakeIdentity](m4m.math.md#matrixmakeidentity)
- [matrixMakeRotateAxisAngle](m4m.math.md#matrixmakerotateaxisangle)
- [matrixMakeScale](m4m.math.md#matrixmakescale)
- [matrixMakeTransformRTS](m4m.math.md#matrixmaketransformrts)
- [matrixMakeTranslate](m4m.math.md#matrixmaketranslate)
- [matrixMultiply](m4m.math.md#matrixmultiply)
- [matrixProject\_OrthoLH](m4m.math.md#matrixproject_ortholh)
- [matrixProject\_PerspectiveLH](m4m.math.md#matrixproject_perspectivelh)
- [matrixReset](m4m.math.md#matrixreset)
- [matrixScaleByNum](m4m.math.md#matrixscalebynum)
- [matrixTransformNormal](m4m.math.md#matrixtransformnormal)
- [matrixTransformVector3](m4m.math.md#matrixtransformvector3)
- [matrixTransformVector4](m4m.math.md#matrixtransformvector4)
- [matrixTranspose](m4m.math.md#matrixtranspose)
- [matrixViewLookatLH](m4m.math.md#matrixviewlookatlh)
- [matrixZero](m4m.math.md#matrixzero)
- [myLookRotation](m4m.math.md#mylookrotation)
- [numberLerp](m4m.math.md#numberlerp)
- [quat2LookRotation](m4m.math.md#quat2lookrotation)
- [quat2Lookat](m4m.math.md#quat2lookat)
- [quatClone](m4m.math.md#quatclone)
- [quatEqual](m4m.math.md#quatequal)
- [quatFromAxisAngle](m4m.math.md#quatfromaxisangle)
- [quatFromEulerAngles](m4m.math.md#quatfromeulerangles)
- [quatFromYawPitchRoll](m4m.math.md#quatfromyawpitchroll)
- [quatIdentity](m4m.math.md#quatidentity)
- [quatInverse](m4m.math.md#quatinverse)
- [quatLerp](m4m.math.md#quatlerp)
- [quatLookRotation](m4m.math.md#quatlookrotation)
- [quatLookat](m4m.math.md#quatlookat)
- [quatMagnitude](m4m.math.md#quatmagnitude)
- [quatMultiply](m4m.math.md#quatmultiply)
- [quatMultiplyDataAndQuat](m4m.math.md#quatmultiplydataandquat)
- [quatMultiplyVector](m4m.math.md#quatmultiplyvector)
- [quatNormalize](m4m.math.md#quatnormalize)
- [quatReset](m4m.math.md#quatreset)
- [quatRotationTo](m4m.math.md#quatrotationto)
- [quatToAxisAngle](m4m.math.md#quattoaxisangle)
- [quatToEulerAngles](m4m.math.md#quattoeulerangles)
- [quatToMatrix](m4m.math.md#quattomatrix)
- [quatTransformVector](m4m.math.md#quattransformvector)
- [quatTransformVectorDataAndQuat](m4m.math.md#quattransformvectordataandquat)
- [quatYAxis](m4m.math.md#quatyaxis)
- [quaternionFormat](m4m.math.md#quaternionformat)
- [radToDeg](m4m.math.md#radtodeg)
- [rectClone](m4m.math.md#rectclone)
- [rectCollided](m4m.math.md#rectcollided)
- [rectEqul](m4m.math.md#rectequl)
- [rectInner](m4m.math.md#rectinner)
- [rectOverlap](m4m.math.md#rectoverlap)
- [rectSet](m4m.math.md#rectset)
- [rectSet\_One](m4m.math.md#rectset_one)
- [rectSet\_Zero](m4m.math.md#rectset_zero)
- [scaleToRef](m4m.math.md#scaletoref)
- [sign](m4m.math.md#sign)
- [spriteAnimation](m4m.math.md#spriteanimation)
- [unitxyzToRotation](m4m.math.md#unitxyztorotation)
- [vec2Add](m4m.math.md#vec2add)
- [vec2Clone](m4m.math.md#vec2clone)
- [vec2Distance](m4m.math.md#vec2distance)
- [vec2Dot](m4m.math.md#vec2dot)
- [vec2Equal](m4m.math.md#vec2equal)
- [vec2FormJson](m4m.math.md#vec2formjson)
- [vec2Length](m4m.math.md#vec2length)
- [vec2Multiply](m4m.math.md#vec2multiply)
- [vec2Normalize](m4m.math.md#vec2normalize)
- [vec2SLerp](m4m.math.md#vec2slerp)
- [vec2ScaleByNum](m4m.math.md#vec2scalebynum)
- [vec2ScaleByVec2](m4m.math.md#vec2scalebyvec2)
- [vec2Set](m4m.math.md#vec2set)
- [vec2SetAll](m4m.math.md#vec2setall)
- [vec2Subtract](m4m.math.md#vec2subtract)
- [vec3Add](m4m.math.md#vec3add)
- [vec3Angle](m4m.math.md#vec3angle)
- [vec3AngleBetween](m4m.math.md#vec3anglebetween)
- [vec3ClampLength](m4m.math.md#vec3clamplength)
- [vec3Clone](m4m.math.md#vec3clone)
- [vec3Cross](m4m.math.md#vec3cross)
- [vec3Distance](m4m.math.md#vec3distance)
- [vec3Dot](m4m.math.md#vec3dot)
- [vec3Equal](m4m.math.md#vec3equal)
- [vec3Exclude](m4m.math.md#vec3exclude)
- [vec3FormJson](m4m.math.md#vec3formjson)
- [vec3Format](m4m.math.md#vec3format)
- [vec3IsParallel](m4m.math.md#vec3isparallel)
- [vec3Length](m4m.math.md#vec3length)
- [vec3Max](m4m.math.md#vec3max)
- [vec3Min](m4m.math.md#vec3min)
- [vec3Minus](m4m.math.md#vec3minus)
- [vec3Normalize](m4m.math.md#vec3normalize)
- [vec3Perpendicular](m4m.math.md#vec3perpendicular)
- [vec3Product](m4m.math.md#vec3product)
- [vec3Project](m4m.math.md#vec3project)
- [vec3ProjectOnPlane](m4m.math.md#vec3projectonplane)
- [vec3Reflect](m4m.math.md#vec3reflect)
- [vec3Reset](m4m.math.md#vec3reset)
- [vec3SLerp](m4m.math.md#vec3slerp)
- [vec3ScaleByNum](m4m.math.md#vec3scalebynum)
- [vec3ScaleByVec3](m4m.math.md#vec3scalebyvec3)
- [vec3Set](m4m.math.md#vec3set)
- [vec3SetAll](m4m.math.md#vec3setall)
- [vec3SetByFloat](m4m.math.md#vec3setbyfloat)
- [vec3Set\_Back](m4m.math.md#vec3set_back)
- [vec3Set\_Down](m4m.math.md#vec3set_down)
- [vec3Set\_Forward](m4m.math.md#vec3set_forward)
- [vec3Set\_Left](m4m.math.md#vec3set_left)
- [vec3Set\_One](m4m.math.md#vec3set_one)
- [vec3Set\_Right](m4m.math.md#vec3set_right)
- [vec3Set\_Up](m4m.math.md#vec3set_up)
- [vec3SqrLength](m4m.math.md#vec3sqrlength)
- [vec3Subtract](m4m.math.md#vec3subtract)
- [vec4Add](m4m.math.md#vec4add)
- [vec4Clone](m4m.math.md#vec4clone)
- [vec4FormJson](m4m.math.md#vec4formjson)
- [vec4SLerp](m4m.math.md#vec4slerp)
- [vec4ScaleByNum](m4m.math.md#vec4scalebynum)
- [vec4Set](m4m.math.md#vec4set)
- [vec4SetAll](m4m.math.md#vec4setall)
- [x\_AXIS](m4m.math.md#x_axis)
- [y\_AXIS](m4m.math.md#y_axis)
- [z\_AXIS](m4m.math.md#z_axis)

### Variables

- [DEG2RAD](m4m.math.md#deg2rad)
- [RAD2DEG](m4m.math.md#rad2deg)
- [defaultRotationOrder](m4m.math.md#defaultrotationorder)

### Classes

- [ExtenArray](../classes/m4m.math.ExtenArray.md)
- [ReuseArray](../classes/m4m.math.ReuseArray.md)
- [angelref](../classes/m4m.math.angelref.md)
- [commonStatic](../classes/m4m.math.commonStatic.md)
- [pool](../classes/m4m.math.pool.md)

### Interfaces

- [Iquat](../interfaces/m4m.math.Iquat.md)
- [Ivec2](../interfaces/m4m.math.Ivec2.md)
- [Ivec3](../interfaces/m4m.math.Ivec3.md)

### Enumerations

- [RotationOrder](../enums/m4m.math.RotationOrder.md)

### Type Aliases

- [byte](m4m.math.md#byte-1)
- [double](m4m.math.md#double-1)
- [float](m4m.math.md#float-1)
- [int](m4m.math.md#int)
- [short](m4m.math.md#short)
- [ubyte](m4m.math.md#ubyte-1)
- [uint](m4m.math.md#uint)
- [ushort](m4m.math.md#ushort)

## Functions

### Byte

▸ **Byte**(`v?`): [`byte`](m4m.math.md#byte-1)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `v` | `string` \| `number` | `0` |

#### Returns

[`byte`](m4m.math.md#byte-1)

#### Defined in

[render/struct.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L34)

___

### Double

▸ **Double**(`v?`): [`double`](m4m.math.md#double-1)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `v` | `string` \| `number` | `0` |

#### Returns

[`double`](m4m.math.md#double-1)

#### Defined in

[render/struct.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L83)

___

### Float

▸ **Float**(`v?`): [`float`](m4m.math.md#float-1)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `v` | `string` \| `number` | `0` |

#### Returns

[`float`](m4m.math.md#float-1)

#### Defined in

[render/struct.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L75)

___

### GetPointAlongCurve

▸ **GetPointAlongCurve**(`curveStart`, `curveStartHandle`, `curveEnd`, `curveEndHandle`, `t`, `out`, `crease?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `curveStart` | `vector3` | `undefined` |
| `curveStartHandle` | `vector3` | `undefined` |
| `curveEnd` | `vector3` | `undefined` |
| `curveEndHandle` | `vector3` | `undefined` |
| `t` | `number` | `undefined` |
| `out` | `vector3` | `undefined` |
| `crease` | `number` | `0.3` |

#### Returns

`void`

#### Defined in

[framework/math/utilMath.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/utilMath.ts#L28)

___

### Int16

▸ **Int16**(`v?`): [`short`](m4m.math.md#short)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `v` | `string` \| `number` | `0` |

#### Returns

[`short`](m4m.math.md#short)

#### Defined in

[render/struct.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L42)

___

### Int32

▸ **Int32**(`v?`): [`int`](m4m.math.md#int)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `v` | `string` \| `number` | `0` |

#### Returns

[`int`](m4m.math.md#int)

#### Defined in

[render/struct.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L50)

___

### Multiply

▸ **Multiply**(`p1`, `p2`, `p0`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p1` | `vector2` |
| `p2` | `vector2` |
| `p0` | `vector2` |

#### Returns

`number`

#### Defined in

[framework/math/geometricoperation.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/geometricoperation.ts#L38)

___

### UByte

▸ **UByte**(`v?`): [`ubyte`](m4m.math.md#ubyte-1)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `v` | `string` \| `number` | `0` |

#### Returns

[`ubyte`](m4m.math.md#ubyte-1)

#### Defined in

[render/struct.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L27)

___

### UInt16

▸ **UInt16**(`v?`): [`ushort`](m4m.math.md#ushort)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `v` | `string` \| `number` | `0` |

#### Returns

[`ushort`](m4m.math.md#ushort)

#### Defined in

[render/struct.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L59)

___

### UInt32

▸ **UInt32**(`v?`): [`uint`](m4m.math.md#uint)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `v` | `string` \| `number` | `0` |

#### Returns

[`uint`](m4m.math.md#uint)

#### Defined in

[render/struct.ts:67](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L67)

___

### caclStringByteLength

▸ **caclStringByteLength**(`value`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `string` |

#### Returns

`number`

#### Defined in

[framework/math/string.ts:3](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/string.ts#L3)

___

### calPlaneLineIntersectPoint

▸ **calPlaneLineIntersectPoint**(`planeVector`, `planePoint`, `lineVector`, `linePoint`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `planeVector` | `vector3` |
| `planePoint` | `vector3` |
| `lineVector` | `vector3` |
| `linePoint` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/geometricoperation.ts:3](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/geometricoperation.ts#L3)

___

### colorClone

▸ **colorClone**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `color` |
| `out` | `color` |

#### Returns

`void`

#### Defined in

[framework/math/color.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/color.ts#L49)

___

### colorFormJson

▸ **colorFormJson**(`json`, `_color`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `json` | `string` |
| `_color` | `color` |

#### Returns

`void`

#### Defined in

[render/struct.ts:739](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L739)

___

### colorLerp

▸ **colorLerp**(`srca`, `srcb`, `t`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `srca` | `color` |
| `srcb` | `color` |
| `t` | `number` |
| `out` | `color` |

#### Returns

`void`

#### Defined in

[framework/math/color.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/color.ts#L62)

___

### colorMultiply

▸ **colorMultiply**(`srca`, `srcb`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `srca` | `color` |
| `srcb` | `color` |
| `out` | `color` |

#### Returns

`void`

#### Defined in

[framework/math/color.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/color.ts#L33)

___

### colorSet

▸ **colorSet**(`out`, `r`, `g`, `b`, `a`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `color` |
| `r` | `number` |
| `g` | `number` |
| `b` | `number` |
| `a` | `number` |

#### Returns

`void`

#### Defined in

[framework/math/color.ts:3](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/color.ts#L3)

___

### colorSet\_Black

▸ **colorSet_Black**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `color` |

#### Returns

`void`

#### Defined in

[framework/math/color.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/color.ts#L18)

___

### colorSet\_Gray

▸ **colorSet_Gray**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `color` |

#### Returns

`void`

#### Defined in

[framework/math/color.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/color.ts#L25)

___

### colorSet\_White

▸ **colorSet_White**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `color` |

#### Returns

`void`

#### Defined in

[framework/math/color.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/color.ts#L11)

___

### colorToCSS

▸ **colorToCSS**(`src`, `hasAlpha?`): `string`

颜色转成 CSS 格式

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `src` | `color` | `undefined` |  |
| `hasAlpha` | `boolean` | `true` | 是否包含Alpha |

#### Returns

`string`

like #ffffffff

#### Defined in

[framework/math/color.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/color.ts#L81)

___

### count

▸ **count**(`tag`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tag` | `string` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:452](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L452)

___

### countEnd

▸ **countEnd**(`tag`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tag` | `string` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:456](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L456)

___

### countStart

▸ **countStart**(`tag`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tag` | `string` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:448](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L448)

___

### degToRad

▸ **degToRad**(`degrees`): `number`

角度转换为弧度

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `degrees` | `number` | 角度 |

#### Returns

`number`

#### Defined in

[framework/math/number.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L45)

___

### floatClamp

▸ **floatClamp**(`v`, `min?`, `max?`): `number`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `v` | `number` | `undefined` |
| `min` | `number` | `0` |
| `max` | `number` | `1` |

#### Returns

`number`

#### Defined in

[framework/math/number.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L7)

___

### floatFormat

▸ **floatFormat**(`num`, `maxDot`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |
| `maxDot` | `number` |

#### Returns

`number`

#### Defined in

[framework/math/vector3.ts:341](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L341)

___

### getKeyCodeByAscii

▸ **getKeyCodeByAscii**(`ev`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `KeyboardEvent` |

#### Returns

`number`

#### Defined in

[framework/math/number.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L26)

___

### isContain

▸ **isContain**(`p1`, `p2`, `p3`, `p4`, `mp`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p1` | `vector2` |
| `p2` | `vector2` |
| `p3` | `vector2` |
| `p4` | `vector2` |
| `mp` | `vector2` |

#### Returns

`boolean`

#### Defined in

[framework/math/geometricoperation.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/geometricoperation.ts#L31)

___

### mapLinear

▸ **mapLinear**(`x`, `a1`, `a2`, `b1`, `b2`): `number`

使 x 值从区间 <a1, a2> 线性映射到区间 <b1, b2>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `x` | `number` | 第一个区间中值 |
| `a1` | `number` | 第一个区间起始值 |
| `a2` | `number` | 第一个区间终止值 |
| `b1` | `number` | 第二个区间起始值 |
| `b2` | `number` | 第二个区间起始值 |

#### Returns

`number`

#### Defined in

[framework/math/number.ts:69](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L69)

___

### matrix2Quaternion

▸ **matrix2Quaternion**(`matrix`, `result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `matrix` | `matrix` |
| `result` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:279](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L279)

___

### matrix3x2Clone

▸ **matrix3x2Clone**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix3x2` |
| `out` | `matrix3x2` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:380](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L380)

___

### matrix3x2Decompose

▸ **matrix3x2Decompose**(`src`, `scale`, `rotation`, `translation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix3x2` |
| `scale` | `vector2` |
| `rotation` | [`angelref`](../classes/m4m.math.angelref.md) |
| `translation` | `vector2` |

#### Returns

`boolean`

#### Defined in

[framework/math/matrix.ts:102](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L102)

___

### matrix3x2Equal

▸ **matrix3x2Equal**(`mtx1`, `mtx2`, `threshold?`): `boolean`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `mtx1` | `matrix3x2` | `undefined` |
| `mtx2` | `matrix3x2` | `undefined` |
| `threshold` | `number` | `0.00001` |

#### Returns

`boolean`

#### Defined in

[framework/math/matrix.ts:916](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L916)

___

### matrix3x2Inverse

▸ **matrix3x2Inverse**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix3x2` |
| `out` | `matrix3x2` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:484](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L484)

___

### matrix3x2MakeIdentity

▸ **matrix3x2MakeIdentity**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `matrix3x2` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:410](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L410)

___

### matrix3x2MakeRotate

▸ **matrix3x2MakeRotate**(`angle`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `angle` | `number` |
| `out` | `matrix3x2` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:781](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L781)

___

### matrix3x2MakeScale

▸ **matrix3x2MakeScale**(`xScale`, `yScale`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `xScale` | `number` |
| `yScale` | `number` |
| `out` | `matrix3x2` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:603](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L603)

___

### matrix3x2MakeTransformRTS

▸ **matrix3x2MakeTransformRTS**(`pos`, `scale`, `rot`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pos` | `vector2` |
| `scale` | `vector2` |
| `rot` | `number` |
| `out` | `matrix3x2` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:539](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L539)

___

### matrix3x2MakeTranslate

▸ **matrix3x2MakeTranslate**(`x`, `y`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |
| `out` | `matrix3x2` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:560](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L560)

___

### matrix3x2Multiply

▸ **matrix3x2Multiply**(`lhs`, `rhs`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `lhs` | `matrix3x2` |
| `rhs` | `matrix3x2` |
| `out` | `matrix3x2` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:879](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L879)

___

### matrix3x2TransformNormal

▸ **matrix3x2TransformNormal**(`mat`, `inp`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `mat` | `matrix` |
| `inp` | `vector2` |
| `out` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:596](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L596)

___

### matrix3x2TransformVector2

▸ **matrix3x2TransformVector2**(`mat`, `inp`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `mat` | `matrix` |
| `inp` | `vector2` |
| `out` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:589](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L589)

___

### matrixAdd

▸ **matrixAdd**(`left`, `right`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `left` | `matrix` |
| `right` | `matrix` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1275](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1275)

___

### matrixClone

▸ **matrixClone**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:372](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L372)

___

### matrixDecompose

▸ **matrixDecompose**(`src`, `scale`, `rotation`, `translation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix` |
| `scale` | `vector3` |
| `rotation` | `quaternion` |
| `translation` | `vector3` |

#### Returns

`boolean`

#### Defined in

[framework/math/matrix.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L53)

___

### matrixEqual

▸ **matrixEqual**(`mtx1`, `mtx2`, `threshold?`): `boolean`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `mtx1` | `matrix` | `undefined` |
| `mtx2` | `matrix` | `undefined` |
| `threshold` | `number` | `0.00001` |

#### Returns

`boolean`

#### Defined in

[framework/math/matrix.ts:1298](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1298)

___

### matrixGetEuler

▸ **matrixGetEuler**(`src`, `order`, `rotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix` |
| `order` | [`RotationOrder`](../enums/m4m.math.RotationOrder.md) |
| `rotation` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L149)

___

### matrixGetRotation

▸ **matrixGetRotation**(`src`, `result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix` |
| `result` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:249](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L249)

___

### matrixGetScale

▸ **matrixGetScale**(`src`, `scale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix` |
| `scale` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:566](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L566)

___

### matrixGetTranslation

▸ **matrixGetTranslation**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L5)

___

### matrixGetVector3ByOffset

▸ **matrixGetVector3ByOffset**(`src`, `offset`, `result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix` |
| `offset` | `number` |
| `result` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1196](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1196)

___

### matrixInverse

▸ **matrixInverse**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:421](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L421)

___

### matrixIsIdentity

▸ **matrixIsIdentity**(`mtx`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `mtx` | `matrix` |

#### Returns

`boolean`

#### Defined in

[framework/math/matrix.ts:1310](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1310)

___

### matrixLerp

▸ **matrixLerp**(`left`, `right`, `v`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `left` | `matrix` |
| `right` | `matrix` |
| `v` | `number` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1142)

___

### matrixLookat

▸ **matrixLookat**(`position`, `target`, `upAxis`, `out`): `void`

看向目标位置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `position` | `vector3` | 所在位置 |
| `target` | `vector3` | 目标位置 |
| `upAxis` | `vector3` | 向上朝向 |
| `out` | `matrix` | - |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:983](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L983)

___

### matrixLookatLH

▸ **matrixLookatLH**(`forward`, `up`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `forward` | `vector3` |
| `up` | `vector3` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1036](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1036)

___

### matrixMakeEuler

▸ **matrixMakeEuler**(`rotation`, `order`, `out`): `void`

从欧拉旋转初始化矩阵

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `rotation` | `vector3` | 旋转弧度值 |
| `order` | [`RotationOrder`](../enums/m4m.math.RotationOrder.md) | 旋转顺序 |
| `out` | `matrix` | 输出矩阵 |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:617](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L617)

___

### matrixMakeIdentity

▸ **matrixMakeIdentity**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:388](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L388)

___

### matrixMakeRotateAxisAngle

▸ **matrixMakeRotateAxisAngle**(`axis`, `angle`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `axis` | `vector3` |
| `angle` | `number` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:730](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L730)

___

### matrixMakeScale

▸ **matrixMakeScale**(`xScale`, `yScale`, `zScale`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `xScale` | `number` |
| `yScale` | `number` |
| `zScale` | `number` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:581](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L581)

___

### matrixMakeTransformRTS

▸ **matrixMakeTransformRTS**(`pos`, `scale`, `rot`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pos` | `vector3` |
| `scale` | `vector3` |
| `rot` | `quaternion` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:523](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L523)

___

### matrixMakeTranslate

▸ **matrixMakeTranslate**(`x`, `y`, `z`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |
| `z` | `number` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:553](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L553)

___

### matrixMultiply

▸ **matrixMultiply**(`lhs`, `rhs`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `lhs` | `matrix` |
| `rhs` | `matrix` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:800](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L800)

___

### matrixProject\_OrthoLH

▸ **matrixProject_OrthoLH**(`width`, `height`, `znear`, `zfar`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `width` | `number` |
| `height` | `number` |
| `znear` | `number` |
| `zfar` | `number` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:947](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L947)

___

### matrixProject\_PerspectiveLH

▸ **matrixProject_PerspectiveLH**(`fov`, `aspect`, `znear`, `zfar`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `fov` | `number` |
| `aspect` | `number` |
| `znear` | `number` |
| `zfar` | `number` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:927](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L927)

___

### matrixReset

▸ **matrixReset**(`mat`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `mat` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1206](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1206)

___

### matrixScaleByNum

▸ **matrixScaleByNum**(`value`, `mat`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |
| `mat` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1252](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1252)

___

### matrixTransformNormal

▸ **matrixTransformNormal**(`vector`, `transformation`, `result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `transformation` | `matrix` |
| `result` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1182](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1182)

___

### matrixTransformVector3

▸ **matrixTransformVector3**(`vector`, `transformation`, `result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `transformation` | `matrix` |
| `result` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1150](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1150)

___

### matrixTransformVector4

▸ **matrixTransformVector4**(`src`, `mtx`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `vector4` |
| `mtx` | `matrix` |
| `out` | `vector4` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1166](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1166)

___

### matrixTranspose

▸ **matrixTranspose**(`src`, `out`): `void`

**`language`** zh_CN
当前矩阵转置

**`version`** m4m 1.0

**`platform`** Web,Native

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `matrix` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L23)

___

### matrixViewLookatLH

▸ **matrixViewLookatLH**(`eye`, `forward`, `up`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eye` | `vector3` |
| `forward` | `vector3` |
| `up` | `vector3` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1088](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1088)

___

### matrixZero

▸ **matrixZero**(`mat`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `mat` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:1229](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L1229)

___

### myLookRotation

▸ **myLookRotation**(`dir`, `out`, `up?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `dir` | `vector3` | `undefined` |
| `out` | `quaternion` | `undefined` |
| `up` | `vector3` | `pool.vector3_up` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:470](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L470)

___

### numberLerp

▸ **numberLerp**(`fromV`, `toV`, `v`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `fromV` | `number` |
| `toV` | `number` |
| `v` | `number` |

#### Returns

`number`

#### Defined in

[framework/math/number.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L74)

___

### quat2LookRotation

▸ **quat2LookRotation**(`pos`, `targetpos`, `upwards`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pos` | `vector3` |
| `targetpos` | `vector3` |
| `upwards` | `vector3` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:341](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L341)

___

### quat2Lookat

▸ **quat2Lookat**(`pos`, `targetpos`, `out`, `updir?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `pos` | `vector3` | `undefined` |
| `targetpos` | `vector3` | `undefined` |
| `out` | `quaternion` | `undefined` |
| `updir` | `vector3` | `m4m.math.pool.vector3_up` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:316](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L316)

___

### quatClone

▸ **quatClone**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `quaternion` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L52)

___

### quatEqual

▸ **quatEqual**(`quat`, `quat2`, `threshold?`): `boolean`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `quat` | `quaternion` | `undefined` |
| `quat2` | `quaternion` | `undefined` |
| `threshold` | `number` | `0.000001` |

#### Returns

`boolean`

#### Defined in

[framework/math/quat.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L64)

___

### quatFromAxisAngle

▸ **quatFromAxisAngle**(`axis`, `angle`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `axis` | `vector3` |
| `angle` | `number` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:195](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L195)

___

### quatFromEulerAngles

▸ **quatFromEulerAngles**(`ax`, `ay`, `az`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ax` | `number` |
| `ay` | `number` |
| `az` | `number` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:227](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L227)

___

### quatFromYawPitchRoll

▸ **quatFromYawPitchRoll**(`yaw`, `pitch`, `roll`, `result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `yaw` | `number` |
| `pitch` | `number` |
| `roll` | `number` |
| `result` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L112)

___

### quatIdentity

▸ **quatIdentity**(`src`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:2](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L2)

___

### quatInverse

▸ **quatInverse**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `quaternion` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L100)

___

### quatLerp

▸ **quatLerp**(`srca`, `srcb`, `out`, `t`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `srca` | `quaternion` |
| `srcb` | `quaternion` |
| `out` | `quaternion` |
| `t` | `number` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:171](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L171)

___

### quatLookRotation

▸ **quatLookRotation**(`dir`, `upwards`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `dir` | `vector3` |
| `upwards` | `vector3` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:347](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L347)

___

### quatLookat

▸ **quatLookat**(`pos`, `targetpos`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pos` | `vector3` |
| `targetpos` | `vector3` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:284](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L284)

___

### quatMagnitude

▸ **quatMagnitude**(`src`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `quaternion` |

#### Returns

`number`

#### Defined in

[framework/math/quat.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L48)

___

### quatMultiply

▸ **quatMultiply**(`srca`, `srcb`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `srca` | `quaternion` |
| `srcb` | `quaternion` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:130](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L130)

___

### quatMultiplyDataAndQuat

▸ **quatMultiplyDataAndQuat**(`srca`, `srcaseek`, `srcb`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `srca` | `Float32Array` |
| `srcaseek` | `number` |
| `srcb` | `quaternion` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:145](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L145)

___

### quatMultiplyVector

▸ **quatMultiplyVector**(`vector`, `scr`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `scr` | `quaternion` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:160](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L160)

___

### quatNormalize

▸ **quatNormalize**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `quaternion` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L10)

___

### quatReset

▸ **quatReset**(`src`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:277](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L277)

___

### quatRotationTo

▸ **quatRotationTo**(`start`, `end`, `out`): `void`

计算 从 start 到 end 旋转的四元数

#### Parameters

| Name | Type |
| :------ | :------ |
| `start` | `vector3` |
| `end` | `vector3` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:438](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L438)

___

### quatToAxisAngle

▸ **quatToAxisAngle**(`src`, `axis`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `quaternion` |
| `axis` | `vector3` |

#### Returns

`number`

#### Defined in

[framework/math/quat.ts:207](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L207)

___

### quatToEulerAngles

▸ **quatToEulerAngles**(`src`, `result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `quaternion` |
| `result` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:244](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L244)

___

### quatToMatrix

▸ **quatToMatrix**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `quaternion` |
| `out` | `matrix` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L77)

___

### quatTransformVector

▸ **quatTransformVector**(`src`, `vector`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `quaternion` |
| `vector` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L19)

___

### quatTransformVectorDataAndQuat

▸ **quatTransformVectorDataAndQuat**(`src`, `srcseek`, `vector`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `Float32Array` |
| `srcseek` | `number` |
| `vector` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L33)

___

### quatYAxis

▸ **quatYAxis**(`pos`, `targetpos`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pos` | `vector3` |
| `targetpos` | `vector3` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/quat.ts:405](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/quat.ts#L405)

___

### quaternionFormat

▸ **quaternionFormat**(`vector`, `maxDot`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `quaternion` |
| `maxDot` | `number` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:334](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L334)

___

### radToDeg

▸ **radToDeg**(`radians`): `number`

弧度转换为角度

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `radians` | `number` | 弧度 |

#### Returns

`number`

#### Defined in

[framework/math/number.ts:55](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L55)

___

### rectClone

▸ **rectClone**(`src`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `rect` |
| `out` | `rect` |

#### Returns

`void`

#### Defined in

[framework/math/rect.ts:67](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/rect.ts#L67)

___

### rectCollided

▸ **rectCollided**(`r1`, `r2`): `boolean`

检测两个矩形是否相碰

#### Parameters

| Name | Type |
| :------ | :------ |
| `r1` | `rect` |
| `r2` | `rect` |

#### Returns

`boolean`

#### Defined in

[framework/math/rect.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/rect.ts#L63)

___

### rectEqul

▸ **rectEqul**(`src1`, `src2`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src1` | `rect` |
| `src2` | `rect` |

#### Returns

`boolean`

#### Defined in

[framework/math/rect.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/rect.ts#L16)

___

### rectInner

▸ **rectInner**(`x`, `y`, `src`): `boolean`

判断点是否在矩形中

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `x` | `number` | 点坐标x |
| `y` | `number` | 点坐标y |
| `src` | `rect` | 矩形 |

#### Returns

`boolean`

#### Defined in

[framework/math/rect.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/rect.ts#L29)

___

### rectOverlap

▸ **rectOverlap**(`r1`, `r2`): `boolean`

判断两矩形是否重叠

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `r1` | `rect` | 矩形1 |
| `r2` | `rect` | 矩形2 |

#### Returns

`boolean`

#### Defined in

[framework/math/rect.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/rect.ts#L42)

___

### rectSet

▸ **rectSet**(`out`, `x`, `y`, `w`, `h`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `rect` |
| `x` | `number` |
| `y` | `number` |
| `w` | `number` |
| `h` | `number` |

#### Returns

`void`

#### Defined in

[framework/math/rect.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/rect.ts#L51)

___

### rectSet\_One

▸ **rectSet_One**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `rect` |

#### Returns

`void`

#### Defined in

[framework/math/rect.ts:2](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/rect.ts#L2)

___

### rectSet\_Zero

▸ **rectSet_Zero**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `rect` |

#### Returns

`void`

#### Defined in

[framework/math/rect.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/rect.ts#L9)

___

### scaleToRef

▸ **scaleToRef**(`src`, `scale`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `src` | `color` |
| `scale` | `number` |
| `out` | `color` |

#### Returns

`void`

#### Defined in

[framework/math/color.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/color.ts#L41)

___

### sign

▸ **sign**(`value`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`number`

#### Defined in

[framework/math/number.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L16)

___

### spriteAnimation

▸ **spriteAnimation**(`row`, `column`, `index`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `row` | `number` |
| `column` | `number` |
| `index` | `number` |
| `out` | `vector4` |

#### Returns

`void`

#### Defined in

[framework/math/utilMath.ts:4](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/utilMath.ts#L4)

___

### unitxyzToRotation

▸ **unitxyzToRotation**(`xAxis`, `yAxis`, `zAxis`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `xAxis` | `vector3` |
| `yAxis` | `vector3` |
| `zAxis` | `vector3` |
| `out` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/math/matrix.ts:326](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/matrix.ts#L326)

___

### vec2Add

▸ **vec2Add**(`a`, `b`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector2` |
| `b` | `vector2` |
| `out` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/math/vector2.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L8)

___

### vec2Clone

▸ **vec2Clone**(`from`, `to`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector2` |
| `to` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/math/vector2.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L12)

___

### vec2Distance

▸ **vec2Distance**(`a`, `b`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector2` |
| `b` | `vector2` |

#### Returns

`number`

#### Defined in

[framework/math/vector2.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L19)

___

### vec2Dot

▸ **vec2Dot**(`lhs`, `rhs`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `lhs` | `vector2` |
| `rhs` | `vector2` |

#### Returns

`number`

#### Defined in

[framework/math/vector2.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L62)

___

### vec2Equal

▸ **vec2Equal**(`vector`, `vector2`, `threshold?`): `boolean`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `vector` | `vector2` | `undefined` |
| `vector2` | `vector2` | `undefined` |
| `threshold` | `number` | `0.00001` |

#### Returns

`boolean`

#### Defined in

[framework/math/vector2.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L68)

___

### vec2FormJson

▸ **vec2FormJson**(`json`, `vec2`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `json` | `string` |
| `vec2` | `vector2` |

#### Returns

`void`

#### Defined in

[render/struct.ts:731](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L731)

___

### vec2Length

▸ **vec2Length**(`a`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector2` |

#### Returns

`number`

#### Defined in

[framework/math/vector2.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L37)

___

### vec2Multiply

▸ **vec2Multiply**(`a`, `b`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector2` |
| `b` | `vector2` |

#### Returns

`number`

#### Defined in

[framework/math/vector2.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L58)

___

### vec2Normalize

▸ **vec2Normalize**(`from`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector2` |
| `out` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/math/vector2.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L47)

___

### vec2SLerp

▸ **vec2SLerp**(`vector`, `vector2`, `v`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector2` |
| `vector2` | `vector2` |
| `v` | `number` |
| `out` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/math/vector2.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L42)

___

### vec2ScaleByNum

▸ **vec2ScaleByNum**(`from`, `scale`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector2` |
| `scale` | `number` |
| `out` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/math/vector2.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L27)

___

### vec2ScaleByVec2

▸ **vec2ScaleByVec2**(`from`, `scale`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector2` |
| `scale` | `vector2` |
| `out` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/math/vector2.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L32)

___

### vec2Set

▸ **vec2Set**(`vector`, `x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector2` |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

#### Defined in

[framework/math/vector2.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L86)

___

### vec2SetAll

▸ **vec2SetAll**(`vector`, `value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector2` |
| `value` | `number` |

#### Returns

`void`

#### Defined in

[framework/math/vector2.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L78)

___

### vec2Subtract

▸ **vec2Subtract**(`a`, `b`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector2` |
| `b` | `vector2` |
| `out` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/math/vector2.ts:4](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector2.ts#L4)

___

### vec3Add

▸ **vec3Add**(`a`, `b`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector3` |
| `b` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L31)

___

### vec3Angle

▸ **vec3Angle**(`from`, `to`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector3` |
| `to` | `vector3` |

#### Returns

`number`

#### Defined in

[framework/math/vector3.ts:251](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L251)

___

### vec3AngleBetween

▸ **vec3AngleBetween**(`from`, `to`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector3` |
| `to` | `vector3` |

#### Returns

`number`

#### Defined in

[framework/math/vector3.ts:299](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L299)

___

### vec3ClampLength

▸ **vec3ClampLength**(`vector`, `maxLength`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `maxLength` | `number` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:272](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L272)

___

### vec3Clone

▸ **vec3Clone**(`from`, `to`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector3` |
| `to` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L16)

___

### vec3Cross

▸ **vec3Cross**(`lhs`, `rhs`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `lhs` | `vector3` |
| `rhs` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:176](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L176)

___

### vec3Distance

▸ **vec3Distance**(`a`, `b`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector3` |
| `b` | `vector3` |

#### Returns

`number`

#### Defined in

[framework/math/vector3.ts:264](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L264)

___

### vec3Dot

▸ **vec3Dot**(`lhs`, `rhs`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `lhs` | `vector3` |
| `rhs` | `vector3` |

#### Returns

`number`

#### Defined in

[framework/math/vector3.ts:219](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L219)

___

### vec3Equal

▸ **vec3Equal**(`vector`, `vector2`, `threshold?`): `boolean`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `vector` | `vector3` | `undefined` |
| `vector2` | `vector3` | `undefined` |
| `threshold` | `number` | `0.00001` |

#### Returns

`boolean`

#### Defined in

[framework/math/vector3.ts:378](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L378)

___

### vec3Exclude

▸ **vec3Exclude**(`excludeThis`, `fromThat`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `excludeThis` | `vector3` |
| `fromThat` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:245](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L245)

___

### vec3FormJson

▸ **vec3FormJson**(`json`, `vec3`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `json` | `string` |
| `vec3` | `vector3` |

#### Returns

`void`

#### Defined in

[render/struct.ts:721](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L721)

___

### vec3Format

▸ **vec3Format**(`vector`, `maxDot`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `maxDot` | `number` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:327](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L327)

___

### vec3IsParallel

▸ **vec3IsParallel**(`lhs`, `rhs`, `precision?`): `boolean`

指定两个向量是否平行

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `lhs` | `vector3` | `undefined` | 向量 |
| `rhs` | `vector3` | `undefined` | 向量 |
| `precision` | `number` | `1e-6` | 精度 |

#### Returns

`boolean`

#### Defined in

[framework/math/vector3.ts:196](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L196)

___

### vec3Length

▸ **vec3Length**(`a`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector3` |

#### Returns

`number`

#### Defined in

[framework/math/vector3.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L61)

___

### vec3Max

▸ **vec3Max**(`v0`, `v1`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `v0` | `vector3` |
| `v1` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:293](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L293)

___

### vec3Min

▸ **vec3Min**(`v0`, `v1`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `v0` | `vector3` |
| `v1` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:287](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L287)

___

### vec3Minus

▸ **vec3Minus**(`a`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L51)

___

### vec3Normalize

▸ **vec3Normalize**(`value`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L122)

___

### vec3Perpendicular

▸ **vec3Perpendicular**(`vector`, `out`): `void`

获取指定 向量的 垂直向量

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:410](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L410)

___

### vec3Product

▸ **vec3Product**(`a`, `b`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector3` |
| `b` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:166](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L166)

___

### vec3Project

▸ **vec3Project**(`vector`, `onNormal`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `onNormal` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:223](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L223)

___

### vec3ProjectOnPlane

▸ **vec3ProjectOnPlane**(`vector`, `planeNormal`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `planeNormal` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:239](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L239)

___

### vec3Reflect

▸ **vec3Reflect**(`inDirection`, `inNormal`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inDirection` | `vector3` |
| `inNormal` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:211](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L211)

___

### vec3Reset

▸ **vec3Reset**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:308](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L308)

___

### vec3SLerp

▸ **vec3SLerp**(`vector`, `vector2`, `v`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `vector2` | `vector3` |
| `v` | `number` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:314](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L314)

___

### vec3ScaleByNum

▸ **vec3ScaleByNum**(`from`, `scale`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector3` |
| `scale` | `number` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:156](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L156)

___

### vec3ScaleByVec3

▸ **vec3ScaleByVec3**(`from`, `scale`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector3` |
| `scale` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:146](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L146)

___

### vec3Set

▸ **vec3Set**(`vector`, `x`, `y`, `z`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `x` | `number` |
| `y` | `number` |
| `z` | `number` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:400](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L400)

___

### vec3SetAll

▸ **vec3SetAll**(`vector`, `value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector3` |
| `value` | `number` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:391](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L391)

___

### vec3SetByFloat

▸ **vec3SetByFloat**(`x`, `y`, `z`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |
| `z` | `number` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:320](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L320)

___

### vec3Set\_Back

▸ **vec3Set_Back**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L82)

___

### vec3Set\_Down

▸ **vec3Set_Down**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L98)

___

### vec3Set\_Forward

▸ **vec3Set_Forward**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L74)

___

### vec3Set\_Left

▸ **vec3Set_Left**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L106)

___

### vec3Set\_One

▸ **vec3Set_One**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:69](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L69)

___

### vec3Set\_Right

▸ **vec3Set_Right**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:114](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L114)

___

### vec3Set\_Up

▸ **vec3Set_Up**(`out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L90)

___

### vec3SqrLength

▸ **vec3SqrLength**(`value`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `vector3` |

#### Returns

`number`

#### Defined in

[framework/math/vector3.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L65)

___

### vec3Subtract

▸ **vec3Subtract**(`a`, `b`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector3` |
| `b` | `vector3` |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/math/vector3.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector3.ts#L41)

___

### vec4Add

▸ **vec4Add**(`a`, `b`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `vector4` |
| `b` | `vector4` |
| `out` | `vector4` |

#### Returns

`void`

#### Defined in

[framework/math/vector4.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector4.ts#L26)

___

### vec4Clone

▸ **vec4Clone**(`from`, `to`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector4` |
| `to` | `vector4` |

#### Returns

`void`

#### Defined in

[framework/math/vector4.ts:4](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector4.ts#L4)

___

### vec4FormJson

▸ **vec4FormJson**(`json`, `vec4`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `json` | `string` |
| `vec4` | `vector4` |

#### Returns

`void`

#### Defined in

[render/struct.ts:711](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L711)

___

### vec4SLerp

▸ **vec4SLerp**(`vector`, `vector2`, `v`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector4` |
| `vector2` | `vector4` |
| `v` | `number` |
| `out` | `vector4` |

#### Returns

`void`

#### Defined in

[framework/math/vector4.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector4.ts#L17)

___

### vec4ScaleByNum

▸ **vec4ScaleByNum**(`from`, `scale`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `vector4` |
| `scale` | `number` |
| `out` | `vector4` |

#### Returns

`void`

#### Defined in

[framework/math/vector4.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector4.ts#L38)

___

### vec4Set

▸ **vec4Set**(`vector`, `x`, `y`, `z`, `w`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector4` |
| `x` | `number` |
| `y` | `number` |
| `z` | `number` |
| `w` | `number` |

#### Returns

`void`

#### Defined in

[framework/math/vector4.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector4.ts#L62)

___

### vec4SetAll

▸ **vec4SetAll**(`vector`, `value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `vector` | `vector4` |
| `value` | `number` |

#### Returns

`void`

#### Defined in

[framework/math/vector4.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/vector4.ts#L50)

___

### x\_AXIS

▸ **x_AXIS**(): `vector3`

#### Returns

`vector3`

#### Defined in

[framework/math/number.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L79)

___

### y\_AXIS

▸ **y_AXIS**(): `vector3`

#### Returns

`vector3`

#### Defined in

[framework/math/number.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L83)

___

### z\_AXIS

▸ **z_AXIS**(): `vector3`

#### Returns

`vector3`

#### Defined in

[framework/math/number.ts:87](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L87)

## Variables

### DEG2RAD

• **DEG2RAD**: `number`

#### Defined in

[framework/math/number.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L37)

___

### RAD2DEG

• **RAD2DEG**: `number`

#### Defined in

[framework/math/number.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/number.ts#L38)

___

### defaultRotationOrder

• **defaultRotationOrder**: [`RotationOrder`](../enums/m4m.math.RotationOrder.md) = `RotationOrder.YXZ`

引擎中使用的旋转顺序。

unity YXZ
playcanvas ZYX
three.js XYZ

#### Defined in

[framework/math/RotationOrder.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/math/RotationOrder.ts#L50)

## Type Aliases

### byte

Ƭ **byte**: `number`

#### Defined in

[render/struct.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L9)

___

### double

Ƭ **double**: `number`

#### Defined in

[render/struct.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L16)

___

### float

Ƭ **float**: `number`

#### Defined in

[render/struct.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L15)

___

### int

Ƭ **int**: `number`

#### Defined in

[render/struct.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L12)

___

### short

Ƭ **short**: `number`

#### Defined in

[render/struct.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L11)

___

### ubyte

Ƭ **ubyte**: `number`

#### Defined in

[render/struct.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L10)

___

### uint

Ƭ **uint**: `number`

#### Defined in

[render/struct.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L14)

___

### ushort

Ƭ **ushort**: `number`

#### Defined in

[render/struct.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/struct.ts#L13)
