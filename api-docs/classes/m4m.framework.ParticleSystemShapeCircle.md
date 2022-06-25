[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystemShapeCircle

# Class: ParticleSystemShapeCircle

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystemShapeCircle

粒子系统 发射圆盘

**`author`** feng3d

## Hierarchy

- [`ParticleSystemShapeBase`](m4m.framework.ParticleSystemShapeBase.md)

  ↳ **`ParticleSystemShapeCircle`**

## Table of contents

### Properties

- [\_module](m4m.framework.ParticleSystemShapeCircle.md#_module)
- [emitFromEdge](m4m.framework.ParticleSystemShapeCircle.md#emitfromedge)

### Accessors

- [arc](m4m.framework.ParticleSystemShapeCircle.md#arc)
- [arcMode](m4m.framework.ParticleSystemShapeCircle.md#arcmode)
- [arcSpeed](m4m.framework.ParticleSystemShapeCircle.md#arcspeed)
- [arcSpread](m4m.framework.ParticleSystemShapeCircle.md#arcspread)
- [radius](m4m.framework.ParticleSystemShapeCircle.md#radius)

### Methods

- [calcParticlePosDir](m4m.framework.ParticleSystemShapeCircle.md#calcparticleposdir)

### Constructors

- [constructor](m4m.framework.ParticleSystemShapeCircle.md#constructor)

## Properties

### \_module

• `Protected` **\_module**: [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md)

#### Inherited from

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[_module](m4m.framework.ParticleSystemShapeBase.md#_module)

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L10)

___

### emitFromEdge

• **emitFromEdge**: `boolean` = `false`

是否从圆形边缘发射。

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L79)

## Accessors

### arc

• `get` **arc**(): `number`

#### Returns

`number`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L22)

• `set` **arc**(`v`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L27)

___

### arcMode

• `get` **arcMode**(): [`ParticleSystemShapeMultiModeValue`](../enums/m4m.framework.ParticleSystemShapeMultiModeValue.md)

The mode used for generating particles around the arc.

在弧线周围产生粒子的模式。

#### Returns

[`ParticleSystemShapeMultiModeValue`](../enums/m4m.framework.ParticleSystemShapeMultiModeValue.md)

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L37)

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

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L42)

___

### arcSpeed

• `get` **arcSpeed**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

When using one of the animated modes, how quickly to move the emission position around the arc.
当使用一个动画模式时，如何快速移动发射位置周围的弧。

#### Returns

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L66)

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

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L71)

___

### arcSpread

• `get` **arcSpread**(): `number`

Control the gap between emission points around the arc.

控制弧线周围发射点之间的间隙。

#### Returns

`number`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L52)

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

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L57)

___

### radius

• `get` **radius**(): `number`

#### Returns

`number`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L12)

• `set` **radius**(`v`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L17)

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

[framework/particlesystem/shapes/ParticleSystemShapeCircle.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeCircle.ts#L88)

## Constructors

### constructor

• **new ParticleSystemShapeCircle**(`module`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `module` | [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md) |

#### Inherited from

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[constructor](m4m.framework.ParticleSystemShapeBase.md#constructor)

#### Defined in

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L12)
