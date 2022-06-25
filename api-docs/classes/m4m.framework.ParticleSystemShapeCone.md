[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystemShapeCone

# Class: ParticleSystemShapeCone

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystemShapeCone

粒子系统发射圆锥体，用于定义基于圆锥体的粒子发射时的初始状态。

**`author`** feng3d

## Hierarchy

- [`ParticleSystemShapeBase`](m4m.framework.ParticleSystemShapeBase.md)

  ↳ **`ParticleSystemShapeCone`**

## Table of contents

### Properties

- [\_module](m4m.framework.ParticleSystemShapeCone.md#_module)
- [emitFrom](m4m.framework.ParticleSystemShapeCone.md#emitfrom)

### Accessors

- [angle](m4m.framework.ParticleSystemShapeCone.md#angle)
- [arc](m4m.framework.ParticleSystemShapeCone.md#arc)
- [arcMode](m4m.framework.ParticleSystemShapeCone.md#arcmode)
- [arcSpeed](m4m.framework.ParticleSystemShapeCone.md#arcspeed)
- [arcSpread](m4m.framework.ParticleSystemShapeCone.md#arcspread)
- [length](m4m.framework.ParticleSystemShapeCone.md#length)
- [radius](m4m.framework.ParticleSystemShapeCone.md#radius)

### Methods

- [calcParticlePosDir](m4m.framework.ParticleSystemShapeCone.md#calcparticleposdir)

### Constructors

- [constructor](m4m.framework.ParticleSystemShapeCone.md#constructor)

## Properties

### \_module

• `Protected` **\_module**: [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md)

#### Inherited from

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[_module](m4m.framework.ParticleSystemShapeBase.md#_module)

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L10)

___

### emitFrom

• **emitFrom**: [`ParticleSystemShapeConeEmitFrom`](../enums/m4m.framework.ParticleSystemShapeConeEmitFrom.md) = `ParticleSystemShapeConeEmitFrom.Base`

粒子系统圆锥体发射类型。

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:111](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L111)

## Accessors

### angle

• `get` **angle**(): `number`

Angle of the cone.
圆锥的角度。

#### Returns

`number`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L15)

• `set` **angle**(`v`): `void`

Angle of the cone.
圆锥的角度。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L20)

___

### arc

• `get` **arc**(): `number`

Circle arc angle.

#### Returns

`number`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L56)

• `set` **arc**(`v`): `void`

Circle arc angle.

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L61)

___

### arcMode

• `get` **arcMode**(): [`ParticleSystemShapeMultiModeValue`](../enums/m4m.framework.ParticleSystemShapeMultiModeValue.md)

The mode used for generating particles around the arc.
在弧线周围产生粒子的模式。

#### Returns

[`ParticleSystemShapeMultiModeValue`](../enums/m4m.framework.ParticleSystemShapeMultiModeValue.md)

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:70](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L70)

• `set` **arcMode**(`v`): `void`

The mode used for generating particles around the arc.
在弧线周围产生粒子的模式。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`ParticleSystemShapeMultiModeValue`](../enums/m4m.framework.ParticleSystemShapeMultiModeValue.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L75)

___

### arcSpeed

• `get` **arcSpeed**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

When using one of the animated modes, how quickly to move the emission position around the arc.
当使用一个动画模式时，如何快速移动发射位置周围的弧。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L98)

• `set` **arcSpeed**(`v`): `void`

When using one of the animated modes, how quickly to move the emission position around the arc.
当使用一个动画模式时，如何快速移动发射位置周围的弧。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L103)

___

### arcSpread

• `get` **arcSpread**(): `number`

Control the gap between emission points around the arc.
控制弧线周围发射点之间的间隙。

#### Returns

`number`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:84](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L84)

• `set` **arcSpread**(`v`): `void`

Control the gap between emission points around the arc.
控制弧线周围发射点之间的间隙。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L89)

___

### length

• `get` **length**(): `number`

Length of the cone.

圆锥的长度（高度）。

#### Returns

`number`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L43)

• `set` **length**(`v`): `void`

Length of the cone.

圆锥的长度（高度）。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L48)

___

### radius

• `get` **radius**(): `number`

圆锥体底部半径。

#### Returns

`number`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L28)

• `set` **radius**(`v`): `void`

圆锥体底部半径。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L33)

## Methods

### calcParticlePosDir

▸ **calcParticlePosDir**(`particle`, `position`, `dir`): `void`

计算粒子的发射位置与方向

#### Parameters

| Name | Type |
| :------ | :------ |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) |
| `position` | `vector3` |
| `dir` | `vector3` |

#### Returns

`void`

#### Overrides

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[calcParticlePosDir](m4m.framework.ParticleSystemShapeBase.md#calcparticleposdir)

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCone.ts:120](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCone.ts#L120)

## Constructors

### constructor

• **new ParticleSystemShapeCone**(`module`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `module` | [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md) |

#### Inherited from

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[constructor](m4m.framework.ParticleSystemShapeBase.md#constructor)

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L12)
